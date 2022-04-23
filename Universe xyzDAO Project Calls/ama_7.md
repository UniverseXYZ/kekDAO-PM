
# Universe XYZ AMA Notes– #007

### Meeting Date/Time: Wednesday 2022/3/9 at 20:00 UTC

### Meeting Duration: 90 mins

### [Github Agenda Page](https://github.com/UniverseXYZ/xyzDAO-PM/issues/45)

### [Audio/Video of the meeting](https://youtu.be/1q0eM9tKe_o)

### Breakdown:

Moderator: Mark Ward

Scribe: Tammy M.

Attendees: Mark Ward, Tyler Ward, Tim Kang, Troy Murray, Ryan Shtirmer, Dragos Rizescu, Cezar Paraschiv, Pavlo Bendus, Dmytro Dutka, Ilia Andreev, Zhivko Todorov, Stanislav Trenev, Andon Mitev, Algernon (Young Algy), Nick Ward

## Intro

## Marketplace Update

**Mark:** The main update in the Marketplace is coming in the next few days. We will try our best to deploy the contracts and then create a DAO vote to launch the protocol. Our goal is to do that within the next few days. I'm not going to give an exact date. 

**Tyler:** We are going to try for Friday.

**Troy:** Let me put it this way. We are forming the proposal right now, and we plan on putting it in on Friday. So we're there, people.

 ## Pre AMA Question ?

### **Question:**

We're going to jump right into the first question, resistance; What if someone plugs into Universe and makes a Marketplace on their website? Will Universe get a portion of the fees from the trades there?

#### **Answer:**

**Tyler:** Yes

**Troy:** Yes

**Mark:** Yes

**Troy:** There will be a front end that has the ability to plug in and use it, and there will be a finder's fee, and the front end will be able to keep it. The main protocol itself, which is the DAO, which is Universe, will get a cut. So it's being designed to incentivize other front ends to use the back end and our Marketplace so they can be sustainable, but it also sustains the protocol.

**Mark:** So I think that answers that. 

### **Question:** 

The next question is; When to vote? 

#### **Answer:**

**Mark:** Hopefully, Friday, if all goes to plan.

**Troy:** There's a warm-up period. On Friday, everyone will have a couple of days to stake their XYZ. If you don't have a stake once that warm-up period is done, there will be a snapshot and whoever was staked during that warm-up period. You will then be able to vote. It will start Sunday, or it's going to start Monday. I don't fully remember right now. You will have four days to vote so that you have ample time. Just make sure you're staked during the warm-up period. You will have this weekend to get in. We don't see any reason not to put the proposal in on Friday unless something catastrophic occurs, which I don't foresee happening.

**Mark:** I went and read ahead, Troy, I think these next few questions might be best for you to answer, or you can decide what to answer. 

### **Question:**

But Chad has a series of questions; The first one is, Why must we vote on a proposal that would never be voted against? Is it only for legal reasons that the team distributes responsibility and aligning incentives? I guess that's the first question.

#### **Answer:**

**Troy:** I can answer that. It's a bit of both, but it's better if a community wants to launch something like this. It's better to show that the whole community is activating it so everyone can share in that. Obviously, there's some legal stuff around that, too. I'm surprised more DAOs don't do it that way.

**Mark:** Tyler had a few talks with other Founders in the industry, and they had also recommended that we do it this way. Chad had some other questions.

**Tyler:** I thought we should have minted the minting contracts through that. But the exchange of NFTs themselves is an NFT exchange, and it's run by the DAO; it should be activated by DAO. We probably should have gone through that process for the minting.

**Trevor:** You can see some information about our minting and Marketplace and our Auctions in our white paper. 

**Mark:** Chad, the answer to these other questions is that I think this came up within the last month and a half, and we decided to do it this way.

**Tyler:** We decided that we should go through the process on the finish line. I think that we all agreed that it was the right move. That week will be excellent for us to deal with kinks. It is done and are going through the DAO vote process.

**Trevor:** The community is going to be able to audit the contracts when the DAO proposal is launched. The contracts will be in place, and the DAO proposal is specified that the DAO is the owner of these contracts. So this will allow the community to review our work. If something is wrong, we can always not pass the vote or abrogate the vote. We can always iterate if something's wrong. I don't expect that will happen, but it gives the community the chance to review our work, review the smart contracts, and make sure that everything is 100% solid before it actually goes live.

**Mark:** That's an extremely good point, too. 

### **Question:**

James asked a question; What were some of the Kinks holding up a launch? 

#### **Answer:**

**Mark:** We have just had some issues with our back-end Scraper. It was testing and fixing things when you're building something like this. It seems like once you fix something, another thing breaks.

**Tyler:** You're also launching a large piece of software.

**Troy:** This is a full-on application that had to be worked out. This isn't just launching smart contracts into the network that are going to run. There's a software application behind the whole thing. Working through those kinks and edge cases takes a while because it's not simple; it's not just running computations on Ethereum. It's a very sophisticated application that takes time, and we've all learned that the hard way.

**Trevor:** The Data Scraper is very complex. It consists of 10-12 microservices—multiple replicas of each of those microservices that analyze the entire blockchain. Every NFT and every transaction that the NFT has ever been a part of. So it's not just the wallets connected to Universe; it's the entire blockchain. We've gone through many iterations of improving this. One example: We are now looking for an improvement where the Scraper runs forward and backward in time. So that we can give it a star block, which is a recent block, and it monitors all the recent transactions. Then it also goes backwards in time to get all of the most recent transactions first, as opposed to starting three years in the past and going forward from there. There are a lot of very complex parts to this project, and I'm confident that it will be perfect by the time we release it to the public.

### **Question:**

James F's next question was; Why is the XYZ price bot gone? Any reason for that? 

#### **Answer:**

**Mark:** It's just in the Universe dash. It's not under crypto price bots. So the crypto price bots are ETH and Bitcoin, and then you have the XYZ price bot right above in the Universe dash. 

**Add Speaker:** I was just saying. Yeah, it's back now, but it was gone.

**Mark:** Okay. Maybe someone fixed it.

**Tyler:** It is a bot, so it goes down sometimes, like in fear. It can go down. 

**Troy:** Discord can go down, the botmaster. Some of those things probably had to get turned back on.

### **Question:**

Autobobro has a question; What is the decentralization model of Universe XYZ?

#### **Answer:**

**Tyler:** I don't understand that question.

**Mark:** Our model is to decentralize everything we can, look at the industry, and decentralize the centralized aspects. We will continue building and trying to decentralize everything we can around NFT. Our main goal is to centralize every aspect of this protocol.

**Trevor:** There are certain things you can't decentralize on the blockchain right now. You can't put kubernetes and a database on the blockchain. We can decentralize respect to the smart contracts with respect to the DAO proposals. But there are just certain things that still have to be on Web, too.

**Mark:** Eventually, and hopefully, there are ways to decentralize some of these things, and we'll get there, make proposals, and build towards that.

**Trevor:** As soon as the internet, computer or fleek are mature products, we will certainly be looking at deploying there. Right now, it's just not quite at that stage yet. We still need certain components that are on cloud providers. There's just no way around that right now.

### **Question:**

Chad has another question; What does the autonomous part of the DAO first governance model mean to the Universe team? In other words, how will Universe continue to remain governed with autonomy as its distribution continues?

#### **Answer:**

**Tyler:** The autonomous part is that the contracts run, and no one can turn them. We could shut down the front end that runs the DAO. The contracts run autonomously. So that word of it is saying that it can run autonomously from utilized authority.

I was just saying that the contracts run autonomously from any centralized entity. So it's a decentralized organization that runs autonomously. It doesn't need a centralized entity running autonomously as distribution continues. The point of that is that the plan for distributing more of the token is to put it in the hands of more people. Depending on what the distribution cuts ultimately look like. Fewer people can push a DAO vote forward than the POAP would. Then it becomes more and more decentralized, meaning there are more holders for voting and partaking in governance on the network. 

**Mark:** And that's the beauty of a decentralization team. AlgoMagicBeans has a question.

**Nick:** I just want to say something because I got a DM from a fake Polymorphs announcement. Where obviously not minting Polymorphs, don't click on any DMs ever. We're not going to ever DM you. Rayne and I are going to ban these people.

### **Question:**

AlgoMagicBeans question is; Are there any features that will come with the release of the Marketplace that other key competitors will not have? 

#### **Answer:**

**Mark:** I think Chuba's favourite feature is that we will have an on-chain order book. I don't think that anyone in the industry has that. Chuba would be the best person to explain why that is more powerful. The way I understand it is that when you have on-chain orders, like how OpenSea has front-end hacks, it's harder, if not impossible, to hack. One of these on-chain orders is from our front end or another front end unless you interact with the contracts that are bugged.

**Trevor:** We've had the contracts written for a while on-chain orders. I don't think they will be releasing the first version of the front piece in the first sprint. I like them because other contracts can hook into them and leverage floor bids if they need a source of NFT liquidity. We'll see what kind of cool things people can do with it.

**Mark:** We will be the first decentralized protocol Marketplace. Zora is a protocol, but they are a centralized entity, and we are not. We are a DAO, and it goes back to that decentralization talk. 

### **Question:**

Today, we've had some of these questions; Why will we deploy our contracts with the DAO?

#### **Answer:**

**Mark:** That is how it needs to be and how it needs to be done. Hopefully, if you're listening to this conversation, you've already heard why we've been doing that. Thank you for the questions. I think that we answered the rest of this question. 

**Mark:** but we will bring bulk listings and all sorts of floor bidding and cool stuff like that. But as Chuba says, we're going to bring a lot of those things in on the 2nd iterations because the best way to scale this is not to put it all up at one time. It releases it in segments, but we have a lot of work that we've done, and we just want to release it in sections just because it's easier to maintain stuff from breaking, and you can find what happens easier. It's just a better way to do this from a development standpoint.

### **Question:**

James asked a question; the question is about Dev teamwork. 

#### **Answer:**

**Tyler:** That would be a major move towards centralization. I'm not a Dev. I don't know if Troy wants to add to what I'm about to say. I would say that we placed more trust in Dfinity working than what it probably deserved. The coming year will determine if Dfinity will quote on quote 'work'. Right now, it doesn't. I know Troy's talked to quite a bit. I have nothing but respect for Dfinity.

I wouldn't say that it works for any of the use cases we need it to right now. But what they're building is ambitious, and I respect that team and hope it will work at some point. 

**Trevor:** Yes. Agreed.

**Troy:** I would say it's probably still pretty far out, but I know they're still developing. It's entangled in internal stuff going on. So I haven't talked to them in a while, but it's on my list to reach out to them soon. There is just a bunch of other more important stuff to get done. Then we have some other solutions that we're cooking up that will help alleviate some of the stuff we are planning on Dfinity doing, so stay tuned for that.

**Mark:** We're building a lot. 

### **Question:**

ChicagoNine has one more question; I think we've answered this in the past. It goes back to the question last week about Fiat On-Ramps. Will Universe deploy to Moonbeam? 

#### **Answer:**

**Mark:** I'm pretty sure that is what OpenSea uses so that you can use a credit card. We are not planning on using any type of Fiat On-Ramp system like that for our Marketplace right now.

**Troy:** Can I jump in on that one?

**Mark:** Yeah.

**Troy:** It's tough to set up a Fiat On-Ramp with a DAO because you don't have an entity. It's completely impossible. But what we are doing is incentivizing those Marketplaces that are those front ends that attach onto our back end, and they can facilitate those types of connections. Graviton itself is an entity that could do something like that. I would say Universe won't use it, but I would expect to see other front ends to use it.

**Mark:** That's a great way to put it. That is all the questions we have asked Algo if, Dfinity ICP blockchain, and it is yes, it's a cool product. They have some cool chats over there, and they're cool people. We definitely wish them the best if nobody has any other questions.

**Tyler:** Other than that guy, James, that is a good idea once we launch the Marketplace; I think a spreadsheet with just generalized sprints is probably a good idea so that you know what features are coming. Because you're right, it will constantly result in a bunch of questions. So maybe that's something that I like.

I think that's something that we could do for the newsletter. We had plans to do a newsletter, and then our Marketplace had gotten delayed, and I think we have a lot coming out between the Polymorph. Our minting contracts are a lot. James is saying notion. Maybe a public notion would be good.

Maybe Mark and Rayne can help put something like that together. We use notion so that we will create it as a public notion. It's a good idea. We'll figure out a format that works.

**Mark:** Rayne loves that kind of stuff. Rayne was asking me about it the other day. He said something like that, but he wanted it for himself. A lot of requests have come through the support. We have been taking feature requests and putting them into our internal slack. We can create a feature request channel, but sometimes the discussions get a little bit lengthy. Then you don't know the best place to go and look for and say here's the list. We're taking the feature request through the support or how they've just been coming in. I'm sure we already have a channel about feature requests. Maybe we archived it.

**Algy:** Doing it through support tickets makes the most sense because you can save that conversation. 

**Mark:** If you look in the ideas channel right now, there are some serious dynamic royalties. These are great suggestions. I'm pretty sure we already have pretty dynamic royalties. We've been working with Tim Kang on that, and you will see that as the Marketplace launches.

**Algy:** I told our team that I agree with this point, that Rhino Zeros makes that once we have our Marketplace release, work on creating, what he's saying, a home page that just brings people straight to the Marketplace. I'm pretty sure that we already have a V2 homepage. 

**Mark:** Dima has been working on this, and I think we will be able to make that happen, but not right away when it launches. It'll come through as we scale everything and get everything attached. I don't think we have any more questions.

## Feature Set

**Trevor:** I've got a few quick notes regarding the feature set and how we compare.

**Nick:** Along with feature request stuff, I'm working a lot on putting together community checklists and guides that can be used to make your way through the ecosystem. I also want to work on standards and terms used frequently and consistently so everyone is on a similar page.

**Trevor:** I've got another couple of quick comments about feature sets and how we might compare it to competitors. Just because we're a DOA and our stuff will be open-sourced is one of the primary things. We have a non-anonymous team. If you compare us to Looks Rare, that has a completely anonymous team, that all of their stuff is completely closed source, and it also all depends on the OpenSea API, that's just weak. Our stuff doesn't depend on OpenSea at all. We have an anonymous team, and we're going to open source as much of our stuff as possible. You'll also be able to use our APIs to build your own applications. 

Then as far as specific features, I can't drop too much alpha, but we do have several killer features that are right on the horizon that nobody else in the ecosystem is doing right now. The Scraper is the boss. Nobody has a Data Scraper as advanced as ours. It's looking at the entire blockchain, every single NFT, every single transaction that's ever happened. So it's been a massive project. That in itself is one of the things that sets us apart from Looks Rare. It's just pinging the OpenSea API and pulling down the transactions for only the user that signed in.

**Mark:** Are these the docs for developers to integrate with Universe? We haven't released the docs yet to integrate with developers, and they are going to come right after we launch everything and is exactly where you will go, and yes, this is where it's going to be. We'll have how to connect to APIs and how to connect to certain things. Then we'll even add a UI tool kit so that people can take UI from Universe and add it to their front end if they want. 

**Algy:** I have a question for Zach. Honestly, do we have any updates as far as polymor floor, besides the fact that we're getting more focused on it? The community has created a lot of the lore around Clown Charles and the scrambling functions. We've been working on having more built out like lore for the Polymorphs. We'll have some updates as far as Polymorphs and what they're doing because you guys are wondering. Where are the Polymorphs, and what are they doing? 

**Mark:** The polymers are going south by southwest. We're going to FLUF World. FLUF house. 

**Algy:** There's so much fun stuff for the Polymorphs and cool stuff that we have ready for. That's why I hoped I could share a little bit of content on the Polymorph. 

**Mark:** We're not telling anybody about that. Okay, we'll talk soon, everybody. We're out of questions, and we had some really good questions. Thank you, guys. I think that led to a good discussion. Okay, thank you, Chad. We love you all. We'll see you all soon—next week.

**Rayne:** I will say I recently just pushed the call notes; they've been delayed; we just did 14 to 20. Then we'll do the AMAs once we figure out the best format. Then you guys can always easily reference just all the project information that's come out over the months. There's a lot there, honestly. A lot of questions that are frequently asked are there. So I'll convert those to articles for the knowledge base, so that stuff will all be easy to find in time.

**Mark:** Zach might be lying. He might do it everywhere. He's psyops you all hard. All right, we appreciate you all, and we'll get back. Okay, guys, we love you all.




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
