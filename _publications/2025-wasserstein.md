---
title: "Wasserstein distances, neuronal entanglement, and sparsity"
collection: publications
category: manuscripts
permalink: /publication/2025-wasserstein
excerpt: ''
date: 2025-04-01
isconf: true
venue: 'ICLR'
special: 'as a <strong>Spotlight Presentation</strong>'
paperurl: 'https://openreview.net/forum?id=cnKhHxN3xj'
citation: 'Sawmya, S.*, <strong>Kong, L.*</strong>, Markov, I., Alistarh, D., & Shavit, N. N. (2025). Wasserstein distances, neuronal entanglement, and sparsity. The 13th International Conference on Learning Representations (ICLR 2025, Spotlight Presentation). https://openreview.net/pdf?id=cnKhHxN3xj'
---


Disentangling polysemantic neurons is at the core of many current approaches to interpretability of large language models. Here we attempt to study how disentanglement can be used to understand performance, particularly under weight sparsity, a leading post-training optimization technique. We suggest a novel measure for estimating neuronal entanglement: the Wasserstein distance of a neuron's output distribution to a Gaussian. Moreover, we show the existence of a small number of highly entangled "Wasserstein Neurons" in each linear layer of an LLM, characterized by their highly non-Gaussian output distributions, their role in mapping similar inputs to dissimilar outputs, and their significant impact on model accuracy. To study these phenomena, we propose a new experimental framework for disentangling polysemantic neurons. Our framework separates each layer's inputs to create a mixture of experts where each neuron's output is computed by a mixture of neurons of lower Wasserstein distance, each better at maintaining accuracy when sparsified without retraining. We provide strong evidence that this is because the mixture of sparse experts is effectively disentangling the input-output relationship of individual neurons, in particular the difficult Wasserstein neurons.
