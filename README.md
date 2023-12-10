# Dynamic_APSP_AGT-23
## Attempts at Understanding Dynamic APSP Algorithms

* This repository contains a primitive implementation of Demetrescu & Italiano's algorithm for maintaining all pairs' shortest paths for a directed weighted graph with real edge weights.
* The implementation is a randomised version that can be easily made deterministic by Zwick's result.
* The runtime of the algorithm is $\mathrm{O}n^{2.5}\sqrt{S \log^3 n}$ where S is the size of the set of weights each edge could assume.

> The code is in the form of a Jupyter Notebook. Please run all cells in chronological order to get consistent results.
