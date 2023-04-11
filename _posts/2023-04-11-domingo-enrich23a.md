---
title: 'Compress Then Test: Powerful Kernel Testing in Near-linear Time'
software: github.com/microsoft/goodpoints
abstract: Kernel two-sample testing provides a powerful framework for distinguishing
  any pair of distributions based on n sample points. However, existing kernel tests
  either run in $n^2$ time or sacrifice undue power to improve runtime. To address
  these shortcomings, we introduce Compress Then Test (CTT), a new framework for high-powered
  kernel testing based on sample compression. CTT cheaply approximates an expensive
  test by compressing each n point sample into a small but provably high-fidelity
  coreset. For standard kernels and subexponential distributions, CTT inherits the
  statistical behavior of a quadratic-time test—recovering the same optimal detection
  boundary—while running in near-linear time. We couple these advances with cheaper
  permutation testing, justified by new power analyses; improved time-vs.-quality
  guarantees for low-rank approximation; and a fast aggregation procedure for identifying
  especially discriminating kernels. In our experiments with real and simulated data,
  CTT and its extensions provide 20–200x speed-ups over state-of-the-art approximate
  MMD tests with no loss of power.
section: Regular Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: domingo-enrich23a
month: 0
tex_title: 'Compress Then Test: Powerful Kernel Testing in Near-linear Time'
firstpage: 1174
lastpage: 1218
page: 1174-1218
order: 1174
cycles: false
bibtex_author: Domingo-Enrich, Carles and Dwivedi, Raaz and Mackey, Lester
author:
- given: Carles
  family: Domingo-Enrich
- given: Raaz
  family: Dwivedi
- given: Lester
  family: Mackey
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
pdf: https://proceedings.mlr.press/v206/domingo-enrich23a/domingo-enrich23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
