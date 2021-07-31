---
title: Euler's φ Function
aside:
    toc: true
tags: number-theory
mathjax: true
---
## Definition
$\phi(n)$ is the number of integers between 0 and n-1 who is coprime with n.
$\phi(n):=|\{a: 0 \leqslant a<n \wedge(a, n)=1\}|$
<!--more-->

## Properties
1. Let a be an integer comprime with n. Then $a ^ { \phi ( n ) } \equiv 1 \bmod n$
2. (m,n)=1 $\implies \phi(mn)=\phi(m) \cdot \phi(n)$
3. $\sum _ { d \mid n } \phi ( d ) = n$