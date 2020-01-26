---
layout: post
blog-category: blog
title: Optimization Lecture 3
author: Som Phene
bigimg: log/images/diggity-marketing-s8HyIEe7lF0-unsplash.jpg
tags: [ Weierstrass theorem, Open, Closed, Unbounded, Discontinuous, Compact, Interior, Closure, Boundary, Optimization with constraints, constraints, inf, sup, Minimum, Convergence, Set, Heine-Borel theorem, Continuous, Function, equality constraints, Inequality constraints, Real Analysis, Sequence, Subsequence, Calculus, MA 105, Optimization, SC 607, Ankur Kulkarni] 
---

### Optimization with Constraints
* Find the $$3^{3d}$$ lecture notes linked: [SC 607 IITB Lecture Notes 3 (Google Drive link)](https://drive.google.com/file/d/1DFK0Ax5-B16WvBRULAouGL6jEfiQ-54k/view?usp=sharing), [Lecture Notes 3 (Github link)](https://github.com/somphene/Optimization-Ankur-Kulkarni-SC-607-IITB-2020/blob/4c19d756ed33fef0c6e088111afc1f509bff4a76/Notes/Optimization_Som_S__Phene%20(3).pdf).
* Find the entire lecture notes linked: [SC 607 IITB Lecture Notes 1-3 (Google Drive link)]https://drive.google.com/file/d/1b7Rjg2MHsa2YIjilapCP1tI9-0D1EcwQ/view?usp=sharing), [Lecture Notes 1-3 (Github link)](https://github.com/somphene/Optimization-Ankur-Kulkarni-SC-607-IITB-2020/blob/c4ec0377702554424f87192e8446f5347426677d/
* Interior: $$C$$ is any set then,
$$ \dot{C} = \textrm{interior of C} = \underset{S \textrm{ is open} \, \& S \subseteq C}{\bigcup} S
$$
\end{definition}
\begin{definition}
[Closure]Let $$C \subseteq \mathbb{R}^n$$ be any set.
$$ \overline{C} = \textrm{closure of C} = \underset{S \textrm{ is closed} \, \& S \supseteq C}{\bigcap} S$$
\end{definition}
\begin{definition}
[Boundary] $\partial C = \overline{C}\setminus \dot{C}$.
\end{definition}
* Local minimum is exactly what the English word says: a point in the domain is a local minimum of the function if there is a neighbourhood in which the function takes values greater than or equal to the value at such a point. That is $$x^* \in S$$ is said to be a $$\textbf{local minimum}$$ if $$ \exists \, r >0$$ s.t. 
$$ f(x^*) \le f(x) \quad \forall x \in B(x^*, r) \cap S
$$ 
* Unconstrained minimum and global minimum are the corresponding terms given for the above inequality holding over all of $$\mathbb{R}^n$$ or over all of the feasible region respectively. What about constraints while trying to optimize?
* $$\textbf{Goal}: \min f(x)$$ s.t. $$g_i(x) \le 0 \quad \forall i= 1, \ldots , m; \\
h_j(x)= 0 \quad \forall j= 1, \ldots , p$$ are satisfied.
* Weierstrass Theorem gives existence of a global minimum.
* Isolated local minimum $$\implies$$ strict local minimum.
* Geometry of inequality constraints is very different from that of equality constraints. Interior vs Boundary of a set.
* Interior of a set is an open set since it is an arbitrary union of open sets. In fact it is the largest open set contained in $$C$$. \vocab{Closure} of a set is a closed set since it is an arbitrary intersection of closed sets. In fact it is the smallest closed set containing $$C$$. It follows that if $C$ is open, $\dot{C}=C$ and if $$C$$ is closed, then $$\overline{C}=C$$. This means that if $$C$$ is open, $$\partial C$$ contains no point of $C$ and if $C$ is closed, all points of $$\partial C$$ are points of $$C$$.
