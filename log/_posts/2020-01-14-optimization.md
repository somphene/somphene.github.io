---
layout: post
blog-category: blog
title: Optimization Lecture 2
author: Som Phene
bigimg: log/images/diggity-marketing-s8HyIEe7lF0-unsplash.jpg
tags: [Bolzano-Weierstrass, GLB, LUB, Infimum, Minimum, Convergence, Open, Closed, Compact, Set, Heine-Borel theorem, Continuous, Function, Weierstrass theorem, Real Analysis, Sequence, Subsequence, Calculus, MA 105, Optimization, SC 607, Ankur Kulkarni] 
---
### Real Analysis and Weierstrass Theorem

* Find the $$2^{nd}$$ lecture notes linked: [SC 607 IITB Lecture Notes 2 (Google Drive link)](https://drive.google.com/file/d/1u7p2qEo98nxA9R2o2ZLkg7aO8ETTpJbH/view?usp=sharing), [Lecture Notes 2 (Github link)](https://github.com/somphene/Optimization-Ankur-Kulkarni-SC-607-IITB-2020/blob/99ad8f7babee3df9c1e825cf82a984cafa0411d4/Notes/Optimization_Som_S__Phene%20(2).pdf).
* Find the entire lecture notes linked: [SC 607 IITB Lecture Notes 1-2 (Google Drive link)](https://drive.google.com/file/d/1LRuWnZvlzprghZ7q0LLM2Vfkr5USftGX/view?usp=sharing), [Lecture Notes 1-2 (Github link)](https://github.com/somphene/Optimization-Ankur-Kulkarni-SC-607-IITB-2020/blob/c4ec0377702554424f87192e8446f5347426677d/Notes/Optimization_Som_S__Phene%20(1-2).pdf)
* $$\textbf{Bolzano-Weierstrass}$$ Theorem states that every bounded sequence in $$\mathbb{R}^n$$ converges. This can be seen as follows: every real sequence has a monotone subsequence (construct one such by looking at the roofs of the sequnence). Monotone and bounded in $$\mathbb{R}^n$$ combines to give convergence. 
* $$S$$ is an Open set if for every point of $$S$$, we can find a ball of positive radius containing it and which is contained entirely inside $$S$$. A set is said to be closed if its complement is open. 
* Arbitrary union of open sets is open. Finite intersections of open sets is open. By DeMorgan's Laws, the corresponding stability under unions and intersections of closed sets can be seen to be exactly the reverse: Arbitrary intersection of closed sets is closed and finite union of closed sets is closed. Notions of open and closed sets depend on the ambient space but is there a notion independent of ambient space? Yes! that of a [compact set](https://mathcs.org/analysis/reals/topo/compact.html). Similar to closed sets, Compact sets are also stable under arbitrary intersection and finite unions.
* Since we shall be working in $$\mathbb{R}^n$$ with the Euclidean metric, it is imperative to introduce a useful characterization of compact sets in $$\mathbb{R}^n$$. This is given by the $$\textbf{Heine-Borel Theorem}$$ which states that compact sets in $$\mathbb{R}^n$$ are precisely those that are closed and bounded.
* Denote a $$\textbf{Ball of radius} \,\, r>0$$ in $$\mathbb{R}^n$$ as: 
$$B(x,r)= \{ y \in \mathbb{R}^n \, | \,\,  \lVert y-x \rVert  < r \} $$
* Just as in the notion of convergence, we pose another challenge- $$f \colon \mathbb{R}^n \to \mathbb{R} $$ is said to be $$\textbf{continuous at a point}$$ $$x \in \mathbb{R}^n$$ if $$\forall \epsilon >0, \quad \exists \delta > 0, \quad$$ such that $$ \lvert f(y)-f(x) \rvert < \epsilon, \quad \forall y \in B(x,\delta)$$
* Sequentially continuous function means that for any fixed $$x$$, every sequence $$x_n \to $$x_0 \implies $$f(x_n) \to f(x)$$. 
* Recall from Calculus (MA 105), that in Metric Spaces, sequentially continuous is equivalent to contiuous functions. (This is provided Axiom of Choice or Counatbility is assumed, for details see [Axiom of Countability](https://en.wikipedia.org/wiki/Axiom_of_countability) or find a time to discuss with [Aryaman](https://aryamanmaithani.github.io/)).
* While convergence to optimal solution may be shown, is there a guarantee that it can be attained in the feasible region? Here's where $$\textbf{Weierstrass Theorem}$$ comes handy. It states that for continuous functions on compact sets, the infimum exists and is attained on the compact set itself.
