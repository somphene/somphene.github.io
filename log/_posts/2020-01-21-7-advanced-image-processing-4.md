---
layout: post
blog-category: blog
title: Advanced Image Processing Lecture 4
author: Som Phene
bigimg: log/images/jakob-owens-l82NzBSYbj0-unsplash.jpg
tags: [Signals, Reconstruction, Inverse, Bounds, Image Processing, CS 754, Ajit Rajwade]
---
### Bounds on Sparse signal reconstruction

* Find the $$4^{th}$$ lecture notes linked: [CS 754 Lecture Notes 4](https://drive.google.com/file/d/1EZZqK8UaIdwmtNlhMlkiEYoHSDZhAWLc/view?usp=sharing)
* Stated theorem giving bounds on the reconstruction of image. 
* Intuition behind $$L^1$$ being better norm than $$L^p$$ for optimal solution. Starting with near zero $$L^1$$ norm, draw balls of increasing norm and see that the optimal solution is sparse (min is single point on the axis where the contraint equation line becomes tangent to the $$L^1$$ norm ball). Whereas in the case of $$L^2$$ norm, the optimal point is off the axis and hence not sparse. Saumya asked whether this means the optimal solution is non-zero only along one axis.
* Cameras: Standard scans 2D array and Rice Single Pixel (for compressive sensing) stores the dot product (single value) directly instead of the whole array.
