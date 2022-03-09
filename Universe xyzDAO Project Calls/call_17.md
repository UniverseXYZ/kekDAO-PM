# xyzDAO Project Call Notes  – #017

### Meeting Date/Time: Thursday 2021/11/18 at 14:00 UTC

### Meeting Duration: 31:26 mins

### [Github Agenda Page](https://github.com/UniverseXYZ/xyzDAO-PM/issues/34)

### [Audio/Video of the meeting](https://youtu.be/VCk0fhQz8mw)

### Breakdown:

Moderator: Mark Ward

Scribe: Tammy M.

Attendees: Mark Ward, Tyler Ward, Troy Murray, Ryan Shtirmer, Dmytro Dutka, Dragos Rizescu, Algernon (Young Algy), Nick Ward

## Intro

**Mark:** What's up, everyone? Welcome to Project Call 17. It is Thursday, November 18, 2021. 

We're excited to get back to you guys getting into the holiday season, but we will reassure you that we will be hustling and bustling over the next two months to try and get all of these products out for everyone, hopefully ASAP. But we have a lot to work on. We're going to jump into the minting updates. So recently, last week, we did a soft launch for our minting contracts, and they are live right now. Currently, we kind of just released the bare bones. We have our very own Tim Kang working on many features to add to this minting contract coming out in the next few weeks once we get them all finalized and ready. But we do have more features coming to the minting contracts. I'm not going to give any details on those exactly, but I want everyone to know Tim is a pretty brilliant mind. He has an extreme passion for these contracts and wants to add features that he's wanted to see in the industry over the last few years.

And we all are pretty sure that these features are going to set us apart and that we haven't seen these before. Tim is working on these personally, and those should be coming out in the next few weeks, hopefully within the next month on the minting side. So many more features are coming, so that's something to be excited about. And then next, we kind of roll into the marketplace updates. 

Ryan, do you want to give maybe some feedback on the back end and some of the scraper stuff we've been working on, order books, Fleek and that kind of stuff?

## Products [[02:24]](https://youtu.be/VCk0fhQz8mw?t=144)

**Ryan:** If you'll allow me as well. Can I do a little half an alpha leak on Tim's minting stuff? If not.

**Mark:** Don't give out too much. But Ryan has all the inside scoop on some of the cool features.

**Ryan:** If anyone knows Tim Kang, you'll see he's a decentralization maximalist, as we endearing call him, and he's a massive fan of when your metadata lasts forever, and it's stored in all the right places. That's about all I'll say there, but we're very excited to see that play out. 

### Marketplace 🖼 [[02:38]](https://youtu.be/VCk0fhQz8mw?t=175)

Regarding the marketplace, auctions and some other stuff we're working on, there's been a lot of progress made towards the back-end, especially on the marketplace. There are two very major back-end components there. There's an order book that maintains a list of all the orders and allows you to submit orders to it, which is like the heart and soul of the back end. We've finished this up and are in testing and are excited to start implementing that into our main site and the other major component is a data scraper. We have an existing data scraper right now that you can see when you log into your site that Morales powers, but we're building this robust, fast and complete coverage data scraper that is just talking right to the blockchain.

It's talking fast to it and getting all this data like the super high speed that is unimaginable. If you're printing out the information, you're slowing it down. That's how fast it is. We are all very excited about that since I mentioned that we are all decentralization maximalists to one degree or another. And that's the focus that we like to go on. We've been playing around a good bit with Fleek and talking to Harrison about that, and we've managed to get some data stuff ready on fleek. So the Universe website is available now on Fleek. We'll be getting links out and getting a Fleek.Universe set up for the short term, but there will be some cool stuff there because you'll be able to browse the Universe site right off of IPFS. I think those are the major updates from my end, but we're all super excited.

**Mark:** I have one more update for the marketplace too. I don't know if this is something we said publicly, but we have had many questions in the Discord and elsewhere. There are many questions about Gas fees, layer twos, alternative blockchains and marketplaces. We want to reiterate that while we are working on this marketplace, this will be layer one, Ethereum deployed on ETH. And basically, we are already thinking about and working with teams like Polygon and another layer two. But I won't mention it right now, but we are talking with these teams, and we have to deploy on Ethereum first. But once we do that, we're going to be looking towards layer two is pretty quick to offer those feeless Gas list solutions to users who want to use those blockchains submit for a fee. But that's going to be coming after the regular marketplace, but we want everyone to know we are looking into L Two, S, ZK's and all that different fun jazz that's happening on the layer two side.

**Ryan:** Since that's kind of half the timeline, we may want to update everyone on the answer to the "when auctions" "when marketplace" questions. I can give you the current answer: we're targeting Q1 of 2022 to launch both products. So we're super excited that it will be an enjoyable couple of months.

**Mark:** So like I said, over the next two months, we are hustling and trying to finish a lot of this work we've been doing over the last six months and trying to cross our T's, dot our I's and get these all published for you. Ryan says Q1 2022. If it's possible to go earlier, we will, but we don't want to put ourselves on the plank too early, but it's looking like we're going to be able to go live by then. Is there anything we're missing about the marketplace?

**Ryan:** Can I get back to you on the options? If you want to jump into that.

**Mark:** Yes.

**Troy:** Just so everyone knows the Fleek integration, one of the cool things about that is that we have an intense connection with the founder of Fleek. One of the things we did when we talked about this was having the Universe DAO pay for the services. So there is no central company that is paying for these services. It's being paid directly from the DAO, and it gets paid out yearly. We essentially got loaded on there because we know them so well. But do you lookout for a DAO vote around actually paying Fleek? I think it was only like $200 for the whole year or something like that. It wasn't a lot, but it's a pretty cool way forward with all that from a decentralization standpoint. I'm excited about being able to pay directly from a DAO for a service like that, but that's just geeking out.

**Dragos:** That's the first step towards this whole vision.

### Auctions 🧑‍⚖️ 🖼 [[08:07]](https://youtu.be/VCk0fhQz8mw?t=487)

**Mark:** Okay, so next auctions. So as everyone knows, where we started for Universe was auctions. I see many people remember us doing the NFTs, and when we started that, I wish Tyler or Tim was on this call. They could always go back into detail because they were the ones that lived this. But when they were minting those Pepes, they had almost as a paradigm shift kind of thing happened to them where they had tried minting on OpenSea and Bounce, and they had almost struggled in their first time minting NFTs. And they said we need to make a platform that makes this easy. So they went and tried to do this, and it wasn't as easy as they had thought. So they said we need to go and make something that is user-friendly. And the deeper they dove, as Ryan had mentioned, is the decentralization Maxi and Tim and Tyler started to look at the NFTs and say, like really, how decentralized are these NFTs? And that's really where our journey began. And over these last 6 to 7 months, we have been diving into how we can decentralize NFTs from storage and make them live forever on the blockchain?

Because of what we see right now, it's not the case. And I've heard Tim say a few times and have listened to other people say this is there are skeptics in the NFT space that call NF to say our NFT is actually NFTs because a lot of them do live on nodes that could disappear at the end of the day or what happens to this art if everything goes to crap? These are the questions that nobody wanted to ask. But I believe Tyler and Tim started, or more Tim, but started asking these questions and saying, like, look, we need to move forward.

**Troy:** This conversation came more from what we were talking about using the Internet and ICP system because the big issue was around. Like when we were architecting all of it early on before there was a token. I talked about this in that Multiverse medium article, but we had hour-long jam sessions around what we wanted to achieve with it. But ICP wasn't available. Again, this falls back into our relationship with Harrison because he built much fleek on top of ICP, but none of that was available at the time. So we had to create bandaids.

**Ryan:** We did play around with ICP integration with our front end through Fleek. It's not something we can offer yet, but it is something that we will work to provide eventually. The ICP network is not yet ready to handle all of what we're asking from it, but we're all expecting it will be.

**Mark:** I wanted to reiterate that this is our mission.

We always say we are creating a decentralized marketplace, and I'm not sure people truly understand what we mean by that. And you can decentralize the marketplace pretty easily. You do a DAO, give a token, and someone will stamp the centralized on that. But really, what we want to do is decentralize is make truly decentralized NFTs that are going to live forever. And that's the marketplace we want to build, not just a decentralized run marketplace. We want to genuinely decentralize the marketplace down to file storage.

**Mark:** What's that, Ryan?

**Ryan:** Decentralize everything— or at least as much as possible.

**Mark:** Yes, as much as possible. That's why we bring up the definitive and ICP stuff because those tools weren't there at first. Those tools are being built out a lot better, and eventually, we'll be able to migrate to those and get to that almost fully decentralized. It's like you solve one problem, and another one pops up. So I can't say as soon as we go to definity, we're going to be completely decentralized, but we're working towards it. And it was why we focused on the auctions first, because really, what we wanted to build wasn't a possibility. We realized that no one had completely built NFTs completely decentralized because it wasn't a capability in the industry at the time. So we focus on auctions. And this is one of the main things that we put a lot of our blood, sweat and tears into. And it's finally going through its final round of audits. This auction style was modelled after Justin Blouse tiered style auction. There is still no auction type like this in the space after eight months, so no one's beating us to it.

And we think that we've built this to the T, and we're excited to launch this for everyone. Still, that's going into its last final audit, and we still have to do some connections and testing once all that is finished. But we're hoping that we're going to be able to launch that pretty soon. But it still could be a month depending on testing because we want to test everything. And like we always say, security is something we take super seriously. So we audit everything, and we test the hell out of everything. That was a long little spiel about the decentralization, but I just wanted to let everyone know. I've seen a lot of stuff in the community about it, and it's taking all six months to ship a marketplace. But realistically, I want some people to realize we started with the options. And part of the reason why we did that is we started with maintenance and auctions because you got to mint NFT to have an auction. But the marketplace was something we saw coming afterwards because we were hoping that the tech in the industry would move forward as we did and as it has some sort of developed as planned.

We started the marketplace a little later, but we're still on track to build what we wanted to create, a fully decentralized NFT marketplace. And I do want to say I don't think that anyone has beaten us. I've seen many community members say, oh, this company will beat you all, but it's just because Super Rare starts a DAO and gives out a token; as I said, you can decentralize the community and decentralize the token. But at the end of the day, if the tech and protocols are not decentralized, there's still room to grow and things that we need to work on. I don't think that we need to get complacent as an industry. I believe that this is why I think in universes because I believe that we see the problems; I was taught these problems. I didn't see the issues either. I'm not the deepest code understander, so it took people smarter than me to tell me, hey, look at these problems in NFTs, and I had to go and do my research and understand it.

But that makes me more understanding that other people don't understand these issues. And some people are just going with the flow and winging it because of NFTs. 

**Troy:** Pretty sure most people don't understand it at all.

**Mark:** I mean, people can call us industry-like leaders or influencers, and even some of the best influencers don't even realize that these NFTs aren't what they say they are. So this is just something we're interested in fixing, and we can sit here and ramble all day. But until people start understanding why and asking why these things aren't going to get fixed, they're not going to get better. But luckily, we're working on it, but we'll move off the options. Those are significant updates that are moving into the final rounds of audits, and hopefully, we can get those pushed out ASAP. But just because it's finished doesn't mean it's getting released. We still have to test and ensure everything's good in the audit round. So just everyone be patient. But we're working as fast as we can. To finalize this call. We'll just kind of wrap up and reiterate.

## Yield Farming 🚜🌾 [[17:36]](https://youtu.be/VCk0fhQz8mw?t=1056)

I've been telling everyone the last few weeks that there are some farming opportunities. You go over to League, DAO or Enter DAO, you're able to farm. Then you always got some opportunities in the DAO as well. And I always just mentioned to the newcomers that if you're new to NFTs and crypto, I always recommend the DAO to learn about governance. You have to be staked in the DAO to vote. And if you never participated in governance, it's worth learning. I think knowledge is key in this industry, and learning about governance and why people are using governance, I believe to be very important. So just want to reiterate that you're new to NFTs and don't know about it. Troy had mentioned a proposal to come up soon to pay for the fleek services. So that'll be something that you'll be able to vote on in the next few weeks to a month. Like I said, if you're new to governance, you're going to have an opportunity to vote in the next few weeks and learn a bit of that.

## Proposal: [PID 4](https://dao.universe.xyz/governance/proposals/4) 🗳 [[18:55]](https://youtu.be/VCk0fhQz8mw?t=1135)

**Troy:** Actually, to separate something, another proposal will also be coming out. It will be the first signal, and it's around the multiverse. It has to do with the stuff I've been working on behind the scenes with many other people. And it will involve governance from an entity standpoint of protocols. And then, on top of that, you also get a good update on the projects occurring underneath the multiverse. Right now, there's a lot of development, but I'm not talking about it because it's kind of all in private repos, and you can kind of find it if you look for it, but things are moving along with that. I think that's a pretty good update. I'll just leave it at that. It might not come out until Monday just because, to be honest, half our team has been sick, and people have been catching up on everything that's been going on. This kind of just comes after, and people need to read it, so be on the lookout for that.

**Mark:** Also, Dragos. You have a net announcement about TMY.

**Dragos:** That's still in the works, man. That's still in the works.

**Mark:** Do we have any other updates or anything we want to say? No. Nobody wants to say anything.

Algy? Nothing. If Algy doesn't want to say anything, there's absolutely nothing left to say. Okay, here he is. He might have something to say.

**Algy:** No, I think we forgot to look at the project call questions in the Discord.

## Community Questions ❓ [[21:26]](https://youtu.be/VCk0fhQz8mw?t=1286)

**Mark:** Oh, nice. Great reminder. Let's go check that out.

**Algy:** Honestly, I was just looking at it, and I feel like I don't know the best way to word this, but some of these questions feel concerned, troll, and funny, but I don't know if that's okay to say, but they do. But, like what Mark was saying, I'm not going to say any marketplace, specifically in almost every marketplace. Still, I collect a lot in nearly every marketplace that currently exists, tries to say they're decentralized and that term is just so loosely used, and I don't even think people know what it means. When we release our marketplace, people will see what we mean. Like someone specifically brought up a marketplace that just dropped, and it's just not a good comparison to what we're building. I recommend you guys go check out Sushi Swatzby Marketplace. It's awesome. It's not a good comparison, though, to what we're building. It's a lot more basic.

**Mark:** I mean, to be honest, I wouldn't even really compare OpenSea to what we're building.

**Ryan:** Seeing questions about Sushi's Marketplace, and we love Sushi. We're big fans of Maki and the whole team, but they're not launching a marketplace from my current understanding. As of now, they're launching a curated drops platform, which is very different from what we are trying to offer. So if anyone was concerned about that, I'm not. And I don't think you should be either.

**Algy:** And then I think the other question was about advertising our minting platform, and we just aren't doing that because of the fact that we have more minting features coming relatively soon. And it doesn't financially make sense for the data. Start marketing to get new people to mine when all the tools aren't available yet. That was more of a beta feature that we just wanted to show people how the flow might work. Even that feature is subject to change. We just wanted to show everyone a beta, kind of just be patient with us. The core community of people in that Universe, Discord, knows precisely that. We're serious and building something that will impact the space and change the world. So if anybody has doubts, you guys should consider talking to some of the people in the general chat in the community, and they can reassure you. I've seen it happen all the time.

**Mark:** We could just fork it and stamp some cool UI on it and just say * it. Like, here you go. But we're going to build something cool instead of just the decentralized marketplace that everyone else is making.

**Algy:** As Mark said, the NFTs are going to be decentralized. It's more than just decentralizing the team and the community. It's also about decentralizing what you're building.

**Mark:** Yeah, decentralizing the assets decentralizing the token is essential too. But let's be honest. We want this * to live forever, and it's just what no one wants to talk about. What if all these IPFS notes go down? What if OpenSea goes down?

**Ryan:** I have an update on the data scraper. One tricky problem with building an extensive system like that is that many of those IPFS links are down. It's a very non-negligible number. Like, I don't have a specific percentage, and I can't say if it's like 20 or 30 or five or whatever, but we have ways of working around that because other places do catch these NFTs for now. But it is an obvious problem that IPFS alone is likely insufficient because these nodes do go down, and people stop pinning their content. So I know many people like you said, Mark, aren't worried about this for one reason or another, and it's because they haven't encountered the problems. The second their NFT is not visible anymore on the new platform they're testing out, people start to pay attention. Nobody seems to care about decentralization until it matters. Once it matters now, either it's too late, or maybe it's not, and we have made a lot of good progress. But that's something that I've noticed.

**Mark:** Very well said, Ryan.

**Algy:** Yeah, and I don't want to sound like we're not blaming anybody for wondering. We have had a couple of delays, but not similar to anything. But basically, the reason the delays happen is that we want to make sure it's secure and works as well as possible. I was going to say similar to some other projects that have had delays recently, but usually, it's not for no reason when delays happen on a project. There's a good reason that we're trying to make it work as good as possible so that when it comes out, everything is like we're saying, truly decentralized and the experience is the best.

**Mark:** And we're going to push the code that we said we're going to push. Like Tyler and Troy, our founder's track record in building the products. We're going to say some people have always said, hey, build faster, build faster. But at the end of the day, what we've said, we're going to build, and the products work, the tools work, and we're not going to take shortcuts. We're going to make a decentralized marketplace like we said we were. We're building as fast as we can. But we're trying to build something that no one else has built. We answered the community questions. I think we've told or have given all the updates. We love everyone. We love the community. We just want everyone to know we feel like we're under the gun. We want to push our products live as fast as possible. But as Ali said, we have to do our part. We don't want to lose anyone's NFT. We don't want to lose anyone's money. The most important thing is auditing these contracts and making sure everything is safe and secure.

So everyone, bear with us. We're building what we're saying. We're not taking shortcuts, even if it's going to save us time. So we're going to make this right, and we're sticking to our guns. All right, everyone, I think we're good. Hit like subscribe. Do something nice for your mom. Donate some NFTs for Christmas to your little brothers and sisters this year. I just want to say the next call will be like Christmas time. We may or may not have a project called online. Our next project call will be on December 7. But then the next call is going to be around Christmas. So I'll update the community if we have any changes to our call agenda. But there may be a chance that we either move the call or just have a really short updated call for Christmas time. But I just wanted to update everyone on that. All right, I think we're good. See you, everyone.

**Troy:** Wait, Mark, really quick. There will probably be the next call because we have multiverses coming down here in Puerto Rico on that week. So we're most likely having a pretty big update around that because we will be hosting that. So the one after that, that's Christmas. And so I would guess you probably won't. But we will have an update. We might even be doing it from the convention on some level that would be sick.

**Mark:** And just to update, thanks for reminding me. We have that Meta Versa event on December 7, 2021, in Puerto Rico, San Juan. So if you want to get away from the cold and get down to the warmth, beautiful San Juan in December. But also Ryan and I are going to Art Basel. Hit us up, and We're going to be down there.




<br>

### Project Links 🔗👇

* Website: [universe.xyz](https://universe.xyz)
* Project Info: [DOCS](https://docs.universe.xyz/)
* Twitter: [@universe_xyz](https://twitter.com/universe_xyz)
* Discord: [Invite](https://discord.gg/QnkfAG6X52)
* Youtube: [Channel](https://www.youtube.com/channel/UCWt00md9T2b4iTsHWp_Fapw)

#### Universe NFTs
* PolyMorphs: [OpenSea](https://opensea.io/collection/polymorphs)
* Lobby Lobsters: [OpenSea](https://opensea.io/collection/lobby-lobsters)
* STAND WITH UKRAINE: [OpenSea](https://opensea.io/collection/standwithukrainedrop)
* Core Drops: Coming Soon!
