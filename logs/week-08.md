# Week 8

**Dates:** 08-05 to 08-11

## Goals
-Fix the issue with the identity branch
-Increase the efficiency with optimization techniques perhaps with sampling
-Verify the syndrome example

## Approach and Implementation
This week I was able to resolve the issue with the identity branch via optimizations made to the sampling procedure which involved vectorization to save samples, and utilizing the same samples for each of the branches since they do not require differing examples. This cuts the time taken to sample down significantly, enough to verify that the 3-qubit syndrome example works. However, I would like to increase the speed of this as it seems rather slow compared to some abstract interpretation results in other papers that I have seen.

## Results
In my discussion with Prof. Zhang, we identified that increasing the number of qubits for the example would still be necessary although he agreed with my choice of the initial algorithm with the syndrome error correction. It ought to be improved in efficiency over the next week.



## Notes
-No notes for this week, I think it is all clear above.

