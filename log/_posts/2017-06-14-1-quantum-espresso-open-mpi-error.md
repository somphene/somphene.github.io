---
layout: post
blog-category: blog
title: Quantum Espresso Initialization Open MPI error
author: Som Phene
image: 
tags: [Quantum, Espresso, Resources, Input, Open MPI, Initialization, Error] 
---

Q. When we type source Qunatum Espresso 6.0 openmpi it gives this error:

```
pw.x: error while loading shared libraries: libmpi_f90.so.1: cannot open shared object file: No such file or directory
``` 
Is there something wrong with the binary?

A. I went to the office hours of HPC. There the person checked some commands that had open MPI in it. He just told us to write to the admins that this is the problem. In a few days, he replied back with 

Please initialize your environment with OpenMPI 1.6.4 before Quantum Espresso:

```
source /usr/usc/openmpi/1.6.4/setup.sh
source /usr/usc/qespresso/6.0/setup.sh
```

Q. We got rid of the shared file error after using the comments but now we are getting a segmentation fault:

![Segmentation Fault](https://drive.google.com/file/d/0B2Uc1VPlIxGabktqVlFZbTRIOVdxYXFuWXNPMDZndGJtTnMw/view?usp=sharing)

A. MPI programs are designed to run on multiple computers in a cooperative manner. To have the correct environment, you must run Quantum Espresso on compute node(s) in the cluster allocated by the batch system; otherwise it will not initialize correctly.

```
> Reading input from standard input
>
> %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
> Error in routine read_namelists (1):
> reading namelist control
> %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
>
> stopping ...

 ```
 
This is not an error in MPI. Theinput is malformed. We found the error in the input.
