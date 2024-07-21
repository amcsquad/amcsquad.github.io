---
title: What I've Learnt Working On Jagex's Unannounced MMORPG
layout: post
post-image: "https://onedrive.live.com/embed?resid=9594E849DC7FC39E%2161046&authkey=%21ALtuWGd37RY-laQ&width=1920&height=1634"
description: One morning, I woke up to an email titled 'Welcome to Jagex Games Studio' - I could barely believe it!
legacy: true
tags:
- Jagex
- C++ Programming
- Unreal Engine
- Internship/Placement
---

One April morning, I woke up to a great surprise, I had gotten an email titled: *Welcome to Jagex Games Studio*, I was quite tired at the time so I had to read the email a few times to realise it was real.

This email offered me a once-in-a-lifetime **Game Engineering Internship** at **Jagex Games Studio**, I immediately accepted the offer and went to tell everyone!

Before this Internship, I had not played RuneScape, so between the time of accepting my offer and starting my first day at Jagex, I was fighting Goblins, sheering sheep, and completing a handful of quests! I'm not really an MMORPG type of person, but I must admit, I found myself spending hours exploring the colossal medieval fantasy world of Gielinor and making friends!

I started my first day in the middle of May, a new face in the games industry, I had *never* worked a job like this before, I was excited to see what it was like to work in a tech industry, and to see what work was ahead of me! And it was *so* much different from the retail job I was used to working!

Jagex hired **4** new interns, **2 Game Engineers** (including me) and **2 Artists**, we all quickly became good friends. All of us were split up within the many teams in Jagex to work in different areas.

I was put on the unannounced MMORPG (For the sake of ease, I'll be calling this "The MMORPG" throughout the blog) project for **2 months**, this game is currently in **pre-production**, and the **remaining month** of my internship would be spent working on **Old School RuneScape**, which, as I'm sure you're aware is a **live** game. I like this structure as it **allows me to experience game development at different stages**.

In this blog post I will be talking about the 2 months I spent working on the MMORPG, and as you are probably aware, the game I'm working on is Unannounced; so, I can't say too much about the title or talk about specifics, therefore a lot of this blog would be *anonymised*, mostly talking about **tools I've learnt** to use and **programming skills** I've picked up along the way.

Jagex were amazing at helping me settle in, they prepared plenty of introductory calls with many different people from different teams to help me with IT, learning about the company amongst a few other things, as well as calls with a handful of people from the MMORPG team, introducing me to the ideas behind the game, and the codebase. Within the team, we also had a few social evenings, where we played games like Golf With Your Friends, these social evenings were great fun!

I decided to contact other people in many different roles and teams to talk to them about what their role is to help me learn more about the games industry. I've also talked to many different programmers and asked them about their journey into the games industry and any tips so I can learn from them and make some friends!

---

![Tools Image](https://onedrive.live.com/embed?resid=9594E849DC7FC39E%2161048&authkey=%21AKucsn4UU3QJ0g0&width=2300&height=800)

### What I've learnt

At Jagex, I was using a number of tools which I had never used before, these tools were used for **source control**, **general game development**, **documentation**, and **task organization**.

The game itself is being made in **Unreal Engine**, and I was working on the game during the time it was developed using **UE4**.

I've personally always been hesitant on using Unreal Engine as I've been pretty comfortable using Unity, having to use a different engine was a *challenge* at first, but a *welcome* one, it taught me that **the best way to adapt and use new tools is to just use them**, engines change all the time in the games industry, so I'm happy that I now have the **confidence** to approach whatever comes my way.

Using C++ with Unreal Engine was another hurdle, I had tried using it beforehand and found the macros confusing, which in turn made me run into many problems, so this internship taught me how to use these to develop many **game mechanics** which involved the use of **networking** and **replication**, that was another thing I was new to as well, a handful of the other skills which I've learnt were how to use **delegates** and **interfaces**.

Some of the highlight contributions of mine within the MMORPG include but aren't limited to:
* **Player Name Mechanic** - The player can put in their own username and it appears above their head for themselves and everyone else playing to see.
* **Player Respawning** - The player respawns a few seconds after they die.
* **Enemy Respawning** - Enemies respawn a few seconds after being killed.
* **XP & Levelling** - Players can gain experience points after battling enemies, once they get a certain amount of experience points, they can level up.
* **Debug Commands** - I've implemented a handful of debug commands to help with playtesting.

**Source control** is another important tool, I've used Git beforehand, but for this project **Perforce** was used with **Swarm for code reviews** alongside **Unreal Game Sync** to keep all the project files up to date.

Perforce was easy enough to learn as it is similar to Git, and through using Perforce and having team members to ask questions, **I've learned how to fix conflicts** - before this was something I was worried to approach in case I messed it up.

Code Reviews is something new to me, beforehand, my teams would just push the code into the main branch or their own branch without any code review process, but I found doing code reviews quite fun! It's really interesting to see other peoples process to making a mechanic, and code reviews allowed me to ask questions about their code and other people to give me feedback, which in turn helped me learn more about the codebase, and how to improve my code.

**Documentation** and **task organization** is very important in ensuring everyone is staying as productive as possible, one of the main productivity tools the team used was an online task manager called **BaseCamp**, which is now a tool I'm using in my personal time as well.

Basecamp is like a collection of tools which can be used to open up discussions, to-do lists and automatic check-ins. To-do lists were used and they helped me organise the work which I was going to do throughout the week and ensured I was on track to finish on time.

During the development of the game, there is sometimes things which need to be documented, whether that be help guides on how to do something, or design decisions, on this MMORPG team, we gathered our documentation using a tool called **Confluence**.

I quite enjoyed documenting my findings, some of the stuff I've documented were a **how to play document**, which got used quite a lot as the MMORPG didn't have a tutorial in it yet, and **a few programming cheat-sheets**, to help me learn and help others learn as well.

Documentation is something which I will definitely be doing in the future for my own projects.

---

![Extracurricular Image](https://onedrive.live.com/embed?resid=9594E849DC7FC39E%2161047&authkey=%21AACkI7_5v5BX_Ic&width=1920&height=636)

### Extracurricular Activities & Work

Whilst working at Jagex, I've participated in many activities outside of my role, and learnt lots through them.

One of the first activities I attended was the **Diversity Champion Training**, which was a group workshop where we chatted about **diversity in the games industry**. During this we talked about how we could make the games industry more diverse, and how to be there for anyone to talk to about any issues they may be having.

We also talked about the painting ['A Room In New York'](https://en.wikipedia.org/wiki/Room_in_New_York) by Edward Hopper, through open discussion about what was happening in the photo we concluded that we can't judge things by how we see it, as there could be many sides to every story. I learnt that *I should be the change that I want to see!*

Another activity I participated in was the **Into Games Virtual Work Experience** - I volunteered through Jagex to help **mentor college students**, and they had to work as a team to produce a game design document and game prototype in accordance to a brief, this was the first time I've ever done mentoring, and although these students were only a few years younger than me, and I was an intern, so I was new to the games industry, I decided to bite the bullet and try my hand at mentoring.

I realised through this that I really enjoy it! I prepared a handful of slides for each session with the students, and they were able to produce some great work by the end of the week! I talk more about my experience with this mentoring in this blog post [here](/blog/guiding-students-through-designing-prototyping-a-game)

I was also able to go to Cambridge to check out the Jagex studio too! An **Intern Social Day** was arranged for all of the interns to meet up, have a tour around the studio, meet some people from Jagex and look around Cambridge!

I've never been to Cambridge, seen a game studio, or been in my own hotel room before, so this was a whole load of new experiences!

The studio was amazing, it had artwork and foam sword props everywhere, there was loads of plants, and kitchens on every floor with Jagex branded mugs and glasses, the desks were separated into their different teams, and there was even a cafeteria and pub!

After we saw the studio, we had a nice picnic outside for lunch, and then went into Cambridge town to do champagne punting, and have an evening meal. I had great time getting to know everyone!

The next time I went to Cambridge was for the MMORPG offsite.

The offsite was to discuss the goals of the MMORPG and plans for the future, and we had these meetings in a beautiful fancy conference room in a hotel we stayed in. During the talks, we had tea, and small snacks.

We also had lunch at the hotel and went into the Cambridge town for a big group dinner. It was great fun getting to meet the MMORPG team in person!

---

![Tea Image](https://onedrive.live.com/embed?resid=9594E849DC7FC39E%2161045&authkey=%21AIIkFSmfDFl0-ZU&width=600&height=300)

### Conclusion

Overall, I've learnt many things working on Jagex's unannounced MMORPG team for 2 months during my internship. It may not seem like a long time, but within those two months I've learnt many programming skills, different tools, and the different types of roles in the games industry. I've also noticed a boost in my confidence, speaking skills and capability to learn and adapt to new things.

This internship has made me realise what my goal is for the future: I hope to one day grow my skills in **programming** and **leadership** so I can become a **Lead Programmer**!

---

### Next - The Final Month Of My Internship

[My Time Working On Old School RuneScape's Engine Team](/blog/my-time-working-on-old-school-runescapes-engine-team) - Aug 17, 2021