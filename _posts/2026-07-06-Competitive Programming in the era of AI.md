---
title: Competitive Programming in the Era of AI
date: 2026-07-07 12:15:00 +0530
categories: [Programming]
tags: [advice, programming, ai, llms, competitive-programming] # TAG names should always be lowercase
# pin: true
image:
  path: /assets/img/wanderer-above-a-sea-of-fog.jpg
  alt: Wanderer above the Sea of Fog, Caspar David Friedrich
---

*Picture this.  You've had a draining week at university or at work. You're exhausted, and you need a break. Most people would play a few video games, grab a few beers with their friends, or just sleep. But you have the (mis?)-fortune of being addicted to this weird, aesthetically questionable website called Codeforces (or AtCoder, or whatever your favorite OJ is).* 

*You check the list of upcoming contests, and you're in luck. "Nice," you think to yourself, "two rated contests back to back!" This is going to allow you to farm some rating! That sweet, juicy, delicious rating.  Maybe it's because the rest of your life is so dry that you get your weekly fill of validation (or disappointment) from these random internet points. Still, at least you're being productive. You want to get out of this Specialist rut you've been stuck in and into Expert. This is an academic goal. Or so you tell yourself. The truth is, you're simply addicted to the adrenaline rush that contests give you. It was never about being productive.*

*So, the contest time arrives. You watch the counter slowly tick down... and it's on! You're frantically reading the first question. You discard the fluff and your eyes narrow in on the parts that look mathematical... Okay, you need to know what the question is asking... You locate a line that looks important... read it. Alright! The logic was pretty clear in your mind. First question. Obviously easy. Everyone's going to get it. Only speed matters, and not getting a wrong answer penalty due to rushing. You quickly code it out, hit the submit button. The server is stuck, because everyone is submitting. After some time, AC. Whew. You check the standings. You submitted just in 2 minutes. Quick enough. You have a small lead. You don't waste any more time, switching to the second question. The fun is only beginning.*

*And so it goes. The contest is two hours long. One hour in, and you've solved three questions, no penalties. Pretty sweet. Should be enough for some positive rating gain. And then you move on to the fourth, but you're stuck. It's pretty hard. Probably DP. You hate DP which is non-standard. You probably should practice your DP. One of these days.*

*Anyways, you watch the contest go on. You know from experience most people will also be stuck, and since you were quick, your rank should be good.* 

*That doesn't happen. The leaderboard keeps climbing. And climbing. You stare at the fourth question, frustrated. Almost 3,000 people have solved it by now. That isn't going to give you any rating. What? Are you just stupid? The question stares back at you, its face cold and inscrutable. In desperation, you try a few greedy approaches. They fail. Two WAs.*

*The contest ends. You ended up with a -30 delta. You're a bit numb. This was a good contest.  That was the worst part. Everything went right. On a typical day, you wouldn't have done this well.*

*You know ratings shouldn't matter. Random internet points. But it still stings. You don't like losing. Maybe you're not cut out for this. Why are you still doing this anyway? You wanted to attend the ICPC Regionals. But you can barely maintain a stable specialist rank.* 

*You're frustrated. You look at the standings. So many grays and greens above you. It's disappointing. This is when competitive programming loses some of the magic that made it so special to you.* 

*You don't up-solve that question you were stuck at. You don't register for the next contest. For the first time in a long while, you wonder if you're done.*

---
# Introduction

Over the past two years, competitive programming has (not so) quietly entered a new era. With the release of Large Language Models which can solve an increasing fraction of CP problems, getting an AC can be as simple as pasting the question statement into your favorite model, and pasting back (without even looking at the code) the response.

It's also clear that an increasing number of participants are relying on AI tools for their contests, either for the entire contest (which I jokingly like to call "LLM-Zombies") or parts where they get stuck (the more skilled cheaters). We'll just use the term "unfair player" to refer to them, since such behavior is explicitly forbidden by the rules. Unfair players have a disastrous effect on the leaderboard, since Codeforces uses a rating system which works based on ranking and how many users solved a problem, this deflates the ratings of problems as well as genuine participants. [This blog](https://codeforces.com/blog/entry/154620) by [Christine-](https://codeforces.com/profile/Christine-) estimates that *"The rating deflation for legitimate participants is around 150-190 rating points"*.

On a platform where rating points of just 200 can completely change your rank, this is a huge difference. Worse, this risks driving away legitimate participants and increases the proportion of unfair players. If the proportion of unfair players increases, the rating deflates further, creating a vicious cycle.

Competitive programming is uniquely unprepared to deal with this situation, since it has long run on an honor-based system : The only way to obtain solutions to difficult algorithmic questions during live contests was to ask a strong participant, who would be unlikely to share them with you. There wasn't any way for unfair players to Google solutions or look them up in a textbook, or click a button to get the answer. But now there is.

I've split this post into a few parts: What I think genuine contestants should do, how to use AI to effectively train, and some (perhaps controversial) suggestions to the very structure of how we conduct contests.

# How to CP, the leaderboard is full of LLM-Zombies!

### 1. Detach yourself from rating
I think this should have been obvious by now, but the rating indicator in your profile is not the same as it was in the past. Not just because of unfair players, but because other people in the space know that it simply isn't a good measure anymore (since it is easily faked by unfair means), and it has already stopped being the signal it once was. While this is sad, it should also be somewhat liberating, especially if you are the type to be afraid about rating loss during contests. Thus: detach yourself from rating. I know this is easier said than done, and we will now need a new anchor to gauge our progress. Several of the next suggestions address this.
### 2. Take part in offline contests
The Informatics Olympiads if you're still in school, and ICPC Regionals if you're currently in university, being offline competitions (not counting the qualifiers), provide a more legitimate proof of your skill than rating, and also tend to be (arguably) more enjoyable to take part in. I'm sure there are other offline contests as well, based on your region. The current landscape makes them more valuable, not less. Prepare for them seriously if you can.
### 3. Take part in old Virtual Contests
If you want to experience CP as it was, take part in older virtual contests from (my subjective opinion) the 2019-2023 era. Why this specific time? Because the contestants at the time were still strong (the actual skill of contestants and difficulty of problems has increased over time). But they were not using LLMs - The LLMs of the time were still rudimentary. It is an effective way to gauge your progress based on how you rank and the number of problems solved. Take these VCs as seriously as contests and track your improvement over time in a notebook. You can even calculate a "virtual" rating change with tools like [Virtual Rating Change Calculator](https://cfviz.netlify.app/virtual-rating-change.html).
### 4. You *know* when you improve
A lot of contestants used rating as the sole judge of whether they improved or not. However, our minds already know the toil associated with real growth -- overcoming a hard problem which stumped you for a while, or learning a difficult new concept and practicing it till it becomes second nature. Rating is a convenience, yes, but you already have an internal sense of how good you are. Trust it and hone that sense.
### 5. Play Rated contests when you have a bigger margin
Let's say you still want to improve your official rating and rank. Then, following the 1-3 above, take part in contests more sparingly, when you expect your performance is surely going to be 150-200 points above your current rating. This way, even with deflation, you will still gain rating. It is possible to overdo this and never take part in contests at all, but then, by 4, it is you're responsibility to know if your improving as a contestant.
### 6.  Promote fairness in your local circles
This point has less to do with how to individually get better, but it is equally important. I'm sure that some of you reading this have friends, classmates who also do CP. Please keep your local CP clubs and friend circles clean, as much as possible. If you know someone is blatantly cheating, you obviously cannot stop them, but you can try to talk to them. This is especially relevant for students currently in university.

# On Using AI for Practice
From a surface glance: Using AI for practice will surely be great! You have an effective tool to use when you're stuck at a problem to provide you with hints. If your solution isn't passing, the tool can find your bugs and point them out for you. Perhaps it will be like chess, where the existence of strong engines pushed contestants to learn and refine their skills to an even greater extent.

Perhaps. But this is a dangerous path to go down. Why do I say this? Because it is very tempting to use AI not as a tool but as a crutch. Let's pick an example : Alice and Bob are both solving a particularly hard problem for their rating range. Both recognize it uses this technique which is slightly unfamiliar for them. Both Alice and Bob code out their solutions, but both have implementations littered with bugs.

Bob gets his first WA, thinks for a little bit, and upon not spotting the issue, pastes his code into GPT, or Gemini, or whatever his favorite LLM is. After a minute, the machine thinks and spits out an explanation of what exactly Bob was doing wrong. Bob reads it, quickly, and it seems obvious. They were all silly bugs. He quickly makes the changes and submits - AC. This whole process took ten minutes.

Alice gets her first WA, thinks for a little bit, and doesn't get any solution. So she spends almost an hour : swapping out parts of code, adding debug print statements, submitting various versions of the code. Finally, an hour and 3 more WAs later, she gets her AC. She is more tired after her exercise, but also more satisfied with the AC.

A month later, both of them take part in an offline contest, where another problem using the technique comes up. Who do you think codes it correctly and faster? I think most people would agree that it would be Alice -- the skill of manually debugging is often more enlightening than learning the algorithms themselves.

So, I recommend using AI more sparingly : Don't use it to debug code which you yourself struggle to debug. Ideally, don't use it for debugging - it is one of the skills you're trying to train. It's alright to use it to prepare a list of topics to train, to make plans or schedules, to explain a topic to you in different words. Generalizing this advice : **Don't use AI tools in training in a way where *they* perform a task that *you* want to be better at.**

# A (hypothetical) new structure for contests
I believe that AI-assisted unfair play is a serious issue which degrades the experience for all participants including themselves, makes contests uninteresting and wastes the effort of the authors. I would like to argue that this potentially could be a "phase-transition" moment, and that some new structure for contests could be useful, especially stricter proctoring methods. Some (very subjective) suggestions from my end would be:
1. **Fight fire with fire:**  I believe a lot of unfair play can be detected by ML-based models, although I am not particularly skilled myself in that area. However, the tells of LLM usage are pretty clear to humans when looking at the code, so I believe a system which can recognize those signs is not far-fetched, and worth looking into.
2. **Use rapid changes in rating and performance as indicators** : A player who performed at a Newbie level in the past 10 contests and suddenly jumped to CM-level performance should attract investigation. It is the easiest way to catch foul play, and I think contest websites should have some checks of that sort in the future, similar to how chess websites work.
3. **Public Reporting / Review :** A large portion of the user base of the websites don't wish to see it populated with unfair players. This is why websites and extensions like the popular [CF Cheater Database](https://cf-cheater-database.vercel.app/) have sprung up throughout the past few years. I believe such a reporting system should be made official, and any instance of detected cheating be visible on the profile.
4. **Limiting the creation of new accounts :** Banning a account associated with unfair play is difficult, as unfair players may just decide to create a new account. Thus, there have to be stricter measures to create new accounts, which leads me to my next point.
5. **Collect mobile numbers to verify new accounts**:  OTP-based verification could be required to create new accounts, and prevent unverified accounts from participating in contests. Although there has been historical push-back against this for privacy reasons, I believe it's a reasonable trade-off for the current environment. Most sport-related websites today implement some sort of mobile verification, and this comes with the added benefit of also reducing bot spam.
No anti-cheat system can ever be perfect. But the goal isn't to eliminate unfair play entirely -- which is impossible --  but maybe with a good-enough system and stricter structure in place, rating can recover some of its lost meaning and competitive programming its older charm.

# In Closing
Back to the main discussion, I don't think the AI-era is completely terrible for the serious contestant. The value of problems which train your brain only increases when we increasingly outsource thinking to AI agents, since those systems are still fallible, and need a trained eye to detect mistakes. The only thing which is dying is the leaderboard, and many may even argue that this is a good thing. CP, like most mind sports which had to deal with the existence of engines, will continue on. Let's close by revisiting the hypothetical contestant whose story we discussed in the beginning. 

---

*After a long time away from competitive programming, one day, you decide to give contests again.  Only this time, you don't look at the leaderboard as much. You're stuck at a hard problem, and you know it's hard. It doesn't matter how many submissions it has.*

*After the contest, you upsolve the question. It takes you a few days. But you're fulfilled, since you know that you overcame something difficult for you, and you had to push yourself.*

*Maybe one day the leaderboard will become trustworthy again.*

*Maybe it won't.*

*Either way, you still plan to solve algorithm problems on those Friday evenings, on this weird website with the questionable UI.*

*Just not for the number beside your username.*
