---
layout: post
blog-category: blog
title: Intro to Machine Learning (ML) Lecture 2
author: Som Phene
image: 
tags: [I, M, L, Introduction, 02, Linear, Regression, Machine, Learning]
---

### Linear Regression

* Find the Machine Learning $$2^{nd}$$ Lecture notes linked [Lecture Notes 2](https://drive.google.com/file/d/1ce2XilD2CnruB9klBBIDU9gAjjS-UF1A/view?usp=sharing)

In Introduction to Machine Learning ([course webpage](https://www.cse.iitb.ac.in/~pjyothi/cs419/index.html)) second class, Prof. [Jyothi](https://www.cse.iitb.ac.in/~pjyothi/) started with Linear model for regression. Treatment of error as random variable, model via stochastic processes. I asked if the error is classified into deterministic (device based, on which we have control) and random before modeling and she said that generally its not, however if a good mathematical model for the deterministic error is known then it can be incorporated. How do we quantify that our regression model or fitting to data os good or bad? For that purpose, Evaluation function was defined, absolute error and least squares error were introduced, their advantages and disadvantages were discussed. In absolute value, Mathematical properties (differentibalility) are lost but in least sqaure, it magnifies error. Analytic closed form optimal solution for the least square error was calculated and shown to be the orthogonal projection onto the subspace spanned by the parameters. This was the geometric interpretation to the least squares optimal solution. The prefactor in the expression is also called the $$\bf{Moore-Penrose Pseudo Inverse}$$. We also touched on curve fitting by using generic basis. One example of basis in which there was seemingly "no pattern" to generate the $${n+1}^{th}$$ basis from the previous was shown. A student asked about it and the Prof. said that its an open problem to find certain suitable basis. There was no discussion of fourier theory or other analysis of convergnce as everything was finite dimensional (as in the advanced image processing or wavelets class). When I asked what about infinite dimensions, she said that this would naturally lead to kernel based methods. Completeness and linear independence of basis was not at all discussed. 

### Workshop
Note that tomorrow there will be : Workshop on Machine Intelligence and Data Science on Saturday, January 18th, 2020 (IITB MInDS
workshop) in B. Nag Auditorium, VMCC. This is mainly for post graduate students and researchers. This is part of the Institute’s efforts to intensify activities in this area including setting up a centre for Machine Intelligence and Data Science at IIT Bombay. Here's the schedule:
09:00 AM – 10:0 AM  (Session 1)
* Talk on Vision / video analytics by Prof. Ganesh Ramakrishnan, CSE
* Talk on Image processing and analytics by Prof. Amit Sethi, EE
* Talk on Satellite image processing, Prof. Biplab Banerjee, CSRE
* Talk on Speech, Prof. Preethi Jyothi, CSE

10:00 AM – 10:30 AM
Keynote address by Mr. Mayur Datar, Chief Data Scientist & VP of
Engineering, Flipkart

10:30 AM – 11:00 AM
Tea break

11:00 AM – 12:00 PM  (Session 2)
* Talk on Natural language by Prof. Pushpak Bhattacharyya, CSE
* Talk on ML / DL / RL foundations by Prof. Sunita Sarawagi, CSE
* Talk on Social networking (Speaker to be confirmed)
* Talk on Math / statistical foundations by Prof. Radhendushka
Srivastava, Maths

12:00 PM – 12:30 PM
* Talk on Autonomous underwater vehicle (Student speaker to be confirmed)
* Talk on Self-driving cars, Sedrica (Student speaker to be confirmed)

12:30 PM – 02:00 PM
Poster session & Lunch (First floor foyer, VMCC)

02:00 PM – 02:45 PM  (Session 3)
* Talk on Logistics / Supply chain / IE by Prof. Jayendran
Venkateswaran, IEOR
* Talk on Decision making 1 by Prof. Ankur Kulkarni, SysCon
* Talk on Decision making 2 by Prof. Jayakrishnan Nair, EE

02:45 PM – 03:30 PM  (Panel discussion)
Moderator: Prof. Sunita Sarawagi, CSE, IITB
- Mr. Mayur Datar, Chief Data Scientist, Flipkart
- Mr. Anand Sivasubramanian, Consulting Advisor, TCS
- Mr. Abhishek Shekhar, Executive Director, J P Morgan
- Mr. Varun Aggarwal, Co-founder, Aspiring Minds

03:30 PM – 04:00 PM
Tea break

04:00 PM – 05:15 PM (Session 4)
* Talk on AI in management by Prof. Rajendra M. Sonar, SOM
* Talk on Power systems control / IoT by Prof. Anupama Kowli, EE
* Talk on Manufacturing by Prof. Asim Tewari, ME
* Talk on Proteomics / genomics by Prof. Sanjeeva Srivastava, BSBE
* Talk on Chem. Engg. overview by Prof. Ravindra Gudi, ChE
