# The Matrix Code Equivalence Problem
This repository contains implementations of algorithms for solving the Matrix Code Equivalence problem (MCE).

These algorithms are a result of joint work with [Krijn Reijnders](https://krijnreijnders.com/) and [Simona Samardjiska](https://samardjiska.org/). See our paper: [Hardness estimates of the Code Equivalence Problem in the Rank Metric](https://eprint.iacr.org/2022/276)

The files taken from the open source implementation of the paper-- have ```BFV13``` at the beginning of the name. They are slightly modified to make them work with $q > 2$ and with $N \ne k$.

The files ```QMLE_modelisation_main.magma``` and ```QMLE_modelisation_main.magma``` can be used to test the Groebner attack. The parameters can be set on the first 10 lines. It is possible to choose whether we generate random or collision-derived instances. It is also possible to specify the rank of the matrix representing the linear part of the system.

The file ```MCE_QMLE_main.magma``` is the main program for Algorithm 1. The parameters can be set on the first 5 lines.

Algorithm 2 with the non-zeros can be executed using ```MCE_solve_nonzeros.magma```. The parameters can be set on the first 5 lines.
