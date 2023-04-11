---
title: Federated Learning under Distributed Concept Drift
software: 'URL: https://github.com/microsoft/FedDrift'
abstract: Federated Learning (FL) under distributed concept drift is a largely unexplored
  area. Although concept drift is itself a well-studied phenomenon, it poses particular
  challenges for FL, because drifts arise staggered in time and space (across clients).
  Our work is the first to explicitly study data heterogeneity in both dimensions.
  We first demonstrate that prior solutions to drift adaptation, with their single
  global model, are ill-suited to staggered drifts, necessitating multiple-model solutions.
  We identify the problem of drift adaptation as a time-varying clustering problem,
  and we propose two new clustering algorithms for reacting to drifts based on local
  drift detection and hierarchical clustering. Empirical evaluation shows that our
  solutions achieve significantly higher accuracy than existing baselines, and are
  comparable to an idealized algorithm with oracle knowledge of the ground-truth clustering
  of clients to concepts at each time step.
section: Notable Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: jothimurugesan23a
month: 0
tex_title: Federated Learning under Distributed Concept Drift
firstpage: 5834
lastpage: 5853
page: 5834-5853
order: 5834
cycles: false
bibtex_author: Jothimurugesan, Ellango and Hsieh, Kevin and Wang, Jianyu and Joshi,
  Gauri and Gibbons, Phillip B.
author:
- given: Ellango
  family: Jothimurugesan
- given: Kevin
  family: Hsieh
- given: Jianyu
  family: Wang
- given: Gauri
  family: Joshi
- given: Phillip B.
  family: Gibbons
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
pdf: https://proceedings.mlr.press/v206/jothimurugesan23a/jothimurugesan23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
