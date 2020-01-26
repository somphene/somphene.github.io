---
layout: post
blog-category: blog
title: Optimization by Ankur Kulkarni
author: Som Phene
bigimg: log/images/diggity-marketing-s8HyIEe7lF0-unsplash.jpg
tags: [Introduction, Limit, Convex, Symmetry, Geometry, Metric space, Convergence, Existence, Uniqueness, Isoperimetric, Real Analysis, Sequence, Optimization, SC 607, Ankur Kulkarni] 
---
### Optimization by Prof. Ankur Kulkarni, SC 607 IITB (2020)
* Regular updates for this course can be found on the linked page: [Som Phene Log Tag: SC 607](https://somphene.github.io/tags/#SC%20607) and relevant material on [Som Phene Log Tag: Optimization](https://somphene.github.io/tags/#Optimization).
* This log documents my work for the above course and is not checked to be free from errors. Please send comments, point out errors, and suggestions via email to somphene1 at gmail dot com. Any mistakes are attributed to my own hastiness and not the Professor who has most probably not seen any of this work. 
* This course offering is being recorded by [CDEEP](http://www.cdeep.iitb.ac.in/) so the lecture videos are uploaded on their [site](http://www.cdeep.iitb.ac.in/vod/vodCloud/course_intra.php?ccode=320) (LDAP sign in needed). It will also be uploaded to [NPTEL](https://nptel.ac.in/) with the course name Optimization from fundamentals.

### Introduction to Optimization and Real Aanalysis
* Find the $$1^{st}$$ lecture notes linked: [Lecture Notes 1 (Google Drive link)](https://drive.google.com/file/d/1cTBcl2U1-vUzwPCGR5QQukErB8nR5xXk/view?usp=sharing), [Lecture Notes 1 (Github link)](https://github.com/somphene/Optimization-Ankur-Kulkarni-SC-607-IITB-2020/blob/b2b3c11fdb81e3cebb18da5f42848f6f92dfeeea/Optimization_Som_S__Phene%20(1).pdf). 
* As this is being recorded for [CDEEP](http://www.cdeep.iitb.ac.in/vod/vodCloud/course_intra.php?ccode=320), it places constraints on teaching style and interaction. 
* Started with an introduction to optimization and provided motivation to build formal techniques to solve optimization problems. The class ended with some review of Real Analysis.
* Existence of optimal solution to a problem cant be taken for granted and must be proved. This requires notions of convergence for which Real Analysis must be reveiwed. 
* The notion of a sequence $$ (x_n)_{n \in \mathbb{N}}$$ converging can be formalized as a challenge problem: A sequence converges to a point $$x^*$$ means that for any given $$\epsilon >0$$ (that could be as small as the challenger demands), there is a point in the sequence after which all points are within $$\epsilon >0$$ distance of $$x^*$$. That is
$$  \forall \epsilon >0, \quad \exists \,\, n_0 \in \mathbb{N}, \quad \textrm{such that} \\ \quad \| x_n-x^* \| < \epsilon, \quad \forall n > n_0  $$
