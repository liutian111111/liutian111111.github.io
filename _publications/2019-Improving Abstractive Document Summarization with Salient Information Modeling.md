---
title: "Improving Abstractive Document Summarization with Salient Information Modeling"
collection: publications
permalink: /publication/2019-Improving Abstractive Document Summarization with Salient Information Modeling
excerpt: 'Comprehensive document encoding and salient information selection are two major difficulties for generating summaries with adequate salient information...'
date: 2019-02-01
---
Comprehensive document encoding and salient information selection are two major difficulties for generating summaries with adequate salient information. To tackle the above difficulties, we propose a Transformer-based encoder-decoder framework with two novel extensions for abstractive document summarization. Specifically, (1) to encode the documents comprehensively, we design a focus-attention mechanism and incorporate it into the encoder. This mechanism models a Gaussian focal bias on attention scores to enhance the perception of local context, which contributes to producing salient and informative summaries. (2) To distinguish salient information precisely, we design an independent saliency-selection network which manages the information flow from encoder to decoder. This network effectively reduces the influences of secondary information on the generated summaries. Experimental results on the popular CNN/Daily Mail benchmark demonstrate that our model outperforms other state-of-the-art baselines on the ROUGE metrics.

[Download paper here](https://aclanthology.org/P19-1205.pdf)

Recommended citation: You Y, Jia W, **Liu T**, et al. Improving abstractive document summarization with salient information modeling[C]//Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics. 2019: 2132-2141.