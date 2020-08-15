---
layout: post
blog-category: blog
title: Quantum espresso PWscf
author: Som Phene
image: 
tags: [Quantum, Espresso, Resources, Input] 
---

Anshuman Kumar (then an EP alumnus, PhD student, now Professor at IITB) coming to the rescue for me again: 
"I am providing two approaches, which have generally been mentioned in the other answers. The only place where my answer differs is that it is specific to PWscf.
Two methods:

1) Brute force:
Run scf calculation for different lattice parameters.
Plot total lattice energy as a function of the lattice parameter
Look for minimum energy point, whose abscissa will give the optimized lattice constant

2) Smart way
a) In the &control block in you input file, set:
calculation='vc-relax',
b) In the &ions block of the input file, set
ion_dynamics = 'bfgs'
c) In the &cell block, set
cell_dynamics = 'bfgs'
cell_dofree = 'xyz'

Thats all."
