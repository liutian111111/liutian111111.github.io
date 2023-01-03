---
title: "Data Diversification Revisited: Why Does It Work?"
collection: publications
permalink: /publication/2021-09-14-Data Diversification Revisited-Why Does It Work
excerpt: 'Data Diversification is a recently proposed method of data augmentation for Neural Machine Translation (NMT)...'
date: 2021-09-14
paperurl: 'https://link.springer.com/content/pdf/10.1007/978-3-030-86365-4.pdf?pdf=button%20sticky'
citation: 'Song Y, **Liu T**, Jia W. Data Diversification Revisited: Why Does It Work?[C]//International Conference on Artificial Neural Networks. Springer, Cham, 2021: 521-533.'
---
Data Diversification is a recently proposed method of data augmentation for Neural Machine Translation (NMT). While it attracts broad attention due to its effectiveness, the reason for its success is unclear. In this paper, we first establish a connection between data diversification and knowledge distillation, and prove that data diversification reduces the modality complexity. We also find knowledge distillation has a lower complexity of data modality than data diversification, but challenging to boost performance. Our analysis reveals that knowledge distillation has a negative impact on the word frequency distribution where increasing rare words with unreliable representations. Furthermore, data diversification trains multiple models to further decrease the modality complexity, suffering from unbearable computational expenses. To reduce the computational cost, we propose adjustable sampling, which samples a model multiple times instead of training multiple models. Different from other sampling methods, our method introduces entropy to adjust the quality and diversity of the generated sentences, achieving the goal of reducing modality complexity and noise introduction. Extensive experimental results show our method dramatically reduces the computational cost of data diversification without loss of accuracy, and achieves improvements over other strong sampling methods.

[Download paper here](https://link.springer.com/content/pdf/10.1007/978-3-030-86365-4.pdf?pdf=button%20sticky)

Recommended citation: Song Y, **Liu T**, Jia W. Data Diversification Revisited: Why Does It Work?[C]//International Conference on Artificial Neural Networks. Springer, Cham, 2021: 521-533.