---
title: "Real-Time Procedural Generation with GPU Work Graphs"
collection: publications
permalink: /publication/Kuth24RPG.html
category: manuscripts
date: 2024-08-01
venue: 'Proc. ACM Comput. Graph. Interact. Tech.'
---
## Authors
Bastian Kuth, Max Oberberger, Carsten Faber, Dominik Baumeister, Matthäus Chajdas, Quirin Meyer
## Abstract
We present a system for real-time procedural generation that makes use of the novel GPU programming model, work graphs. The nodes of a work graph are shaders, which dynamically generate new workloads for connected nodes. This greatly simplifies the implementation of recursive procedural algorithms on GPUs. Combined with GPU ray tracing and procedural mesh shaders, our system makes use of this graph structure to tackle various common problems of procedural generation. Our system is very easy to implement, requiring no additional data structures from what would already be available in a modern rendering engine. We demonstrate the real-time editing capabilities on representative examples. We augment the scene in the teaser image with 79,710 instances in 3.74 ms on an AMD Radeon RX 7900 XTX.
## Downloads

[Preprint](../files/Kuth24RPG.pdf){:target="_blank"}

[Official Version](https://doi.org/10.1145/3675376){:target="_blank"}

[Google Scholar](https://scholar.google.com/scholar?q=Real+Time+Procedural+Generation+with+GPU+Work+Graphs){:target="_blank"}