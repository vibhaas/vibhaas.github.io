---
title: Probability I - Counting and Axioms
date: 2024-08-04 08:30:45 +0530
categories: [Programming]
math: true
tags: [notes, math, probability, btech, undergrad] # TAG names should always be lowercase
---

- Back to index: [Probability 0](/posts/probability0/)

## 1. On Counting
 *(This will be basic combinatorics for probability.)*

#### 1.1 Basic Principle of Counting

> **Principle:** When two *independent* experiments are performed, having $n$ and $m$ outcomes respectively, then together there are $nm$ outcomes of both the experiments. 
{: .prompt-tip }

> **Proof:** We can enumerate all the outcomes for both the experiments. Let us number the outcomes of the first experiment $1, 2, ..., n$ and the outcomes of the second experiment $1, 2, ..., m$. Then an ordered pair $(i, j), 1 \leq i \leq n, 1 \leq j \leq m$, represents the joint outcome that event $i$ experiment occurred in the first experiment and event $j$ occurred in the second experiment. We can enumerate all ordered pairs as follows:
>
>$$
\begin{matrix}
    (1, 1) & (1, 2) & \dots  & (1, m) \\
    (2, 1) & (2, 2) & \dots  & (2, m) \\
    \vdots & \vdots & \ddots & \vdots \\
    (n ,1) & (n, 2) & \dots  & (n, m)
\end{matrix}
$$
>
>Clearly, there are $n$ rows and $m$ columns in the above matrix. So, we have $n \times m$ total possible outcomes.
{: .prompt-info }

#### 1.2 General Principle of Counting

> **Principle:** If there are $r$ events to be performed, having $n_1, n_2, ..., n_r$ outcomes respectively, then together there are a total of $n_1n_2...n_r$ outcomes.
{: .prompt-tip }

> **Proof:** Left to reader. Use induction.
{: .prompt-info }

#### 1.3 Permutation of $n$ objects

> **Statement:** The number of rearrangements of $n$ objects is given by $n!$.
{: .prompt-tip }

> **Proof:** Let us have $n$ experiments: Choosing the first object from $n$ objects, choosing the second object from the remaining $n-1$ objects and so on. The number of outcomes for the first experiment is $n$, and in the second $n-1$ and so on. Therefore, by the Principle of Counting, the total number of outcomes are $n \cdot (n-1) \cdot (n-2) \cdot \cdot \cdot 1 = n!$.
{: .prompt-info }
