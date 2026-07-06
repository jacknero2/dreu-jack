# Week 2

**Dates:** 06-23 to 06-30

## Goals
My primary goal for this week was to understand the current state of the art methodologies for the formal verification of quantum algorithms, and to begin to formulate several possible directions for research to present to Prof. Zhang along with an broad overview of the different methologies associated with them.

## Approach and Implementation
My primary strategy for doing so consisted of reading the initial two papers, and when I came across unfamiliar technical jargon, I visited the references that first defined that terminology. After a couple of levels down the tree of this, I was able to find the most foundational papers for formal verification and a thorough attempt at understanding was made (specifically in quantum Relational Hoare Logic, although the details are not important for this report). Afterwards, I reread the initial papers with greater understanding. I then undertook to read surveys of the field to the present both in formal verification broadly and as it applied to post-quantum cryptography. These papers presented general future work suggestions in their conclusions that helped me spot the holes in the field that could potentially be filled with my summer research project for DREU-QIS. In conjunction with the surveys, I found papers that cited my professor’s initial two papers, and therefore was able to find the most cutting edge research in the topic.

Finally, I compiled the most important high-level perspectives on each of the papers that I considered important, and produced a presentation that demonstrated my understanding of the field to the present and my perspective on the top four best next steps that could be taken this summer. 

## Results

I discussed this information with my professor and he very supportively advised that I choose the problem that I was the most interesting to me out of the four that I suggested (which turned out to be one of the more difficult problems, on the hybridization of formal verification strategies in order to reduce the statespace of quantum algorithms for analysis of key zones). He also suggested that I choose a backup (one of the easier ideas that I presented) in case research in the more difficult topic became unavoidably roadblocked. 

Finishing the discussion, I resolved (at his direction) to create a research proposal over the next several days to send to Prof. Zhang that would outline the specific strategy for improving the field through my hybridization idea. I would also need to examine that vein further to see what progress has specifically been made in that area (although a very survey identified it as a field of continued interest, so I assume that there is plenty of room for growth). 

## Notes

Important ideas formulated:
    1. Separation of Clifford and non-Clifford sections of quantum algorithms
    2. Case study in proofs using various methodologies including EasyPQC for protocol verification
    3. Adaptation of quantum Squirrel methology for quantum oracles
    4. Hybridized approach of models for reduction in computational intensity
