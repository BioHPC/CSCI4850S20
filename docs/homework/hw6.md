---
layout: page
title: HW#6
subtitle: Homework #6 (20 points)
---

### Due
Thu, Mar 5 2020, 11:59 PM

### Homework #6
Consider the problem of computing in parallel the dot product of two float
vectors x[N] and y[N] using p processes.
Initially the data (the vectors x and y) are at the "master" processor P0.
The computed dot product will be at P0, which will print the result.
Consider all the elements of x and y to be equal to 1.0. The correct value of
the dot product is N.
1. Implement the parallel dot product using only point to point communication routines (send and recv functions).
2. Measure the execution time for N=100, 10000, 1000000 and for p=2,4,8. You can use the function MPI::Wtime() command at the master node (or any good way for it). Be careful when N = 100 and p = 8 (100 is not divided by 8). Comment on how the CPU time scales with problem size N and with the number of processors p.

### Submit
Provide code and analysis document (docx, txt, pdf) to Blackboard.
