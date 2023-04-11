---
title: Adaptive Tuning for Metropolis Adjusted Langevin Trajectories
software: https://github.com/tensorflow/probability/tree/main/discussion/adaptive_malt
abstract: Hamiltonian Monte Carlo (HMC) is a widely used sampler for continuous probability
  distributions. In many cases, the underlying Hamiltonian dynamics exhibit a phenomenon
  of resonance which decreases the efficiency of the algorithm and makes it very sensitive
  to hyperparameter values. This issue can be tackled efficiently, either via the
  use of trajectory length randomization (RHMC) or via partial momentum refreshment.
  The second approach is connected to the kinetic Langevin diffusion, and has been
  mostly investigated through the use of Generalized HMC (GHMC). However, GHMC induces
  momentum flips upon rejections causing the sampler to backtrack and waste computational
  resources. In this work we focus on a recent algorithm bypassing this issue, named
  Metropolis Adjusted Langevin Trajectories (MALT). We build upon recent strategies
  for tuning the hyperparameters of RHMC which target a bound on the Effective Sample
  Size (ESS) and adapt it to MALT, thereby enabling the first user-friendly deployment
  of this algorithm. We construct a method to optimize a sharper bound on the ESS
  and reduce the estimator variance. Easily compatible with parallel implementation,
  the resultant Adaptive MALT algorithm is competitive in terms of ESS rate and hits
  useful tradeoffs in memory usage when compared to GHMC, RHMC and NUTS.
section: Regular Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: riou-durand23a
month: 0
tex_title: Adaptive Tuning for Metropolis Adjusted Langevin Trajectories
firstpage: 8102
lastpage: 8116
page: 8102-8116
order: 8102
cycles: false
bibtex_author: Riou-Durand, Lionel and Sountsov, Pavel and Vogrinc, Jure and Margossian,
  Charles and Power, Sam
author:
- given: Lionel
  family: Riou-Durand
- given: Pavel
  family: Sountsov
- given: Jure
  family: Vogrinc
- given: Charles
  family: Margossian
- given: Sam
  family: Power
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
pdf: https://proceedings.mlr.press/v206/riou-durand23a/riou-durand23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
