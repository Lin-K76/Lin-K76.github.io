---
title: "Negative pre-activations differentiate syntax"
collection: publications
category: manuscripts
permalink: /publication/2026-negative
excerpt: ''
date: 2026-04-01
isconf: true
venue: 'ICLR'
fullvenue: 'The 14th International Conference on Learning Representations (ICLR 2026)'
selected: true
paperurl: 'https://openreview.net/forum?id=RzcCrU0tXP'
arxiv: 'https://arxiv.org/abs/2509.24198'
authors: '<strong>Linghao Kong</strong>, Angelina Ning, Micah Adler, & Nir N. Shavit'
citation: '<strong>Kong, L.</strong>, Ning, A., Adler, M., & Shavit, N. N. (2026). Negative pre-activations differentiate syntax. The 14th International Conference on Learning Representations (ICLR 2026). https://openreview.net/forum?id=RzcCrU0tXP'
---

Modern large language models increasingly use smooth activation functions such as GELU or SiLU, allowing negative pre-activations to carry both signal and gradient. Nevertheless, many neuron-level interpretability analyses have historically focused on large positive activations, often implicitly treating the negative region as less informative, a carryover from the ReLU-era. We challenge this assumption and ask whether and how negative pre-activations are functionally utilized. We address this question by studying a sparse subpopulation of Wasserstein neurons whose output distributions deviate strongly from a Gaussian baseline and that functionally differentiate similar inputs. We show that this negative region plays a functional role rather than reflecting a mere gradient optimization side effect. A minimal, sign-specific intervention that zeroes only the negative pre-activations of a small set of Wasserstein neurons substantially increases perplexity and sharply degrades grammatical performance on BLiMP and TSE, whereas both random and perplexity-matched ablations of many more non-Wasserstein neurons in their negative pre-activations leave grammatical performance largely intact. Conversely, on a suite of non-grammatical benchmarks, the perplexity-matched control ablation is more damaging than the Wasserstein neuron ablation, yielding a double dissociation between syntax and other capabilities. Part-of-speech analysis localizes the excess surprisal to syntactic scaffolding tokens, layer-specific interventions show that small local degradations accumulate across depth, and training-dynamics analysis reveals that the same sign-specific ablation becomes more harmful as Wasserstein neurons emerge and stabilize. Together, these results identify negative pre-activations in a sparse subpopulation of Wasserstein neurons as an actively used substrate for syntax in smooth-activation language models.