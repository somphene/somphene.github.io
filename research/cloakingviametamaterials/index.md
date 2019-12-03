---
layout: page
title: Metamaterial Cloaking
subtitle: Design Optimization of Metamaterials for Cloaking
use-site-title: true

---
#### Keywords: 
Inverse Problems, Geometric Analysis, Design Optimization, Dirichlet to Neumann (DtN) Map, Steklov Eigenvalues, Spectral Theory, Asymptotic Expansions, Cloaking, Metamaterials, Transformation Media (Optics), Polarization Tensors, Electrical Impedance Tomography 

### [Synopsis](https://drive.google.com/file/d/1NbbyIOf-f-dG5ewxvtFywo-6XBzZ6K2P/view?usp=sharing)

### Poster 
* Different parts of this work were presented at Tech and Research & Development exposition, ResearchX, IIT Bombay to Professors, esteemed guests, Alumni, experts from industry and students. [Poster](https://drive.google.com/file/d/1kz88fNsu9a-dw6SsTkoKsX1vWJh6yJw6/view?usp=sharing)

### Introduction
The primary reason why I got interested in physics was because of the story of electromagnetism. My high school physics teacher's motivating demonstrations and inspirational lectures including examples like Nikola Tesla was what got me interested in electromagnetism in the first place. Reading through online sites all night and trying to figure out how cloaking in [Tesla’s mysterious experiments/ Philadelphia experiments](https://teslauniverse.com/nikola-tesla/books/nikola-tesla-and-secrets-philadelphia-experiment) could work, made me realize that I didnt understand electromagnetism. Since then, its been eight years and I have tried to constantly improve my understanding, leading to my Master's Thesis on novel techniques for cloaking. I hope in the process of making this final year thesis, I go one step further. Every once in a while, a new problem pops up and again I get the same feeling of ‘I don't understand electromagnetism’. It’s this everyday struggle of not being able to reinterpret and connect stories that keeps me going. 

Classical electromagnetic field theory is one of the oldest theories and it has stood the test of time, be it the quantum revolution or general relativity, electromagnetism has emerged as a highly robust theory. Simple and beautiful, this classical theory is based on the deceptively concise formulation of [Maxwell's Equations](https://en.wikipedia.org/wiki/Maxwell%27s_equations) but their consequences are profoundly deep. Exploiting one such consequence, cloaking of objects has been theoretically described and practically demonstrated. My work has been on developing new techniques and implementing novel schemes to improve cloaking. I also extend these methods to different phenomenon like acoustic, thermal and elastic cloaks, and build a unified theory for transformation media techniques in my thesis. 

The novel schemes for cloaking build on nonlinear transformation schemes proposed by Qiu, Steven Johnson et al [paper](https://www.osapublishing.org/oe/abstract.cfm?uri=oe-17-16-13467). The key idea is to make use of asymptotic expansions of Steklov Eigenvalues to evaluate vanishing tensors which enable optimization of inverse geometry. 

### Abstract
We start with an introduction to Cloaking and Metamaterials. Next, we develop Transformation Media Theory which extends ideas of [transformation optics](https://en.wikipedia.org/wiki/Transformation_optics), that gave rise to classical cloaking techniques proposed by Pendry and Kohn, to different areas like acoustics cloaks, elastic cloaks, thermal cloaks and so on. Approximate cloaks based on segmentation are explained for the case of three dimensional spherical cloaks. Prof. Qui and Prof. Steven Johnson’s method of nonlinear transformations is employed for enhanced cloaking performance. Then we introduce the [Dirichlet to Neumann (DtN) map](https://en.wikipedia.org/wiki/Poincar%C3%A9%E2%80%93Steklov_operator) and Steklov eignevalues ([Paper ](https://arxiv.org/abs/0912.5392) explaining relationship). The key tool of Asymptotic expansion for Steklov eigenvlaues is used to propose an alternative  scheme  for  approximate  cloaks. The  higher  efficiency  of  this  novel  idea  is justified theoretically and computationally verified. These treatments give a taste of the usefulness of the theory of operators applied to engineering problems of designing cloaks.

### Maxwell's Equations and Geometric problems
$$
\label{eq:M1} \divvec{(\boldsymbol{\varepsilon}E)} & = & \rho_e\\ 
\label{eq:M2} \divvec{(\boldsymbol{\mu}H)} & = & 0\\ 
\label{eq:M3}  \curlvec{E} & = & - \boldsymbol{\mu}\,\frac{\partial \H}{\partial t} \\ 
\label{eq:M4}   \curlvec{B} & = & \boldsymbol{\varepsilon} \, \timediff{E} + j_e
$$

Maxwell's Equations are linear PDEs.However, they are very nonlinear with respect to geometric settings. This imposes limitations on the proposed invisibility cloaking (Pendry, 2006) with scaling. 

### Theoeretical and Computational Analysis

I have worked on simulation plasmonic microlenses and analyzing the transmission spectra. I plan to tackle invisibility cloaking by homogenization techniques.

### Applications
Suppose we are able to make an elastic cloak, it means that the object being elastically cloaked will not be affected by waves from outside. Acoustic cloaks may be used to protect bridges from (earthquakes) seismec waves. Electromagnetic cloaking for radar invisibility finds many applications in military and defence. Inverse problems arising from cloaking have applications in Biological image reconstruction to treat cardiac diseases. [Electrical impedance tomography](https://en.wikipedia.org/wiki/Electrical_impedance_tomography) which is an equivalent way of thinking of the cloaking problem is another interdisciplinary applications that cloaking has.

