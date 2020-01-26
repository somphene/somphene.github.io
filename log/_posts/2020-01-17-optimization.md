---
layout: post
blog-category: blog
title: Optimization Lecture 3
author: Som Phene
bigimg: log/images/diggity-marketing-s8HyIEe7lF0-unsplash.jpg
tags: [ Weierstrass theorem, Optimization with constraints, constraints, inf, sup, Infimum, Minimum, Convergence, Set, Heine-Borel theorem, Continuous, Function, Real Analysis, Sequence, Subsequence, Calculus, MA 105, Optimization, SC 607, Ankur Kulkarni] 
---

Updated version of my notes is linked below:
* Find the $$3^{3d}$$ lecture notes linked: [SC 607 IITB Lecture Notes 3 (Google Drive link)](), [Lecture Notes 3 (Github link)](https://github.com/somphene/Optim).
* Find the entire lecture notes linked: [SC 607 IITB Lecture Notes 1-2 (Google Drive link)](https://drive.google.com/file/d/1LRuWnZvlzprghZ7q0LLM2Vfkr5USftGX/view?usp=sharing), [Lecture Notes 1-2 (Github link)](https://github.com/somphene/Optimization-Ankur-Kulkarni-SC-607-IITB-2020/blob/c4ec0377702554424f87192e8446f5347426677d/
* Local minimum is exactly what the English word says: a point in the domain is a local minimum of the function if there is a neighbourhood in which the function takes values greater than or equal to the value at such a point. That is $$x^* \in S$$ is said to be a $$\textbf{local minimum}$$ if $$ \exists \, r >0$$ s.t. 
$$ f(x^*) \le f(x) \quad \forall x \in B(x^*, r) \cap S
$$ 
* Unconstrained minimum and global minimum are the corresponding terms given for the above inequality holding over all of $$\mathbb{R}^n$$ or over all of the feasible region respectively. What about constraints while trying to optimize?
* $$\textbf{Goal}$$: min $f(x)$ s.t. $g_i(x) \le 0 \quad \forall i= 1, \ldots , m; \\
h_j(x)= 0 \quad \forall j= 1, \ldots , p$$ are satisfied.
