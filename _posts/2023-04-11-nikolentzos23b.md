---
title: Graph Alignment Kernels using Weisfeiler and Leman Hierarchies
software: https://github.com/giannisnik/gawl
abstract: Graph kernels have become a standard approach for tackling the graph similarity
  and learning tasks at the same time. Most graph kernels proposed so far are instances
  of the R-convolution framework. These kernels decompose graphs into their substructures
  and sum over all pairs of these substructures. However, considerably less attention
  has been paid to other types of kernels. In this paper, we propose a new kernel
  between graphs which reorders the adjacency matrix of each graph based on soft permutation
  matrices, and then compares those aligned adjacency matrices to each other using
  a linear kernel. To compute the permutation matrices, the kernel finds corresponding
  vertices in different graphs. Two vertices match with each other if the Weisfeiler-Leman
  test of isomorphism assigns the same label to both of them. The proposed kernel
  is evaluated on several graph classification and graph regression datasets. Our
  results indicate that the kernel is competitive with traditional and state-of-the-art
  methods.
section: Regular Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nikolentzos23b
month: 0
tex_title: Graph Alignment Kernels using Weisfeiler and Leman Hierarchies
firstpage: 2019
lastpage: 2034
page: 2019-2034
order: 2019
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
pdf: https://proceedings.mlr.press/v206/nikolentzos23b/nikolentzos23b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
