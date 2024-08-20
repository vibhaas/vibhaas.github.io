---
title: So you want to learn how to program
date: 2024-08-17 08:30:45 +0530
categories: [Programming]
tags: [college, btech, advice, programming, get-started, first-post] # TAG names should always be lowercase
pin: true
image:
  path: /assets/img/Cp-anime.png
  alt: Fun image of two programmers from Everrule's (in)famous "CP Anime Blog" :P
---

## Introduction

You just got admitted to your Computer Science (or some other science / engineering) degree, and you are wondering, but _how do I start to learn how to program_? Perhaps you are in high school, and notice some of your friends who are into coding and you think it looks cool. Or perhaps you want to automate the boring tasks in Minecraft and are learning AutoHotkey, and now you got interested in expanding your skills. 

This article is for you. Although it is primarily written for the first category of people, I believe it will be a valuable read for anyone learning to program.

If you _do_ fall into the first category, that I believe it will be valuable to read this post from cover-to-cover, but feel free to skip around.

Although posted on my blog, this post has been a collabarative effort by many people. Special thanks to:

- **Alex Gijo** _(2023 batch, IIITK)_: For their contribution in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).
- **Glen Enosh** _(2023 batch, IIITK)_: For co-authoring [On Machine Learning and AI](#on-machine-learning-and-ai) and their contributions in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).
- **Harissh Ragav Dhamodaran** _(2023 batch, IIITK)_: For co-authoring [On Machine Learning and AI](#on-machine-learning-and-ai) and their contributions in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).
- **Laavanya Rajan** _(2023 batch, IIITK)_: For their contribution in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).
- **Siddhant Nema** _(2022 batch, IIITK)_: For their contribution in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).
- **Shaun Alan Joseph** _(2023 batch, IIITK)_: For their contribution in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).
- **Vipin Karthic** _(2023 batch, IIITK)_: For authoring [On Game Development](#on-game-development) and their contributions in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).

I also thank them for providing their valuable time towards proof-reading this blog.

## About Me

This is section is here to answer the question: Why should you listen to what I have to say?

I am currently a 2nd year student of Computer Science and Engineering at [IIIT Kottayam](https://www.iiitkottayam.ac.in/). I am a Coordinator for the [Coders Club at IIITK](https://www.linkedin.com/company/codersclub-iiitk/). I learnt to program in 2nd grade, and [dabbled](https://codepen.io/vibhaas) in programming as a hobby whenever I had free time. In 11th grade I won a [Bronze Medal](https://www.linkedin.com/in/vibhaas/overlay/1714978989419/single-media-viewer/) in [INOI](https://www.iarcs.org.in/inoi/), a competition to select the students who would represent India at the [Informatics Olympiad](https://ioinformatics.org/). I enjoy competitive programming, holding a title of [Expert on Codeforces](https://codeforces.com/profile/accord). You can get to know me better using the [About](/about) page.

As this post is written in my perspective, so naturally some of the advice will be more relevant to a similar section of people compared to others. I have attempted to mitigate this by keeping my advice as general as possible and the inclusion of other contributers.

## Before we get started

Before we begin our discussion about how to get started with programming, I want to provide you with some tips. These are things you should _not_ do while programming, and common pitfalls to avoid. Let's get into it!

### 1. Be self-reliant

First and most important, do **NOT** expect to learn how to code well from college (especially, in an Indian Engineering college). While you will learn how to code in college, it will not amount to much without spending a large amount of time in self-learning. Also, relying solely on college will lead to write bad code in an outdated programming framework, and it will make any competent programmer wince by just looking at it. Fortunately, resources to learn coding abound on the internet! We will discuss some in the [How to Get Started](#how-to-get-started) section.

### 2. Do not expect it to be easy

For unknown reasons, a lot of people expect coding to be easy, or they watch some youtube tutorials and assume that they now know how to code. Peter Norvig put it best in his essay (which I highly recommend reading), [Teach Yourself Programming in Ten Years](https://www.norvig.com/21-days.html):

> Walk into any bookstore, and you'll see how to Teach Yourself Java in 24 Hours alongside endless variations offering to teach C, SQL, Ruby, Algorithms, and so on in a few days or hours... The conclusion is that either people are in a big rush to learn about programming, or that programming is somehow fabulously easier to learn than anything else.

Let me make it clear: _Coding is not easy!_ Just like any craft, it takes discipline and deliberate practice over a long period of time to actually become a decent programmer. Do not expect it to be easy. Programming is vast, and to learn it to an intermediate level as a complete beginner, it will take you at least two years of practice. To become a master at the craft of programming it may take you five, ten years, or more! I cannot say, since I do not consider myself one! So, you must develop a love for the craft, which is the only way to hone your skills to this level. It is important to keep this in mind.

### 3. Learn how to program, not any particular language

Most programming languages are very similar, like different dialects of the same language, rather than completely different languages. So, instead of trying to learn the syntax of many different languages, it is better to learn how to program well in _one_ particular language before trying others. 

For an analogy, learning syntax is like learning how to make words and sentences in a language. Learning to program is like learning how to write books with it. So, write a good one.

### 4. Syntax vs "knowing" a language

> A language that doesn't affect the way you think about programming, is not worth knowing ~ Alan Perlis

Different programming languages have different use cases and philosophies on how to perform the same task. This is a continuation of the previous subsection on learning how to program well -- learn your language well, too! The syntax structures which are common between languages are just the surface - every language has something fresh and interesting to offer.

To illustrate what I mean, consider a programmer extremely proficient in C++. He will be able to pick up the syntax of Python within 1-2 days. However, he wouldn't have learnt how to write _Pythonic_ code, and code in the philosophy and style of Python, or follow its best practices, and will likely take a few months if he wants to grasp that.

This is what I mean by syntax vs "knowing a language". Be a native speaker of your language and not just memorize the words.

### 5. Know when to stop learning

By "stop learning", I mean to stop consuming online courses and tutorials. Start applying what you have learnt to the real world. A lot of programmers suffer from impostor syndrome, the feeling of not being good enough and being under-confident. This leads them to constantly consume more and more tutorials and not actually coding. However, this becomes counter-productive. At a stage, further learning is only possible by applying what you have already learnt. 

### 6. Write Clear Code

> "_Beautiful code is short and concise, so if you were to give that code to another programmer they would say, 'oh, that’s well written code.' It’s much like as if you were writing a poem._" ~ Santiago Gonzalez

> "_Always code as if the guy who ends up maintaining your code will be a violent psychopath who knows where you live._" ~ John Woods

Most real world coding projects involve the collaboration of tens to hundreds of programmers. They also involving maintaining and update ten years old codebases. 

Do you think that would be easier if the code looked like this:

```cpp
bool brpt(int n,int m,vector<vector<int>>&adj){
  vector<int>c(n,-1);
  for(int i=0;i<n;++i){if      (c[i]  ==  -1){stack<int >s;s.push(i);c[i]=0;
    while(!s.empty()   ){
       int u=s.top(); s.pop();for(int v:adj[u]){if(c[v]==-1){c[v]=1-c[u];s.push(v);}
else if(c[v]==c[u])return false;}}}
        }return true;
}
```

or like this:

```cpp
// Function to check if a graph is bipartite
bool isBipartite(int N, int M, vector<vector<int>> &adj) {
    // Vector to store the color of each node (0 or 1)
    vector<int> color(N, -1); // -1 == unvisited

    // Loop through each node to handle disconnected graphs
    for (int start = 0; start < N; ++start) {
        // If the node is already colored, skip it
        if (color[start] != -1) {
            continue;
        }

        // Use a stack for DFS
        stack<int> stk;
        stk.push(start);
        color[start] = 0; // Start coloring with 0

        // Perform DFS
        while (!stk.empty()) {
            int node = stk.top();
            stk.pop();

            // Iterate over all adjacent nodes
            for (int neighbor : adj[node]) {
                // If the neighbor has not been colored, color it with the opposite color
                if (color[neighbor] == -1) {
                    color[neighbor] = 1 - color[node];
                    stk.push(neighbor);
                }
                // If the neighbor has the same color, the graph is not bipartite
                else if (color[neighbor] == color[node]) {
                    return false;
                }
            }
        }
    }
    return true; // If no conflicts, the graph is bipartite
}
```

Which do you think is easier to understand and debug? Now, admittedly, the number of comments in the second example are a bit excessive, but it is important to **comment your code**! Make sure to use standard and expressive variable naming, even spacing and the best practices for the languages you are using.

## How to Get Started

This is section is to help you learn enough CS to be able to continue to learn yourself. This is not meant as an exhaustive list but a starting point.
### Roadmap

1. **Learn one "mainstream" programming language.** I recommend starting out with C/C++, Python or Java. Learn the syntax and how to work with variables, control structures, loops, functions and common data structures.
2. **Learn some basic web development.** Learn how HTML, CSS and JavaScript work, being able to code basic front-end websites.
3. **Learn OOPs (Object Oriented Programming).** You should be able to understand objects and classes; encapsulation, inheritance, polymorphism, how to create packages (or the equivalent) in your programming language of choice.
4. **Learn how to use Git/Github.**
5. **Practice by solving coding problems on websites like [LeetCode](https://leetcode.com/), and make a few personal projects.**

It doesn't really matter what resources you use as long as you accomplish the above mentioned points. Personally, I am partial towards [CS50's Introduction to Computer Science](https://www.harvardonline.harvard.edu/course/cs50-introduction-computer-science) which is a popular online MOOC by Harvard University. The [FreeCodeCamp Youtube Channel](https://www.youtube.com/c/Freecodecamp) also has excellent tutorials on various topics.
### Timeframe

Here is a rough time-frame for accomplishing what I mentioned (of course, this varies from person to person!):

1. **Learning your first programming language.** This should take anywhere from 1-3 months. You don't just want to know it theoretically, you want to make sure that you can quickly write code without referring and making trivial bugs. For this, you should solve lots of problems!
2. **Learning basic web development.** This is a questionable inclusion into the list. Not everyone considers web development interesting, while some love it and make a career in it. However, I believe a basic understanding of web development is essential for any programmer. This step should take about a month or so.
3. **Learn OOPs.** This shouldn't take much long, however, it is a style of thinking and not just a bunch of concepts, so do not rush this. This should take about a month again.
4. **Learn how to use Git/Github.** Learning how to use a version control system (primarily Git) is essential as a programmer. It still astounds me how many students in CS engineering are not comfortable working with Git. Do not be afraid of Git / Github. It is simple to pick up and should not take more than 2 weeks of effort.
5. **Practice Problems on [LeetCode](https://leetcode.com/) / Make Projects.** This is a more long-term phase. Problem practice is supposed to consistent, so its hard to give a time line for this. It is meant to be done alongside the first four and much after as well. Basically, practice your skills on problems and projects for as long as you need to!

That's about it. After this, you will (hopefully) discover where your interests lie and be able to direct your further journey in Computer Science by yourself. Good luck, and have fun!

## On Machine Learning and AI

<div class="custom-card-template-widget-lite"> <div style="text-align: left;"> This section on Machine Learning and AI was contributed by <a href="https://www.linkedin.com/in/glen-enosh-924414215">Glen Enosh</a> and <a href="https://www.linkedin.com/in/harissh-ragav-dhamodaran-b7a8aa289/">Harissh Ragav Dhamodaran</a>, core members of the <a href="https://www.linkedin.com/company/enigma-iiitkottayam">Enigma AI Club</a> at IIITK. </div></div>
### Getting Started

> _AI will probably most likely lead to the end of the world, but in the meantime, there'll be great companies. - Sam Altman_

Ever feel like your Netflix recommendations know you better than your own family? That's the subtle magic of AI at work – and it's just the tip of the iceberg! Here are some tips and tricks, where we demystify artificial intelligence: it's less "_Terminator_" and more "your grandma asking Alexa to play '_Despacito_'" (it's a vibe).

![img-description](/assets/img/AI-roadmap.png){: width="500" .center }
_Image: "A learning track for AI". Image designed by [Maniraj B](https://www.linkedin.com/in/maniraj-bonkuri/). Click to zoom._

Above is the magnificent roadmap that is the default question for every fresher. The roadmap contains both mathematics and frameworks that implement the learnt theory. The green part (like always) is the easier part, it covers all the basic math which is required to understand the basics of ML. The yellow part is the harder path and contains all the basic ML Algorithms and their implementations. The Red Part is the relatively hardest part. It contains maths and implementations of Neural Networks which is a part of Machine Learning. This part is pretty important because its the basics of all the current trends in AI like LLMs and Stable Diffusions, you know… All the fancy stuff.

### Some tips and tricks

- If you have prepared for JEE Mathematics, it should cover the maths in the roadmap. Just review the mentioned concepts.
- The roadmap is designed with the knowledge needed for each step.
What works for us may not work for you, but aim to complete most of the concepts in the roadmap.
- Don’t trust us. Jump to advanced levels, face challenges, get mocked by the lack of knowledge, and doubt your ability. It’s okay to feel so. Don’t give up. Return to basics to understand the necessity of following the roadmap.Return to basics to understand the necessity of following the roadmap.
- The key to learning stuff in this specific field is not just consistency and dedication, you have to choose the pertinent subjects to dedicate your time to.
- The learning curve in AI is steeper than cubic polynomials, the initial steps can be tiring and exhausting. So, Try implementing the stuff that you learnt cuz visual learning proves to be helpful in the long run.
- Don’t blindly follow the tutorials implementing the ML and ANN algos, try to understand the intuition behind the algo and then code it up.
- Don’t ask too many questions up front. Just dive in and get started!

## On Game Development

<div class="custom-card-template-widget-lite"> <div style="text-align: left;"> This section on Game Development was contributed by <a href="https://www.linkedin.com/in/vipin-karthic-1b111828a">Vipin Karthic</a>. </div></div>

### Introduction

_So you want to do Game development, or you have an amazing idea, that you think is going to become one of the best games ever. You might want to do gamedev for multiple reasons, money, enjoyment, fame, or maybe even youtube._

Everyone starts somewhere, so let's make few things very clear:

1. **ANYONE CAN MAKE A VIDEO GAME**, that game you made when you were 10? It counts.
2. **There is No Perfect Way** to make a game, Game development is an art and a science; the "perfect way" is what works best for you. And last but not the least,
3. **Game Development is more than just programming**, There is so much more to developing a game other than the coding, since you are all starting to program, let's just cover the needed things :).

Developing a game majorly consists of the following:

#### 1. Game Design

Think of it as a making a plan before you build a house on Minecraft, you always list out things like: What is the goal of your house?, What color do you want your house?, etc. Similarly, ask yourself: What is the goal of the game?, What kind of game are you going about?, Do you want the game to be really trivial?. Even if you think your ideas are SHIT, list them out. Even a rough scribble will help you out.

#### 2. Art and Animation

Now that you know what idea you have, start making your art. If you don't want to, there are so many websites online where you can find free art for your game, properly licensed for your usage. If you do want to make ur own art, start out with Aseperite (Learn how to draw and make simple art) or with Blender (Learn how to make models). Since it is your first game, don't go overkill, remember we are just learning. Don't confuse learning with making a project.

#### 3. Audio and Sound Designing

Sound designing can seem hard at the beginning. So, when just starting out, use available free audio online. If you want to make your own music there are a lot of applications like Audacity etc. Again, start slow, sound designing needs some experience before you can become really good at it.

### Game Programming

Now that you know what to make, now we choose a language. You might not want to choose an engine, and write everything from scratch, like rendering, and shader code, Stop, you are not a professional. Start small, it is okay to start small. Choose an engine (free ones, obviously). Learn how to use it, and then boom! By the time you finish programming, you already have a completed game, now its just a matter of refining and testing :)

Remember all are equally important, remove one thing from the above mentioned, and its like playing a game on the pc without a peripheral. (Imagine playing CSGO, or Elden Ring, without the Animation or the Sound, :scared:  :D). I'll attach resources at the end where you can read more in detail, and give you some general tips for the game you are making.

Some tips:

1. Sorry, You cannot make a game like GTA 5, its just too big for someone starting out to make, Start small, its completely fine, to start small and then level yourself up.
2. Don't feel bad if you feel like redoing your Art and Code you've. Its okay to improvise or refactor, if you find something better.
3. Once you start a game, FINISH IT, yes it might seem simple at the beginning, but Game development is frustrating, Patience will take a long way.
4. No one knows everything, you learn everything in your own way, at your own speed. Don't let others decide the speed of ur learning, make sure you learn it to ur satisfaction.
5. As you make more games, start making the game bigger relative to the previous game, for example, you could implement new things that your previous game didn't have

### Links and Resources

1. **Reddit:** [https://www.reddit.com/r/gamedev](https://www.reddit.com/r/gamedev)
2. **Photo link:** (verify licensing) [https://daily.gamedev.tv/infographic-showing-game-dev-careers/](https://daily.gamedev.tv/infographic-showing-game-dev-careers/)
3. **Indies Discord:** [https://discord.gg/workwithindies](https://discord.gg/workwithindies)
4. **GDL Discord:** [https://discord.gg/gamedev](https://discord.gg/gamedev)

**Disclaimer:** These are all personal opinions that I felt right, even though I recommend you all to do this, choose what you think will fit you right always.

## Programming Challenges

This is an extension to Point 5 of [How to get Started](#how-to-get-started) --- solving programming challenges and hackathons can also be a valuable way to gain experience and learn how to code. It can also help build valuable connections within your community!

### 1. Hackathons

> Think of it as a coding party, but instead of just chilling, you’re making cool stuff—apps, websites, gadgets, whatever you can imagine. The goal? Build something real by the end of the event, usually within 24-48 hours.

Hackathons are collaborative events where groups of people try out new ideas and come up with something novel to develop. Traditionally, Hackathons are meant to be events where you spend a day or two and come up with a new idea or product and develop it from scratch. 

It is an intense but fun experience - a lot of Hackathons run right through the night onto the next day, making coffee a vital resource for working after the ideation.

However, a lot of Hackathon competitions conducted in India tend to have the ideation _before_ the development. Often, you are expected to submit your idea and a PPT presentation well in advance.

This, unfortunately, sometimes turns it into a PPT competition, where people write buzzwords in their PPT without really having any skills (it goes without saying, don't do that). However, if you get to the later stages of the Hackathon, it can be a really rewarding experience.

A popular Hackathon in India is the [Smart India Hackathon](https://www.sih.gov.in/), which happens every year. Do check it out and also other hackathons. They are a valuable way to collaborate with others on projects.

### 2. Competitive Programming

Competitive Programming is a mindsport in which contestants solve programming problems / puzzles in a limited time frame. It is similar to the contests on [LeetCode](https://leetcode.com/), with some of the biggest platforms for practicing CP (as it is commonly abbreviated) being [Codeforces](https://codeforces.com/), [CodeChef](https://www.codechef.com) and [AtCoder](https://atcoder.jp/).

You will especially enjoy it if you are into Math / Puzzles or other mindsports like Chess. If you saw my profile, you know that I am pretty into it myself, and so I will be writing a blog post only about "How to get started with CP" soon. Until then, I refer you to the following videos and books if you are interested to learn more:

- **Famous CPer Errichto on "How to Start with Competitive Programming":** 

{% include embed/youtube.html id='xAeiXy8-9Y8' %}

- **Famous CPer William Lin on "Starting Competitive Programming - Steps and Mistakes":** 

{% include embed/youtube.html id='bVKHRtafgPc' %}

- **Blog by GM on a way to practice Competitive Programming:** [https://codeforces.com/blog/entry/66909](https://codeforces.com/blog/entry/66909)

- **The Competitive Programmers Handbook (CPH):** [Link](https://usaco.guide/CPH.pdf).

- If you are currently a student at IIIT Kottayam, join the **Coders Club Discord Server** (invite link: [https://discord.gg/5H9BHSQDQG](https://discord.gg/5H9BHSQDQG)).

### 3. CTFs

Capture the Flag (CTF) Competitions are cybersecurity competitions where you solve challenges related to hacking, reverse engineer, cryptography, and digital forensics. The goal is to find hidden "flags" (usually a piece of text like a code) within puzzles or systems, to show that you managed to break into the system. These flags give you points.

{% include embed/youtube.html id='8ev9ZX9J45A' %}

There are two main types:

1. **Jeopardy-Style:** Challenges are like a quiz with categories (e.g., web hacking, reverse engineering) where each solved task gives a flag and points.
2. **Attack-Defend:** Teams defend their own systems while trying to hack into others’ networks to capture flags.

Generally, while starting out it is better to participate in Jeopardy-style contests as those are easier on beginners. CTFs can be a really fun and rewarding experience, and I recommended everyone to try them out (regardless of whether they want a career in cybersecurity or not).

A prominent CTF competition which occurs every year is the [PicoCTF](https://picoctf.org/). Solving PicoCTF problems should give you a taste of what CTF problems are like. Also, go through the resources mentioned in the [AwesomeCTF github](https://github.com/apsdehal/awesome-ctf).

Some other useful links:

- [CTF101](https://ctf101.org/)
- [CTFtime](https://ctftime.org/)
- [Roppers CTF Bootcamp](https://www.roppers.org/courses/ctf)
- [TryHackMe](https://tryhackme.com/)

## Tips from batchmates and seniors

And finally, I have collected some tips from my batchmates and seniors. They mention things they wished they knew before starting their programming journey and the suggestions they have for you:

<!-- ============= card template start ============= -->
<div class="custom-card-template-widget">
<!-- Image of the person -->
<a href="https://www.linkedin.com/in/siddhantnema/"><img src="/assets/img/ref-imgs/siddhant-nema.jpeg" alt="Siddhant Nema's Photo" style="width: 100px; height: 100px; border-radius: 50%; object-fit: cover;"></a>
<!-- Text content -->
<div style="text-align: left;">
<!-- Quotation text -->
<p style="font-size: 1.2em; line-height: 1.4;  margin: 0;">
<ol>
    <li>Always try out new things. You never know what field you might like in Computer Science. </li>
    <li>Find something you vibe with rather than searching for a cash cow. Not everyone needs to be learning ML or doing CTFs or CP. Do what makes you happy!</li>
    <li>When you've finally found something you like, you will end up hitting a wall at some point. It is important to know that it's very natural and when you overcome this you will unlock a new level of mastery in your field. Be patient and persevere through it.</li>
    <li>Stop shifting the blame to external factors. "The prof isn't good" or "There are too many cheaters in contests" or "It was my internet" are good examples of little white lies you tell yourself to stay complacent. Being accountable to your mistakes is the best way to overcome failure.</li>
    <li>Chill. Now this one is mostly ignored. Nothing is more important than your peace. Give yourself a break once in a while.</li>
</ol>
</p>
<!-- Author's name -->
<p style="font-weight: bold; font-size: 1em; text-align: right; margin: 0; margin-top: 10px;">
    ~ <a href="https://www.linkedin.com/in/siddhantnema/">Siddhant Nema</a>
</p></div></div>
<!-- ============= card template end ============= -->

<!-- ============= card template start ============= -->
<div class="custom-card-template-widget">
<!-- Image of the person -->
<a href="https://www.linkedin.com/in/harissh-ragav-dhamodaran-b7a8aa289/"><img src="/assets/img/ref-imgs/harissh-ragav.jpeg" alt="Harissh Ragav's Photo" style="width: 100px; height: 100px; border-radius: 50%; object-fit: cover;"></a>
<!-- Text content -->
<div style="text-align: center;">
<!-- Quotation text -->
<p style="font-size: 1.2em; line-height: 1.4;  margin: 0;">
<span style="font-weight: 400;">If you ever feel like getting stuck in a specific part, take a break, chill and then come back to it with a different point of view.</span>
</p>
<!-- Author's name -->
<p style="font-weight: bold; font-size: 1em; text-align: right; margin: 0; margin-top: 10px;">
    ~ <a href="https://www.linkedin.com/in/harissh-ragav-dhamodaran-b7a8aa289/">Harissh Ragav Dhamodaran</a>
</p></div></div>
<!-- ============= card template end ============= -->

<!-- ============= card template start ============= -->
<div class="custom-card-template-widget">
<!-- Image of the person -->
<a href="https://www.linkedin.com/in/glen-enosh-924414215/"><img src="/assets/img/ref-imgs/glen-enosh.jpeg" alt="Glen Enosh's Photo" style="width: 100px; height: 100px; border-radius: 50%; object-fit: cover;"></a>
<!-- Text content -->
<div style="text-align: left;">
<!-- Quotation text -->
<p style="font-size: 1.2em; line-height: 1.4;  margin: 0;">
<span style="font-weight: 400; text-align: left; align-items: left;"><ul>
    <li>Try doing your logical work in the morning and your creative work at night. </li>
    <li>Take on tougher projects involving skills or domains you haven’t completely explored but are interested in. This can create an urge to acquire the necessary skills or knowledge. You can either clutch or crumble under pressure, but if you have genuine interest and urge, you will survive.</li>
</ul></span>
</p>
<!-- Author's name -->
<p style="font-weight: bold; font-size: 1em; text-align: right; margin: 0; margin-top: 10px;">
    ~ <a href="https://www.linkedin.com/in/glen-enosh-924414215/">Glen Enosh</a>
</p></div></div>
<!-- ============= card template end ============= -->

<!-- ============= card template start ============= -->
<div class="custom-card-template-widget">
<!-- Image of the person -->
<a href="https://www.linkedin.com/in/alex-gijo/"><img src="/assets/img/ref-imgs/alex-gijo.jpeg" alt="Alex Gijo's Photo" style="width: 100px; height: 100px; border-radius: 50%; object-fit: cover;"></a>
<!-- Text content -->
<div style="text-align: left;">
<!-- Quotation text -->
<p style="font-size: 1.2em; line-height: 1.4;  margin: 0;">
<span style="font-weight: 400;"><ol>
    <li>Never be satisfied with your project. Sounds strange, but you can always make it better. Supposed to make a todo list website? Why not learn to make it run as an app on the phone. Once you learn to over-do, your works will suddenly stand out among the crowds of copy-pasted code.</li>
    <li>Don’t worry if it doesn’t work right. If everything did, you’d be out of a job. Learn the art of using documentations and forum online, like stackoverflow.</li>
    <li>Remember to touch grass—your code doesn’t need a break, but your brain definitely does.</li>
</ol></span>
</p>
<!-- Author's name -->
<p style="font-weight: bold; font-size: 1em; text-align: right; margin: 0; margin-top: 10px;">
    ~ <a href="https://www.linkedin.com/in/alex-gijo/">Alex Gijo</a>
</p></div></div>
<!-- ============= card template end ============= -->

<!-- ============= card template start ============= -->
<div class="custom-card-template-widget">
<!-- Image of the person -->
<a href="https://www.linkedin.com/in/laav10/"><img src="/assets/img/ref-imgs/laavanya-rajan.jpeg" alt="Laavanya Rajan's Photo" style="width: 100px; height: 100px; border-radius: 50%; object-fit: cover;"></a>
<!-- Text content -->
<div style="text-align: left;">
<!-- Quotation text -->
<p style="font-size: 1.2em; line-height: 1.4;  margin: 0;">
<ol>
    <li>Never feel shy to ask - When in doubt or when it feels like the internet can't solve your problem, feel free to approach the right faculty and seniors/peers. You think it's dumb? Nah don't think, just ask it away!</li>
    <li>You are your greatest motivator. Trusting yourself is key to self improvement. Set achievable goals and take small steps towards it. Being consistent is important to keep up with stuff.</li>
    <li>Explore. Your college life is like a buffet, you get to explore everything but at the end of it pick what suits you the best. </li>
    <li>Keep learning, be curious. Don't just do something for the sake of it.</li>
</ol>
</p>
<!-- Author's name -->
<p style="font-weight: bold; font-size: 1em; text-align: right; margin: 0; margin-top: 10px;">
    ~ <a href="https://www.linkedin.com/in/laav10/">Laavanya Rajan</a>
</p></div></div>
<!-- ============= card template end ============= -->

<!-- ============= card template start ============= -->
<div class="custom-card-template-widget">
<!-- Image of the person -->
<a href="https://www.linkedin.com/in/shaunalanjoseph/"><img src="/assets/img/ref-imgs/shaun.jpeg" alt="Shaun Alan Joseph's Photo" style="width: 100px; height: 100px; border-radius: 50%; object-fit: cover;"></a>
<!-- Text content -->
<div style="text-align: center;">
<!-- Quotation text -->
<p style="font-size: 1.2em; line-height: 1.4;  margin: 0;">
<span style="font-weight: 400;">"I use Vim, btw."</span>
</p>
<!-- Author's name -->
<p style="font-weight: bold; font-size: 1em; text-align: right; margin: 0; margin-top: 10px;">
    ~ <a href="https://www.linkedin.com/in/shaunalanjoseph/">Shaun Alan Joseph</a>
</p></div></div>
<!-- ============= card template end ============= -->

<!-- ============= card template start ============= -->
<div class="custom-card-template-widget">
<!-- Image of the person -->
<a href="https://www.linkedin.com/in/vipin-karthic-1b111828a/"><img src="/assets/img/ref-imgs/vipin-karthic.jpeg" alt="Vipin Karthic's Photo" style="width: 100px; height: 100px; border-radius: 50%; object-fit: cover;"></a>
<!-- Text content -->
<div style="text-align: left;">
<!-- Quotation text -->
<p style="font-size: 1.2em; line-height: 1.4;  margin: 0;">
<span style="font-weight: 400;"><ol>
    <li>Don't stress yourself out over on what you want to do in the first month of learning how to program, start somewhere, and spend a reasonable amount of time in the fields you might to work, before choosing one and becoming really good at it.</li>
    <li>During your learning period of a language, try your best not to involve the usage of AI, code everything out on your own, it will help you both in developing debugging skills, and at the end you just become a better programmer.</li>
    <li>After you learn how to "use" a language, and when you start a project based on a tutorial, don't copy code as the tutorial says, see a part, understand it, and implement on your own with your own twist.</li>
    <li>Invest time learning before committing to something.</li>
    <li>Do not take too many things and once, and at the end, accomplishing nothing. Start with one thing, and once you learn how to manage your time efficiently take on other projects, I personally won't recommend doing more than 2 things at once.</li>
</ol>PS: I also use Vim, btw.</span>
</p>
<!-- Author's name -->
<p style="font-weight: bold; font-size: 1em; text-align: right; margin: 0; margin-top: 10px;">
    ~ <a href="https://www.linkedin.com/in/vipin-karthic-1b111828a/">Vipin Karthic</a>
</p></div></div>
<!-- ============= card template end ============= -->

## Concluding Remarks

If you read through all that, great job! I tried to cover all the most common questions I get asked, and I hope this post was helpful to you too! 

If you liked it, consider [**[Subscribing]**](https://forms.gle/wW19wehDTp7a3esF7) to my blog! You will be e-mailed everytime I post. I promise every post will be as useful and high quality as this one. Also, you can leave a like or a comment to let me know you how you found this post. Thank you for reading! :)