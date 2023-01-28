---
title: "Economics of Semantic Communication System: An Auction Approach"
excerpt: "We propose an incentive design framework for the semantic model trading and semantic information trading to support the deployment of semantic communication systems. We model the competition in the semantic model trading and semantic information trading with auction mechanisms. We propose an effective feature reduction method for data transmission under a limited data transfer budget."
collection: publications
permalink: /publications/2022-12-02-Economics of Semantic Communication System An Auction Approach
date: 2022-12-02
venue: 'IEEE Transactions on Vehicular Technology'
paperurl: 'https://arxiv.org/abs/2208.05040'
thumbnail: /images/papers/semauc1.png
citation: 'Zi Qin Liew, Hongyang Du, Wei Yang Bryan Lim, Zehui Xiong, Dusit Niyato, Chunyan Miao, and Dong In Kim. "Economics of Semantic Communication System: An Auction Approach." IEEE Transactions on Vehicular Technology, arXiv preprint arXiv:2208.05040 (2022).'
---

[Download paper here](http://hongyangdu.github.io/files/Liew et al_2022_Economics of Semantic Communication System.pdf)


**Abstract**: Semantic communication technologies enable wireless edge devices to communicate effectively by transmitting semantic meaning of data. Edge components, such as vehicles in next-generation intelligent transport systems, use well-trained semantic models to encode and decode semantic information extracted from raw and sensor data. However, the limitation in computing resources makes it difficult to support the training process of accurate semantic models on edge devices. As such, edge devices can buy the pretrained semantic models from semantic model providers, which is called “semantic model trading”. Upon collecting semantic information with the semantic models, the edge devices can then sell the extracted semantic information, e.g., information about urban road conditions or traffic signs, to the interested buyers for profit, which is called “semantic information trading”. To facilitate both types of the trades, effective incentive mechanisms should be designed. Thus, in this paper, we propose a hierarchical trading system to support both semantic model trading and semantic information trading jointly. The proposed incentive mechanism helps to maximize the revenue of semantic model providers in the semantic model trading, and effectively incentivizes model providers to participate in the development of semantic communication systems. For semantic information trading, our designed auction approach can support the trading between multiple semantic information sellers and buyers, while ensuring individual rationality, incentive compatibility, and budget balance, and moreover, allowing them achieve higher utilities than the baseline method.

**Index Terms**: Semantic communication, incentive mechanism, auction

<br/><img src='/images/papers/semauc1.png' width = "700">

Fig. 1: The system model which includes semantic model trading and semantic information trading. In the semantic model trading, edge devices trade with semantic model providers to obtain semantic encoders/decoders for semantic communications. In the semantic information trading, edge devices equipped with semantic encoders/decoders trade semantic information with buyers.

<br/><img src='/images/papers/semauc2.png' width = "700">

Fig. 2: Sample output of semantic encoder with 16 features, input sentence: “thirdly it criticises the shortcomings but in a positive manner”.

<br/><img src='/images/papers/semauc3.png' width = "700">

Fig. 3: Illustration of controlled dropout during the training.

<br/><img src='/images/papers/semauc4.png' width = "700">

Fig. 12: Average number of winning sellers with and without deep learning in the double auction mechanism.