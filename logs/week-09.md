# Week 9

**Dates:** 08-12 to 08-18

## Goals
This week I ought to begin writing the paper and spend time analyzing program to see if there are modifications that could increase efficiency and reduce the time taken to analyze each barrier candidate.


## Approach and Implementation
Over the course of this week I began to write the introduction to the paper/final report (I was able to copy and paste previous framework descriptions I had created for Prof. Zhang into the implementation and some of the relateed work sections) and was able to identify what had been going wrong in the program with the 3-qubit example which was still slow up until this point. Whenever a barrier certificate was being verified the difficult counterexamples were being discarded at the end of a rejection when it would better serve efficiency to reuse them for future candidates, thus increasing ability of the program to identify issues with a given proposed candidate with more ease rather than relying purely on the SMT.

## Results
The result of this week was that the paper was began and the 3-qubit example was able to be verified more quickly with the new additions to the code, saving the counterexample. In the coming week more tests must be done according to Prof. Zhang's suggestions. This will be added to the paper when complete.

## Notes
-No notes at this time.
