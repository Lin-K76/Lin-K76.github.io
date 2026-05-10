---
title: "Expand neurons, not parameters"
collection: publications
category: manuscripts
permalink: /publication/2026-expand
excerpt: ''
date: 2026-07-01
isconf: true
venue: 'ICML'
fullvenue: 'The 43rd International Conference on Machine Learning (ICML 2026)'
selected: true
paperurl: 'https://arxiv.org/abs/2510.04500'
authors: '<strong>Linghao Kong*</strong>, Inimai Subramanian*, Yonadav Shavit, Micah Adler, Dan Alistarh, & Nir N. Shavit'
citation: '<strong>Kong, L.*</strong>, Subramanian, I.*, Shavit, Y., Adler, M., Alistarh, D., & Shavit, N. N. (2026). The 43rd International Conference on Machine Learning (ICML 2026). https://arxiv.org/abs/2510.04500'
---

This work demonstrates how increasing the number of neurons in a network without increasing its number of non-zero parameters improves performance. We show that this gain corresponds with a decrease in interference between multiple features that would otherwise share the same neurons. On symbolic tasks, specifically Boolean code problems, splitting each neuron into sparser sub-neurons with knowledge of the clauses systematically reduces polysemanticity metrics and yields higher task accuracy. Notably, even random splits of neuron weights approximate these gains, indicating that reduced collisions, not precise assignment, are a primary driver. Consistent with the superposition hypothesis, the benefits of this framework grow with increasing interference: when polysemantic load is high, accuracy improvements are the largest. Transferring these insights to real models—classifiers over CLIP embeddings, CNNs, and deeper multilayer networks—we find that widening networks while maintaining a constant non-zero parameter count consistently increases accuracy. These results identify an interpretability-grounded mechanism to leverage width against superposition, improving performance without increasing the number of non-zero parameters. Such a direction is well matched to modern accelerators, where memory movement of non-zero parameters, rather than raw compute, is often the dominant bottleneck.