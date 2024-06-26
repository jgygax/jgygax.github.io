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