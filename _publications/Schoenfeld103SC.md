---
title: "3-SAT on CUDA: Towards a Massively Parallel SAT Solver"
collection: publications
permalink: /publication/Schoenfeld103SC.html
category: manuscripts
date: 2010-01-01
venue: '2010 International Conference on High Performance Computing &amp; Simulation'
---
## Authors
Quirin Meyer, Fabian Schönfeld, Marc Stamminger, Rolf Wanka
## Abstract
This work presents the design and implementation of a massively parallel 3-SAT solver, specifically targeting random problem instances. Our approach is deterministic and features very little communication overhead and basically no load-balancing cost at all. In the context of most current parallel SAT solvers running only on a handful of cores, we implemented our solver on Nvidia's CUDA platform, utilizing more than 200 parallel streaming processors, and employing several millions of threads to work through single problem instances. As most common sequential solver techniques had to be discarded, our approach is additionally supported by a new set of global heuristics, designed specifically to be easily exploited by the underlying thread parallelism.
## Downloads

[Preprint](../files/Schoenfeld103SC.pdf){:target="_blank"}

[Official Version](https://ieeexplore.ieee.org/document/5547116){:target="_blank"}

[Google Scholar](https://scholar.google.com/scholar?q=3+SAT+on+CUDA:+Towards+a+Massively+Parallel+SAT+Solver){:target="_blank"}