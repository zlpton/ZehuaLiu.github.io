---
title: "Enabling AI-Generated Content (AIGC) Services in Wireless Edge Networks"
excerpt: "To the best of our knowledge, this is the first research work to discuss the deployments, aforementioned challenges, and future directions of AI-Generated Content (AIGC) in wireless edge networks. We propose a general and effective model to illustrate the relationship between computational resources and user-perceived quality evaluation metrics. We propose a deep reinforcement learning-enabled algorithm for the optimal AIGC service provider (ASP) selection."
collection: submitted
permalink: /submitted/2023-01-01-Enabling AI-Generated Content (AIGC) Services in Wireless Edge Networks
date: 2023-01-01
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2211.16662'
thumbnail: /images/papers/semblo1.png
citation: 'Hongyang Du, Zonghang Li, Dusit Niyato, Jiawen Kang, Zehui Xiong, and Dong In Kim. "Enabling AI-Generated Content (AIGC) Services in Wireless Edge Networks." arXiv preprint arXiv:2301.03220 (2023).'
---

[Download paper here](http://hongyangdu.github.io/files/Du et al_Enabling AI-Generated Content (AIGC) Services in Wireless Edge Networks.pdf)

**Abstract**: Artificial Intelligence-Generated Content (AIGC) refers to the use of AI to automate the information creation process while fulfilling the personalized requirements of users. However, due to the instability of AIGC models, e.g., the stochastic nature of diffusion models, the quality and accuracy of the generated content can vary significantly. In wireless edge networks, the transmission of incorrectly generated content may unnecessarily consume network resources. Thus, a dynamic AIGC service provider (ASP) selection scheme is required to enable users to connect to the most suited ASP, improving the users’ satisfaction and quality of generated content. In this article, we first review the AIGC techniques and their applications in wireless networks. We then present the AIGC-asaservice (AaaS) concept and discuss the challenges in deploying AaaS at the edge networks. Yet, it is essential to have performance metrics to evaluate the accuracy of AIGC services. Thus, we introduce several image-based perceived quality evaluation metrics. Then, we propose a general and effective model to illustrate the relationship between computational resources and user-perceived quality evaluation metrics. To achieve efficient AaaS and maximize the quality of generated content in wireless edge networks, we propose a deep reinforcement learning-enabled algorithm for the optimal ASP selection. Simulation results show that the proposed algorithm can provide a higher quality of generated content to users and achieve fewer crashed tasks by comparing with four benchmarks, i.e., overloading-avoidance, random, round-robin policies, and the upper-bound schemes.

**Index Terms**: AI-generated content, wireless networks, performance metric, deep reinforcement learning

<br/><img src='/images/papers/aigc1.png' width = "700">

Figure 1: Generative techniques in AIGC [9], categories of AIGC, and applications in wireless edge networks. We list several online available AIGC services as examples, e.g., ChatGPT for text-to-text AIGC (https://openai.com/blog/chatgpt/), Imagen for text-to-image AIGC (https://imagen.research.google/), DreamFusion for text-to-3D AIGC (https://dreamfusion3d.github.io/), Crypko for image-to-image AIGC (https://crypko.ai/), and Human Voice Generator for audio-related AIGC (https://murf.ai/).

<br/><img src='/images/papers/aigc2.png' width = "700">

Figure 2: Example of an AaaS for repairing corrupted images. The corrupted images are shown in Part A, and the repaired images under different inference steps are shown in Part D. Part B shows how the performance metric, BRISQUE, varies over different inference steps. Part C shows the system model of ASP selection problem. A experiment demo is shown in Part E.

<br/><img src='/images/papers/aigc3.png' width = "700">

Figure 3: The relationship between the number of inference steps and various perceived image quality metrics, i.e., TV, BRISQUE, DSS, HaarPSI, MDSI, and VIF.

<br/><img src='/images/papers/aigc4.png' width = "700">

Figure 5: Reward values versus the number of iteration number in DRL. For performance comparison, we show the results of overloading-avoidance, random, round-robin policies, and their upper bound.