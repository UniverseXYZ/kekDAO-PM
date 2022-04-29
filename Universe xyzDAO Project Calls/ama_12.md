# Universe XYZ AMA Notes– #012

### Meeting Date/Time: Wednesday 2022/4/13 at 20:00 UTC

### Meeting Duration: 56.5 mins

### [Github Agenda Page](https://github.com/UniverseXYZ/xyzDAO-PM/issues/49)

### [Audio/Video of the meeting](https://youtu.be/bt-XOOY0oY0)

### Breakdown:

Moderator: Mark Ward

Scribe: Tammy M.

Attendees: Mark Ward, Tyler Ward, Troy Murray, Ryan Shtirmer, Algernon (Young Algy), Nick Ward, Rayne Leach, Zach Owens, Trevor Latson

## Intro

**Ryan:** Thanks everyone for coming! Welcome to Universe AMA #12. 

We have a handful of exciting updates for you on Marketplace priorities and what we are working on. 🛠


## Universe Updates [[00:25]](https://youtu.be/bt-XOOY0oY0?t=25) 🌌 ⏫

We are upgrading our infrastructure to be powering the front-end from something called Amplify Now. The major benefit it gives us is that we can run Next JS applications and enable SEO more explicitly Open Graph. For those not familiar with [Open Graph](https://ogp.me/), you can see its image and name when you send a link to an NFT on Universe. You can also send Universe links on social media over text, Twitter, and Discord. You will see support for that shortly, and we will make an announcement.

The next thing was 1155s. Our scraper is supporting 1155s, and over the next week, they'll start showing up in your wallet. We will enable 1155 support for the NFTs and then for trading the NFTs. We're solving the partial fill problem because ERC 1155s have different amounts, and they're closer to ERC 20s than they are 721s. You will be able to list multiple 1155s in one transaction and make offers for multiple 1155s in one transaction. We're working on fixing both the search and trade filtering. I'm bundling these together because they are both a part of the improvements to the data scraper. There's technical stuff optimizing all queries and making sure everything is bundled efficiently. 

There is cross-team coordination going on within Universe. We have [Lime Chain](https://twitter.com/LimeChainHQ) and additional contributors onboard and a team out of New Zealand. Another fix that has been made and pushed to production and being tested is the hardware wallets and being able to list entities for sale. We realized that the old signature method ETH sign B3 was no longer working with the ledger and MetaMask. So we upgraded to B4, and everything seemed fine, and you were able to list your NFTs for sale. We quickly realized that the ledger was not following the proper signing standard, and it was not using the right way of passing that data along.

The last two numbers of the signature were not correct. They're always the same so that we can replace and fix them on our side, and now people can buy NFTs from a ledger. One last thing is that not all the NFTs on Ethereum follow the 721 standards. We already have support for many of these, including [Crypto Punks](https://cryptopunks.app/). Another one that we've been building out support for is the [Hashmasks](https://twitter.com/TheHashmasks) which do not have token URIs. There's been a little bit of work reconstructing that side of the equation, and it is in testing; within the next 24 hours, all the Hashmasks should be showing up properly. We can build a handful of other collections out of those custom integrations that need it, especially some with the weird B64 stuff brought up.

If you know or work with a collection that is not standard 721 and wants support for it, like the regular 721, please make a snapshot post or reach out to me, and we'll work together to get something done. That covers all of the major updates and critical points. We can either transition to questions, or I can give it back to Mark and let him say a few words.

**Mark:** You hit on many points. We have all hands on deck as we work on the marketplace. 🦾

We can hop into questions next. 

## Community Questions [[06:15]](https://youtu.be/bt-XOOY0oY0?t=375)⁉️

**Mark:** Put your questions in the Pre AMA Channel, and post them in the forum. I'll continue to refresh if new questions pop up. 

### **Question:** ❓

Are any updates on the Polymorphs? And wondering what the plan in the future for them will be?

### **Answer:**

**Mark:** We haven't been talking about the Polymorphs, but we have many updates for them coming. 

We have V2 Polymorphs that we're going to ask everybody to burn; they will be compatible with Polygon and all the games we've built. We plan to integrate with our friends in the ecosystem, like FLUF and ASM. We will have people migrating their Polymorphs to the V2 Polymorphs. They will be the same art, but they will have more capabilities and scramble for a lower fee, and you can put them on Etherium and scramble them both ways, depending on where you want to keep your assets.

Polymorphs and Universe are very aligned in branding. We've started a [Instagram](https://www.instagram.com/universe.xyz/) and [TikTok](https://tiktok.com/@universe.xyz) to get more targeted marketing on Twitter. We have more people interacting on Twitter and getting more engagement. Check us out on Instagram and TikTok, and give us a follow and feedback on the content you are seeing. 👀 

**Ryan:** I won't expand on what comes after burning. But I will say there's a bunch of stuff in the works in the first steps to participating in all the Polymorphic craziness. 😜 

**Mark:** We have hired more developers and a team. There's a Polymorph development team and a Marketplace team, and they are different development teams. They are from Lime Chain; they are new devs that we brought on and will only be working on the Polymorphs. 

## Communications: Alternating Bi-Weekly AMA & Project Calls 

**Mark:** We've gotten some feedback that some AMAs are redundant because we get the same questions. 

So we're going to switch to an alternative idea. We are going to do these bi-weekly. Next week we will have a project call, then the week after that, we will have an AMA. Project calls are more informative because we can record and release them. We brainstormed this week on trying to line up times. What is an AMA time that makes sense for everyone to join? 3:00 PM Eastern is a great time for the community, but it's a terrible time for Lime Chain because they are in Eastern Europe. 

The best way is to go back and have our recorded 9/10 AM calls that Lime Chain and all the developers can join. We also had capacity problems and mic interference.

## Marketing Content & Builder Talent [[15:28]](https://youtu.be/bt-XOOY0oY0?t=928) 📰

**Zach:** A ton of interesting things are getting built around the Polymorphs— you definitely want to follow the Instagram and Tiktok.

**Mark:** We'll be pushing out a ton of content on our socials and pushing more material around the Polymorphs. (There is a ton built for the Morphs) 

There is a large push behind the scenes for the Polys. We've have huge plans. And with a proper team devoted to the Polymorphs, we won't be taking away resources from the marketplace development. 🧠

Also, we are looking at bringing on more people to help. If people from the community are interested and have the experience, we'd love to talk to more people. I don't know if Tyler wants to add anything to that.

**Tyler:** In general, across the board, we're doing a lot. We released the Marketplace. We're getting our ducks in a row. Improvements are coming. 

We've only released about 20% of what we've worked on. I know we're in the fast-moving industry, but I would have patience because a lot of time and investment has gone into the aggregate of what we're building.

We tend to finish what we start. 🏁

## Behind the Scenes [[17:55]](https://youtu.be/bt-XOOY0oY0?t=1075) 🎬

**Mark:** Also, what I was mentioning, Tyler; would you like to add something about dev talent? 

**Tyler:** We adding dev talent. It's hard because we're segmenting, and we've got developers added to [Graviton](https://graviton.xyz), and that's namely [Troy's](https://mobile.twitter.com/Danny_Desert) deal. What Troy is working on will bring utility to the XYZ token, and that's a separate raise of capital. So it's not coming from Universe coffers— outside of the grant. Graviton has the grant primarily for governance power; this way they can enact change at a protocol level.

We've added in-house back-end resources. Now that the Marketplace is out, Tim has been cranking out a ton of smart contracts, and we have additional private auditors that we've been working with.

Lime Chain has been crushing it and adding people. We're even talking about adding someone that can help from a full-stack capacity and a game dev. I know that 3D modellers aren't actual developers, but for the Deviant and Polymorph-related stuff, we brought Zach ([Transmental](https://twitter.com/transmental)) on, and he is extremely technical. Troy has people on his team that are helping. 

Now we have the capital and excitement around the project. So each one of the things that I discussed has a lead team. It took a lot to get here; I feel that with each week passing, things get better.

### **Question:** ❓

Is the hiring of devs more about realizing you need more than you have, or is it about opportunistically adding talent?

### **Answer:**

**Tyler:** Originally it was probably more opportunistic, and now it's a need.

**Mark:** Universe has grown, and we have minting contracts and a marketplace. It's not easy to bring people in and know where all the points are. We need to make sure there's a person that can help fix or solve something and knows certain areas where they need to pick up the slack. As companies scale, they need to hire more people. 

**Tyler:** In the beginning, it was exploratory. We did embark on doing things that people haven't done in Web3. When we launched the Polymorphs, [George](https://twitter.com/GSpasov) didn't take long to contribute and work. Auctions are needed in the market, and we haven't launched the Auctions and Raffles that Tim created and we have a bunch of things 80% done.

It takes time to build a back-end and front-end for all functions. 

We are much more effective in saying this is the direction we can go. It's time to move things from 80% to 100%. We have to get from being an effectual organization (exploratory) to one with a singular point mission that moves us to a set goal. A wide range of opportunities could arise. 🔑

This is why it's best we segment and iterate and continue to push out those tentacles, and we will start to see things are working. 

**Mark:** Yes, and continue to add features that the community wants and bring those through DAO votes.

### **Question:** ❓

Can we talk about plugging in the ASM brains into a Polymorph?

### **Answer:**

**Mark:** So that everyone knows, Tyler and I are advisors for [Altered State Machines](https://www.alteredstatemachine.xyz/).

We did sign NDAs to become advisors for that. So there are some things that we can't talk about with the development of the brain. 

But I did have a super promising call with Hal, the CTO of ASM, last week. We dove pretty deep into the capability of the Polymorphs with the Brains. The first answer is yes, it's possible. This is something that I thought we could open up to the community about after I talked to him. We need to decide what the Polymorphs are going to learn. The Polymorph is a host, and the host teaches it how to do something, and there's code written. We can decide what we want the Polymorphs to become as a community. 

If we want to integrate with ASM and the Brains, we 100% can. Then we can make a game around that and teach the brain how to do some cool 💩.

**Ryan:** The brain should be able to learn to operate and would not be outside of its capacity from what I understand. But I'm not an ASM expert.

### **Question:** ❓

Is there anything the community can do to help build the community? 

I feel like we should be working on something like that to get new people wanting to use XYZ.

### **Answer:**

**Mark:** As we're making improvements, the best thing that you can do is tell your friends about Universe and tell them to use it. You can tell them that it will be better; it's usable. There are some things that we want to improve and get fixed. Getting listings on Universe that's the best thing. 

> [Link to the Marketplace](https://universe.xyz/marketplace)

**Ryan:** To add to that, Snapshot votes, whether it's on features or new collections to add. We look at that regularly and are happy with community support. 💙

**Nick:** Somebody was talking about plugging into the back-end. I don't know how much you want to talk about that, Tyler.

**Mark:** There's confusion because on your podcast with [Gmoney](https://twitter.com/gmoneyNFT), Tyler, I think you worded it as Universe would help build front-ends, but I think that was a little misleading.

> [Gmoney Podcast](https://youtu.be/kEblt-vj0ug)

### **Question:** ❓

Would we as Universe help them build front-ends? 

### **Answer:**

**Tyler:** We have had major brands and technology reach out to us. 

A DAO shouldn't be selling a service and monetizing via transactions on the protocol. We will do something under Graviton because if we have to go under NDA, and I'll name a company we're not talking to as an example— Reebok, Universe can't sign an NDA with Reebok. 

Everything that Universe launches has to be open-source. If we do a very boutique product for some gaming group because they want a walled garden marketplace embedded within their application, then it becomes something that we should be doing. 🙅

There are certain things we're not going to do. Companies are already integrating into marketplaces, doing custom drops, writing custom smart contracts, and boutique type contracts. Naturally, those groups will see Universe as an opportunity to plug into.

We need to be focused on improving the protocol and the Marketplace through the process of documenting it, where it's easy for people to embed these types of things into their sites. 

### **Question:** ❓

Are you gonna create tools to make it easy to plug and play?
 
### **Answer:**
 
**Tyler:** Yes, we will create tools that make it easy to plug and play. 🔌 💻

Universe will be successful if a hundred different agencies and groups build on top of Universe. We got a head start on everyone. It's a permissionless protocol, anybody can plugin.

### **Question:** ❓

Would you consider another analog Web2 example to be [Linux](https://www.linux.org/)? 

### **Answer:**

**Tyler:** Linux, yes. 

Troy may be able to answer that better than I. 

It's a very successful open-source ecosystem. Anyone should be thinking about Blockchain in terms of Linux in general. What Blockchain offers is the ability to own and vote on the progression of Linux, which is extremely powerful. That doesn't mean that a [Red Hat](https://en.wikipedia.org/wiki/Red_Hat) doesn't need to exist. They are both successful and separate from each other. 

> The best analogy I could give is if Universe is Linux or Uniswap, then we still need to build a Red Hat on top of it. 

That didn't preclude or stop a ton of people from being able to benefit and profit off of Linux. This will play out in a similar capacity, with the difference being the ownership and the governance component over the open-source protocol itself. 

Ethereum is Web3 so it will play out differently. The plan around Universe is not to be a singular application that everyone accesses on Universe.XYZ. It's to have a versioning ecosystem like Ethereum was a while back. If we can get 1000 devs a month building on Universe when Universe doesn't even directly compensate, and we are at that spot a year or two from now, I will say it's a conclusion we won.

### **Question:** ❓

Any plans on expanding to Moonbeam? 

### **Answer:**

**Tyler:** We are not expanding the Moonbeam at the moment.

For the Polymorphs, we got to look at [Polygon](https://twitter.com/0xPolygon), but it's not as easy to launch the entire back-end. It's not EVM compatible and thats needed to scrape the chain. We need to get an Ethereum working correctly before looking at other platforms.

**Mark:** If we're going to create Polygon assets, we should probably consider a Polygon marketplace. We have reasons why we'd move towards Polygon. People know that we are working on a drop with Synthetix, which is to be dropped on [Optimism](https://twitter.com/optimismPBC). We're going to have to build an Optimism marketplace for that drop. 

We thought the EVM compatible, and EVM equivalent stuff wasn't hard. Tyler can talk about it. I'm sure they're moving [Barnbridge](https://barnbridge.com) over to Optimism, and that 💩 was more difficult than originally thought.

**Tyler:** A DeFi application needs to keep track of the transactions regarding the app. Or they use an oracle for the current market price or the separation between two points. EVM compatibility for DeFi is very different from EVM compatibility for an entire NFT Marketplace. DeFi doesn't even need a back-end because it doesn't need as much data to function. We've already released Barnbridge and its products on Optimism, Avalanche, Arbitrum, and BSC.

**Mark:** We will answer the remaining questions in the Discord Pre AMA Channel. 

We appreciate everyone coming and joining the AMA. 💙

We will have more development teams on those calls so that everyone will get more insight. 🦾


<br>

### Project Links 🔗👇

* Website: [universe.xyz](https://universe.xyz)
* Project Info: [DOCS](https://docs.universe.xyz/)
* Twitter: [@universe_xyz](https://twitter.com/universe_xyz)
* Discord: [Invite](https://discord.gg/QnkfAG6X52)
* Instagram: [Profile](https://www.instagram.com/universe.xyz/)
* Tiktok: [Profile](https://tiktok.com/@universe.xyz)
* Medium: [Page](https://medium.com/universe-xyz)
* Youtube: [Channel](https://www.youtube.com/channel/UCWt00md9T2b4iTsHWp_Fapw)
* Community Center: [Notion Page](https://clowncharles.notion.site/clowncharles/Universe-Community-Center-9e4043a8e6844769be26032bfe089baa)

#### Universe NFTs
* PolyMorphs: [Universe](https://universe.xyz/collection/0x1cbb182322aee8ce9f4f1f98d7460173ee30af1f)
* Lobby Lobsters: [Universe](https://universe.xyz/collection/0xc0cb81c1f89ab0873653f67eea42652f13cd8416)
* STAND WITH UKRAINE: [OpenSea](https://opensea.io/collection/standwithukrainedrop)
* Core Drops: Coming Soon!
