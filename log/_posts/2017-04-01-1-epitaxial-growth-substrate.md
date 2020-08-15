---
layout: post
blog-category: blog
title: DFT for simulation of materials growth
author: Som Phene
image: 
---

## Epitaxial Growth of a material on a substrate

### Aim
To understand the epitaxial growth of Au on MoS2. Especially why is the predominant experimentally observed orientation {111} and not one of the other two possible orientations? Follow this with a similar calculation for growth of another phosphide on graphene. 

### Introduction 
* Epitaxy means the growth of a single crystal film on top of a crystalline substrate.
* For most thin film applications (hard and soft coatings, optical coatings, protective coatings) it is of little importance.
* However, for semiconductor thin film technology it is crucial.

### Heteroepitaxy

* Trying to grow a layer of a different material on top of a substrate leads to unmatched lattice parameters.
* This will cause strained or relaxed growth and can lead to interfacial defects.
* Such deviations from normal would lead to changes in the electronic, optic, thermal and mechanical properties of the films.

### Plan of action:

Use DFT to simulate growth of gold on dichalcogenides

Stages of DFT calculation

1. Modelling of structure interface using Virtual Nanolab followed by relaxation  and scf of the structure in VASP.

2. Electronic structure for Au on MoS2. 
* PBE
* PBE sol
* Meta-GGA

3. Data visualization by p4vasp or GNU plot
4. Parameter Calculations

