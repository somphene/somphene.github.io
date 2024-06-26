---
layout: post
blog-category: blog
title: Atomistic Modeling of Materials Tutorial
author: Som Phene
image: 
tags: [Atomistic, Modeling, Materials, Quantum, Espresso, Resources, Input] 
---

* MIT Atomistic Modeling of Materials [video lectures](https://www.youtube.com/watch?v=tynCH4dosA8)

* [Lecture Notes](https://ocw.mit.edu/courses/materials-science-and-engineering/3-320-atomistic-computer-modeling-of-materials-sma-5107-spring-2005/lecture-notes/)

* [DMSE MIT electronic materials courses](https://ocw.mit.edu/courses/find-by-topic/#cat=engineering&subcat=materialsscienceandengineering&spec=electronicmaterials)

* [Lab 3 handout](http://www.chemistry2011.org/ResourceFiles/lab3_handout.pdf)

* We are going to use ultrasoft pseudopotentials here. In the case of normconserving pseudopotentials, ecutrho (the charge density cutoff) is automatically determined by 4*ecutwfc. However, in the case of ultrasoft pseudopotentials, we need an augmented charge around the ion core, so ecutrho should be higher than 4*ecutwfc. The usual value is 25-35 Ry for ecutwfc and 200-300 Ry for ecutrho. You might want to do a convergence check. Keep in mind that the value you should look at is the energy difference or force, not the absolute value of the energy (the energy will not converge unless you use very, very high ecutwfc and ecutrho). 

* You will notice that there are now three additional flags at the end of our atomic coordinates. These flags define the degrees of freedom available for those atoms during relaxation (zero = disallow motion in that direction for that atom). In the example shown above, the Ba and Ti ions are fixed, while the O ions are allowed to relax. So the format is: atomic label pos_x pos_y pos_z allow_x allow_y allow_z You will find that using scripts will save you tons of time on this problem set. Not using scripts would mean that you could spend literally days sitting at a computer waiting for runs to finish. You should be able to set up the appropriate scripts based on the ones we've already used for examining Fe and also the example script from last problem set. A sample shell script for submitting a job using this example input file can be found in the ~brandonw/LAB3 directory. You should copy this file and modify it appropriately.
