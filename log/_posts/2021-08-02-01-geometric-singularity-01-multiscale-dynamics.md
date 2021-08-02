---
layout: post
blog-category: blog
title: Geometric Singularity 01 
author: Som Phene
bigimg: log/images/01.jpg
tags: [Geometric, Singularity, Sameer Kailasa, University of Michigan, Victoria Booth, Philip Hartman, Johns Hopkins University, David Matveevich Grobman, Moscow University, Algebraic, Variety, Polynomial, Equivalence, Geometry, Summer, Introduction]
---

## Multiscale Dynamic

### Linear ODE
- Matrix exponential flow.
- Jordan decomposition to Diagonal $$+$$ Nilpotent.
  - Diagonal ( $$Re ( \lambda ) > 0$$ or $$Re ( \lambda ) < 0$$ ) exponential flow at most exponential (Unstable $$E^u$$ or Stable $$E^s$$ subspace respectively).
  - Nilpotent ( $$Re ( \lambda ) = 0$$ exponential flow at most polynomial (Center subspace $$E^c$$).   
  - Direct Sum decomposition $$\mathbb{R}^n = E^s \oplus E^c \oplus E^u$$

### Invariant Manifold

Nonlinear system $$\dot{x} = f ( x )$$, smooth vector field, has equilibrium point $$p$$ if $$ f ( p ) =0$$.
- Matrix is hyperbolic if Direct Sum decomposition is diagonal: $$\mathbb{R}^n = E^s \oplus 0 \oplus E^u$$.
- Hartman-Grobman: If equilibrium point is hyperbolic, Then in a neighborhood around p, the nonlinear system is topologically conjugate to its linearised system $$\dot{x} = Df ( x )$$.
  - Stable-Unstable Manifold: Unstable $$W^u$$ or Stable $$W^s$$ manifold topologically conjugate to the linear Unstable $$E^u$$ or Stable $$E^s$$ subspace.
  - Center Manifold
  
### Codimension 1 bifurcations of equilibrium

For $$x$$ in $$\mathbb{R}$$ , $$\mu$$ in $$\mathbb{R}$$, let $$ f ( x , \mu )$$ be a one parameter family of vector fields. Bifurcation theory characterize geometric transition in phase portrait with respect to $$\mu$$. For hyperbolic equilibrium point $$p^*$$ at $$\mu^*$$,
- Implicit function theorem $$\implies$$ the equilibrium perturbs smoothly to $$p^*(\mu)$$ in some neighbourhood $$I$$ of $$\mu^*$$.
- Continuity of eigenvalues $$\implies$$ the equilibrium $$p^*(\mu)$$ is hyperbolic in the neighbourhood $$I$$ of $$\mu^*$$.

Generic way to lose hyperbolicity in a one parameter family:
- Real eigenvalue passes through zero (Saddle node bifurcation)
  -  Then in a neighborhood around $$p$$, the phase portrait is equivalent to its universal system $$\dot{x} = \mu - x^2$$.
- Complex eigenvalue pair pass through zero (Hopf bifurcation).
 - If the eigenvalue pass through zero with non-zero speed along x-direction, first Lyapunov coefficient not zero Then Hopf bifurcation.
 - Hopf Bifurcation Scaling
 
### Introduction: Van der Poly Oscillator
For $$a$$ and $$\epsilon$$ (small) positive constants,
$$ \begin{align}
  \dot{x} &= x - \frac{x^3}{3} + y \quad \textrm{fast}\\
  \dot{y} &= \epsilon \cdot (a - x) \quad \textrm{slow}
\end{align}
$$
There is a unique equilibrium point $$p := (a, \frac{a^3}{3})$$ with Jacobian and eigenvalues $$ \lambda = \frac{(1-a^2) \pm ((a^2-1)^2-4\cdot \epsilon)^{\frac{1}{2}}}{2}$$
- Along cubic: differentio-algebraic
- Away from cubic: parameter


### R
- Grobman--Hartman theorem was first proved (Grobman, D. M. (1959). "О гомеоморфизме систем дифференциальных уравнений" [Homeomorphisms of systems of differential equations]. Doklady Akademii Nauk SSSR. 128: 880–881.) in 1959 by the Russian mathematician David Matveevich Grobman (born in 1922) from Moscow University, student of Nemytsckii. The next year, Philip Hartman (1915--2015) at John Hopkins University (USA) independently confirmed this result (Hartman, Philip (1960). "A lemma in the theory of structural stability of differential equations". Proceedings of the American Mathematical Society, 11, (4): 610–620. doi:10.2307/2034720).
- [Brown University, Vladimir_Dobrushkin, Methods of Applied Mathematics II course](https://www.cfm.brown.edu/people/dobrush/am34/Mathematica/ch3/linear.html)
