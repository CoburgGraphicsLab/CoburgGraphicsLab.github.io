---
title: "Multiresolution Attributes for Hardware Tessellated Objects"
collection: publications
permalink: /publication/Schaefer13MAH.html
category: manuscripts
date: 2013-01-01
venue: 'IEEE Transactions on Visualization and Computer Graphics'
---
## Authors
Henry Schäfer, Magdalena Prus, Quirin Meyer, Jochen Süßmuth, Marc Stamminger
## Abstract
Hardware tessellation is one of the latest GPU features. Triangle or quad meshes are tessellated on-the-fly, where the tessellation level is chosen adaptively in a separate shader. The hardware tessellator only generates topology; attributes such as positions or texture coordinates of the newly generated vertices are determined in a domain shader. Typical applications of hardware tessellation are view dependent tessellation of parametric surfaces and displacement mapping. Often, the attributes for the newly generated vertices are stored in textures, which requires uv unwrapping, chartification, and atlas generation of the input meshâa process that is time consuming and often requires manual intervention. In this paper, we present an alternative representation that directly stores optimized attribute values for typical hardware tessellation patterns and simply assigns these attributes to the generated vertices at render time. Using a multilevel fitting approach, the attribute values are optimized for several resolutions. Thereby, we require no parameterization, save memory by adapting the density of the samples to the content, and avoid discontinuities by construction. Our representation is optimally suited for displacement mapping: it automatically generates seamless, view-dependent displacement mapped models. The multilevel fitting approach generates better low-resolution displacement maps than simple downfiltering. By properly blending levels, we avoid artifacts such as popping or swimming surfaces. We also show other possible applications such as signal-optimized texturing or light baking. Our representation can be evaluated in a pixel shader, resulting in signal adaptive, parameterization-free texturing, comparable to PTex or Mesh Colors. Performance evaluation shows that our representation is on par with standard texture mapping and can be updated in real time, allowing for application such as interactive sculpting.
## Downloads

[Official Version](https://ieeexplore.ieee.org/document/6470610?arnumber=6470610){:target="_blank"}

[Google Scholar](https://scholar.google.com/scholar?q=Multiresolution+Attributes+for+Hardware+Tessellated+Objects){:target="_blank"}