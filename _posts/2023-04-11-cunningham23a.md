---
title: Actually Sparse Variational Gaussian Processes
software: https://github.com/HJakeCunningham/ASVGP
abstract: Gaussian processes (GPs) are typically criticised for their unfavourable
  scaling in both computational and memory requirements. For large datasets, sparse
  GPs reduce these demands by conditioning on a small set of inducing variables designed
  to summarise the data. In practice however, for large datasets requiring many inducing
  variables, such as low-lengthscale spatial data, even sparse GPs can become computationally
  expensive, limited by the number of inducing variables one can use. In this work,
  we propose a new class of inter-domain variational GP, constructed by projecting
  a GP onto a set of compactly supported B-spline basis functions. The key benefit
  of our approach is that the compact support of the B-spline basis functions admits
  the use of sparse linear algebra to significantly speed up matrix operations and
  drastically reduce the memory footprint. This allows us to very efficiently model
  fast-varying spatial phenomena with tens of thousands of inducing variables, where
  previous approaches failed.
section: Regular Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cunningham23a
month: 0
tex_title: Actually Sparse Variational Gaussian Processes
firstpage: 10395
lastpage: 10408
page: 10395-10408
order: 10395
cycles: false
bibtex_author: Cunningham, Harry Jake and de Souza, Daniel Augusto and Takao, So and
  van der Wilk, Mark and Deisenroth, Marc Peter
author:
- given: Harry Jake
  family: Cunningham
- given: Daniel Augusto
  family: Souza
  prefix: de
- given: So
  family: Takao
- given: Mark
  family: Wilk
  prefix: van der
- given: Marc Peter
  family: Deisenroth
date: 2023-04-11
address:
container-title: Proceedings of The 26th International Conference on Artificial Intelligence
  and Statistics
volume: '206'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 4
  - 11
pdf: https://proceedings.mlr.press/v206/cunningham23a/cunningham23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
