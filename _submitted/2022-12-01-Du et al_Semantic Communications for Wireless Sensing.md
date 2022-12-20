---
title: "Semantic Communications for Wireless Sensing: RIS-aided Encoding and Self-supervised Decoding"
excerpt: "We propose the inverse semantic communications as a new paradigm. Instead of extracting semantic information from messages, we aim to encode the taskrelated source messages into a hyper-source message for data transmission or storage. Following this paradigm, we design an inverse semantic-aware wireless sensing framework with three algorithms for data sampling, reconfigurable intelligent surface (RIS)-aided encoding, and self-supervised decoding, respectively. Using the sensing data collected from real-world, we show that our framework can reduce the data volume by 95% compared to that before encoding, without affecting the accomplishment of sensing tasks."
collection: submitted
permalink: /submitted/2022-12-01-Semantic Communications for Wireless Sensing: RIS-aided Encoding and Self-supervised Decoding
date: 2022-11-01
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2210.15130'
citation: 'Hongyang Du, Jiacheng Wang, Dusit Niyato, Jiawen Kang, Zehui Xiong, and Junshan Zhang. "Semantic Communications for Wireless Sensing: RIS-aided Encoding and Self-supervised Decoding." arXiv preprint arXiv:2211.12727 (2022).'
---

[Download paper here](http://hongyangdu.github.io/files/Du et al_Semantic Communications for Wireless Sensing.pdf)

**Abstract**: Semantic communications can reduce the resource consumption by transmitting task-related semantic information extracted from source messages. However, when the source messages are utilized for various tasks, e.g., wireless sensing data for localization and activities detection, semantic communication technique is difficult to be implemented because of the increased processing complexity. In this paper, we propose the inverse semantic communications as a new paradigm. Instead of extracting semantic information from messages, we aim to encode the taskrelated source messages into a hyper-source message for data transmission or storage. Following this paradigm, we design an inverse semantic-aware wireless sensing framework with three algorithms for data sampling, reconfigurable intelligent surface (RIS)-aided encoding, and self-supervised decoding, respectively. Specifically, on the one hand, we design a novel RIS hardware for encoding several signal spectrums into one MetaSpectrum. To select the task-related signal spectrums for achieving efficient encoding, a semantic hash sampling method is introduced. On the other hand, we propose a self-supervised learning method for decoding the MetaSpectrums to obtain the original signal spectrums. Using the sensing data collected from real-world, we show that our framework can reduce the data volume by 95% compared to that before encoding, without affecting the accomplishment of sensing tasks. Moreover, compared with the typically used uniform sampling scheme, the proposed semantic hash sampling scheme can achieve 67% lower mean squared error in recovering the sensing parameters. In addition, experiment results demonstrate that the amplitude response matrix of the RIS enables the encryption of the sensing data.

**Index Terms**: Semantic communications, reconfigurable intelligent surface, wireless sensing, self-supervised learning

<br/><img src='/images/papers/semss1.png' width = "700">

Figure 1: Fig. 1. The ideas of conventional, semantic, and inverse semantic communications. Motivated by the inverse semantic-aware communication, we propose an inverse semantic-aware encoding and decoding framework and show the results. Specifically, we select 10 original signal amplitude/phase spectrum (Part I) by using our proposed Algorithm 2, and encode them into one MetaSpectrum by using the RIS and Algorithm 1. After wireless transmission, the reconstruction results (Part II) are obtained by decoding the MetaSpectrum using Algorithm 3. The sensing data is collected by real experiments with an IEEE 802.11ax based test platform [13].

<br/><img src='/images/papers/semss2.png' width = "700">

Figure 2: Fig. 2. The framework of the proposed inverse semantic-aware wireless sensing system.

<br/><img src='/images/papers/semss3.png' width = "700">

Figure 3: The process of modulating the amplitude and phase spectrums through RIS, and then performing differential encoding and shifting addition.

<br/><img src='/images/papers/semss4.png' width = "700">

Figure 4: The process of generating the resized matrices from the amplitude and phase spectrums, and then obtaining the semantic hash fingerprint.

<br/><img src='/images/papers/semss5.png' width = "700">

Figure 5: Test scenario and hardware of the receiver.

<br/><img src='/images/papers/semss6.png' width = "700">

Figure 6: The variation of the decoded amplitude and phase spectrums at time 4:5 s in the experiment, the corresponding semantic hash matrix, the estimated 2D AoA spectrum by Proposition 2 with the number of outer loop decoding iterations, where the data compression ratio is 5%.

<br/><img src='/images/papers/semss7.png' width = "700">

Figure 8: Comparison between different sampling methods and ground truth in terms of 2D AoA changes with movement of human.

<br/><img src='/images/papers/semss8.png' width = "700">

Figure 9: Comparison of azimuth AoA estimation results that are obtained by using the original and decoded signals, respectively.