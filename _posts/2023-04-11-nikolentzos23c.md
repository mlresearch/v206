---
title: Geometric Random Walk Graph Neural Networks via Implicit Layers
software: https://github.com/giannisnik/grwnn
abstract: Graph neural networks have recently attracted a lot of attention and have
  been applied with great success to several important graph problems. The Random
  Walk Graph Neural Network model was recently proposed as a more intuitive alternative
  to the well-studied family of message passing neural networks. This model compares
  each input graph against a set of latent “hidden graphs” using a kernel that counts
  common random walks up to some length. In this paper, we propose a new architecture,
  called Geometric Random Walk Graph Neural Network (GRWNN), that generalizes the
  above model such that it can count common walks of infinite length in two graphs.
  The proposed model retains the transparency of Random Walk Graph Neural Networks
  since its first layer also consists of a number of trainable “hidden graphs” which
  are compared against the input graphs using the geometric random walk kernel. To
  compute the kernel, we employ a fixed-point iteration approach involving implicitly
  defined operations. Then, we capitalize on implicit differentiation to derive an
  efficient training scheme which requires only constant memory, regardless of the
  number of fixed-point iterations. Experiments on graph classification datasets demonstrate
  the effectiveness of the proposed approach in comparison with state-of-the-art methods.
section: Regular Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nikolentzos23c
month: 0
tex_title: Geometric Random Walk Graph Neural Networks via Implicit Layers
firstpage: 2035
lastpage: 2053
page: 2035-2053
order: 2035
cycles: false
bibtex_author: Nikolentzos, Giannis and Vazirgiannis, Michalis
author:
- given: Giannis
  family: Nikolentzos
- given: Michalis
  family: Vazirgiannis
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
pdf: https://proceedings.mlr.press/v206/nikolentzos23c/nikolentzos23c.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
