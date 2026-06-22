---
title: "3-SAT on CUDA: Towards a Massively Parallel SAT Solver"
collection: publications
category: manuscripts
permalink: /publication/Schoenfeld103SC
date: 2010-06-28
venue: '2010 International Conference on High Performance Computing &amp; Simulation'
---

## Abstract

This work presents the design and implementation of a massively parallel 3-SAT solver, specifically targeting random problem instances. Our approach is deterministic and features very little communication overhead and basically no load-balancing cost at all. In the context of most current parallel SAT solvers running only on a handful of cores, we implemented our solver on Nvidia&apos;s CUDA platform, utilizing more than 200 parallel streaming processors, and employing several millions of threads to work through single problem instances. As most common sequential solver techniques had to be discarded, our approach is additionally supported by a new set of global heuristics, designed specifically to be easily exploited by the underlying thread parallelism.

## Recommended Citation
Meyer, Quirin; Schönfeld, Fabian; Stamminger, Marc; Wanka, Rolf. (2010). 3-SAT on CUDA: Towards a Massively Parallel SAT Solver, <i>2010 International Conference on High Performance Computing & Simulation</i>
## Downloads


<a href='../files/Schoenfeld103SC.pdf'>Download paper here</a>
