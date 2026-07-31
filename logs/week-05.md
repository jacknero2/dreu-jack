# Week 5

**Dates:** 07-13 to 07-20

## Goals
The goal of this week was to refine my description of a quantum system in order to handle gate errors as well as refine the process of certifying quantum-classical systems with barrier certificates such that it could be used to certify an algorithm. Additionally, a goal was to actually certify a very basic 2-qubit example to give a proof of concept for my process.


## Approach and Implementation
Over the course of this week, I focused my framework into a clearly defined tuple which describes a classical-quantum statespace in which multiple Hamiltonians could be used depending on different conditional tracts. This was done by defining a set of timestep functions that map to families of gates related to the intended unitary gate at a given timestamp and tract (based on a previous classical decision). This is a novel formulation of quantum-classical dynamical systems and mirrors with a bit of adaptation the original paper in 2003. The result of this reformulation was that it allowed me to refine the definition of a barrier certificate of a hybrid algorithm since I now had a well formed vocabulary to describe those algorithms. This definition was fairly naive and immediate and allowed me to generate a basic example based on maintaining a quantum register at a specific state despite decoherence and interference effects caused by the ambient environment.


## Results
The result of my reformulation of both the description of systems and the general barrier certificate allowed me to generate an example off a 2-qubit algorithm that my barrier certificate method clearly certified as safe. This was presented in a meeting with Prof. Zhang and he agreed that my formulation made sense. His guidance was to continue in my analysis, extending a certification to a more complicated example with more differences between computational tracts to see if my method extends beyond simple examples (which I believe that it does).



## Notes
-I will need to provide a meaningful bound on the complexity of my approach given that the statespace could very well become exponential (how exponential and which use cases it could reasonably be applied to using automated methods remains to be seen)

