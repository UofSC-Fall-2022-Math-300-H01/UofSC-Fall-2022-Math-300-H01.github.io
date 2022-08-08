---
layout: page
title: Solving Linear Systems
nav_order: 1
has_children: true
parent: Notes
reading_estimate: true
---

## A motivating example

Linear algebra is ubiquitous. It can even appear seemingly out of no-where. 

For example, assume we have two races of aliens. They are at constant war. 
To understand the progress of the war, we want to know the population of each 
at any given time. 

Let us try to mathematize this. First, we need to assign some labels. Let's call 
the population of the first group $X$ and the population of the second $Y$. 

These are functions of time, which we call $t$. So we can also write $X(t)$ and 
$Y(t)$ to emphasize this. 

Now the populations grow as they procreate. The populations decrease with repeated 
conflicts. Let's make this more precise. 

- Say it takes 4 aliens to produce 1 more of $X$ and 3 aliens to make 
1 more of $Y$ and 
- 2 aliens of type $X$ eliminates 1 of $Y$ while 3 aliens of $Y$ remove 1 of $X$. 

Then we can model the populations with the system of differential equations:

$$
 X^\prime(t) = \frac{1}{4} X(t) - \frac{1}{3} Y(t) \\ 
 {} \\
 Y^\prime(t) = - \frac{1}{2} X(t) + \frac{1}{3} Y(t). 
$$

This seems complicated. Let's try to understand a basic problem: is possible for 
the populations $X$ and $Y$ to be constant? In other words, is there a steady-state 
solution? 

If the populations are constant, then we have 
$$ 
 X^\prime(t) = Y^\prime(t) = 0 
$$
and there are fixed constant values $x$ and $y$ so that 
$$
    X(t) = x \text{ and } Y(t) = y 
$$
for any value of time $t$. 

So, we need to solve 
$$ 
 0 = \frac{1}{4} x - \frac{1}{3} y \\
 {} \\
 0 = - \frac{1}{2} x + \frac{1}{3} y
$$
for the possible $x$ and $y$. Can we? 

The collection of equations is a called a *system of linear equations*. Our first 
goal is to understand when it is possible to find solutions and how we can do so 
explicitly. 