---
title: "Parallel Dense-Geometry-Format Topology Decompression"
collection: publications
permalink: /publication/Meyer25PDT.html
category: manuscripts
date: 2025-01-01
venue: 'Eurographics 2025 - Short Papers'
---
## Authors
Quirin Meyer, Joshua Barczak, Sander Reitter, Carsten Benthin
## Abstract
Dense Geometry Format (DGF) [BBM24] is a hardware-friendly representation for compressed triangle meshes specifically designed to support GPU hardware ray tracing. It decomposes a mesh into meshlets, i.e., small meshes with up to 64 positions, triangles, primitive indices, and opacity values, in a 128-byte block. However, accessing a triangle requires a slow sequential decompression algorithm with O(T) steps, where T is the number of triangles in a DGF block. We propose a novel parallel algorithm with O(logT) steps for arbitrary T. For DGF, where T ≤ 64, we transform our algorithm to allow O(1) access. We believe that our algorithm is suitable for hardware implementations. With our algorithm, a custom intersection shader outperforms the existing serial decompression method. Further, our mesh shader implementation achieves competitive rasterization performance with the vertex pipeline. Finally, we show how our method may parallelize other topology decompression schemes.
## Downloads

[Official Version](https://diglib.eg.org/items/1ed469e0-1923-46cc-91d6-b137b8aa8f8e){:target="_blank"}

[Google Scholar](https://scholar.google.com/scholar?q=Parallel+Dense+Geometry+Format+Topology+Decompression){:target="_blank"}