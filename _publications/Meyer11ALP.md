---
title: "Adaptive Level-of-Precision for GPU-Rendering"
collection: publications
permalink: /publication/Meyer11ALP.html
category: manuscripts
date: 2011-01-01
venue: 'Vision, Modeling, and Visualization (2011)'
---
## Authors
Quirin Meyer, Gerd Sussner, Günther Greiner, Marc Stamminger
## Abstract
Video memory is a valuable resource that has grown much slower than the rendering power of GPUs over the last years. Today, video memory is often the limiting factor in interactive high-quality rendering applications. The most often used solution to reduce memory consumption is to apply level-of-detail (LOD) methods: only a simplified version of the mesh with less vertices and triangles is kept in memory. In this paper we examine a simple orthogonal compression approach that is mostly neglected: adapting the level-of-precision (LOP) of vertex data. The main idea is to quantize vertex positions according to the current view distance, and adapt precision by adding or removing single bit planes. We provide an analysis of the resulting image error, and show that visual artifacts can be avoided by simply constraining the quantization for critical vertices. Our approach allows both random access on vertex data as well as quickly switching between LOP. In experiments we found that our approach compresses vertex positions by about 70percent on average without loss in rendering performance or image quality.
## Downloads

[Preprint](../files/Meyer11ALP.pdf){:target="_blank"}

[Official Version](https://diglib.eg.org/items/fa6a6143-ea8f-4dd4-8eae-d40b3e216ad4){:target="_blank"}

[Google Scholar](https://scholar.google.com/scholar?q=Adaptive+Level+of+Precision+for+GPU+Rendering){:target="_blank"}