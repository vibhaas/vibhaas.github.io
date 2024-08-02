---
title: So you want to learn how to program
date: 2024-07-28 08:30:45 +0530
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

If you _do_ fall into the first category, that I believe it will be valuable to read this post from cover-to-cover.

Although posted on my blog, this post has been a collabarative effort by many people. Special thanks to:

- **Alex Gijo** _(2023 batch, IIITK)_: For their contribution in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).
- **Glen Enosh** _(2023 batch, IIITK)_: For co-authoring [On Machine Learning and AI](#on-machine-learning-and-ai) and their contributions in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).
- **Harissh Ragav Dhamodaran** _(2023 batch, IIITK)_: For co-authoring [On Machine Learning and AI](#on-machine-learning-and-ai) and their contributions in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).
- **Laavanya Rajan** _(2023 batch, IIITK)_: For authoring [Programming Challenges: CTFs](http://127.0.0.1:4000/posts/So-you-want-to-learn-how-to-program/#3-ctfs) and their contributions in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).
- **Siddhant Nema** _(2022 batch, IIITK)_: For their contribution in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).
- **Shaun Alan Joseph** _(2023 batch, IIITK)_: For their contribution in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).
- **Vipin Karthic** _(2023 batch, IIITK)_: For their contribution in [Tips from batchmates and seniors](#tips-from-batchmates-and-seniors).

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

So, this my roadmap for a beginner programmer:

1. **Learn one "mainstream" programming language.** I recommend starting out with C/C++, Python or Java. Learn the syntax and how to work with variables, control structures, loops, functions and common data structures.
2. **Learn some basic web development.** Learn how HTML, CSS and JavaScript work, being able to code basic front-end websites.
3. **Learn OOPs (Object Oriented Programming).** You should be able to understand objects and classes; encapsulation, inheritance, polymorphism, how to create packages (or the equivalent) in your programming language of choice.
4. **Learn how to use Git/Github.**
5. **Practice by solving coding problems on websites like [LeetCode](https://leetcode.com/), and make a few personal projects.**

It doesn't really matter what resources you use as long as you accomplish the above mentioned points. Personally, I am partial towards [CS50's Introduction to Computer Science](https://www.harvardonline.harvard.edu/course/cs50-introduction-computer-science) which is a popular online MOOC by Harvard University. The [FreeCodeCamp Youtube Channel](https://www.youtube.com/c/Freecodecamp) also has excellent tutorials on various topics.

Here is a rough time-frame for accomplishing what I mentioned (of course, this varies from person to person!):

1. **Learning your first programming language.** This should take anywhere from 1-3 months. You don't just want to know it theoretically, you want to make sure that you can quickly write code without referring and making trivial bugs. For this, you should solve lots of problems!
2. **Learning basic web development.** This is a questionable inclusion into the list. Not everyone considers web development interesting, while some love it and make a career in it. However, I believe a basic understanding of web development is essential for any programmer. This step should take about a month or so.
3. **Learn OOPs.** This shouldn't take much long, however, it is a style of thinking and not just a bunch of concepts, so do not rush this. This should take about a month again.
4. **Learn how to use Git/Github.** Learning how to use a version control system (primarily Git) is essential as a programmer. It still astounds me how many students in CS engineering are not comfortable working with Git. Do not be afraid of Git / Github. It is simple to pick up and should not take more than 2 weeks of effort.
5. **Practice Problems on [LeetCode](https://leetcode.com/) / Make Projects.** This is a more long-term phase. Problem practice is supposed to consistent, so its hard to give a time line for this. It is meant to be done alongside the first four and much after as well. Basically, practice your skills on problems and projects for as long as you need to!

That's about it. After this, you will (hopefully) discover where your interests lie and be able to direct your further journey in Computer Science by yourself. Good luck, and have fun!

## On Machine Learning and AI

This section on Machine Learning and AI was contributed by [Glen Enosh](https://www.linkedin.com/in/glen-enosh-924414215) and [Harissh Ragav Dhamodaran](https://www.linkedin.com/in/harissh-ragav-dhamodaran-b7a8aa289/), core members of the [Enigma AI Club](https://www.linkedin.com/company/enigma-iiitkottayam/) at IIITK.

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
- Try doing your logical work in the morning and your creative work at night.
- Don’t trust us. Jump to advanced levels, face challenges, get mocked by the lack of knowledge, and doubt your ability. It’s okay to feel so. Don’t give up. Return to basics to understand the necessity of following the roadmap.Return to basics to understand the necessity of following the roadmap.
- Take on tougher projects involving skills or domains you haven’t explored but are interested in. This can create an urge to acquire the necessary skills or knowledge. You can either clutch or crumble under pressure, but if you have genuine interest and urge, you will survive.
- The key to learning stuff in this specific field is not just consistency and dedication, you have to choose the pertinent subjects to dedicate your time to.
- If you ever feel like getting stuck in a specific part, take a break, chill and then come back to it with a different point of view.
- The learning curve in AI is steeper than cubic polynomials, the initial steps can be tiring and exhausting. So, Try implementing the stuff that you learnt cuz visual learning proves to be helpful in the long run.
- Don’t blindly follow the tutorials implementing the ML and ANN algos, try to understand the intuition behind the algo and then code it up.
- Don’t ask too many questions up front. Just dive in and get started!

## On Cybersecurity

Lorem Ipsum.

## Programming Challenges

This is an extension to Point 5 of [How to get Started](#how-to-get-started): solving programming challenges and hackathons can also be a valuable way to gain experience and learn how to code. It can also help build valuable connections within your community!

### 1. Hackathons

Lorem Ipsum.

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

Lorem Ipsum.

## Tips from batchmates and seniors

And finally, I have collected some tips from my batchmates and seniors. They mention things they wished they knew before starting their programming journey and the suggestions they have for you:



## Concluding Remarks

Lorem Ipsum.
