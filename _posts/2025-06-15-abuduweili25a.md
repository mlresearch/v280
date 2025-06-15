---
title: Revisiting the Initial Steps in Adaptive Gradient Descent Optimization
openreview: pJVxTOUCkw
abstract: 'Adaptive gradient optimization methods, such as Adam, are prevalent in
  training deep neural networks across diverse machine learning tasks due to their
  ability to achieve faster convergence. However, these methods often suffer from
  suboptimal generalization compared to stochastic gradient descent (SGD) and exhibit
  instability, particularly when training Transformer models.  In this work, we show
  the standard initialization of the second-order moment estimation ($v_0 =0$) as
  a significant factor contributing to these limitations. We introduce simple yet
  effective solutions: initializing the second-order moment estimation with non-zero
  values, using either data-driven or random initialization strategies. Empirical
  evaluations demonstrate that our approach not only stabilizes convergence but also
  enhances the final performance of adaptive gradient optimizers. Furthermore, by
  adopting the proposed initialization strategies, Adam achieves performance comparable
  to many recently proposed variants of adaptive gradient optimization methods.  Our
  code is available at https://github.com/Walleclipse/Adam_Initialization.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: abuduweili25a
month: 0
tex_title: Revisiting the Initial Steps in Adaptive Gradient Descent Optimization
firstpage: 305
lastpage: 322
page: 305-322
order: 305
cycles: false
bibtex_author: Abuduweili, Abulikemu and Liu, Changliu
author:
- given: Abulikemu
  family: Abuduweili
- given: Changliu
  family: Liu
date: 2025-06-15
address:
container-title: Conference on Parsimony and Learning
volume: '280'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 6
  - 15
pdf: https://raw.githubusercontent.com/mlresearch/v280/main/assets/abuduweili25a/abuduweili25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
