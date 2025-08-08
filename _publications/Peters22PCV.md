---
title: "Permutation Coding for Vertex-Blend Attribute Compression"
collection: publications
permalink: /publication/Peters22PCV.html
category: manuscripts
date: 2022-05-01
venue: 'Proc. ACM Comput. Graph. Interact. Tech.'
---
## Authors
Christoph Peters, Bastian Kuth, Quirin Meyer
## Abstract
Compression of vertex attributes is crucial to keep bandwidth requirements in real-time rendering low. We present a method that encodes any given number of blend attributes for skinning at a fixed bit rate while keeping the worst-case error small. Our method exploits that the blend weights are sorted. With this knowledge, no information is lost when the weights get shuffled. Our permutation coding thus encodes additional data, e.g. about bone indices, into the order of the weights. We also transform the weights linearly to ensure full coverage of the representable domain. Through a thorough error analysis, we arrive at a nearly optimal quantization scheme. Our method is fast enough to decode blend attributes in a vertex shader and also to encode them at runtime, e.g. in a compute shader. Our open source implementation supports up to 13 weights in up to 64 bits.
## Downloads

[Preprint](../files/Peters22PCV.pdf){:target="_blank"}

[Official Version](https://doi.org/10.1145/3522607){:target="_blank"}

[Google Scholar](https://scholar.google.com/scholar?q=Permutation+Coding+for+Vertex+Blend+Attribute+Compression){:target="_blank"}