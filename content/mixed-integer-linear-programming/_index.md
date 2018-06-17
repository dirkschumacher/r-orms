---
date: 2018-04-28T14:26:06+02:00
title: Mixed-integer programming
weight: 5
---

Combinatorial optimization problems can be found in many places: finding the optimal seating plan for you and your coworkers, designing a conference schedule or setting up facilities in an emergency situation. 

Many of these real world optimization problems can be naturally formulated as a special class of problems, called a [mixed-integer linear program (MILP)](https://en.wikipedia.org/wiki/Integer_programming). As the name suggests, the aim is to optimize a linear objective function, subject to a set of linear inequalities with some of the variables being integer valued. Once able to formulate the problem as a MILP, you can use specialized open-source and commercial solvers that have been developed over the past decades to efficiently solve it to optimality.

This sections aims to give you an overview about MILPs, how to model and solve them in R. (Real) world examples can be found in the [practicals](practicals) section.

Also, always take a look at the [CRAN Optimization Task View](https://cran.r-project.org/web/views/Optimization.html), it lists essentially all packages available for combinatorial optimzation (including MILPs). 