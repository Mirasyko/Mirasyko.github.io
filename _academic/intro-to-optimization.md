---
layout: default
title: "Convex Optimization — Basics"
date: 2025-08-24
tags: [optimization, convexity, duality]
excerpt: "Definitions, examples, and first properties of convex sets and functions."
---


A set $C \subseteq \mathbb{R}^n$ is **convex** if for any $x, y \in C$ and any $\theta \in [0,1]$, we have
$$
\theta x + (1-\theta) y \in C.
$$


A function $f: \mathbb{R}^n \to \mathbb{R}$ is **convex** if for all $x,y$ and $\theta \in [0,1]$,
$$
f(\theta x + (1-\theta) y) \le \theta f(x) + (1-\theta) f(y).
$$


**Jensen's inequality.** For a random variable $X$ and convex $f$,
$$
f(\mathbb{E}[X]) \le \mathbb{E}[f(X)].
$$


**Example.** The $\ell_2$ norm $\|x\|_2$ is convex because its epigraph is a convex cone. The function $x \mapsto \|Ax-b\|_2^2$ is convex with Hessian $2A^\top A \succeq 0$.


**Lagrangian and Dual.** For $\min_x f(x)$ s.t. $g_i(x) \le 0$, $Ax = b$,
$$
\mathcal{L}(x,\lambda,\nu) = f(x) + \sum_i \lambda_i g_i(x) + \nu^\top(Ax-b).
$$
The dual function is $g(\lambda,\nu) = \inf_x \mathcal{L}(x,\lambda,\nu)$ with $\lambda\ge 0$. Under Slater's condition, strong duality holds.