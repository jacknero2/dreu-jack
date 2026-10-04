# Week 7

**Dates:** 07-28 to 08-04

## Goals
-Work on the development of the implementation, including modifications of the original subroutine for the purpsoses of more complicated examples that reduce the complexity of the algorithm and the difficult of the verification
-Continue to work on creating interesting and well-chosen circuits for the algorithm to verify

## Approach and Implementation
This week was rather frustrating in that the initial designs for a more complicated circuit were not able to verified by the program as it currently stood. However, signficant optimizations were made to the LP process that ultimately allowed a 3-qubit syndrome correction algorithm to be verified for a few of the branches (one of the branches has been taking too long and I was unable to recieve its results before the meeting with Prof. Zhang). This consisted primarily in utilizing sparsity, as the preference towards more L1 sparsity allows for a more simple candidate to be proposed to the SMT solver, which struggles with more complicated candidates. The sparse results however have not been enough and next week we need to investigate resolving this bottleneck which I believe must be in the sample generation process.

## Results
The results of this weeks work have primarily been in the speeding up of the subroutines in the program, as the branching seems to be working properly. There are strange discrepancies in the amount of time it takes to solve one of the branches, which is weird because the branch in question is merely the identity branch. I do not know as of now how to solve this and hope to do so in the coming week.

## Notes
-Need to fix the issue with the identity branch

