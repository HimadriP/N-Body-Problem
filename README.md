# N-Body-Problem
Parallelizing the Barnes Hut and the All-pairs Algorithm for the N-Body Problem.
More info on N-Body Problem, Refer : https://en.wikipedia.org/wiki/N-body_problem

## All pairs Algorithm (Naive Approach)
The Algorithm has been implemented on OpenMP and CUDA and the graphs were plotted for both the architectures.

## Barnes Hut Algorithm (Quad Tree Based)
Two separate versions of the algorithm (parallelizing two separate secctions) has been implemented on OpenMP.
The First one parallelizes the `ComputeMassDistribution` function and the second one parallelizes the `ComputeForce` function.
Results are depicted in the graphs which were plotted.

## Input
Input used is the galatic datasets of princeton.edu.
