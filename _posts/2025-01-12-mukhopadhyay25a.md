---
title: Transformers at a fraction
openreview: 1U0kkt7ymn
abstract: Transformer-based large models, such as GPT, are known for their performance
  and ability to effectively address tasks. Transformer-based models often have many
  parameters, which are trained to achieve high-performance levels. As a result, they
  cannot be run locally on devices with smaller memory sizes, such as mobile phones,
  necessitating the use of these models remotely by sending the data to the cloud.
  This exposes us to privacy concerns over sending confidential data to the server,
  among others. In this work, we propose a method to make these large models easier
  to run on devices with much smaller memory while sacrificing little to no performance.
  We investigate quaternion neural networks, which can reduce the number of parameters
  to one-fourth of the original real-valued model when employed efficiently. Additionally,
  we explore sparse networks created by pruning weights as a method of parameter reduction,
  following the Lottery Ticket Hypothesis. We perform the experiments on vision and
  language tasks on their respective datasets. We observe that pruned quaternion models
  perform better than the real-valued models in severely sparse conditions.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mukhopadhyay25a
month: 0
tex_title: Transformers at a fraction
firstpage: 193
lastpage: 203
page: 193-203
order: 193
cycles: false
bibtex_author: Mukhopadhyay, Aritra and Joshi, Rucha Bhalchandra and Tiwari, Nidhi
  and Mishra, Subhankar
author:
- given: Aritra
  family: Mukhopadhyay
- given: Rucha Bhalchandra
  family: Joshi
- given: Nidhi
  family: Tiwari
- given: Subhankar
  family: Mishra
date: 2025-01-12
address:
container-title: Proceedings of the 6th Northern Lights Deep Learning Conference (NLDL)
volume: '265'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 1
  - 12
pdf: https://raw.githubusercontent.com/mlresearch/v265/main/assets/mukhopadhyay25a/mukhopadhyay25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
