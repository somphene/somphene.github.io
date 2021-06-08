---
layout: post
blog-category: blog
title: Enumerative Geometry 01
author: Som Phene
bigimg: log/images/01.jpg
tags: [Hermann Schubert, Quang Dao, William Fulton, University of Michigan, Schubert, Grassmann, Young, Representation, Allen Knusten, Terrence Tao, Puzzle, Introduction]
---

## Count Geometric variety

Please find linked: 
 - [PBS-Youtube-Schubert Calculus](https://www.youtube.com/watch?v=_kDK2vQ0YgM):
 - Sperner's Lemma and Fixed point thm? Tensor contraction? Thomas Lam's course Proof of matchings by contracting 0, 1?
 - Fulton Young Tableaux 
 - [Variations on a Theme of Schubert Calculus](https://arxiv.org/pdf/1804.08164.pdf?fbclid=IwAR3x2coAp3n4bLPkdZ0LYRwiq8AbVryQcg2yRFyUtHtBcYZB7-CCQMpI7cg)
 - Aaron Pixton
 - Thomas Lam
 - Charlotte Chen (Grassmannian, Rep theory geometric side)
 - Tasho Kaletha (Langlands, Lefschetz Principle)

### Summer minicourse Quang Dao - Vietnam, UMich - Flavors of Schubert Calculus 

- Enumerative Geometry: counting algebro-geometric objects satisfying some given conditions.
- Motivating question: How many lines meet all 4 gievn lines in $$P^3$$ space?
  - lines in  $$P^3$$ is 2-plane in 4 space hence Consider Gr(2,4).

- Plucker embedding is an injective embedding  of minors to a closed subvariety hence a projective variety. 
  - Contrapositive(Matrix has rank at least k iff at least one minor has rank at least k)= None of the minors have rank at least k iff Matrix has rank less than k
  - Each minor is a determinant which gives an equation on coefficients of basis vectors.
  - Anna Brosowsky's example: let k=2, n=3. Let X be the matrix of variables, with entries x_ij. Then a matrix with rank < 2 is a matrix with all 2x2 minors 0, i.e. satisfying the 3 minors being 0: x_11*x_22 = x12*x21, x12*x23=x22*x13, and x11*x23 = x13*x21
  - Affine Charts. Theorem on locally isomorphic. Also irreducible and smooth.
- Schubert Cells 
  - Fix a basis and complete flag. Every subpace in Gr(k,n) can be represented by a unique $$k \times n$$ row echelon form.
  - Poisition is the column index of leading (from right to left) 1s. The following zeros form a Young diagram.
  - Partition (number of row entries)$$\lambda_i$$ Corresponding to Position $$(n-k+i-\lambda_i)$$. Open in Schubert variety is Schubert cell (denote by $$\circ$$). Schubert cell closure in Zariski topology.
  - The boundary Schubert variety/ Schubert cell is a disjoint union of cells. This gives an affine stratification.
  - The cohomology class is independent of choice of complete flag as they are related by Gl(k) action.
  - Example: set of k-subspaces meeting a given space.

### R

- Swaraj Sridhar Pande refers to [Speyer's Algebraic Geometry course](http://www.math.lsa.umich.edu/~speyer/631/) for interpreting the equations of Plucker embedding to be a projective variety.
