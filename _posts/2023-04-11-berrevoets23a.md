---
title: To Impute or not to Impute? Missing Data in Treatment Effect Estimation
software: https://github.com/jeroenbe/mcm
abstract: Missing data is a systemic problem in practical scenarios that causes noise
  and bias when estimating treatment effects. This makes treatment effect estimation
  from data with missingness a particularly tricky endeavour. A key reason for this
  is that standard assumptions on missingness are rendered insufficient due to the
  presence of an additional variable, treatment, besides the input (e.g. an individual)
  and the label (e.g. an outcome). The treatment variable introduces additional complexity
  with respect to why some variables are missing that is not fully explored by previous
  work. In our work we introduce mixed confounded missingness (MCM), a new missingness
  mechanism where some missingness determines treatment selection and other missingness
  is determined by treatment selection. Given MCM, we show that naively imputing all
  data leads to poor performing treatment effects models, as the act of imputation
  effectively removes information necessary to provide unbiased estimates. However,
  no imputation at all also leads to biased estimates, as missingness determined by
  treatment introduces bias in covariates. Our solution is selective imputation, where
  we use insights from MCM to inform precisely which variables should be imputed and
  which should not. We empirically demonstrate how various learners benefit from selective
  imputation compared to other solutions for missing data. We highlight that our experiments
  encompass both average treatment effects and conditional average treatment effects.
section: Regular Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: berrevoets23a
month: 0
tex_title: To Impute or not to Impute? Missing Data in Treatment Effect Estimation
firstpage: 3568
lastpage: 3590
page: 3568-3590
order: 3568
cycles: false
bibtex_author: Berrevoets, Jeroen and Imrie, Fergus and Kyono, Trent and Jordon, James
  and van der Schaar, Mihaela
author:
- given: Jeroen
  family: Berrevoets
- given: Fergus
  family: Imrie
- given: Trent
  family: Kyono
- given: James
  family: Jordon
- given: Mihaela
  family: Schaar
  prefix: van der
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
pdf: https://proceedings.mlr.press/v206/berrevoets23a/berrevoets23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
