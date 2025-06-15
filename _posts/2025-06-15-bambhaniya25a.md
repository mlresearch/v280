---
title: Progressive Gradient Flow for Robust N:M Sparsity Training in Transformers
openreview: HJjauwys0B
abstract: N:M Structured sparsity has garnered significant interest as a result of
  relatively modest overhead and improved efficiency. Additionally, this form of sparsity
  holds considerable appeal for reducing the memory footprint owing to their modest
  representation overhead. There have been efforts to develop training recipes for
  N:M structured sparsity, they primarily focus on low-sparsity regions (50%). Nonetheless,
  performance of models trained using these approaches tends to decline when confronted
  with high-sparsity regions (80%). In this work, we study the effectiveness of existing
  sparse training recipes at high-sparsity regions and argue that these methods fail
  to sustain the model quality on par with low-sparsity regions. We demonstrate that
  the significant factor contributing to this disparity is the presence of elevated
  levels of induced noise in the gradient magnitudes. To mitigate this undesirable
  effect, we employ decay mechanisms to progressively restrict the flow of gradients
  towards pruned elements. Our approach improves the model quality by up to 2% and
  5% in vision and language models at high sparsity regime, respectively. We also
  evaluate the trade-off between model accuracy and training compute cost in terms
  of FLOPs. At iso-training FLOPs, our method performs better than conventional sparse
  training recipes, exhibiting an accuracy improvement of up to 2%.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bambhaniya25a
month: 0
tex_title: Progressive Gradient Flow for Robust N:M Sparsity Training in Transformers
firstpage: 1170
lastpage: 1190
page: 1170-1190
order: 1170
cycles: false
bibtex_author: Bambhaniya, Abhimanyu Rajeshkumar and Yazdanbakhsh, Amir and Subramanian,
  Suvinay and Kao, Sheng-Chun and Agrawal, Shivani and Evci, Utku and Krishna, Tushar
author:
- given: Abhimanyu Rajeshkumar
  family: Bambhaniya
- given: Amir
  family: Yazdanbakhsh
- given: Suvinay
  family: Subramanian
- given: Sheng-Chun
  family: Kao
- given: Shivani
  family: Agrawal
- given: Utku
  family: Evci
- given: Tushar
  family: Krishna
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
pdf: https://raw.githubusercontent.com/mlresearch/v280/main/assets/bambhaniya25a/bambhaniya25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
