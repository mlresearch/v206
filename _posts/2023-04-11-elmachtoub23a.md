---
title: Balanced Off-Policy Evaluation for Personalized Pricing
software: https://github.com/yzhao3685/pricing-evaluation
abstract: We consider a personalized pricing problem in which we have data consisting
  of feature information, historical pricing decisions, and binary realized demand.
  The goal is to perform off-policy evaluation for a new personalized pricing policy
  that maps features to prices. Methods based on inverse propensity weighting (including
  doubly robust methods) for off-policy evaluation may perform poorly when the logging
  policy has little exploration or is deterministic, which is common in pricing applications.
  Building on the balanced policy evaluation framework of Kallus (2018), we propose
  a new approach tailored to pricing applications. The key idea is to compute an estimate
  that minimizes the worst-case mean squared error or maximizes a worst-case lower
  bound on policy performance, where in both cases the worst-case is taken with respect
  to a set of possible revenue functions. We establish theoretical convergence guarantees
  and empirically demonstrate the advantage of our approach using a real-world pricing
  dataset.
section: Regular Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: elmachtoub23a
month: 0
tex_title: Balanced Off-Policy Evaluation for Personalized Pricing
firstpage: 10901
lastpage: 10917
page: 10901-10917
order: 10901
cycles: false
bibtex_author: Elmachtoub, Adam and Gupta, Vishal and Zhao, Yunfan
author:
- given: Adam
  family: Elmachtoub
- given: Vishal
  family: Gupta
- given: Yunfan
  family: Zhao
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
pdf: https://proceedings.mlr.press/v206/elmachtoub23a/elmachtoub23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
