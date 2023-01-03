---
title: "Robust Multimodal Sentiment Analysis Via Tag Encoding of Uncertain Missing Modalities"
collection: publications
permalink: /publication/2022-09-19-Robust Multimodal Sentiment Analysis Via Tag Encoding of Uncertain Missing Modalities
excerpt: 'Multimodal sentiment analysis aims to extract emotions with multiple data sources, usually under the assumption that all modalities are available...'
date: 2022-09-19
paperurl: 'https://ieeexplore.ieee.org/iel7/6046/4456689/09894726.pdf'
citation: 'Zeng J, Zhou J, **Liu T**. Robust Multimodal Sentiment Analysis Via Tag Encoding of Uncertain Missing Modalities[J]. IEEE Transactions on Multimedia, 2022.'
---
Multimodal sentiment analysis aims to extract emotions with multiple data sources, usually under the assumption that all modalities are available. In practice, such a strong assumption does not always hold, and most of multimodal sentiment analysis methods may fail when partial modalities are missing. Some existing works have started to address the missing modality problem; but only considered the single modality missing case, while ignoring the practically more general cases of multiple modalities missing. To this end, in this paper, we propose a Tag-Assisted Transformer Encoder (TATE) network to handle the problem of missing uncertain modalities. Specifically, we design a tag encoding module to cover both the single modality and multiple modalities missing cases, so as to guide the network's attention to those missing modalities. Besides, a new space projection pattern is adopted to align common vectors, taking into account the different importance of each modality. Afterwards, a Transformer encoder-decoder network is utilized to learn the missing modality features, and the outputs of the Transformer encoder are extracted for the final sentiment classification. Extensive experiments and analyses are conducted on CMU-MOSI, IEMOCAP, and MELD datasets, which show that the proposed method can achieve significant improvements compared with several baselines.

[Download paper here](https://ieeexplore.ieee.org/iel7/6046/4456689/09894726.pdf)

Recommended citation: Zeng J, Zhou J, **Liu T**. Robust Multimodal Sentiment Analysis Via Tag Encoding of Uncertain Missing Modalities[J]. IEEE Transactions on Multimedia, 2022.