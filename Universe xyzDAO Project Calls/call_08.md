# xyzDAO Project Call Notes– # 8

### Meeting Date/Time: Thursday 2021/7/15 at 14:00 UTC

### Meeting Duration: 30 mins

### [Github Agenda Page](https://github.com/UniverseXYZ/xyzDAO-PM/issues/18)

### [Audio/Video of the meeting](https://youtu.be/6NlsAzwf40M)

### Breakdown:

Moderator: Mark Ward

Scribe: Rayne L.

Attendees: Mark Ward, Tyler Ward, Nick Ward, Troy Murray, Ryan Shtirmer, Dragos Rizescu, Ilia Andreev, Zhivko Todorov, Stanislav Trenev, Algernon (Young Algy)

## Intro [[00:00](https://youtu.be/6NlsAzwf40M)

**Mark:** Hey everyone! Welcome to project call number eight. We're happy to have you back. 

There are a few things to go over today. We'll let Dragos kick it off with updates about the treasury page.

## DAO Updates (Dragos) [[00:15]](https://youtu.be/6NlsAzwf40M?t=15) 

**Dragos:** Hey, everyone! Thank you for the segway, Mark.

We're working on a new release for the front end of the app. (the DAO - to be specific because there are multiple apps)

To explain in detail, we are adding a treasury page for the DAO. The update should be live later today or tomorrow morning. 

More importantly and likely, what everyone is excited for– the airdrops. That will go live soon as well. I'll let Mark and Ryan talk more about those dynamics. So, back to you!

## Airdrops (Mark & Ryan) 🚁🎁 [[01:00]](https://youtu.be/6NlsAzwf40M?t=60)

**Mark:** Okay, thank you, Dragos!

I'll start with the airdrops and touch base on the dynamics of it. We want to be super clear with everyone. We'll end up releasing some articles over the next few days. So everyone can get their information, whatever way they absorb it.

Look to Medium for an article on how that will work.

> In case you missed it; [Medium: $XYZ Airdrop](https://medium.com/universe-xyz/xyz-airdrop-8a48f085611b)

### Updates & Dynamics

Essentially, you can only claim once. 

Once you've claimed, you are removed from the pool. There is no claiming twice– it's not like the yield farms where you can claim every week. The airdrop will be completely different. The longer you stay in and the more people who exit, the more tokens you'll accrue. But, if you leave early, whenever you hit that claim button, you're done– you've exited the airdrop. So, what you see on the UI in the claim section is what you'll receive.

We want there to be no confusion surrounding the claim. 

*THERE IS ONLY ONE CLAIM FOR THE AIRDROP.*

It will get clearly stated in the article that we'll release. We'll make tweets and make sure to remind people in Discord. So, everyone needs to know this is not the same as the yield farms where you can claim every week. 

It's one claim, and you're done, forever.

I believe that's the critically important part.

**Tyler:** Yeah! 

Everyone, **ONE CLAIM** and you are done **FOREVER.** You **CANNOT* claim weekly. 

- Stay within the Opium contracts you will get rewarded.

- Claim early. You will get penalized. 

It's one claim, and you're done, forever.

**Mark:** Yeah, one claim!

I think Dragos mentioned the airdrop goes live Monday at midnight, which is late for us– 8 PM Sunday –in the Eastern United States. 

**It's Monday, midnight (00:00) UTC.** 

We are extending the airdrop to 100-weeks. Our original plan was to have the claim theory run for 20-weeks, but we prolonged it by 100-weeks for security reasons. We wanted to reduce the risk of having a coordinated attack on the DAO– because of the number of tokens we released.

For cautious reasons, we wanted to extend that. We believe it makes it more fun. And it matches up with several other tokens getting distributed, so it works out well. 

### Breakdown (Pooled together)

I can also reiterate the revised breakdown.

- Polymorphs Holders 3% (Snapshot)
- Discord 3% (Snapshot late February)
- Original Bidders 2% (Frogs - NFPs)

Everyone should know who they are by now. At this point, you know if you're getting an airdrop or not. That airdrop will be claimable via the yield farming page. All of that information on how to claim the drop will be available in the Medium article we release.

I'll pass it over to Ryan. He will give an update on the auctions and minting platform– that we've been developing.

So, Ryan.

**Ryan:** Hey guys! Before I jump into auctions and minting, I want to add one more thing about the airdrops. 

There is a 100-week period of a bonus, but there is an additional 69-weeks afterwards. So, you don't have to worry about timing your exit perfectly at the end. Once the vesting period ends and you've waited for 100-weeks and claimed immediately, or if you forget. You still have a year's grace period to get your tokens out of the contract. There's no reason to be concerned on that front.

Okay, airdrops out of the way. Everyone is super excited.

**Dragos:** One more thing. 

You can go to the XYZ DAO page and see the claim area. You can watch your available balance increase. If you wanted, you could do that every hour of every day, for 100-weeks. 

So, good luck with that. 😀👍

**Mark:** Like the Zapper fi refresh button. People want to get their XP. 😂

**Ryan:** Wait...are airdrops an elaborate yield farm? What?

## Auctions and Minting 🥼⚗️ (Ryan) [[06:42]](https://youtu.be/6NlsAzwf40M?t=402)

**Ryan:** So, auctions and minting. We've been working on the contract for a long time now– nearly six months. We're happy to say that the internal code audits of the Smart contracts. It's 0.1 KB (kilobytes) smaller than the maximum contract size. It's action-packed & full of features.

We're very excited about it. Once we've finished up the internal audits, we'll send those over to Certik. We'll have back & forths.

The goal is to launch this and allow everyone to use Universe as a minting and auction platform– with an eventual marketplace. For now, you guys are close to getting auctions and minting. I don't have a ton more to talk about there because we're not going over the auction mechanics today. 

But we're super excited about this. 

**Mark:** Yeah, next call, we'll probably dive in deep into the auction mechanics. Ideally, we should be pretty timed (or close) to getting everything ready around then. 

So, we'll discuss that more on the next call.

The next thing we'll talk about is the rarity charts. 

## Rarity Charts ⚖️ 📈 (Nick, Al & Ryan) [[07:50]](https://youtu.be/6NlsAzwf40M?t=470)

**Mark:** One thing we want to talk about here– I'll let Al, Ryan and Nick talk about it more –we ended up needing to develop rarity charts. The community started working on this. 

It seems that rarity tools told us that their platform could not support Polymorphs. The properties change. So, we have to figure out how to do that ourselves. 

Ryan, Nick and Al will elaborate further because they played a large role in discussions about this and getting this planned out. 

So, whoever wants to talk about this can. 

**Ryan:** I can start, and then the boys can jump in and give more details as they feel necessary.

I want to note– off the bat. Not only were we not able to use rarity tools because they can't handle dynamic rarities. Also, another issue, Polymorph rarities do not work the same as other projects– that are typically percentage-based. So, traits are not 2% or 6%. Everything may seem rare when you look at it, but that means nothing is rare. 

There is an elaborate rarity system that we designed. It models your rarity exponentially. It has a beautiful formula that you can already see from a Google sheet that's getting tossed around the community. Everyone is excited about it. It takes into account how many matching traits you have in a set as the base. Then there are tons of possibilities whether you scale higher or lower depending on what type of set it is. Whether a Polymorphs a virgin or a complete set. With or without colour mismatches.

So, a bunch is going into this. 

**Note**– this rarity score is not finalized.

We're still working it out. So, if you're going to Opensea and attempting to ape into the ones you believe matches the highest formula for rarity, you may not end up with the calculated rarity that you measure now. 

So, do keep that in mind.

With that being said, it is exciting. The backend is coming together, and the front-end designer is putting together a leaderboard. Several other things will take advantage of the rarity system via the front-end for the entire Polymorphic Universe.

**Mark:** I think another important thing that should get mentioned or repeated. In the formula, no item is valued more than the other. It's a combination of items that may have a stronger rarity than others. Consider that every torso will have +1 or something. (no armour is more valuable than another )

The combination is where the rarity lies. At least, that's my understanding of the equation that's built.

**Ryan:** That's correct, thank you, Mark.

**Nick:** Also, being a virgin, non-scrambled or naked. 

**Mark:** Yeah, there are some bonuses for that too. 

**Nick:** We're trying to stay non-bias. From general community discussion, we've realized that the naked and the virgins will get rare and sought after in the future.

**Mark:** Yeah, and I think one point as well. Our formula makes it extremely hard to predict. A naked Polymorph would get a '0' trait. However, I believe that no-trait is a trait itself. I'd have to run the math on that to see if that works.

We're trying to figure it out– it's more complicated than we had originally thought.

**Nick:** Yeah, another thing to point out. It's still a work in progress. The Google document that is floating around the Discord is a public document. You can comment on it, and we'll change it. The community appears to like the ability to comment. 

**Mark:** Yes, the community has been helping. I believe it was the community that started the rarity tools. So, shoutout to the community for that. For pushing us to help get that going. Once we discovered that rarity tools could not support it. But, shoutout to [rarity tools](https://rarity.tools/)! What they do is very cool.

**Tyler:** Rarity tools straight up said, "No."

**Mark:** Yeah. 😂😂😂

**Tyler:** It doesn't fit their format. 

Shoutout to Ryan. For spearheading tools with the community. And shoutout to Nick for driving in the final hammer. 

Nick and Ryan did the hardest work of it all. They colour-coded the entire sheet.

**Mark:** And Aly did a lot too.

**Tyler:** Yeah! 

Shoutout; to the community, Nick, Ryan and Aly.

We're dropping unique rarity tools because it's a unique drop. 

**Al: The rarity tools that we drop will show people how rare things are based on how well their traits match. It's as simple as that.

**Mark:** Aly, do you want to talk to us about the Polymorph lore that got released over the last two weeks?

It was a good bit of information. I don't think everyone is in the Discord– I'm also not sure if we've posted the lore anywhere. We may have posted it on Twitter.

**Tyler:** I posted it on Twitter.

I think before we discuss lore, we should have an internal conversation today or tomorrow. We have the other drop with the characters and a few other things coming out. Additional elements have been worked on since that happened.

**Mark:** We're only discussing the Polymorph lore.

**Tyler:** Even so, I believe it will get affected by the additional components coming up. 

We can talk publicly about it, although I want people to understand that it's in flux. We're actively fleshing it out. It's probably going to change slightly. And for various reasons relating to contracts that allow you to burn then mint. OG characters could get thrown into this.

I'm not going to say much because I'm unsure how it's going to play out. All I'm saying is that the lore is in flux and changing because the project is constantly being upgraded and changed. (dynamic developing)

We're making Aly's job harder. I don't want him to commit to anything particular on this call– until we flesh everything out.

**Ryan:** With that said, I reviewed some of the changes with Algy yesterday. And it does not seem like some of the newer and exciting things we are building won't conflict with the existing lore. At least for now. (Polymorph lore will not cause an Alpha leak as much as some may expect)

That's subject to change.

**Tyler:** Alright, we'll let Aly pop off. 

I saw someone on Twitter a bit ago say that the Universe team talks about everything they're building. 

It said, "A little less talk and more action."

So, I'd like to highlight it for everyone. Since February, we've dropped Non-Fungible Pepe, an extremely technically advanced DAO, yield farms (with 100's of millions staked– and no technical issues) 

We dropped Polymorphs. I still have the opinion that they're the most technically advanced NFTs ever dropped– thus far.

So, try again.

**Mark:** There's a bunch of shit that we haven't dropped yet. We're still waiting to drop auctions and minting contracts that we've spent months on– they're getting audits.

**Tyler:** And we still have the airdrops coming up.

I'm down to let Aly talk about what he's been working on– now that Ryan said his piece. 

## Polymorph Lore  🧫🦹📖 (Al) [[17:26]](https://youtu.be/6NlsAzwf40M?t=1046)

**Al:** As Tyler said, everything I'm working on is fairly unofficial right now. It's subject to change.  

The Polymorphs live in an alternate universe from us. In their realm (Universe), they constantly switch between parallel dimensions. In turn, they enter new lives/timelines.

It all starts with a battle. Every Polymorph is spawned in the same realm together. Everyone sees each other then. All the Polymorphs are mad and confused because they don't like their outfits. None of them match. They all argue about who looks the coolest. 

From there, they all begin fighting with their varying weapons. During the fight, they realize that none of them can be killed by one another. And so, it escalates very far. There are specific Polymorphs that take "too far." Eventually, it leads to groups and cliques. Which devolves into a cease-fire as none of them can defeat each other.

After the cease-fire, they all begin working on different things. Because they are getting bored, they are stuck together and do not know why. At this time, they all discover new technologies. (which I will not elaborate on yet)

However, some of the new technology they develop allows them to scramble. What you guys already have access to– with your Morphs. 

When they scramble, it sends the Polymorphs to new realms. (This is where it becomes more intricate) 

A lot of them were ready to leave. The majority started scrambling themselves right away. Others stayed because they are nervous. Some want to remain virgins. (unscrambled)

The term 'Virgin' originated in the first realm as a designated label for specific Polymorphs. An ideological debate about the moral obligation to remain unscrambled left certain Polymorphs with a question to stay pure or follow the path of the others. (It's not a label that's widely discussed, however many from the first realm fall into this category)

In the later realms, virgins are widely discussed and referred to when distinguishing from scrambled Morphs. (realm hoppers)

So, it's a ton of different realms. When one is scrambled, it changes dimensions, and there may be people there. It's not like they are sent anywhere by themselves. The only realm where they are by themselves is the first realm where they all see each other.

As soon as they scramble to a new realm, they will see new things in that realm. It can be anything. Every time they scramble. Polymorphs are taken to a new dimension, where who knows what is going on.

I could elaborate further, like specifically what's happened with certain Polymorphs. But, that's more so up to the community. They need to tell us more about their Polymorphs. 

You guys have them. You may not realize it, but you also control the story behind your Polymorph. So, it's up to you all to explain what happened to that Polymorph– to us.

I have a bunch I'll get into explaining some of mine. Later on, once I know more. Because there are still things that I'm learning, Polymorphs are still revealing information even to us. The lore is still getting expanded, and It's all unofficial for now. 

The things I just said may be subject to change. That is why Tyler is kind of nervous about me saying anything. It's not set in stone, and I don't want it to limit what any of you guys come up with or how you want the lore to be. 

So, If you all believe the lore I just said sucks, feel free to send an adjusted version that is more along the lines of what you all think it should be. We'll review that and consider what you think– and what may be a better idea.

As I said, I want you all to expand on the alternate universe idea. Tell us, the first time your Polymorph scrambled, where did it end up? 

What happened to it? 

How does it feel about that? 

That's essentially it.

**Ryan:** Now, Algy, if I understand correctly, the Polymorphic scientists have not discovered everything that there is in the Polymorphic Universe, is that correct?

**Al:** Yes, exactly, they all work together. They're trying to figure out all of the different things that you can do. There is still more to discover.

**Nick:** You might have to talk to Zee about that. He knows all about it.

**Everyone:** 😏😏😏😏

**Al:** Nick's saying that some of our devs know little secrets about that– which they haven't told us. I don't think you'll learn that information on this call. 

**Mark:** The devs are working on a lot of stuff they won't even show me yet.

**Tyler:** Zee, what do you think about this?

**Zee:** We do have some ideas/details that we haven't released yet. So, I like the lore, and I love everything that is happening around this. 

We didn't expect it to blow up this much. Although, we are excited to start building more on top. There is a lot of cool shit coming out.

**Mark:** I also personally think...(I'm not sure if anyone else has noticed) I've been on Twitter the last few weeks– like everyone else in crypto –and I've been seeing the Polymorphs growing on some people out there. I see you. 👀

**Tyler:** Zee and George, the ones who came up with the idea for Polymorphs. (both are devs and advisors for the project) They could have done this drop independently on the platform. But, they brought it as an idea we can develop for the betterment of the Universe. 

All of our designers worked on the artwork based on the concept. So, they get a super special shoutout as all this continues to unfold. 

It's a very selfless move on their behalf. In my opinion, it's also a dope-ass idea. I don't think George and Zhivko have gotten enough love– for how all of this rolled out.

**Zee:** That's greatly appreciated. I'm super excited to prove all the haters wrong who have been bashing Polymorphs on Twitter. There is a fair amount of stuff we are going to continue to build around them. 

**Al:** It's almost funny if you know the Alpha. 

**Nick:** Best way to prove the haters wrong, baby!

**Tyler:** If you know, you know. 

That should be the tweet.

**Ryan:** Yes.

**Zee:** PGMI. 

- **P**.olymorphs
- **G**.onna
- **M**.ake
- **I**.t

**Nick:** PGMI.

**Tyler:** We are not talking about price here. But, we are talking about art.

**Nick:** I'm talking about the tech, baby. That's what Zee and I are here for.

**Tyler:** I'm here for everything. 

**Zee:** The science.

**Tyler:** The gene therapy.

Let's keep going. I believe we can wrap this up. We have another call after this one to go through some internal stuff.

**Mark:** Yeah. I think we've gone over everything. So everyone, thank you for joining us.

Hit like, subscribe, share with your frens. Read posts on Twitter. 

We appreciate everyone.

## PSA 📣 (Tyler)[[26:21]](https://youtu.be/6NlsAzwf40M?t=1581)

**Tyler:** Actually, one thing I would like to bring up for the community so that everyone knows– to sum up, this call. 

We got several tweets this week about the DMCA stuff that had to do with CryptoPunks.

They turned to the left. We've talked a lot about decentralizing the tech stack. Having a DAO run a concept like Opensea. Nate, who caught a ton of flack, he's my friend. He worked with me at Token Foundry. (I'm a very big fan of him from both the human/technical perspective) 

All I want to say, the DAO will need to put mechanisms in place to monitor content on the platform– when it can hurt the platform. There are very nefarious things (not even from a DMCA perspective) that we'll need to have mechanisms in place to prevent bad situations from happening. (DMCA is still included)

Maybe long term, technology gets built that allows for the community to monitor those aspects. But, we're not technically or legally there at this point.

So, I would like to be very clear: **When we launch the minting/auctions and later the marketplace. We'll have to establish committees that are voted in via the DAO. They'll help us moderate content.** 

There are no ways around this. It's not a free-for-all or post what you like. If that's advertised to the ecosystem and Twitter, we'll attract very nefarious people that will do bad things with the platform. 

And this isn't a silver bullet that fixes all and allows anyone to say whatever they want. 

We'll need to install guardrails. If we receive a DMCA letter– we're extremely likely to comply with it via the council. 

It may not be us who receives the request. However, we do not want the entire system to be shut down because people are posting Nazi propaganda. I don't know where it heads long term. 

We want to build an uncensorable system, and communities can govern themselves. But, out of the gate, I don't want people advertising that we are a place that you can post whatever you want, and it's completely unmonitored. We're going to need to establish guardrails. They'll be decided and worked on with the community. However, it's ill-advised to post to Opensea that we can do whatever we want. Plagiarizing content is a problem– for artists as well as platforms.

So, this is a PSA for everyone in the community. I don't know where the conversation started or where it stemmed. However, we are not the silver bullet. Day one, when we launch, it will be a fight against that. It'll be a long, ongoing piece of tech that is written. Then a long discussion with the DAO, community and everyone else. 

The biggest thing is; it will be a community-led decision. 

**Mark:** We are also going to have to figure out how to decentralize this so decisions can get made by the DAO– without the debate dragging along and it taking forever to enact change. 

It will be something that we need to figure out over time. We think this is why people are working in decentralization. To take the leap and try and solve these problems. 

Or else, why do we have innovation? If there are no people who choose to step outside of the box and do this.

I think those were great points, Tyler. That should wrap it up. 

Unless anyone else has anything to say?

**Nick:** PGMI.

**Zee:** PGMI.

**Mark:** Alright, thank you, everybody.

Join us again in two weeks for the next project call.

Hit like, subscribe, please share!

We'll talk to you all soon. 

**Everyone:** ✌️✌️✌️✌️✌️✌️✌️


<br>

### Project Links 🔗👇

* Website: [universe.xyz](universe.xyz)
* Project Info: [DOCS](https://docs.universe.xyz/)
* Twitter: [@universe_xyz](https://twitter.com/universe_xyz)
* Discord: [Invite](https://discord.gg/QnkfAG6X52)
* Youtube: [Channel](https://www.youtube.com/channel/UCWt00md9T2b4iTsHWp_Fapw)

#### Universe NFTs
* PolyMorphs: [OpenSea](https://opensea.io/assets/polymorphs)
* Core Drops: Coming Soon!
