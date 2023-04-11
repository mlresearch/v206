---
title: 'NODAGS-Flow: Nonlinear Cyclic Causal Structure Learning'
software: https://github.com/Genentech/nodags-flows
abstract: Learning causal relationships between variables is a well-studied problem
  in statistics, with many important applications in science. However, modeling real-world
  systems remain challenging, as most existing algorithms assume that the underlying
  causal graph is acyclic. While this is a convenient framework for developing theoretical
  developments about causal reasoning and inference, the underlying modeling assumption
  is likely to be violated in real systems, because feedback loops are common (e.g.,
  in biological systems). Although a few methods search for cyclic causal models,
  they usually rely on some form of linearity, which is also limiting, or lack a clear
  underlying probabilistic model. In this work, we propose a novel framework for learning
  nonlinear cyclic causal graphical models from interventional data, called NODAGS-Flow.
  We perform inference via direct likelihood optimization, employing techniques from
  residual normalizing flows for likelihood estimation. Through synthetic experiments
  and an application to single-cell high-content perturbation screening data, we show
  significant performance improvements with our approach compared to state-of-the-art
  methods with respect to structure recovery and predictive performance.
section: Regular Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sethuraman23a
month: 0
tex_title: 'NODAGS-Flow: Nonlinear Cyclic Causal Structure Learning'
firstpage: 6371
lastpage: 6387
page: 6371-6387
order: 6371
cycles: false
bibtex_author: Sethuraman, Muralikrishnna G and Lopez, Romain and Mohan, Rahul and
  Fekri, Faramarz and Biancalani, Tommaso and Huetter, Jan-Christian
author:
- given: Muralikrishnna G
  family: Sethuraman
- given: Romain
  family: Lopez
- given: Rahul
  family: Mohan
- given: Faramarz
  family: Fekri
- given: Tommaso
  family: Biancalani
- given: Jan-Christian
  family: Huetter
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
pdf: https://proceedings.mlr.press/v206/sethuraman23a/sethuraman23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
