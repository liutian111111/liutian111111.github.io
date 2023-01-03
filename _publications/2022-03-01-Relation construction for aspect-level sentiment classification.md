---
title: "Relation construction for aspect-level sentiment classification"
collection: publications
permalink: /publication/2022-03-01-Relation construction for aspect-level sentiment classification
excerpt: 'Aspect-level sentiment classification aims to obtain fine-grained sentiment polarities of different aspects in one sentence...'
date: 2022-03-01
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0020025521012032/pdfft?md5=82435bdd06f0b06e0f3fdbd5f05232ce&pid=1-s2.0-S0020025521012032-main.pdf'
citation: 'Zeng J, **Liu T**, Jia W, et al. Relation construction for aspect-level sentiment classification[J]. Information Sciences, 2022, 586: 209-223.'
---
Aspect-level sentiment classification aims to obtain fine-grained sentiment polarities of different aspects in one sentence. Most existing approaches handle the classification by acquiring the importance of context words towards each given aspect individually, and ignore the benefits brought by aspect relations. Since the sentiment of one aspect can be deduced through their relationship according to other aspects, in this paper, we propose a novel relation construction multi-task learning network (RMN), which is the first attempt to extract aspect relations as an auxiliary classification task. RMN generates aspect representations through graph convolution networks with a semantic dependency graph and utilizes the bi-attention mechanism to capture the relevance between the aspect and the context. Unlike conventional multi-task learning methods that need extra datasets, we construct an auxiliary relation-level classification task that extracts aspect relations from the original dataset with shared parameters. Extensive experiments on five public datasets from SemEval 14, 15, 16 and MAMS show that our RMN improves about 0.09% to 0.8% on accuracy and about 0.04% to 1.19% on F1 score, compared to several comparative baselines.

[Download paper here](https://www.sciencedirect.com/science/article/pii/S0020025521012032/pdfft?md5=82435bdd06f0b06e0f3fdbd5f05232ce&pid=1-s2.0-S0020025521012032-main.pdf)

Recommended citation: Zeng J, **Liu T**, Jia W, et al. Relation construction for aspect-level sentiment classification[J]. Information Sciences, 2022, 586: 209-223.