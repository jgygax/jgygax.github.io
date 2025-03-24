---
title: "Elucidating the Theoretical Underpinnings of Surrogate Gradient Learning in Spiking Neural Networks"
collection: publications
permalink: /publications/2024-04-24-Elucidating-Theoretical-Underpinnings-of-Surrogate-Gradient-Learning
excerpt: 'Training spiking neural networks (SNNs) to approximate complex functions is essential for studying information processing in the brain and neuromorphic computing. Yet, the binary nature of spikes constitutes a challenge for direct gradient-based training. To sidestep this problem, surrogate gradients (SGs) have proven empirically successful, but their theoretical foundation remains elusive. Here, we investigate the relation of SGs to two theoretically well-founded approaches. On the one hand, we consider smoothed probabilistic models, which, due to lack of support for automatic differentiation, are impractical for training deep SNNs, yet provide gradients equivalent to SGs in single neurons. On the other hand, we examine stochastic automatic differentiation, which is compatible with discrete randomness but has never been applied to SNN training. We find that the latter provides the missing theoretical basis for SGs in stochastic SNNs. We further show that SGs in deterministic networks correspond to a particular asymptotic case and numerically confirm the effectiveness of SGs in stochastic multi-layer SNNs. Finally, we illustrate that SGs are not conservative fields and, thus, not gradients of a surrogate loss. Our work provides the missing theoretical foundation for SGs and an analytically well-founded solution for end-to-end training of stochastic SNNs.'
date: 2025-03-20
venue: 'Neural Computation'
thumbnail: '/images/SG_theory.jpeg'
paperurl: 'https://doi.org/10.1162/neco_a_01752'
preprinturl: 'https://arxiv.org/abs/2404.14964'
codeurl: 'https://github.com/fmi-basel/surrogate-gradient-theory'
citation: '<b>Gygax, Julia</b> & Zenke, Friedemann.'
---
