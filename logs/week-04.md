# Week 4

**Dates:** 07-06 to 07-13

## Goals
The goal of this week were to develop a 2-qubit algorithm that could be verified utilizing the hybrid barrier certificate framework that I had developed in the previous week. Additionally, I had the desire to understand how quantum gate errors might emerge and try to find the best way of describing this issue mathematically, as my framework at that point did not account for this.


## Approach and Implementation
Over the course of this week I attempted to create apply the framework that I had developed, but quickly was confronted by the issues regarding error accomodation. It is a well known behaviour that in any quantum circuit, there are going to be real world errors in which the application of a certain quantum gate is unsuccessful in its intended behaviour (for example a rotation in the Bloch sphere may be off by a marginal angle due to the slightly improper timing of a lazer or x-ray used for the rotation). Thus any mathematical formulation must take into account that, although ideal gates could be represented as single-valued functions of a state at a given time stamp, a family of related gates would best serve as a set-valued function of a state at a given time stamp. Another aspect that became unclear to me was how to represent the conditional decisions based on measurements, ideally without having to account for the propositional logic utilized in these decisions. Moreover, it was at first unclear to me which algorithms could be taken as well chosen examples for application, as complicated examples may not lend themselves to useful discussion, but are more applicable to real world scenarios. 

## Results
Despite my best intentions, my deep dive into the assumptions behind the 3 or so major frameworks that already existed (including the original paper on hybrid algorithms for discrete and continuous systems - not quantum algorithms, this is a bit of an unfortunate similar naming) combined with my confusion on which algorithm to choose to apply my somewhat disheveled certification framework to, and a fear that the statespace of my certification framework of a complicated quantum algorithm would be too complicated for automated methods (such as the sum of squares method) caused me to present my concerns to my mentor instead of the successful application to a 2-qubit algorithm as planned. Prof. Zhang, after listening to my presentation on our Thursday meeting, concluded that while my concerns might prove to be valid for real world applications, the theoretical framework (in the worst case scenario) would still have merit, and it was necessary to apply it to even an arbitrary algorithm to judge whether it would even work in the simplest case. He advised me to continue developing the 2-qubit algorithm analysis and I resolved to complete this task and continue to refine the mathematical understanding of the proper framework.

## Notes
-Focused on understanding the necessary behaviour to be described
-Need to continue to develop the framework in order to apply it to a 2-qubit system.
-Was recommended a couple of quantum computing books in order to find useful algorithms by Prof. Zhang

