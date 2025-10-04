---
title: "Negative pre-activations differentiate syntax"
collection: publications
category: manuscripts
permalink: /publication/2025-negative
excerpt: ''
date: 2025-09-29
venue: 'arXiv'
preprint: true
selected: true
paperurl: 'https://arxiv.org/abs/2509.24198'
authors: '<strong>Linghao Kong</strong>, Angelina Ning, Micah Adler, & Nir N. Shavit'
citation: '<strong>Kong, L.</strong>, Ning, A., Adler, M., & Shavit, N. N. (2025, September). Negative pre-activations differentiate syntax. arXiv preprint. https://arxiv.org/abs/2509.24198'
---

A recently discovered class of entangled neurons, known as Wasserstein neurons, is disproportionately critical in large language models despite constituting only a very small fraction of the network: their targeted removal collapses the model, consistent with their unique role in differentiating similar inputs. Interestingly, in Wasserstein neurons immediately preceding smooth activation functions, such differentiation manifests in the negative pre-activation space, especially in early layers. Pairs of similar inputs are driven to highly distinct negative values, and these pairs involve syntactic tokens such as determiners and prepositions. We show that this negative region is functional rather than simply favorable for optimization. A minimal, sign-specific intervention that zeroes only the negative pre-activations of a small subset of entangled neurons significantly weakens overall model function and disrupts grammatical behavior, while both random and perplexity-matched controls leave grammatical performance largely unchanged. Part of speech analysis localizes the excess surprisal to syntactic scaffolding tokens, and layer-specific interventions reveal that small local degradations accumulate across depth. Over training checkpoints, the same ablation impairs grammatical behavior as Wasserstein neurons emerge and stabilize. Together, these results identify negative differentiation in a sparse subset of entangled neurons as a crucial mechanism that language models rely on for syntax.