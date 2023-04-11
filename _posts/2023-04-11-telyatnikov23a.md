---
title: 'EGG-GAE: scalable graph neural networks for tabular data imputation'
software: https://github.com/levtelyatnikov/EGG_GAE
abstract: Missing data imputation (MDI) is crucial when dealing with tabular datasets
  across various domains. Autoencoders can be trained to reconstruct missing values,
  and graph autoencoders (GAE) can additionally consider similar patterns in the dataset
  when imputing new values for a given instance. However, previously proposed GAEs
  suffer from scalability issues, requiring the user to define a similarity metric
  among patterns to build the graph connectivity beforehand. In this paper, we leverage
  recent progress in latent graph learning to propose a novel EdGe Generation Graph
  AutoEncoder (EGG-GAE) for missing data imputation that overcomes these two drawbacks.
  EGG-GAE works on randomly sampled mini-batches of the input data (hence scaling
  to larger datasets), and it automatically infers the best connectivity across the
  mini-batch for each architecture layer. We also experiment with several extensions,
  including an ensemble strategy for inference and the inclusion of what we call prototype
  nodes, obtaining significant improvements, both in terms of imputation error and
  final downstream accuracy, across multiple benchmarks and baselines.
section: Regular Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: telyatnikov23a
month: 0
tex_title: 'EGG-GAE: scalable graph neural networks for tabular data imputation'
firstpage: 2661
lastpage: 2676
page: 2661-2676
order: 2661
cycles: false
bibtex_author: Telyatnikov, Lev and Scardapane, Simone
author:
- given: Lev
  family: Telyatnikov
- given: Simone
  family: Scardapane
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
pdf: https://proceedings.mlr.press/v206/telyatnikov23a/telyatnikov23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
