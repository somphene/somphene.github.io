---
layout: post
blog-category: blog
title: Smearing and K-points
author: Som Phene
image: 
tags: [Smearing, K-points, Quantum, Espresso, Resources, Input] 
---

Q. Which degauss value should I use for QUANTUM ESPRESSO input file? [Reference](https://www.researchgate.net/post/Which_degauss_value_should_I_use_for_QUANTUM_ESPRESSO_input_file)

A. The smearing is strongly connected with the k-points mesh you use in metals, where you need a good sampling of the occupied manifold (essentially of the Fermi surface).  In principle, the smearing should be as small as possible and the k points mesh as large as possible. Then for degauss => zero and kpoints => infty, you should get the right value, for any quantity.

As this is not computationally feasible, the crucial point is to compromise, choosing the right combination of smearing and kpoints (i.e. maximizing degauss and minimizing k-points) AND at the the same time leaving quite unaltered the quantity that you want to calculate. The point is that a very large smearing, in fact, spuriously affects the quantity you want to calculate (total energy or whatever).  
If you are using a large cell with only $$k=\Gamma$$, try to use the largest smearing, which always helps convergence, monitoring how strongly this affetcs the quantity that you want to calculate, as Roberto suggests.
In my experience, smearing helps also for insulators or molecules, greatly improving the convergence. 
