---
title: "Real-Time Geometry Decompression on Graphics Hardware"
collection: publications
permalink: /publication/Meyer12RTG.html
category: books
date: 2012-08-01
---
## Authors
Quirin Meyer
## Abstract
Real-Time Computer Graphics focuses on generating images fast enough to cause the illusion of a continuous motion. It is used in science, engineering, computer games, image processing, and design. Special purpose graphics hardware, a so-called graphics processing unit (GPU), accelerates the image generation process substantially. Therefore, GPUs have become indispensable tools for Real-Time Computer Graphics. The purpose of GPUs is to create two-dimensional (2D) images from threedimensional (3D) geometry. Thereby, 3D geometry resides in GPU memory. However, the ever increasing demand for more realistic images constantly pushes geometry memory consumption. This makes GPU memory a limiting resource in many Real-Time Computer Graphics applications. An effective way of getting more geometry into GPU memory is to compress geometry.In this thesis, we introduce novel algorithms for compressing and decompressing geometry. We propose methods to compress and decompress 3D positions, 3D unit vectors, and topology of triangle meshes. Thereby, we obtain compression ratios from 2:1 to 26:1. We focus on exploiting the high degree of parallelism available on GPUs for decompression. This allows our decompression techniques to run in real-time and impact rendering speed only little. At the same time, our techniques achieve high image quality: images, generated from compressed geometry, are visually indistinguishable from images generated from non-compressed geometry. Moreover, our methods are easy to combine with existing rendering techniques. Thereby, a wide range of applications may benefit from our results.
## Downloads

[Preprint](../files/Meyer12RTG.pdf){:target="_blank"}

[Google Scholar](https://scholar.google.com/scholar?q=Real+Time+Geometry+Decompression+on+Graphics+Hardware){:target="_blank"}