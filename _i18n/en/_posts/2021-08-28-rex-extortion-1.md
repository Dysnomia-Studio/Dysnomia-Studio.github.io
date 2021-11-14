---
layout: post
title:  "REX Extortion #1 - Publishing my first game on Steam"
tags: gamedev steam marketing extortion
categories: gamedev
---

10 months ago, on October 30th 2020, I was publishing my first game on Steam "[Extortion](https://store.steampowered.com/app/1299430/Extortion/)", it's a game where you're playing an computer engineer which is blackmailed and forced to hack some servers.

After few demands, I decided to write a small article about every steps from preparation to publish of my game, and the following months.

# Project genesis

Extortion was born late februrary 2020 during "[Not a Gamejam](https://itch.io/jam/not-a-gamejam)", a GameJam created by the french development server called "Not A Name". This GameJam lasted 2 weeks, and made me create the begin of the game's story, which is now the story of the game Demo. I liked this project and decided to continue development during the following months, then to publish it on Steam.

To the orginal 15 minutes gameplay chapter, I added 7 other chapters which compiles in a full story.

# Preparing Steam publishing

Until june 2017, Steam was validating games publication through Steam Greenlight, a plateform where community was (in)validating games based on their interest. Since Greenlight's stop, we now use Steam Direct.

Steam direct is now simplier, and follow few steps:
 - Creation of Steamworks account
 - Paying a $100 Valve publication fee
 - Validation of store page by Valve
 - Validation of game build, trailer, and planned release date by Valve
 - Publication of the game by the developer or the editor

# Marketing and wishlist

A very important thing about game publishing, is to advertise the game. We often want to begin advertising when the game is about to be released, when we have full game potential to show, but it's a mistake. You have to build a community around the game from development start to gain more and more wishlists on Steam. Whislists are a **very** important metric when launching a game.

Indeed, a game with many wishlists, and a strong (in terms of copies sold) start, will be highlighted by Steam, and will be even more sold.

You have to keep in mind that wishlist conversion rate of a game is really low. It's often only few percent, maximum 15-20% for games that are really attractive. Indeed, a 10 000 people wishlist will only be converted in few hundred copies sold.

**Warning:** A game that is not selling on the first week is dead. There are some exceptions like Among us, but it had a big and sudden communication from Twitch, but it's pretty uncommon.

On the Extortion side, I got a conversion rate around 8% on the first week, which represent around 40 of the 103 copies sold on this period.

# How to communicate about your game ?

Like said before, it's really important to communicate during the whole development duration. But, the way to communicate and the frequency are as important. You should use animated images (GIF, webp, short videos) instead of pictures, because it attract the attention. You have also to communicate often - even if that's just a picture - at least once a week.

# Where should you communicate about your game ?

**On Twitter:** Using *#screenshotsaturday* or *#wip*, for example. You can also use some common hashtag - that are retweeted by specialized bots and game studios. Those hashtags are: *#gamedev*, *#indiedev*, *#indiegame*, *#indie*, *#IndieGameDev*, ... You give a short descrption, a link, and of course, a GIF.

**On Reddit:** In the subreddits like: *r/IndieDev*, *r/IndieGaming*, *r/playmygame* (this one only if you have a free demo or a free game), ... It's important to follow each subreddit rules. For example, some are limiting paying games, post frequency, or even when to post. Like Twitter, use a GIF or a short vidéo, and post links in the comments.

**On Imgur:** By giving few tags about your game type (or generic ones like "gamedev" by default), talking about and describing your picture, don't hesitate to talk about your content !

**In your favorite communities:** Share around you, talking or writing, but always following theses communities rules. The objective is to have a know game !

**Take care of selfpromotion abuse !** On Reddit, but also on Imgur and other platforms, avoid only publishing self promotional content. There's a nice article about that on [Reddit Wiki](https://www.reddit.com/wiki/selfpromotion) especially about the 1/10 rule.

# Conditions around Steam publishing

Unlike some other platforms - like Epic Games for example - there's no exclusive rights when using Steam. But there are some rules: having the same price everywhere, and updating/releasing at the same time as other platforms.

On the financial side, Steam take a part of your revenues (after removing VAT) of 30% for revenues between 0 and 1 million dollars, 25% between 1 and 50 millions, and 20% over 50 millions. Steam manage itself VAT payments and money exchange; you don't have to think about that.

Steam let you get freely as many game keys as you want. You can sell them, give to press, influencers, testers, and so on. I personaly used them to make some people test Extortion before release and to give game copies when participating to a game award (but I wasn't qualified).

There's also Steam Curatiors, you can give them copies of your games and they will test and review your game. They might even test your game on Twitch ! Curators system is safer than giving keys because they can't sell those copies.

# Getting your revenues on your bank account

Steam only pay with dollars currency, using SWIFT payments. You'll need a bank account that accept dollars and doesn't take too much percentage when converting currencies (if you need to convert) or because of foreign payments.

I don't advise using standard banks (at least in France, where I experimented that), because my own bank took 14% on my first payment (that's a lot !). It's often better to use a specialised service like Wise (Ex-TransferWise).

Payment are done when you reach $100, 30 days after the end of the month that reached that money. You can also raise the minimum amount to optimize bank costs.

# Choosing the price

Price is on your own, you can choose it on a grid between $0 and $199.99. Currency-specific prices will be given to you based on each currency and country economy by Steam, you can customize those prices as well. You can also customize discounts (see next chapter). Price can change during game lifetime (early access, release, reevaluating price, and so on).

When I choosed Extortion's price, I based my price on a similar game I knew, Hacknet, and lowered it a bit (because my game wouldn't be as good, and I knew it). So, I choosed $5.99 and Steam proposed a converted price in euros of 4€99, price that I accepted.

# Discount

When doing launch week, you can choose a discount up to 40%, this discount isn't mandatory but recommended to be able to profit from your more important week in terms of visibility. Then you can't set a discount for 6 weeks.

You're invited (except the first 6 weeks) to every Steam discount, and you can choose to participate or not, and the discount you want to apply (without any limit).

You can also create your own discount period (from 1 to 14 days long).

When you modify your game price, you're not able to have a discount for 30 days.

My own advice, is to set a discount at every Steam discount event, raising slowly the discount with the time. Discounts are the main way to convert wishlists to sells.

# Available services

I tested achievements, demo, Steam Cloud and Steam overlay but there are plenty of available tools (and they are all free !): Workshop, DLC, friends list, community, market, leaderboards, game license authentication (serverside AND clienside), Valve Anti-Cheat, and so on.

See [Steam Documentation](https://partner.steamgames.com/doc/sdk)

# Updating and publishing a game

Steam have a private/public branches system to help us publishing different game versions. You can then, for example, next to *default* branch, have a public beta branch - like I did for Extortion. You could also have a private beta branch, or a branch by major version - like Factorio do for example.

Publishing files can be done via Web UI (if game is lighter than 2 GB), or using SteamCMD which work pretty well with a Continous Integration system.

# Results

About results, I wanted Extortion to reach 30 or 40 copies sold to be able to pay the $100 Steam fee. But I did far more than that ! Here's a summary table of my game life:

|                               | Launch    | After 1 week      | After 1 month | After 6 month | After 1 year |
|:-----------------------------:|:---------:|:-----------------:|:-------------:|:-------------:|:------------:|
| Wishlist                      | 412       | 544               | 635           | 810           | 831          |
| Demo Download                 | 2,802     | 2,834             | 2,864         | 3,649         | 4,621        |
| Copies Sold                   | 0         | 103               | 136           | 216           | 258          |
| Return                        | 0 (0%)    | 11 (10.7%)        | 14 (10.3%)    | 19 (8.8%)     | 23 (8.8%)    |
| Raw revenues <sup>1</sup>     | $0        | $455              | $635          | $1,045        | $1,227       |

<sup>1</sup>: From raw revenues, you have to remove returns, VAT, Steam part (30%), tax, bank costs, and so on.

As you can see, the first week is really important in terms of visibility and revenues.

# Conclusion

That was a small return on experience about Extortion publishing process. If you are interested, check out Extortion on [Steam](https://store.steampowered.com/app/1299430/Extortion/), and my next game [Alchemistry](https://store.steampowered.com/app/1730540/Alchemistry/). I'll write and publish more articles, about some subjects I brievly talked about here, or about some other subjects I have in mind.

You can follow me on [Twitter](https://twitter.com/Elanis42), or join [Dysnomia's Discord](https://discord.gg/c8aARey) if you are curious about my projects.

Have a good day, evening or night, depending when you read this, and see ya !