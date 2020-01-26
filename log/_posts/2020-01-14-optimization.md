---
layout: post
blog-category: blog
title: Optimization Lecture 2
author: Som Phene
bigimg: log/images/diggity-marketing-s8HyIEe7lF0-unsplash.jpg
tags: [Bolzano weierstrass, GLB, LUB, Convergence, Open, Closed, Compact, Set, Heine-Borel theorem, Continuous, Function, Weierstrass, Real Analysis, Sequence, Subsequence, Optimization, SC 607, Ankur Kulkarni] 
---
### Real Analysis and Weierstrass Theorem

* Find the $$2^{nd}$$ lecture notes linked: [SC 607 IITB Lecture Notes 2 (Google Drive link)](https://drive.google.com/file/d/1u7p2qEo98nxA9R2o2ZLkg7aO8ETTpJbH/view?usp=sharing), [Lecture Notes 2 (Github link)](https://github.com/somphene/Optimization-Ankur-Kulkarni-SC-607-IITB-2020/blob/99ad8f7babee3df9c1e825cf82a984cafa0411d4/Notes/Optimization_Som_S__Phene%20(2).pdf).
* Find the entire lecture notes linked: [SC 607 IITB Lecture Notes 1-2 (Google Drive link)](https://drive.google.com/file/d/1LRuWnZvlzprghZ7q0LLM2Vfkr5USftGX/view?usp=sharing), [Lecture Notes 1-2 (Github link)](https://github.com/somphene/Optimization-Ankur-Kulkarni-SC-607-IITB-2020/blob/c4ec0377702554424f87192e8446f5347426677d/Notes/Optimization_Som_S__Phene%20(1-2).pdf)
* $$\textbf{Bolzano-Weierstrass}$$ Theorem states that every bounded sequence in $$\mathbb{R}^n$$ converges. This can be seen as follows: every real sequence has a monotone subsequence (construct one such by looking at the roofs of the sequnence). Monotone and bounded in $$\mathbb{R}^n$$ combines to give convergence. 
* Since we shall be working in $$\mathbb{R}^n$$ with the Euclidean metric, it is imperative to introduce a useful characterization of compact sets in $$\mathbb{R}^n$$. This is given by the $$\textbf{Heine-Borel Theorem}$$ which states that compact sets in $$\mathbb{R}^n$$ are precisely those that are closed and bounded.
* Define a Ball of radius $$r$$ in $$\mathbb{R}^n$$ as 
$$r>0, \quad B(x,r)= \{ y \in \mathbb{R}^n \, | \,\,  \lVert y-x \rVert  < r \} $$
* $$f \colon \mathbb{R}^n \to \mathbb{R} $$ is said to be \vocab{continuous at a point $$x \in \mathbb{R}^n$$} if $$\forall \epsilon >0, \quad \exists \delta > 0, \quad$$ such that $$ \lvert f(y)-f(x) \rvert < \epsilon, \quad \forall y \in B(x,\delta) $$
