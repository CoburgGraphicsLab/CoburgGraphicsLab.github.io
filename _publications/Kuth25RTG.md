---
title: "Real-Time GPU Tree Generation"
collection: publications
permalink: /publication/Kuth25RTG.html
category: manuscripts
date: 2025-01-01
venue: 'High-Performance Graphics - Symposium Papers'
---
## Authors
Bastian Kuth, Max Oberberger, Carsten Faber, Pirmin Pfeifer, Seyedmasih Tabaei, Dominik Baumeister, Quirin Meyer
## Abstract
Trees for real-time media are typically created using procedural algorithms and then baked to a polygon format, requiring large amounts of memory. We propose a novel procedural system and model for generating and rendering realistic trees and similar vegetation specifically tailored to run in real-time on GPUs. By using GPU work graphs with mesh nodes, we render gigabytes-worth of tree geometry from kilobytes of generation code every frame exclusively on the GPU. Contrary to prior work, our method combines instant in-engine artist authoring, continuous frame-specific level of detail and tessellation, highly detailed animation, and seasonal details like blossoms, fruits, and snow. Generating the unique tree geometries of our teaser test scene and rendering them to the G-buffer takes 3.13 ms on an AMD Radeon RX 7900 XTX.
## Downloads

[Preprint](../files/Kuth25RTG.pdf){:target="_blank"}

[Google Scholar](https://scholar.google.com/scholar?q=Real+Time+GPU+Tree+Generation){:target="_blank"}