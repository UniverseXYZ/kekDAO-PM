# Universe XYZ AMA Notes– #001

### Meeting Date/Time: Wednesday 2022/1/26 at 14:00 UTC

### Meeting Duration: 88 mins

### [Github Agenda Page](https://github.com/UniverseXYZ/xyzDAO-PM/issues/38)

### [Audio/Video of the meeting](https://youtu.be/JVhbjAvQxnM)

### Breakdown:

Moderator: Tyler Ward

Scribe: Tammy M.

Attendees: Mark Ward, Tyler Ward, Tim Kang, Troy Murray, Ryan Shtirmer, Algernon (Young Algy), Nick Ward, Rayne Leach, Zach Owens

## Intro
**Troy:** They are popping off, huh?

Everyone loves that. I'm seeing offers for 20 ETH or some crazy stuff. 👀

**Mark:** Offers.

**Troy:** Polymorphs are going to make it.

**Nick:** I got one listed for 420 ETH. 

**Troy:** I got the Sharded Minds Pepe listed for 777. 777.

**Tyler:** I can't even see it because OpenSeas is down.

**Nick:** Yeah, I was just going to say that.

**Troy:** Perfect timing for an AMA. We should tweet that out.

Check out the AMA when you don't have to worry about this anymore.

## Marketplace, OpenSea, Uniswap, & Smart Contracts

**Tyler:** That's what I was talking to Ryan about so that everybody is on the same page because we will launch it in a beta and alpha version. I'm trying to get the timelines of when they come out and when the actual marketplace comes out, especially for the people who weren't on the last one. When we came out with Universe, we had a wide range of ideas and things that we wanted to work on, ranging from extremely ambitious to attainable. I think that everyone should know that when we set out to build Universe. NFT volumes were $10 million a month, then we were rightfully ahead of the market. 

But, on the back-end, you need to run a marketplace with that number of people. Remember that this isn't Uniswap, where bots aren't even interacting with the interface. They're just essentially market-making directly to the Smart Contracts. Many Uniswaps volumes don't necessarily affect the front-end. So ultimately, OpenSea from growing from $10 million in volume to $10 billion in volume. And those being actual people on there transacting those volumes.

You're talking about basically the largest app in the history of DeFi. At the time it was Uniswap, and it could have handled the back-end that we were originally building. So as the market grew aggressively, so did the project's scope.

Some of the other stuff is for long term, deep decentralization. Those things obviously need to scale with the entire blockchain. But a lot of what we've seen in the same way that I think this Community probably gotten spooked once or twice, seeing when Andre from YFI was dropping, the Smart Contracts in front-end and I saw that, and originally had the same feeling that all of you all did. Like, damn it, Andre forks everything and does an awesome job. The problem is that it's easier to do in DeFi because DeFi doesn't get as much traffic as these NFT platforms do.

If there was a DeFi protocol that just got absurd amounts of front-end traffic, that becomes a mode in and of itself because you have to have a back-end that supports that. So where this kind of forkability, I think that all of us learned in DeFi, and it looks immediately like, oh, my God, we're going to get wrecked. 

It's not possible to just easily have a back-end that can handle that load in the same way, I mean, even now, right? OpenSeas down. That OpenSea back end probably is still the back-end that exists in anything in crypto except maybe Coinbase and even Coinbase goes down, right? 

That's very different from the Smart Contract and the front-end operating. So the scope of this entire project was other than what we do and what we find. Naturally, the scope of it grew as we went. So I have not been scared, offset or off-put by the type of front-end and here's the Smart Contract as when Larva Lab dropped that front-end with zero fees. 

But that has to be essentially run on the back-end, and that back-end can cost money to run. So the concept of a zero-fee marketplace, like money, got to come from somewhere. Everybody's going to be dissing about the server's always going down. I have not been worried about a competitor coming out that will come from one of those; we just rushed to market-type scenarios because I know when I saw SOS it was innovative. I thought the vampire attack was clever. 

Ultimately, they're going to run into the same problem. Unless they've been building a back-end in silence for 6 months, they have a journey in front of them, and the same will go for Looksrare. They're ultimately using the API of OpenSeas back-end, which has issues with things being able to be affected on that back-end; you're essentially borrowing their servers or infrastructure. 

When OpenSeas is down, so are all these other platforms; they plug into OpenSea's API. That's a competitive advantage for OpenSea. They can brick the services that are using it, if they become a problem or sell that as a service. Maybe they do if they get to the point that the NFT back-end becomes architected substantially different from historical ones.

With that said, and without getting too deep into weeds. 

When we release our product, because we have seen the excitement around even a slightly decentralized competitor, but still using some of the shortcomings and OpenSeas API, we're probably going to launch with like a beta.

Sorry, like a beta and a test engine. We're doing that because we could have done it sooner, but we didn't want to launch what we had and essentially keep it 3 months in a market where we had that back end could get throttled at any point if we became a legitimate competitor. Then we just gave Alpha on all the open-source Smart Contracts and the interface changes.

Meaning they could just brick us and take all the code. So now that we feel like we can go through a multiple-week testing period. Whenever that starts, the full Alpha version with the back-end that we built is a true enterprise back-end that will be competitive with OpenSeas back-end. We're probably 5-6 weeks away from the complete back-end, and everything else is done. 

The main problem on that back-end is what scrapes the blockchain and shows images instantaneously. A dirty secret of the NFT industry— the past —is that a lot of those images don't exist anymore. They only exist on OpenSeas API because it scraped the back-end for all of those years. So figuring out workarounds of scraping all of that, get it in somewhere. 

It's tecnically not our fault. Many of those NFTs were put on IPFS nodes that don't exist anymore. [Jimmy](https://twitter.com/j1mmyeth) from [AvaStars](https://avastars.io/) has been talking about on-chain metadata and putting images on-chain, people have started to use Arweave. They're looking at other storage solutions. But back in the day, all that stuff didn't exist.

**Troy:** That's why the [Crypto Punks](https://cryptopunks.app/) are entirely on-chain, right?

**Tyler:** Well, Crypto Punks were minted when nobody was using Ethereum. 

Now, if you wanted to put like a 100-megabyte video on Ethereum, you're paying a fortune to get it minted. Back then, they probably mint all the Crypto Punks for $500; it's not that cheap anymore. Putting all of our images on the base layer of Ethereum isn't realistic.

People used a shortcut inbetween when DeFi was blowing up and when NFTs blew up, they used IPFS nodes. If the project didn't work, maybe those IPFS nodes got abandoned. I think that our minting technology and our auction technology have taken account for a lot of that stuff. But suffice to say, everything is in a spot now that we're comfortable having the alpha version even if we get bricked by being a legitimate competitor. 

We're being conservative, saying 6 weeks. We have numerous scrapers numerous functions at the back-end. The way it's architected, we change from a monolithic structure to a microservices structure. This means other people can run that back-end and uphold back-end parts. If it goes down, we can have a long-term mesh network of back-ends. 

> One goes down; the other one goes up. 🎡

So, we think that we built a competitive product. The innovation is not on the more simple things like the front-end and the Smart Contracts. If that's all we needed, we would have launched 6 months ago.

That's probably the part that I'm most excited about. I almost laugh to myself when I look at some of those that have come out recently. And I'm like, good luck because you're going to find out now everything that we had to do to build it. 

### Shoutout: [Opensea](https://opensea.io/)

**Tyler:** Also, shout out to the OpenSea team because as much as everybody complains about them going down, I don't think that people realize that they're going down for a reason. It's not an easy tech problem, and they're scaling; they're building with money that's a legitimate float. 

I do think that there is a massive demand for a truly decentralized service. I don't think people would care about fly-by-night chances of going at it— If there wasn't a legitimate need in the market. And I also think that one of the things that have boded well in our favour was that we had many different things that we wanted to work on. All we ever saw on our Twitter was decentralize OpenSea, decentralize OpenSea, and some of that essentially expanded. Not because it went down all the time, but actually due to other things, and they lost some of the NFT community's trust.

## DCMA

**Tyler:** One thing I do want everyone to know is that— I've read a lot of comments — when I've been tagged regarding "When is Universe coming." It's based around DCMAs.

We still have to run a front-end server the same way that Uniswap does. 🦄

The way that you can think about what's coming is; 

**If OpenSeas=Coinbase Universe=Uniswap.** 

[Uniswap](https://twitter.com/Uniswap) had a long time to build when they started, and they didn't need that degree of back-end. They were running a front-end powered with Smart Contracts. When people say, Uniswap had to take something off the interface because the US government or someone else told them to, whoever's running our servers will have to do the same thing on Universe.XYZ. The benefit of Uniswap, though, and where this becomes decentralized, is that they can't stop the order books. It's a Smart Contract that's permissionless running on-chain. So when those things start to happen, ultimately a project— we're not going to get in everybody else's legal war for them— **If somebody violates someone's Copyright**, AWS might if we don't take it off our interface.

If somebody else wants to set up an interface because they think that they're in the right, that's your ability to do so. We can't shut anyone down to the Smart Contract layer, meaning all the liquidity, pooling of liquidity, and aggregation layers that will probably be built on top of Universe and all these other interfaces that plug into it. That's the power that we are giving to the NFT community. I'm not going to jail on all of your behalfs. So if you all want to do sketchy stuff, do it on your interface. We can't uphold like child porn; you can't put nazi stuff on there. I'm not trying to get into political arguments, I'm trying to create a censor shipless platform, but the platform is not just the interface. So you can do this as you please but be responsible. 

No one can stop you unless you're doing something illegal, and then that's your fault for running out on the interface. So I'm just wanting to be clear so that the expectations are aligned because I've read that, and if we get DCMA and don't take it down, they're just going to hit up AWS.

I get that people can run their servers. That's not what we signed up for. We wanted to build a censorship-resistant platform. That doesn't mean we want to host and uphold the front-end interface. Most of this stuff has nothing to do with the crazy things, and I think DeFi has more to be concerned about with this. Where DeFi could potentially be running some type of security. There are other types of laws, but there will be things that cause disruptions in our industry. It already happens like that in the world. You can run things in China that are not allowed in the US; you can run things in the US that aren't allowed in China. 

DCMA is like a legal dispute, when we got DCMA by Pepe— which launched this project —I could have fought it, and I had a legal dispute. We could have also gotten taken off by OpenSea. What I could have done in part of fighting it is, as a project; I could have hosted my interface and continued to run it and fought that legal battle until I won, and then it is back on there.

So we're talking about the aggregation of liquidity as opposed to this is going to be anarchy, and nobody can stop it on Universe.XYZ.

**Troy:** I think it's important to let everyone know there are safeguards in place to take stuff down, but it's not just one person; there's a guardian system. I don't know if we've ever documented it yet, but it will be in the documents. 📑

**Tyler:** Right, because then otherwise, the people running the interface are liable. It's the same as Uniswap. I know SynthaMan said on here they took S Euro off of Uniswap. They didn't. They didn't take it off the protocol, they took it off their interface, and that's because Uniswap runs that interface long term. Where we build from that, I don't know where that goes. We'll continue to decentralize as much as possible, but we still have to live in the real world and adhere to the rules. You all can do whatever you want. I'm not going to be liable for it.

That's one of the most important things is understanding the timelines and when everything is going to come out. When we do originally Launch, it's going to be a testing period. One of the things I think we should do is look at those protocols that vampire attacked OpenSea. We could probably vampire attack those during that testing period, take out the whales, see who's actively interested in those platforms, and ask them to come test with us and essentially compensate them.

## Minting Contacts & Auctions

**Tyler:** Then we'll have time to adjust and change things about the front-end until we roll out the enterprise back-end. Doing a soft launch doesn't mean that this thing is not going to work. It doesn't mean that you're not going to be able to trade NFTs, list NFTs do all the same things. But, we won't be truly decoupled until we release the other end. But I don't think we need that in order to start. I know that the Marketplace is what everybody is most excited about, but the same thing is happening with minting, which we could launch early next week. Minting is also kind of a beta vs an alpha. 

Our initial Minting Contracts that are going to exist are basic Minting Contracts. They're audited; they work. We released them a while ago and realize they need a ton of work by the time the auction comes out, and there are not that many people using them yet. People will use the Minting Contract. It's kind of the same as OpenSea. People mint on OpenSea because they can also auction them, trade and interact.

Most people aren't just like pinging into the OpenSea Minting Contract— if they already know how to code it —they could mint it themselves.

We wanted to figure out how we could innovate outside of being basic Minting Contracts. Tim '[illestrater](https://twitter.com/illestrater_)' was very strict on this particular one and the functionality that he and a lot of his circles and the people he's connected with. They are deep, deep NFT heads and the type of functionality they would want. What I mean by this is, instead of being able to mint an ERC 721, getting into being able to do a lot more in-depth things with 1155 being able to mint collections that own collections. I'm not saying that all of this is coming with the alpha version. But I think that everyone knows the way that you mint generative art or whatever [Altered State Machine](https://twitter.com/altstatemachine) did with those brains requires different types of Contracts than what it took to mint Punks or the Pepes. 

With that said, even the [Polymorphs](https://universe.xyz/polymorphs) themselves were an extremely innovative NFT, which is a lot of what spawned the fact that you can change your backgrounds on your [FLUFs](https://www.fluf.world/) or add music to the FLUF so that they'll be able to interact into burrows. 

So, we realized that not only is there a massive opportunity to improve on the Minting Functions, I'm sorry, on the marketplace itself. We also want to bring a lot of utility into the Minting Contracts. We're going to turn the original contracts back on because we don't want the alpha version of the Minting Contracts to hold back the alpha version of the marketplace. Ultimately, we could build more Minting Contracts and never launch anything because there's so much that you could essentially do with them. So we put a stop on it and said, those things are done; we need to get them audited. We need to build a front-end into it. So as soon as we build the Alpha Marketplace, we'll also launch Alpha Minting Contracts into it as well. Then they will get a ton of requests and changes to amend and build on top of those.

**Troy:** Or just like even other versions of them, right? You could say that there could be different Minting Contracts underneath the same UI. So whatever the needs are of the people using them, those needs could be reflected inside those Minting Contracts. So there could be an option.

**Tyler:** People will be able to put their own types of Minting Contracts on there. We've worked with a couple of different groups with very innovative contracts. I don't want Universe to become a walled garden. The more utility the ecosystem can get on the platform, the better, right? Instead of having one way that you can mint again, there are infinite ways that you could mint. That's going to be an ever going thing that we're always adding Minting Contracts. We'll probably develop very innovative ways to whitelist audited Contracts, where we don't charge a fee for Minting or Auctions. Maybe we bake that in; if people are going to be coming on and putting on a bunch of code the way that people in YFI introduce strategies, people aren't going to do that for free. So it's just an option. Governance is going to have to make those types of decisions on where we go. Because ultimately, the question would then be, are you taking away from the artist by giving them a ton of different options, or are you enabling them to be more artistic because they have a bunch of things that they can do, and you're not limiting them?

I don't think we take fees on Minting and Auctions. Governance can change their mind on that later. And this is how we'll give it to the world. It's ultimately going to be your decision to make these decisions long term. I'm just giving you some options and how this is going to be very different from the NFT Marketplaces and experiences that you have had up to this point. It's not all going to be day one, but this is where it progresses as long as we're all successful. And then the Auctions Contracts are very close to being done as well. But we're obviously in multiple sprints to get three different things out simultaneously that I know everybody's been waiting on for a long time. Almost all of them will probably have features cut. And then after we get kind of the Alpha Marketplace out, we'll probably have another 2 month sprint that we get out all the additional features. So there's going to be a lag time where we're fixing missed bugs. We're probably fixing things that people don't like, and we're trying to get the Alpha versions of everything else out.

So there will be a graceful period where hopefully, I'll give us a little bit of patience and know everything that's coming. But with that said, I'm more setting expectations. And if I were playing hype mode, I would say that I think that what we're about to deliver is superior to anything else in the market. The shortcuts that we took anywhere on decentralization are either technically impossible right now or would have been massive builds that we're going to have to work towards long-term as a community. But I think that everyone knows. Having looked at me and Troy's history up to this point, we're dedicated to working through those things, and we'll do it with all of you. We're not going to release the most perfect thing in history, but I think it's a massive step up to what exists now.

That's all the main.

## Decentralized Systems

**Troy:** And in the right direction. There's a ton of other work going on past this that's going on. That's even the next step. But we got to get this stuff out for everyone so you can understand what this is, just like how Uniswap had to get their stuff out for people to understand a Decentralized Exchange. Then you had people building stuff on top of LP pools and how they used it. It's going to be the same thing. But the first iteration of it. It's going to be pretty straightforward what it is. Then where it gets exciting is how people use the decentralized systems. Then, we can even add how we can also be brought to the greater ecosystem. The work is not stopping, we have steps past this, and we all are very excited.

**Tyler:** We just had this battle with something that was 'decentralized enough' because decentralized is a relative term. If someone's a big uni bag holder, don't go like yell to Hayden because he's my friend. Our token distribution is already more decentralized than Uniswap. We don't have an Andreessen Horowitz holding a massive bag. 

> No one owns more than 10% of the entire protocol. 

It will Launch more decentralized, but in the same way that Uniswap is substantially more decentralized than Coinbase. With all of the examples I gave, we will be more decentralized. Then you can go on Dune analytics and look at all the token breakdowns. It should decentralize more over time with more usage. That's the way that these networks are supposed to grow. But because it's a relative term, it's not going to be as decentralized as Bitcoin out of the gate. Ethereum isn't. You've got to get there as an ecosystem. 

So, we're probably saying decentralized in different through puts and mindsets. It's going to be the most decentralized Marketplace that exists for NFTs. 

I don't know if anybody has immediate questions or if Troy wants to expand on any of that overview.

**Troy:** I'm curious if people in the community, because it is an AMA, do you guys have any questions about that or curiosities? Does it make sense?

**Chad:** Yes, from my perspective. 

By the way, everybody has the option to chime in. You can set up your push to talk and join the conversation. 

That makes sense from my perspective as a long-term community member. 🦾

## Barnbridge & Universe

**Tyler:** So, I was on an Enter DAO community call earlier. Troy and I have talked about both through Barnbridge and Universe are; I've started to do a lot more AMAs. We have these like every 2 weeks recorded calls. There are things that we're doing across many projects. If you think of Universe as a mesh network that ultimately likes Polymorph, Bond, FLUF World and ASM. 

Those people have their own technology and teams, but they work closely with our ecosystem. They are people that supported us all the way from back to [Barnbridge](https://barnbridge.com/) and built with us. If you look at most of them, they have some type of DAO structure running them, and that's normally like a fork of the Barnbridge DAO that later Enter DAO improved upon. One of our main goals since 2021 was very much across everything about getting the products out. I think I read somewhere that [Land works](https://twitter.com/landworksxyz) from Enter DAO is Launching today or tomorrow. ASM is coming, burrows are getting minted today with FLUF World. Universe is coming.

**Nick:** I think [Z](https://twitter.com/zhivkoto) said Friday or Saturday not to interrupt,

**Tyler:** I just know what you wrote, but it's whatever.

I'm not trying to drop alpha there. I'm just saying none of us were lazy along the way. Even with all the Barnbridge stuff, we had to get the products out. I think now we've had time to see how these DAOs work. The good thing about having this mesh network of DAO using similar tech is that what gets utilized on one and starts working for one can get utilized across the system. 

Even Zeus from [Olympus](https://www.olympusdao.finance/) told me that a lot of the reasons they went with the DAO first was because he used to hang out in the Barnbridge servers. But building those systems also takes time, and we could have spent all the time perfecting the DAO or perfecting the product. So I will say what's happening in the Slack Channels and this concept of core team we tried to hire from within the community and the more active people. But ultimately, where I think DAOs driving protocols and community-driven DAOs driving protocols to go is in 5 years if we're successful. I believe that we have started to blur the line between what community is, what core team is, who makes what decisions, even down to Troy, and I have talked about who deserves an email of something.

## Muzli Design Tool

**Tyler:** So some of these features are more theoretical at this point, but we are going to start moving a lot more of the communications to Discord. The reason for that is even starting down with working on a project. That is going to be a Chrome browser extension— I don't know if any of you have used Muzli. It's essentially a design tool that designers often use every time they open a new tab in Chrome. It sparks design inspiration because it's a curated list of designs essentially. 

We want to use that same mechanism to attract people to Universe. It is also what OpenSea got in trouble for. It was how they were curating content and the gatekeeping of that. That's not going to be built into our DAO out of the gate. We just need to release it as a feature and make sure people like it before we take the time to build content curation into the actual DAO functionality. You're talking about base layer Ethereum; there's going to be a ton of gas fees to be making determinations of what goes where, everywhere.

And that's something we're all going to have to work together on. The governance may have to move to layer 2 if there are that many degrees of voting and many things that we're talking about. But I do think that's going to be absolutely dope. But that is particularly the way that I think that we offset the fact that that thing is not going to be necessarily driven by the DAO out of the gate. We need to decide what is put on that content curation, completely open, and anyone can read in our community. They all have access to it so that no one can essentially abuse the data any other way. That transparent data can essentially be abused. We don't want that behind a wall. These AMAs will probably be more frequent, and I don't think you will have to wait every two weeks to hear from us on a recorded call where you can't just hop up and talk to us. If these things get huge, we'll probably have to turn them into spaces. But for now, I think we're good.

I wasn't hanging out in the discord anymore because everybody was asking about marketplace, and I mean, we're building it; it's not easy. Right now that it's closer, it's time to talk to everyone because we have the stuff to act on, and we're launching a protocol. There's something to govern now. Up to this point, there hasn't been. I'm not answering all the questions head-on because I want to get through some of the things we went through in the last AMA. It wasn't recorded, so everyone can know some of why that AMA got a lot of excitement within the community. One of the things in particular to polymorph, and before I get to polymorphs, I'll bring up Lobby Lobsters. 

## Lobby Lobsters [[]]() 🦞

**Tyler:**  I want to build into Lobby Lobsters long-term because I like them. But that's not like a project for which we essentially have a road map. We gave all that money away, and we were very transparent about it. They're built on the same tech stack as the Polymorph so that we can build things in the long term.

They can't be a priority over the marketplace right now in the same way that Polymorphs could not. People weren't asking about polymorphs; they were asking about the Universe Marketplace. You guys can look on the DAO. We haven't moved the money. We didn't put it anywhere else. But, we have not stopped working on them. We had to put the Dev resources on these other three products that we have to get out there. 

However, we do have a ton in that same 6 months. We didn't stop doing stuff for them. We have like extensive 3D models for them. We've built them so they can be bridged to Crypto Voxels. We've done additional art projects and drops that will get attached to them, a utility that will work around them. We all talked about the battle game; we didn't forget. We still built it and audited it. The battle game isn't as important as the marketplace. That's the main way Universe is going to make money until we all work together as a DAO to figure it out long term. Something has to sustain all this. I would say that we did not forget about the Polymorphs.

## Polymorph's [[]]() 🤡

**Tyler:** We did not stop working on them. We just prioritized not launching all of this stuff. And I didn't think it was going to take 6 months for us to get all this done. So we just kept building stuff in the meantime. So, anybody that thought we forgot about them— enjoy what is about to get dropped. 

We've also done other drops that are away from the Polymorphs that are like full Universes of characters. Kind of what we originally started with when I made my profile picture. That Darryl Ape. We have comics. We've hired copywriters to write entire comic lines of stories. I stopped talking about this because people like Beanie; I would talk about something on a Twitter space, and suddenly he had some other version of it somewhere else. 

So all the good Alpha, we're going to release it when the community can benefit off of it, and not when we get front run by people taking advantage of us. It's all coming, and I'm pretty excited about it. It is my second time doing it this week, so I'm just getting all the high points and major points, but I want to make sure I didn't leave anything.

I know it's a soapbox, and I said my AMA and everyone could jump on, but I want Troy to say what he thinks. And then, I'll also go through the AMA questions that people are immediately asking.

**Troy:** I think you've covered it pretty much. There was a lot of hype around the last AMA, and the Community got all excited. But it's too bad we didn't record it, so that's on us. 

I'm pretty sure this one is being recorded. So, Tyler, you did cover the whole scope of it all? I don't know. 

## Community Questions [[]]()❓

**Tyler:** I will hit some questions then. 

### **Question:**

I think RoboCop asked; You said that some of the things are not going to be decentralized. What are those? 

### **Answer:**

**Troy:** The idea of decentralization as a spectrum. The difference is that the back-end is not this fully decentralized system. It is a system that can be spun up and run anywhere, but those instances can be shut down. One of the things that we didn't cover on this call was that this came from Ryan or Chuba, as most of you guys probably know him. We describe it as a clearinghouse for the entire ecosystem of NFTs. So what that means is that these back-ends can then be a clearinghouse to a play-to-earn game, or it can be a clearinghouse for NFTs or any NFTs out there. Ryan then put it in a more granular spectre where it's a 3 pronged approach so I can get the tweet for it. But essentially what it means is:  

1. The first tier would be the ability to run, you'd have an artist page, and you can launch your product on our system, and then you can then sell it through the marketplace, and you would have the artist page on the Universe front-end.

2. The second way would be to use our back-end APIs and then plug it into your play to earn again and then the other way. 

3. The third level, which is much more advanced technologically, is you would take our back-end technology and spin it up yourself. That at least gets us to the point of decentralization that allows us and that we are not fully in command of the entire apparatus. 

Is it the perfect answer? No. And are we working on ways to remedy this situation? Yes. So as of right now, that's the closest we can get to the decentralization of the entire back-end. But we are 100% working on getting it to that final step. This is what Tyler talked about it, and we didn't realize how hard of a technological challenge this would be and the crux of the issue, but I feel we've made a ton of progress towards getting to that point. I'm excited we can't leak the Alpha on all that because people will probably try to front-run us on it, as we've seen.

**Tyler:** We didn't end at this point. But ultimately, we built it, and it's coming. The back-end is done; we're rigging up APIs, testing it; we can't release a crappy product. I guess one thing that I'll say is the ability to run fully decentralized storage. It is not just a Universe problem. I was out in NYC, New York and Juan, who runs Foul Coin and started IPFS, was in a match argument with the guy that runs Arweave, and they were talking about how they all fed each other. Neither of them had built a kick-ass solution ready to take over the world to the enterprise level. Same with the front-end stuff. We want Dfinity to come through on some of this stuff. File Coin could go through some of this stuff.

You still can't run a Google-level back-end, front-end anywhere in the world on blockchain, and we can't figure it out. It's that the entire industry is working towards something. I would say the same thing about the DAOs, but I think that many people in NFTs are not necessarily people hanging out in DeFi communities and discords and learning the ins and outs of some of these trade-offs that you have to make. So the expectation is easier said than done. Ethereum has been in development for many years now, and it's still working on scaling capabilities. There will have to be some trade-offs between centralization and decentralization. I don't think we're making.

**Troy:** Can anyone else hear Tyler?

**Algy:** I think his computer might have died again.

**Troy:** Yeah

**Mark:** I can't hear Tyler.

**Troy:** Yeah, I think he's gone. What he's going into, though, is that no one has ever actually figured out this problem. Right. Since the beginning of the time of blockchain, tons of decentralized storage solutions have been tons. One of the first ones was probably Storage Roy back when it was running on Omi Coin, essentially Master Coin, which was the predecessor to Ethereum, and it's still around. But it's not the killer app that everyone's been looking for. There isn't a decentralized AWS yet, so these problems aren't new, but we're working through them. And if we've done anything, I feel like we've gotten us as close as we can with the technology that we have at our hands right now that we can release a product that can at least be in spirit decentralized, and then longer term, we can take it to that next level. That's just what everyone needs to understand that. That's why we're trying to set expectations around that. But we will not be using the OpenSea API. It's not going to happen. We knew that from the beginning. That was not the move.

**Tyler:** Especially because it's not open source, and ours will be open source, and as I said before, it will be a microservice so people will be able to run their own instances. And where this becomes important is, I know when burrows dropped today, my wife, the first time I was ever able to explain to her what the Metaverse was and why it matters. Once you have these virtual worlds, if you think about the ability for when that Travis Scott thing was on, what's that video game Fortnite or like Dead Mouth? Those people pay for skins; they're able to go somewhere like burrow. Party Bears just signed Snoop Dogg. Snoop Dogg can now interact with his fans and like put on concerts and have more inclusive events and this kind of Oculus Quest version of the Metaverse and essentially not have to worry about getting John Lennon. So when those people need to plug into a payment application layer, since that's not their main course of business, they're probably going to want to plug into the one that has the most liquidity.

So what is decentralized is, in my opinion, going to become early on the most valuable thing about Universe as far as the marketplace goes is the fungibility of the liquidity. When they plug into that protocol on their interface, they may only want to show the stuff they want sold on their platform, which is fine. But they're able to plug into deep liquidity pools that integrate across the ecosystem, and they're able to list things there that also show up on Universe. So if you essentially have this network, yes, each front-end can determine what's run there, but the protocol layer is what's going to have the deep level of liquidity. So people are essentially going to build their own back-end, but it's still going to plug into the protocol. That is what is so valuable about this and the reason for that. When I explained it to my wife, I didn't explain it this way. I told her that if you were at that Travis Scott concert for Fortnite, and those were NFTs on Ethereum or Salon or anywhere else, for when we go across the platform, we're not Maxis, we'd go where the industry goes.

We're not going to build it right now; most NFT transactions are on Ethereum, so that's where we built it. If that changes, we'll go where we need to go. Going back to the Travis Scott analogy, Fortnite is a walled garden. Your skins are owned by Fortnite. Eventually, the whole Metaverse, not just Universe, is going to break down that walled garden because the users are going to demand that they have transferability and can use all of these skins and things across other areas where all this decentralizes. So if you think that you're at that concert and Travis Scott drops something to you, you can maybe list it on that interface, but it's also going to show up at the protocol levels for the Universe interface.

You walk up to someone; they have a skin for sale at the concert; you can buy it off of them that will process through Universe. So these platforms no longer have a reason to go through a layer that can essentially censor them because they have a competitive product. So that is why, for the same reason that liquidity will aggregate, and it aggregated for Uniswap once all the sushi rewards went away, it's very hard to fork away all of that liquidity and usage. And that will be the hardest thing that we'll have to compete against with OpenSea is getting listings on our platform. But on a long enough time frame, with enough things quickly plugging into us without the worry that we're going to shut their interface down, that's where it becomes pretty difficult to compete with. You're not just going to interact with Universe on Universe.XYZ, or at least I hope not.

**Troy:** I don't think so. I mean, if you look at the way that comparison to Uniswap. Uniswap is still used in other interfaces. But it's one of the main places where the exchange occurs, and nobody uses Coinbases API to do those exchanges. You're not using OpenSeas APIs to do those exchanges long-term. This is because everyone knows how much they're making, and they'd much rather give it to communities that are building on the decentralized web. So that's a huge ace up our sleeve with how this is going to be delivered. Where I think we've probably beaten a dead horse. It creates a marketplace and a new user face that uses their APIs and then puts some token-omics on top of it. That's not the move. It takes longer, but long term, the payoff is huge. So you're all in the right place, in my opinion.

### **Question:**

So Ox Robocop asked this question; and we're down this rabbit hole?

### **Answer:**

**Tyler:** Yes, most of you, Uniswap track. I primarily interact with Uniswap on one inch. Right. Most of Avi's transactions don't happen on Avi. A lot of them are happening through Zapper. A lot of them are just protocols plugging into them. The reason that Uniswap is so powerful and even Sushi has become so powerful is a lot of the integrations that they built.

The reason integrations were attracted to them is because the same thing that we're saying is, ultimately, Uniswap can't take those liquidity pools down. So, yes, that's how it's going to work. It doesn't mean that we're not going to pull things off of our front-end; if we get DCMA, we literally cannot pull them off with the protocol. I'm kind of going up some of the original ones. Start with team updates after questions. Time constraints designate someone to make records, miss the project, call yada yada, docs.

**Troy:** We got to get the docs.

**Tyler:** We're probably going to need the whole community's help on docs long-term, especially during the testing phase. That's why I want to incentive. I don't want to do a vampire attack that ensures Ponzinomics and Wash Trading. I want to incentivize the community and open up the community to be more people. These are some of the things that can help.

It helps with documentation, helping with all of these things. I don't know if I'm missing anything. I feel like we hit everything; other than I would say that all of these protocols that I think everybody has seen have spawned off of the Universe; you can ask them. Ask Aaron at FLUFs, ask David at Altered State Machine, the Enter DAO guys, I mean, they came on as advisers. I think they were also inspired by what we were building, so they went out and started creating the Metaverse. Ultimately, this was harder to build, so it took longer, even down to League DAO, which has been experimental but fun. All of those are going to be plugging into Universe.

All of the excitement that's happened around Universe when we launched is launching with an ecosystem that is growing. So I think out of the gate, that probably seemed like a distraction, but it wasn't pre-marketing. It was pre integrations. Let's make sure we have things that want to integrate with us by helping all the people around us that want to make cool stuff. We've made some pretty cool stuff, too, and it's coming.

### **Question:**

So Crypto Prowess just asked a question about; Buying XYZ off the market? 

### **Answer:**

**Troy:** We hold XYZ a bunch of it in the treasury. It's about 7%. Then there's the ETH on hand, which will grow as the Marketplace is running, so that will be up to the community to put in proposals around that. We've had talks about creating.

**Tyler:** I was supposed to write a proposal yesterday but didn't know how to bring this up without talking about the price. So I'm just going to try to beat around it as much as I can. If you look at the volumes around what has happened recently, just on excitement. When we Launch, there will probably be more eyeballs on Universe.

If there's no depth and liquidity, it could do things to the pricing of the token that could look like manipulation since we're bringing everyone on this call that has been waiting and waiting. You all know what's happening. We're going to get a lot of new users, and some of those users will want to own the governance token so that they can be a part of this future with us. What we should do with a portion of the XYZ and the ETH currently in the treasury is deep in the depth of that liquidity pool, meaning we swapped the ETH for USDC and the DAO joins that liquidity pool. I don't think we staked for rewards because the deeper the liquidity, I'm not recommending anything about the price. I'm not saying it's going to go up or down. I'm saying that without deep liquidity, I think it could be volatile, and it could be a bad experience for new users that are just experimenting or exploring. So I ethically care about that, and I think we should want people to get the best experience.

So I'll probably put in a proposal to do that. It's ultimately not up to me, but I want to give some of the reasoning behind it without putting myself at legal liability for recommending it. Suppose anything is going to happen. I want to be proactive so that nothing does.

**Troy:** A good way of looking at it is to allow more participants to come in without getting into crazy situations, creating much potential butt hurt in the long term, and it's important.

**Tyler:** The other side of the equation is that it becomes understandable for people to get in.

**Troy:** Yeah.

**Tyler:** The way that liquidity pools work without saying that it's specific to XYZ is if there's $1,000 in a liquidity pool and you try to buy $10,000 worth of it, one you can't. But let's use an actual number. There are a million dollars in a liquidity pool, and someone puts in $500,000 of it sells in a day. That alters how that liquidity pool is comprised until new participants come in. We should all be aware of that, and we should utilize the treasury accordingly.

### **Question:**

So to switch topics a little bit, Gunner does have some questions; One of the things is he's asking us is if, the Universe Marketplace is going to mirror some of the features that Gem Launched with?

### **Answer:**

**Troy:** So the first one is multiple buyers in a single transaction. I don't think we have that, to be honest.

**Tyler:** I don't know if it's in me.

**Mark:** This is Mark. I'm just bumping in. We are working with Genie. I've been talking with Scott.

The founder over there.

Our Marketplace isn't going to be able to have those features built-in, but Genie is going to offer those features for you to be able to floor sweep and do all that cool stuff on Universe. So while necessarily, our front-end UI won't have that feature. You will be able to do it from Genie.

**Tyler:** Does it because they sweep the floor and OpenSea right now. Genie is in an awesome position to be an aggregator. It's not that hard once Genie plugs into us for us to add something like that to our interface.

We still accumulate fees either way when you use Genie OpenSeas to make money. So I think we treat Genie as a friend very much in the same way One-inch and Uniswap are friends. So that everyone knows, this is where I want to become more transparent from what's in Slack versus what's in Discord. We have been dropping ideas, and we follow all you degenerates on Twitter, and you all post ideas for cool features for marketplaces. We have a pretty extensive collection of interesting features to add along with our ideas that have come along the way, and you can't Launch anything perfect. There's a lot of stuff still to build right across the board, and we're listening to those features. We can start being more transparent about how difficult it is to build some of these features. Communicating with the community on that's just an interface level change versus a major Smart Contract addition that we have to get audited and find solidity Devs to do. But I think those conversations start happening in the open. We just want to get a head start before we start leaking alpha. Lower gas fees, OpenSea.

**Troy:** So, some of that comes down to, are you talking about the Mark? Like, what are you talking about? Minting fees, purchasing fees. We are working on a lazy minting feature. It's not going to launch with that; I don't believe. But some of those gas fees come down to the ERC 20, essentially the structure of the Minting Contract that we're talking about, minting. So the amount of metadata that's in there.

**Tyler:** Transfer fees are just Ethereum, right? Like tokens cost more money to transfer than ETH, which is why? Because ERC 20 is not, ETH and ERC 20. We've also been talking to polygon and optimism. We chose to launch on base layer Ethereum because I think we get that right first. But yes, we're going to optimize for fees.

**Troy:** 100%.

**Tyler:** You end up with polygon that has so many crappy coins in your wallet that you can't even find the good ones, and it's also not as secure. I think people want Ethereum NFTs more than they want Polygon NFTs. I believe that the platform is as optimized for gas fees as it can be. But it's going to be similar because we both are doing most of our trading.

**Troy:** Mark has talked about this, and it's hard to get from; if you're minting on a layer two back in the Ethereum into another layer two, that's hard. But if, let's say you're minting on the base layer because everyone's looking for that base layer Ethereum stuff, and then you take it into a layer two for marketplace. I think that gets interesting. So those are ways that we can optimize gas for everyone long term.

**Tyler:** Are you asking a leading question? You might have gotten alpha from Algy or Mark or someone else, and I know certain stuff about Universe that Mark doesn't know. Troy knows stuff that I don't know because it's not one product. There are some aspects of divide and conquer. If somebody told you that, we can verify it 100%, but I legitimately don't know that. Then also, what you're asking about high-grade analytics for collections. If that's also alpha, that comes down to the

**Troy:** You were talking about it earlier.

**Tyler:** But I didn't talk about all its features of it. We are definitely building analytics and features long-term. We also started to work on a Wiki that would also be token curated and community-driven. Tim started to work on that, started to code it, and then he realized that at launch, it was more important to have better Minting Contracts, which are coming as Alpha Minting, which is going to come behind the Alpha Marketplace. So all of this will start to collide where the Muzli extension that I'm talking about is essentially going to launch like our curation, and we'll do it openly in the community and work with you all on it. The secondary aspect of it is going to be much more community-driven, where maybe even XYZ doesn't deserve to dictate what's on the board eight-page. Ultimately we vote on that stuff. We can revoke access for things that things get out of hand. We're 100% working on that, and I think that it's going to be a very powerful tool to bring a lot of people to Universe, but it's going to be iterative.

We're going to roll it out slowly and decentralize it over time. We weren't focused on decentralizing that part because the other parts of what we're building that everybody's asking for are not nice. Still, like existential for the system, we spent most of our time decentralizing. We're not launching a cone of OpenSea; it is the easiest way to put it. We've probably seen one cool tool when some of these surface-level competitors launched in the community. I don't think we're offering one cool tool or one piece of differentiation we're launching. The main one is going to be the decentralized aspect of it, which is most important. But I don't think the average user always cares about that. They'll care about it long-term. But the experience of our platform is going to have a lot of features that are different and new. But now I want to know because that's dope. If it's true and you have alpha, I don't have.

**Algy:** I'm sorry, what was the question that person asked you? I listened to your whole response, I missed the question.

**Tyler:** I just used you as an example. Maybe you talk to Ally because I know everybody's friends with Ally, Nick, and Mark; they work for Universe and are deeply embedded within the NFT community. I also got off the last AMA, and you are still talking some. So I didn't like the way Gunner describes this is it sounds like he has Alpha. And I was saying I don't know if you heard that from somewhere else. It doesn't mean it's not true. I just can't verify it. But he was saying transactions.

**Troy:** I thought he was talking about Gems.

**Nick:** Yeah, he's talking about other marketplace, not ours.

## Gem & Genie Protocols

**Algy:** That isn't a marketplace. That is an aggregator. So Gem and Genie will be 2 protocols that we integrate with it probably, and they will allow people to easily buy NFTs through Universe using certain functions that maybe we haven't built yet, I guess. But the only thing that you can do on Genie right now that OpenSea doesn't allow, for example, you can bulk list and bulk buy, and you can trade your entities for others. So if we, for example, didn't have those features at first, Gem or Genie would come in and be aggregators for those features, but the transactions would still be happening through Universe, even though you're on that site.

**Tyler:** Yeah. Okay. Yeah, I use Genie. I use it to sweep the polymorph for League DAO because I've been so busy building this product that we kicked off the profile picture movement with Pepe; I didn't get to enjoy it the same way as some of you Degens did. I did, but I didn't know what Gem was. One of the benefits of the Universe is that we are a mesh network built around all these things. We've made many friends along the way, especially because of our dedication to doing it the right way and not like shipping a crappy product to market grab and cash grab. We wanted it to be right, but it was not easy. Yeah. Gem's dope.

**Mark:** Gem Launched today, Tyler.

**Tyler:** It sounds like you all have already been talking to them.

**Mark:** I don't know.

**Algy:** Yeah, I contacted the team in their discord, so they already knew what Universe was, and they're looking forward to us.

**Mark:** Universe has landed on Gem, PlanetGem.

**Tyler:** Well, we're about to land on the whole ecosystem here soon.

**Nick:** So what's Gem about? If you have a moment to describe it.

**Algy:** Do you ever use the protocol Genie? Yes or no?

**Nick:** No, but I know what it is.

**Algy:** Okay, so what these protocols do is they allow you to buy. I was just explaining due functions that Marketplaces don't have yet. So the whole point is that Genie and Gem were, Why can't I bulk list or bulk buy items? That's what the people who made Genie thought. And so they built a tool for it connected it to OpenSeas so that they don't have to have their marketplace built. They just make it to where you can easily buy and list your items on OpenSea or any other Marketplace. Rarible, they also have integrated. They'll integrate Universe because I've already talked to the founders, and they're excited about it. Genie and Gem. When you have something listed on Universe. The floor on polymorph is .1, and ten listed, and somebody could go in and click on all of them. They could even go past .1 and sweep as many as they want in one transaction. Then the same goes for listing if you want to list all your NFTs at .1 just to dump them all.

You can click on your NFTs, and then you have to sign for each one individually. But it happens way faster than trying to go through and do it on OpenSea, especially if you have a lot of NFTs. I have 600 NFTs. So using Genie to list items is helpful because OpenSea takes forever to load, and it will allow me to do it a lot faster. So it's not like a competitor in any way. It's just like an aggregator. It's helping the marketplaces because it's driving more business and allowing transactions to occur faster.

## Intergrate

**Tyler:** Nice. Yeah. Well, those are what I'm saying, that those are the types of things that we're just going to be able to integrate. We've also found many Contracts Manifold. One of our team's benefits is that we were early and stuck in the movement Ethos of what NFTs were supposed to be and douchebag cash grabbers. We've developed a lot of friends and connections in the industry, and I think a lot of people are waiting for Universe to ship, outside of just what spawned off of us directly. I know people in this ecosystem, in the community, outside the core team, are also putting in work and making introductions and talking to people. All the people that are on that website are involved in this project.

They've just been waiting like everyone else. I think at this point, so it doesn't turn into rambling, and people don't think they need to listen to a 2 hr podcast. I see Ben Lakoff often here. What's up? Charge particles. Another example of our homies building innovative stuff with NFTs, not like copy paste stuff. There are many more people in here before; I'm not doing this a third time because I'm brain dead. Honestly, I am trying to get off because I don't know when burrows are minting, and I'm trying to mint burrows. FLUF World is going to make it. I can talk about FLUF World differently from Universe because I didn't drop it. burrows and whatever, but I need to get on there and see the alpha. I'm a Degens too.

## Shoutout:

**Troy:** Suppose we're getting close to ending this. I want to shout out that there will be a merch drop tonight. We can drop the link in that merchant, and the merch is sick. So if you guys make it, we're going to buy some bulk out here. So if any of you end up in Puerto Rico at any time, we'll have some for you. Hit us up.

**Mark:** Yeah. So shout out to Jen.

That's our merch partner. He has been with us since Barnbridge. So, if anyone's in Europe or Australia, we did have issues last time getting some stuff delivered because of Covid. But our workaround is that we have EU and Australian merchandise companies out there that are going to support us and help us get stuff shipped out faster. It's all the same gear, but it's getting sourced closer to home on some of you guys. Last year during Covid, we had some problems with some of the mail, but we think this will solve it quickly. Some of our more international people can get their gear faster than they did last time. So everyone, if you bought that gear, you know it's like high quality. I talked about this. All my gear I got from them is still awesome, like black hoodies that didn't fade. They're super comfortable. So they're very quality.

**Tyler:** Whoever that guy's got to make this stuff will make it. But Marks, right. Also, where they're going with this. The Barnbridge stuff was just a hoodie. What those guys are doing with that going forward is dope. I mean, when they originally dropped the Barnbridge ones, I think they came with NFTs, but I think they know where the Metaverse is heading now. It's a year since the Barnbridge one came, so I feel that they're building additional features into them. But that's not even Universe.

## Barnbridge Merch

**Mark:** We'll give a little alpha on that one. If any of the Barnbridge gang has any of those Barnbridge NFTs from the last merch drop, I definitely would hold on to them or delist them if you have them.

**Tyler:** Maybe I'll do something with the Barnbridge NFTs. Long-term for Universe.

**Algy:** The Barnbridge NFTs are 100 ETH 4 . If you go, look at the collection from the first merch drop.

**Tyler:** I'll do something with them one day. Like I'm not giving out a roadmap. We got much other stuff to build. But that wasn't even Barnbridge. I just did it myself and paid for it out of pocket. I just wanted to reward the early people. I didn't even know Universe was something that we would get into. But the other thing I would say is.

**Algy:** I was talking about the other one. There are three different Barnbridge ones.

**Tyler:** Something really important.

**Mark:** I talked about the merch Barnbridge ones from the merch shop last time. A few people got lucky and got one. Those are the ones I was talking about.

**Algy:** But the ones that you're talking about are sick AF. One of them sold recently on resale, so they have people looking at it.

**Tyler:** I didn't do it for any other reason. To just be able to track the super early people that put on because they're a bunch of anonymous frogs.

I'm going to bring something up in a second. But one thing I want to say about the important merch, and I want to drive into everyone, is. Small things that we've done along the way to ensure that this is truly community-run. Is that all of our trademarks, our content, and everything that we drop is Creative Commons. We can't even DCMA people for polymorphs because we never licensed all of that. All of the code is open-source, which is why FLUFs Worlds was able to use some of the components of the FLUFs Altered State Machine. Just use some; well, George wrote all that stuff as a gift for being the advisor, but even our brand, right? So, Jen, that's not us; it's official because I think all of us as the community think it's dope.

## DAO

**Tyler:** But that's just very important. It's just even down to the level of we're a DAO. There's no way for a DAO to own an IP, at least not now. Something Troy is working on in the long term. But ultimately, that's not just ours; it's everyone's, everything we drop is everyones. It's important that you all know that that is how some of the things are structured. So yeah, Jen's stuff isn't going to the DAO. But he took the initiative. He made a dope-ass drop. I think the whole Community benefits from it, and it brings more utility to our ecosystem. But ultimately, you don't need our permission. Now, if you go off and do terrible stuff with the brand, then we as a collective can say that you're damaging us. If you start doing terrible things with it, don't go crazy. You don't want to like piss off a whole ecosystem of autistic NFT Degens. We're not DCMA anyone. The other thing that I was going to say. Is speaking of the early Barnbridge people; I want to talk about the early people in this community because a lot of you all stuck around, and there's been FUD and bull and people thinking we gave up or retired or gave up on the polymorph Prowess came in early on.


## Community & Core Team Members

**Tyler:** It is also about how we're trying to empower community engagement and start to blur these lines long term. That doesn't mean everybody can have a job tomorrow like the DAO. That Multi SIG was a lot of our core team's funding; we had to make sure that we delivered the white paper. There is a multi-sig that we make decisions from right now. Long term. That's all the DAO, right? So, we are trying to bring in people from the community to provide value. So Prowess has been working in the generalized ecosystem. He's been nothing but a gem to the whole NFT community. Burn address. I'm sure that's a core team member; Gunner never left anywhere. I'm not just going to call every person out like Azom came in and does a ton of work like Banana Mercy never left. Ben has stuck around and stuck with us. Navi started messing with NFTs because of Universe. And now I said to someone recently; I think Navi is 30% of the reason that FLUF world is where they're at right now just in terms of shilling skills.

Donovan is one of the only people that never changed his polymorph picture after people thought we gave up on them. Fluffer Nutter that person has done Fluffer Nutter is like another Navi has just done nothing but work for the FLUF Ecosystem. JVK never went anywhere, Knowledgeable Idiot. The same thing as we brought Knowledgeable Idiot on to help with a bunch of the work that needs to happen from a customer service perspective. Honestly, our customer service probably would have sucked if we didn't have someone who was organized and knew their stuff. I could go down all the polymorphs, but I don't know every person, right? Lindy, Markle, I've seen you all continue to ask questions. Max collection. That's the guy who probably has many punks in a wallet that he's never going to find, but he's helped through the whole ecosystem and hasn't stopped Arthur Hayes. I hope we find out you are Arthur Hayes one day. Like Pavel's core team, Pablo Bendis doesn't even get compensated from Universe. He just helps because he loves it and has done nothing to work like sent them in. I think you follow our kind of everywhere because we love synthetics as much as you love our shit.

Transmental tried to work with us as a creative director originally. We didn't have a spot for him, but he's come on recently, and it's like blowing us away with the stuff he can do. Algy is my cousin if he didn't learn NFTs pretty quickly. Popo, you didn't go anywhere like Chad. I think you thought I was scamming you, and we were never going to release the token after the Pepe thing, but hopefully, we showed our true colours along the way, and the platform is dropping. But many of you have been waiting around a long time, and I appreciate the patience. It hasn't gone unnoticed.

**Nick:** Yeah, there's been some trying times, and we made it through it as a community. And that's what's important, the friendships along the way.

**Tyler:** Plus, it helps when things aren't perfect in the beginning because people let the protocol decentralized a little more than if we just come out of the gate and just never had any hard times. But then, further, I think it also builds a stronger bond. So I'm not lying like it's coming. It's going to be fire. I'm pumped about it. I'd almost say that. I almost look at those other platforms at this point in a cocky capacity because I know how hard it was to build what we built.

**Nick:** As you're saying, we did have to kind of squash beef and the people who made it through that early on. Now we have some friendships with a real foundation.

**Tyler:** Hey, but I think we all go hop and go, mint burrows, everyone.

**Troy:** No pun intended.

**Nick:** Confirmative.

**Algy:** Yeah, let's all go hop.

**Mark:** Shaking right now.

**Algy:** Hold on.

**Tyler:** I watch Aaron in that community, too, right. Many people could have used what we started, and front ran us. I've worked with Aaron for a long time and trust him, so he's not one of them, but they also didn't try to grift; they went and created something dope on their own like Enter DAO didn't try to build some crappy version. The things that popped up around Universe are like not copy paste cash grab. Same with League DAO, even Charged Particles in Illuviun like we were involved with them when all this was starting. We haven't stopped talking to those people. We have plans to build into all that stuff long time, Genie. I've been talking with the Genie team since May. Whenever they started introducing that tool, I helped them beta test it. So I will say that I'm not just excited about what we've created for our product. I'm excited that we messed around so much with this Metaverse stuff, doing it the right way. Facebook changed its name. That wasn't a timeline I saw last January happening.

**Troy:** Even Walmart is getting into the NFT trading game, which is crazy.

**Mark:** Microsoft Activision.

**Tyler:** Ultimately

**Algy:** Walmart is building a metaverse shopping experience so that you can put on your VR headset and you can shop. As a VR person in Walmart and they'll deliver your freaking groceries.

**Tyler:** Ultimately, Sosa is correct, however. Microsoft is trying to build like excel spreadsheets in the Metaverse. They're too late because imagine they wouldn't even know what any of this shit means in this AMA. If they went into our general chat, they wouldn't understand what anyone was talking about. We didn't build the Metaverse for Boomers. We made it for the Dgens

**Algy:** Yeah, the Dgens supply. We'll do it. We'll put that on the shirt. Put that on the T-shirt.

**Mark:** But anyway, I love you all. I'm going to hop away and get some random, yeah.

**Troy:** It's definitely for us.

**Algy:** Yeah, I moved all the way from Australia to the USA for this, so I can't mess this up. I skip leg day for this.

**Tyler:** All right, later we'll do this more often and like I said, we'll try to bring some of the slack stuff into the discord. We're going to have some private channels that have to do with code we don't want, like Lurkers in here, but yeah, ultimately, it's going to start being a lot more transparent. I'm getting off. 

Bye, everyone. 

**Troy:** Yeah. 

Bye, everyone! 


<br>

### Project Links 🔗👇

* Website: [universe.xyz](https://universe.xyz)
* Project Info: [DOCS](https://docs.universe.xyz/)
* Twitter: [@universe_xyz](https://twitter.com/universe_xyz)
* Discord: [Invite](https://discord.gg/QnkfAG6X52)
* Youtube: [Channel](https://www.youtube.com/channel/UCWt00md9T2b4iTsHWp_Fapw)

#### Universe NFTs
* PolyMorphs: [Universe](https://universe.xyz/collection/0x1cbb182322aee8ce9f4f1f98d7460173ee30af1f)
* Lobby Lobsters: [Universe](https://universe.xyz/collection/0xc0cb81c1f89ab0873653f67eea42652f13cd8416)
* STAND WITH UKRAINE: [OpenSea](https://opensea.io/collection/standwithukrainedrop)
* Core Drops: Coming Soon!
