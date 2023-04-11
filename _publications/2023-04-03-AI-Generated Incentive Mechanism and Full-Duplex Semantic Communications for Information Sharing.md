---
title: "AI-Generated Incentive Mechanism and Full-Duplex Semantic Communications for Information Sharing"
excerpt: " We analyze the performance of full-duplex D2D communications, including the achievable rate and bit error probability, by using generalized small-scale fading models. To facilitate semantic information sharing among users, we design a contract theoretic AI-generated incentive mechanism. The proposed diffusion model generates the optimal contract design, outperforming two deep reinforcement learning algorithms."
collection: publications
permalink: /publications/2023-04-03-AI Generated Incentive Mechanism and Full Duplex Semantic Communications for Information Sharing
date: 2023-04-03
venue: 'IEEE Journal on Selected Areas in Communications'
paperurl: 'https://arxiv.org/abs/2303.01896'
thumbnail: /images/papers/diff6.png
citation: 'Hongyang Du, Jiacheng Wang, Dusit Niyato, Jiawen Kang, Zehui Xiong, and Dong In Kim. "AI-Generated Incentive Mechanism and Full-Duplex Semantic Communications for Information Sharing." IEEE Journal on Selected Areas in Communications (2023).'
---

[Download paper here](http://hongyangdu.github.io/files/Wang et al_2022_Extremely Large-Scale MIMO.pdf)

**Abstract**: The next generation of Internet services, such as Metaverse, rely on mixed reality (MR) technology to provide immersive user experiences. However, limited computation power of MR headset-mounted devices (HMDs) hinders the deployment of such services. Therefore, we propose an efficient informationsharing scheme based on full-duplex device-to-device (D2D) semantic communications to address this issue. Our approach enables users to avoid heavy and repetitive computational tasks, such as artificial intelligence-generated content (AIGC) in the view images of all MR users. Specifically, a user can transmit the generated content and semantic information extracted from their view image to nearby users, who can then use this information to obtain the spatial matching of computation results under their view images. We analyze the performance of full-duplex D2D communications, including the achievable rate and bit error probability, by using generalized small-scale fading models. To facilitate semantic information sharing among users, we design a contract theoretic AI-generated incentive mechanism. The proposed diffusion model generates the optimal contract design, outperforming two deep reinforcement learning algorithms, i.e., proximal policy optimization and soft actor-critic algorithms. Our numerical analysis experiment proves the effectiveness of our proposed methods.

**Index Terms**: Semantic communications, incentive mechanism, deep reinforcement learning, full-duplex, Metaverse.

<br/><img src='/images/papers/diff0.png' width = "700">

Fig. 3: The semantic-aware free-space information sharing mechanism proposed in this paper. Full-duplex wireless communication is performed between MR HMDs among users. The free-space information is computed by the state-of-art anomaly detection approach named JSR-Net [28]

<br/><img src='/images/papers/diff1.png' width = "700">

Fig. 4: The structure of the semantic encoder. The input is the user’s view image, and the output is the detected interest points and descriptors.

<br/><img src='/images/papers/diff2.png' width = "700">

Fig. 5: The structure of the semantic matching. The input is the received semantic information and the jth user’s semantic encoding results, and the output is the matching results.

<br/><img src='/images/papers/diff6.png' width = "700">

Fig. 6: Diffusion Model for incentive design. Diffusion Model for incentive design. For any given environment, the contract is first randomly generated as the Gaussian noise. After the multi-step denoising through the diffusion model, the output is the contract design that maximizes the optimization objective.

<br/><img src='/images/papers/diff3.png' width = "700">

Fig. 8. The impact of different wireless transmission BEPs on our proposed full-duplex D2D free-space information sharing mechanism. The semantic encoder extracts 150 interest points and corresponding descriptors in the image as the semantic information.

<br/><img src='/images/papers/diff4.png' width = "700">

Fig. 9. The effect of our proposed free-space sharing mechanism under different incentive design schemes, e.g., DRL-PPO, DRL-SAC, and AIgenerated contract.

<br/><img src='/images/papers/diff5.png' width = "700">

Figures: Numerical results