---
title: My Time Working On Old School RuneScape's Engine Team
layout: post
post-image: "https://onedrive.live.com/embed?resid=9594E849DC7FC39E%2161052&authkey=%21ANyrK8EhynOzHDk&width=1952&height=1057"
description: I was given the opportunity to work on engine programming for Old School RuneScape's C++ Client, this helped me learn lots about how game engines work.
legacy: true
tags:
- personal
- jagex
- development
- improvement
---

This blog is a continuation of my previous blog when I talked about my first two months at Jagex on the Unannounced MMORPG team.
**I would recommend that you read that one before this!**

[What I've Learnt Working On Jagex's Unannounced MMORPG](/blog/what-ive-learnt-working-on-jagexs-unannounced-mmorpg) - Jul 17, 2021

---

During the final month of my internship at Jagex, I worked on **Old School RuneScape** on their **Engine team** where my job was to work on the **enhancement of the RuneScape engine** and associated systems.
My last month went by very fast but despite that, I managed to learn loads and do loads of new things!

As I had already been at Jagex for two months the onboarding wasn't as long, I had a few introductory calls with the Engine team to meet everyone and learn about what they work on.

---

### What I've learnt

![Illustration](https://onedrive.live.com/embed?resid=9594E849DC7FC39E%2161050&authkey=%21APYA6Cs6TAUBcOw&width=1600&height=645)

I've learned tons working on the Old School RuneScape engine team.
An example of this is the **many different tools that are used in a live game** like how content and engine are separated with Perforce for content and Git for the engine!
Intellij was used for Java and server code, Visual Studio (which is my default IDE!) for the C++ client code, some Python scripts to build solutions, and GitBash to run Git commands!

Through working on the engine team at Old School RuneScape I've learned a bit about **how engine development compares to gameplay programming**.
There's a lot of comparisons which I could make about their commonalities and differences, the main difference being that engine development isn't always player-facing (which is an obvious one) - I find both types of development great fun anyway!

Working on a live game is another key learning point for me, I've learned about how (in general) they're different in comparison to a game in pre-production.
With a live game, there are loads that I had to set up before I dove into the code, and there are many different branches! It usually takes longer to see your changes in the live game in comparison to a game in pre-production as the live game has to go through many different stages like code reviews and QA! This may be different for every game though! I've also learned that, as well as a live game having many people working on it, there are also loads of different roles and teams which work on different aspects of the live game.
Tools like **Jira** are used to manage everyone's work, and **sprints** are more common to ensure everyone is on track with their work!

**Git Bash** and using Git commands was one of the big things which I've learned out of all the tools I've used. I've not really used Git with commands before, but I did use Git with UI, I liked using TurtoiseGit and GitHub Desktop previously. Now I know how Git works with some commands!

I used **C++** when working on the **Steam engine**, and through doing a client-side ticket I've learned lots about **logic, rendering, being efficient with my code, and how code efficiency compares between a live game and a game in pre-production.**
I also learned about the process of what the RuneScape content developers do through adding some **RuneScript code** which printed something in the game chatbox, and during another call with some content developers, I learned about how to add an NPC into the game with decision dialogue which either ended up with the player battling the NPC or starting a quest for the NPC.
This helped when it came to adding in sprites and packaging them as adding sprites was part of one of the tasks I was working on, and it is something content developers usually work with.

---

### What I've done

![Jagex Blog Post Mention Image](https://onedrive.live.com/embed?resid=9594E849DC7FC39E%2161055&authkey=%21AFMH2wZP4zpoeRs&width=1600&height=645)

One of the main things I've worked on when working on Old School RuneScape's engine team has been officially released on the Steam client! The [newspost here](https://secure.runescape.com/m=news/group-ironman?oldschool=1) mentions this too!

It's a volume slider for the title screen!

This had to be coded from complete scratch, and I had to figure out the most efficient way to render in the volume bar sprites for changing the volume!
Doing this in the codebase meant I needed to learn about all the different systems to do with inserting sprites and saving data for the next time the player opens the client!

<iframe src="https://drive.google.com/file/d/1foSvjsgSucx8CZFhu_vlCnjHB73p9Fcg/preview" width="100%" height="800px" frameborder="0"></iframe>

---

### Extracurricular Activities & Work

![Extracurricular Image](https://onedrive.live.com/embed?resid=9594E849DC7FC39E%2161056&authkey=%21AFHDxxHIk6QvwRQ&width=1600&height=645)

There are lots of things that I've done outside of my role which was fun to do with Jagex.
For example, a Tech Social, where lots of people got together from the tech teams and played games. We played a drawing game and a few online card games! This really helped me with meeting new people from other teams which I might have not met otherwise!

I also decided to travel up to Cambridge on my own accord **to see what it's like to work in the studio** for a week despite it being empty due to renovations and many people working from home.
I quite liked working in the studio, it was a different environment from working at home. At home, I'm surrounded by all of my consoles, posters, and gaming bits, and I've grown comfortable working in that environment, but in the studio, I'm in an open office space where I can talk to the few people who are there and grab a coffee in one of the kitchens! I feel as if I can be a lot more social in an office!
After work in the studio, I went to many places with different groups of people from Jagex! On one of the evenings, I went to a pub, called The Golden Hind, and on another evening, I went to a lovely Japanese restaurant to eat some noodles and dumplings, and another evening I had some pizza, and on the final Friday evening, I went to the Milton Country Park's Food Court! It's an understatement to say I was full! I had a really great time though!

Another activity that I was able to do was go on the **company live stream** to talk to **hundreds** of people at Jagex about how my internship went!
This was great fun to do!
Similar to this I came into the studio again nearer the end of my internship to record a **promotional video**!

I also asked to be a **panelist** in one of the **Old School RuneScape Q&A Twitch live streams** where I answered questions about my internship. This was a little more challenging as there were **thousands** of people watching live who know much more about RuneScape than I do! But nevertheless, it was great fun to do!

<iframe src="https://www.youtube.com/embed/8eg0Re1GqjM" width="100%" height="600px" frameborder="0"></iframe>

I decided to do some **content dev** after work nearer the end of my internship to see what working on content was like. So, I talked to some of the content developers and **tried to make some of my own quests for Old School RuneScape!**
This was great fun as I learned about the process which a Content Developer goes through from start to end!
I didn't really have too much time to do this though because of how late into my internship I asked to do it, but I managed to work on some **detailed quest briefs** and look through some RuneScript code to see how other quests work!

---

### Conclusion

![Conclusion Image](https://onedrive.live.com/embed?resid=9594E849DC7FC39E%2161057&authkey=%21ADqW8Km_GaFjMrs&width=1600&height=645)

I've learned that as I've only spent a month on Old School RuneScape, it was hard to do much because the codebase was so large (And some of it was super old!) - It took a while to get used to it! But either way, **I was able to implement something which I was very proud of!** There are loads of differences between working with a custom engine and working with an engine like Unreal Engine, and there are many differences between working on gameplay programming and engine programming. But overall, this has taught me that **it's not too hard to get used to a new engine, and I shouldn't be scared of approaching new tools!**

In conclusion, I've really enjoyed being an engine developer and I've really liked working on a live game! It's taught me how game engines work under the hood and the **many different paths which programmers can take in the games industry alone!**

I'm thankful to have been given the opportunity to do this internship!