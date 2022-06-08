# Universe XYZ DAO Project Call– #033

### Meeting Date/Time: Wednesday 2022/6/1 at 20:00 UTC

### Meeting Duration: 17 mins

### [Github Agenda Page](https://github.com/UniverseXYZ/xyzDAO-PM/issues/55)

### [Audio/Video of the meeting](https://youtu.be/mmx6clG81DY)

### Breakdown:

Moderator: Mark Ward

Scribe: Tammy M.

Attendees: Mark Ward, Tyler Ward, Tim Kang, Troy Murray, Ryan Shtirmer, Ilia Andreev, Nick Ward, Bianka Ivanova, Zach Owens (transmental)

## Intro

**Mark:** Welcome to Project Call #33.

We have done almost an entire year of project calls. That means we've been building and have a lot to show for it. 

I'm going to pass it off to Ilia, and he's going to give some of the development updates with Ryan, and the other Devs may hop in to share some info.

## Development Updates 🧰 [[00:37]](https://youtu.be/mmx6clG81DY?t=37)

**Ilia:** Thanks, Mark. So as you may have seen in discord, we shared the updates on the end of Sprint 6, and we started Sprint 7. We have been doing a lot to unblock the infrastructure, and we have some progress there. We also have a new DevOp guide starting today, and we will keep you posted on that in later stages. In Sprint 6, we made the new DB healthy and stable in the Dev environment, which is a good part of the scalability and performance improvements. We also stabilized and tested the following year's introduction for the marketplace. A new search filter by traits is done and working with a new database, and we are continuing with the back-end support for it in Sprint 7. We started doing some Dev work and introducing next years in the auctions. We unblocked the work we had for the ERC 1155 support for the front end, and one of the devs are working on it. 

We had a team member doing some initial core functionality tests. So that's going to make our lives easier in the long run. Sprint 7, which we just started yesterday, continues with scalability and performance improvements. Doing reconfiguration of the existing parts of microservices to support the new DB. I mentioned the filter by trades back end support and the auctions to work with the improved marketplace back end. We also want to have ERC 1155 support ready for testing. We are doing new exchanges in user-profiles and my NFT pages. For the nextJS introduction to the auctions front end, we need to have the other components for the front end done and start the front end work for the bundle support. So you will be able to bundle ERC 721s together and sell them in the marketplace.

We may need to do some Polymorph burn to mint related changes to the Universe Website. Zach will have more info on the Polymorphs. 

**Ryan:** Thanks, Ilia. You covered all of the points. I want to add that we have even more back-end improvements coming. I know there's been a struggle to get all of the NFTs scraped. With the improvements made and a few more procedural changes to how we're going to do the sync, there's a strategy to get all those NFTs synced to the back end and have that full-back synce done. We can hand it over to TransMental for some Polymorphic chat.

## Polymorphs 🤡 [[05:30]](https://youtu.be/mmx6clG81DY?t=330)

**Zach:** We are doing some final testing on the Polymorphic burn to mint. We are looking at next Thursday as a launch for that. Bianca, have you been introduced on a call yet?

**Bianka:** I have, yes. 🤝

**Zach:** Just making sure.🙂

We will have another Polymorphic Therapy episode next week with burn to mint. Then we're going to have a bunch of Polymorphs coming out once we get the Polymorphs on a new contract and get scrambling back on. Correct me if I'm wrong, but we're going straight into the polygon bridge after we do. So we'll have another two or three weeks, and then we'll have the polygon bridge up so the scrambling can be cheaper; then, there will be more updates. 

**Mark:** You will be able to scramble on both ethereum mainnet and polygon to start. The marketplace isn't going to have polygon support. That's not one of the main reasons we left it open to ethereum and had both scrambling. Polygon assets will eventually come. While your Polymorph is bridged to polygon, it's not going to show up on the marketplace for the time being and I want everyone to know so they don't think that their Polymorph disappeared. We will move towards eventually getting those assets to show up and make them tradable.

**Nick:** We don't want to delay the Polymorphs anymore because of the marketplace.

**Ryan:** There's a world where you see the Polymorphs in Universe, even if they are on polygon. It's going to be a bit until we open up trading support because, with polygon, we were most interested in their ZK solutions. It doesn't make sense to deploy to their layer 1s. There is an exploration of the L1, and L2 alternatives to ethereum after the complete marketplace is released and out of beta.

**Zach:** They're not going to disappear off the Universe's front end completely. To be clear, the polygon bridge won't be releasing with the burn to mint. It will come a few weeks after.

**Mark:** You can scramble on ethereum mainnet and polygon. Once you move it, there is a chance that you don't see it on Universe, but it's still there, and we're working on it and will bring that functionality as soon as possible.

**Ryan:** If you don't see it on the Universe site directly, you will see it on the Polymorph site, which will be a part of the Universe website.

**Mark:** I'll give it back to Zach. I just wanted to add that.

**Zach:** No, that's good. That's pretty much all the near-term stuff. Maybe we can go further on the AMA if anybody asks questions. But that's all for me. Bianca, do you have anything else to add to that?

**Bianka:** No, whatever you said, and we're doing some regression testing. So expect it soon.

**Mark:** Hey Zach, one more thing to add to this call. We will have one more call before the Monstercat Universe Party. Are there any updates for the community on that?

## Monstercat Universe Party 🐱🌌🗽 [[10:25]](https://youtu.be/mmx6clG81DY?t=625)

**Zach:** I talked to Monstercat about in-between sets and showing the Polymorphic Therapy episodes on the big screen behind the stage. I have given them a Google Drive full of assets for Universe and Polymorphs to be displayed and branded all over the place. Then there are other physical items that we have been whipping up, so the branding is super strong. They are guaranteeing us a fire video with Universe's presence in it. We will relay that back to you when the video comes out. 

**Mark:** People have been bringing up marketing and marketing expenses. How do we measure the return on this party? What kind of KPIs? What kind of things can we measure? Ryan and I will put together some KPIs and figure out how we can pull information, like time on the site traffic, our social media traffic, retweets and other things. We're going to look at the marketplace traffic and see if these parties are bringing traffic to either the Polymorph pages of the marketplace or the marketplace pages themselves. Then we will look at the floor price. We are looking at more measurable, non-financial KPIs. The main financial one that everyone cares about is floor price. We will have a plan for that and be able to give some report on how that party affected Universe.

**Ryan:** We will not add in the short term and the long term, either like Google Analytics or invasive tracking. We have data coming from Cloudflare, specifically about how many people access the site and broad geographic regions of where they're coming from. We will have charts and will be able to pull some secondary metrics like Twitter and hopefully aggregate that data nicely and draw some cool conclusions. 

**Mark:** We are working on a plan and trying our best to figure out how to get the best representation of ROI for a marketing party, and we will share that in the discord.

**Zach:** I want to point out that we went over the party on the last discord AMA. We are  beating a dead horse at this point? We did the party and showed up last year. In the previous AMA, we discussed how if we don't show up this year and show face among the top collectors and other brands that are sponsoring this party, and we don't want to fall off the face of the earth, and we need to continue. Somebody mentioned we should secure the funding for these parties earlier and do it once a year and do the first vote in January to secure the funding for the party later on in the year. 

**Ryan:** I think he recommended that we do three years of votes in advance because we're making the argument that it needs to be continuous and done every year. Then make sure everyone's on board with that upfront and then have a DAO vote, which might be better.

**Zach:** That's all we need to say about the party. 😉🎉

The party's happening. We voted on it, and we will try our best to give the best information afterwards so people can justify it. 

**Mark:** Thank you to the community. Hit like, subscribe, and share our videos on our YouTube. We also have the latest episode of Polymorphic Therapy that aired on the AMA last Thursday. It would be at the end of this video if you missed it. The link will pop up next to the Universe subscribe, so watch the video. 

Thank you, everyone, for joining us, and we'll catch you next week. ✌️💙


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
