---
layout: post
blog-category: blog
title: Quantum espresso, VNL, input- scf, nscf dos
author: Som Phene
image: 
tags: [Quantum, Espresso, Resources, Input] 
---
* Qunatum Espresso input file can be automatically made by Virtual Nano Lab. 
Open new project, Builder, Add to stash from database-Si (alpha)-right click  to export as QE(.in file). 

* Always keep prefix same in all scf, nscf, dos calculations.

1. Should we do scf before relaxation?
* "To converge k-point mesh and ecutwfc, you can do a few dummy scf calculations with approximate lattice parameters (say from experiments). After that you should do a relax calculation with the converged parameters." - Anshuman Kumar (a few years later he joined IITB as an Assistant Professor, whose both graduate courses I enjoyed immensely).

* Range of ecutwfc and ecutrho: ecutwfc, ecutrho depend on type of pseudopotentials used (should test). When using ultrasoft pseudopotentials, set ecutrho = 8-12 × ecutwfc !

