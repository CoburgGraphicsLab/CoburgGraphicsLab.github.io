---
title: "Edge-Friend: Fast and Deterministic Catmull-Clark Subdivision Surfaces"
collection: publications
permalink: /publication/Kuth23EFD.html
category: manuscripts
date: 2023-01-01
venue: 'Computer Graphics Forum'
---
## Authors
Bastian Kuth, Max Oberberger, Matthäus Chajdas, Quirin Meyer
## Abstract
We present edge-friend, a data structure for quad meshes with access to neighborhood information required for Catmull-Clark subdivision surface refinement. Edge-friend enables efficient real-time subdivision surface rendering. In particular, the resulting algorithm is deterministic, does not require hardware support for atomic floating-point arithmetic, and is optimized for efficient rendering on GPUs. Edge-friend exploits that after one subdivision step, two edges can be uniquely and implicitly assigned to each quad. Additionally, edge-friend is a compact data structure, adding little overhead. Our algorithm is simple to implement in a single compute shader kernel, and requires minimal synchronization which makes it particularly suited for asynchronous execution. We easily extend our kernel to support relevant Catmull-Clark subdivision surface features, including semi-smooth creases, boundaries, animation and attribute interpolation. In case of topology changes, our data structure requires little preprocessing, making it amendable for a variety of applications, including real-time editing and animations. Our method can process and render billions of triangles per second on modern GPUs. For a sample mesh, our algorithm generates and renders 2.9 million triangles in 0.58ms on an AMD Radeon RX 7900 XTX GPU.
## Downloads

[Official Version](https://diglib.eg.org/items/5582004e-fda7-4861-a980-4de5634015db){:target="_blank"}

[Google Scholar](https://scholar.google.com/scholar?q=Edge+Friend:+Fast+and+Deterministic+Catmull+Clark+Subdivision+Surfaces){:target="_blank"}