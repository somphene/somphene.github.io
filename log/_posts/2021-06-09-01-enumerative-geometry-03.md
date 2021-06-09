---
layout: post
blog-category: blog
title: Enumerative Geometry 03 Littlewood Richardson
author: Som Phene
bigimg: log/images/01.jpg
tags: [Hermann Schubert, Quang Dao, William Fulton, University of Michigan, Schubert Class, Grassmann, Young, Representation, Prieri, Giambelli, Enumerative, Geometry, Introduction]
---

## Enumerative Geometry Littlewood Richardson

### Review [01]()
 - Structure of cohomology ring.
   - Multiplying, configuration by adding horizontal strip of length $$b$$.
 - Given partitions, how to determine the structure coefficitents?
   - Language of Young Tableaux for Littlewood-Richardson rule.
   
 ### Young Tableaux
-  Semi-Standard Young Tableaux for given a partition is 
  - Entries in rows are non-decreasing,
  - Entries in column are strictly increasing.  
- Z-module Multiplication
- Row insertion
- Reading word: read rows from bottom to top.
- Jeu-de-taquin (Jdt)
  - For partition inclusion: Skew shape, inner corner, outer corner
  - Skew Semi-Standard Young Tableaux (SSYT)
  - To make a semi-standard T from a skew T, slide the entries into the empty space.
  - Jdt slide for inner corner makes it an outer corner. Rectification: when Jdt done for all inner corners.
  - Define Jdt product and show it is equivalent to row insertion.
  
 ### Symmetric Polynomials
- Elements of invariant ring $$\mathbb{Z}[x_1,\ldots,x_n]^{S_n}= \wedge_n$$where $$S_n$$ acts by permuting elements.
- Monomial. Elementary (biject column). power-sum. complete homogeneous (biject row). 
- Schur Polynomial interpolate $$h_k$$ to $$e_k$$
  - $$\mathbb{Z}$$ basis
  - Expand positively in monomial basis
  - Symmetric polynomial
- Define similar family in Tableaux ring giving a ring homomorphism (no.of celss stays the same).
  - Pieri's Rule for Tableaux homomorphs to Schur polynomial.
  - Product Commutative specifically for the $$S_\lambda$$.
- Connection to Schubert Classes
  - Both satisfying Pieri's Rule in respective rings gives a homomorphism to cohomology ring.
 
### Littlewood Richardson Rule
- Enumerate by matching cardinality of two sets to write a given partition as a product of the two given partitions.
