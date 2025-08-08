---
title: "A Survey of Efficient Representations for Independent Unit Vectors"
collection: publications
permalink: /publication/Cigolle14SER.html
category: manuscripts
date: 2014-04-17
venue: 'Journal of Computer Graphics Techniques (JCGT)'
---
## Authors
Zina Cigolle, Sam Donow, Daniel Evangelakos, Michael Mara, Morgan McGuire, Quirin Meyer
## Abstract
The bandwidth cost and memory footprint of vector buffers are limiting factors for GPU rendering in many applications. This article surveys time- and space-efficient representations for the important case of non-register, in-core, statistically independent unit vectors, with emphasis on GPU encoding and decoding. These representations are appropriate for unit vectors in a geometry buffer or attribute stream--where no correlation between adjacent vectors is easily available--or for those in a normal map where quality higher than that of DXN is required. We do not address out-of-core and register storage vectors because they favor minimum-space and maximum-speed alternatives, respectively. We evaluate precision and its qualitative impact across these techniques and give CPU reference implementations. For those methods with good quality and reasonable performance, we provide optimized GLSL GPU implementations of encoding and decoding.
## Downloads

[Preprint](../files/Cigolle14SER.pdf){:target="_blank"}

[Official Version](http://jcgt.org/published/0003/02/01/){:target="_blank"}

[Google Scholar](https://scholar.google.com/scholar?q=A+Survey+of+Efficient+Representations+for+Independent+Unit+Vectors){:target="_blank"}