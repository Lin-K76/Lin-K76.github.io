---
title: "An interpretable latency model for speculative decoding in LLM serving"
collection: publications
category: manuscripts
permalink: /publication/2026-latency
excerpt: ''
date: 2026-05-14
venue: 'arXiv'
preprint: true
selected: true
paperurl: 'https://arxiv.org/abs/2605.15051'
authors: '<strong>Linghao Kong</strong>, Micah Adler, & Nir N. Shavit'
citation: '<strong>Kong, L.</strong>, Adler, M., & Shavit, N. N. (2026, May). An interpretable latency model for speculative decoding in LLM serving. arXiv preprint. https://arxiv.org/abs/2605.15051'
---

Speculative decoding (SD) accelerates large language model (LLM) inference by using a smaller draft model to propose multiple tokens that are verified by a larger target model in parallel. While prior work demonstrates substantial speedups in isolated or fixed-batch settings, the behavior of SD in production serving systems remains poorly understood: request load varies over time, and effective batch size emerges from the serving system rather than being directly controlled or observed. In this work, we develop a simple and interpretable latency model for SD in LLM serving. We infer effective batch size from request rate using Little's Law and decompose per-request demand into load-independent and load-dependent components for prefill, drafting, and verification. We validate our model using extensive measurements from vLLM across verifier and drafter model sizes, prefill and decode lengths, request rates, draft lengths, and acceptance probabilities. The model accurately describes observed latency, explains why speedups often diminish as server load increases, and characterizes how draft length, acceptance rate, and verifier-drafter size shape latency across serving conditions, with implications for configuring SD in deployed systems. We further show how the framework extends to mixture of experts models, where sparse expert activation changes the effective service costs across load regimes. Together, our results provide a structured framework for understanding SD in real LLM serving systems.