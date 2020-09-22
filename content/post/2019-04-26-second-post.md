---
layout: post-no-feature
title: Infinite Series & Number Bases
description: 
categories: Articles
comments: true
---
# Introduction

A Laurent Series is a generalization of a power series and is given by

$$\displaystyle \sum _ { n = - \infty } ^ { \infty } a _ { n } z ^ { n } = \cdots + a _ { -1 } z ^ { - 1 } + a _ { 0 } z ^ { 0 } + a _ { 1 } z ^ { 1 } + \cdots$$

It turns out that our positional number system can be written as a Laurent Series where $z$ is the base and $a_{n}$ are the digits.

# Connection between Decimals and Laurent Series
If we let $z=10$, and $a$ be some real number in base 10, then $a$ can be written as the Laurent Series,

$$a = \sum _ { n = - \infty } ^ { \infty } a _ { n } 10 ^ { n }$$

where $a_{n}$ are the digits of $a$.

### Example 1
If $a = 24$, then we can write:

$$24 = \sum _ { n = - \infty } ^ { \infty } a _ { n } 10 ^ { n }$$

where 

$$
a_{i}=\left\{\begin{array}{ll}{4,} & {i=0} \\ {2,} & {i=1} \\ {0,} & {\text {otherwise}}\end{array}\right.
$$

That is,

$$ \begin{align*}
24 &= \cdots 00024.000 \cdots 
\\
   &=\sum _ { n = - \infty } ^ { \infty } a _ { n } 10 ^ { n }\
\\
   &= \cdots + a _ { -1 } 10 ^ { - 1 } + a _ { 0 } 10 ^ { 0 } + a _ { 1 } 10 ^ { 1 } + \cdots
\\
   &= \cdots + 0 \cdot 10 ^ { - 1 } + 4 \cdot 10 ^ {0} + 2 \cdot 10 ^ { 1 } + 0 \cdot 10^{2} + \cdots
\\
   &= \cdots + 0 + 4 + 20 + 0 \cdots
\\
   &= 24 
\end{align*} $$
