---
title: "Fluctuation-driven initialization for spiking neural network training"
collection: publications
permalink: /publications/2022-12-08-Fluctuation-driven-initialization
excerpt: 'Spiking neural networks (SNNs) underlie low-power, fault-tolerant information processing in the brain and could constitute a power-efﬁcient alternative to conventional deep neural networks when implemented on suitable neuromorphic hardware accelerators. However, instantiating SNNs that solve complex computational tasks in-silico remains a signiﬁcant challenge. Surrogate gradient (SG) techniques have emerged as a standard solution for training SNNs end-to-end. Still, their success depends on synaptic weight initialization, similar to conventional artiﬁcial neural networks (ANNs). Yet, unlike in the case of ANNs, it remains elusive what constitutes a good initial state for an SNN. Here, we develop a general initialization strategy for SNNs inspired by the ﬂuctuation-driven regime commonly observed in the brain. Speciﬁcally, we derive practical solutions for data-dependent weight initialization that ensure ﬂuctuation-driven ﬁring in the widely used leaky integrate-and-ﬁre neurons. We empirically show that SNNs initialized following our strategy exhibit superior learning performance when trained with SGs. These ﬁndings generalize across several datasets and SNN architectures, including fully connected, deep convolutional, recurrent, and more biologically plausible SNNs obeying Dale’s law. Thus ﬂuctuation-driven initialization provides a practical, versatile, and easy-to-implement strategy for improving SNN training performance on diverse tasks in neuromorphic engineering and computational neuroscience.'
date: 2022-12-08
venue: 'Neuromorphic Computing and Engineering'
thumbnail: '/images/spikeinit.jpeg'
paperurl: 'https://iopscience.iop.org/article/10.1088/2634-4386/ac97bb'
preprinturl: 'https://arxiv.org/abs/2206.10226'
codeurl: 'https://github.com/fmi-basel/stork'
citation: 'Rossbroich, Julian*, <b>Gygax, Julia</b>*, & Zenke, Friedemann. (* equal contribution)'
---
title: "Elucidating the Theoretical Underpinnings of Surrogate Gradient Learning in Spiking Neural Networks"
collection: publications
permalink: /publications/2024-04-24-Elucidating-Theoretical-Underpinnings-of-Surrogate-Gradient-Learning
excerpt: 'Training spiking neural networks (SNNs) to approximate complex functions is essential for studying information processing in the brain and neuromorphic computing. Yet, the binary nature of spikes constitutes a challenge for direct gradient-based training. To sidestep this problem, surrogate gradients (SGs) have proven empirically successful, but their theoretical foundation remains elusive. Here, we investigate the relation of SGs to two theoretically well-founded approaches. On the one hand, we consider smoothed probabilistic models, which, due to lack of support for automatic differentiation, are impractical for training deep SNNs, yet provide gradients equivalent to SGs in single neurons. On the other hand, we examine stochastic automatic differentiation, which is compatible with discrete randomness but has never been applied to SNN training. We find that the latter provides the missing theoretical basis for SGs in stochastic SNNs. We further show that SGs in deterministic networks correspond to a particular asymptotic case and numerically confirm the effectiveness of SGs in stochastic multi-layer SNNs. Finally, we illustrate that SGs are not conservative fields and, thus, not gradients of a surrogate loss. Our work provides the missing theoretical foundation for SGs and an analytically well-founded solution for end-to-end training of stochastic SNNs.'
date: 2024-04-24
venue: 'arXiv'
thumbnail: '/images/SG_theory.jpeg'
preprinturl: '<https://arxiv.org/abs/2404.14964>'
codeurl: '<https://github.com/fmi-basel/surrogate-gradient-theory>'
citation: '<b>Gygax, Julia</b> & Zenke, Friedemann.'
---
