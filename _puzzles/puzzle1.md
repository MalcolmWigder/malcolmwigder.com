---
title: Gas me Up
summary: Starting off with a hard one
date: 2025-07-11
image: /Users/malcolmwigder/Desktop/website/malchemy/assets/puzzle1/10.png
layout: default
status: open
---

My first project for Professor Gonnermann was to design experiments to determine how bubbles and liquid separate in liquid. Using some imaging techniques, we extracted the average luminosity of coffee at different \( z \) values, at different times (shown below):

<p>
  <img src="/Users/malcolmwigder/Desktop/website/malchemy/assets/puzzle1/11.png" width="30%">
  <img src="/Users/malcolmwigder/Desktop/website/malchemy/assets/puzzle1/12.png" width="30%">
  <img src="/Users/malcolmwigder/Desktop/website/malchemy/assets/puzzle1/13.png" width="30%">
</p>

But we are not interested in the luminosity — we are interested in the *volume fraction of gas*, at every \( z \), at every \( t \).

We know the total volume fraction of gas, \( a_0 \), and a set of normalized functions  
\( \text{luminosity}(z) = L(z): [0, h] \to [0, 1] \) for every \( t \).

Can we find a function  
\( u(L): [0, 1] \to [0, 1] \) such that  
\( u(L(z)) = a(z) \),  
with the constraint  
$$
\frac{1}{h} \int_0^h u(L(z))\, dz = a_0 \quad \text{for all } t?
$$

Take for granted:

- At \( t = 0 \), both luminosity and volume fraction are flat lines.  
- At \( t = \infty \), they become step functions.

An analytical solution **or** an algorithmic technique is accepted.
