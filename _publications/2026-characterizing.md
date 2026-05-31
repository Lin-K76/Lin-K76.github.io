---
title: "Characterizing plastic regions in neural networks"
collection: publications
category: conferences
permalink: /publication/2026-characterizing
excerpt: ''
date: 2026-07-01
isconf: true
venue: 'ICML'
workshop: 'CATS'
fullvenue: 'The Workshop on Continual Adaptation at Scale: Towards Sustainable AI at the 43rd International Conference on Machine Learning (ICML 2026 Workshop CATS)'
paperurl: 'https://openreview.net/forum?id=Xps07lkTpv'
authors: 'Gwyneth Liu, Nir N. Shavit, & <strong>Linghao Kong</strong>'
citation: 'Liu, G., Shavit, N. N., & <strong>Kong, L</strong>. (2026, July). Characterizing plastic regions in neural networks [Poster presentation]. The Workshop on Continual Adaptation at Scale: Towards Sustainable AI at the 43rd International Conference on Machine Learning (ICML 2026 Workshop CATS), Seoul, South Korea.'
---

Adapting a trained model to a new domain without overwriting prior knowledge is useful only when the model contains a region whose parameter state can support new learning. In vision classifiers, we study plastic regions: contiguous, easily-discoverable regions in which some manipulation of the region improves the target--source trade-off over size-matched control strips elsewhere in the same network. We first characterize a plastic region in ResNet-18 and show that it transfers across target domains, compounds under sequential adaptation, and can be manipulated to recover adaptation capacity at rigid checkpoints. We then analyze plastic-region existence across nine architectures and report observations about network properties that appear to enable or obstruct plastic-region formation.