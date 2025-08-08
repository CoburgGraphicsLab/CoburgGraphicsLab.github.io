---
title: "Data-Parallel Decompression of Triangle Mesh Topology"
collection: publications
permalink: /publication/Meyer12DPD.html
category: manuscripts
date: 2012-01-01
venue: 'Computer Graphics Forum'
---
## Authors
Quirin Meyer, Benjamin Keinert, Gerd Sußner, Marc Stamminger
## Abstract
Abstract We propose a lossless, single-rate triangle mesh topology codec tailored for fast data-parallel GPU decompression. Our compression scheme coherently orders generalized triangle strips in memory. To unpack generalized triangle strips efficiently, we propose a novel parallel and scalable algorithm. We order vertices coherently to further improve our compression scheme. We use a variable bit-length code for additional compression benefits, for which we propose a scalable data-parallel decompression algorithm. For a set of standard benchmark models, we obtain (min: 3.7, med: 4.6, max: 7.6) bits per triangle. Our CUDA decompression requires only about 15\% of the time it takes to render the model even with a simple shader.
## Downloads

[Preprint](../files/Meyer12DPD.pdf){:target="_blank"}

[Official Version](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-8659.2012.03221.x){:target="_blank"}

[Google Scholar](https://scholar.google.com/scholar?q=Data+Parallel+Decompression+of+Triangle+Mesh+Topology){:target="_blank"}