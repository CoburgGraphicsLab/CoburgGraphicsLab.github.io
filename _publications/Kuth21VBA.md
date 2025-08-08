---
title: "Vertex-Blend Attribute Compression"
collection: publications
permalink: /publication/Kuth21VBA.html
category: manuscripts
date: 2022-01-01
venue: 'Proceedings of the Conference on High-Performance Graphics'
---
## Authors
Bastian Kuth, Quirin Meyer
## Abstract
Skeleton-based animations require per-vertex attributes called vertex-blend attributes. They consist of a weight tuple and a bone index tuple. With meshes becoming more complex, vertex-blend attributes call for compression. However, no technique exists that exploits their special properties. To this end, we propose a novel and optimal weight compression method called Optimal Simplex Sampling and a novel bone index compression. For our test models, we compress bone index tuples between 2.3:1 and 3.5:1 and weight tuples between 1.6:1 and 2.5:1 while being visually lossless. We show that our representations can speed rendering and reduces GPU memory requirements over uncompressed representations with a similar error. Further, our representations compress well with general-purpose codecs making them suitable for offline-storage and streaming.
## Downloads

[Official Version](https://doi.org/10.2312/hpg.20211282){:target="_blank"}

[Google Scholar](https://scholar.google.com/scholar?q=Vertex+Blend+Attribute+Compression){:target="_blank"}