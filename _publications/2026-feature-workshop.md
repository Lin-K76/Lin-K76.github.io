---
title: "The feature-space alignment hypothesis for neural network sparsity"
collection: publications
category: conferences
permalink: /publication/2026-feature-workshop
excerpt: ''
date: 2026-04-01
isconf: true
venue: 'ICLR'
workshop: 'Sci4DL'
fullvenue: 'The 2nd Workshop on Scientific Methods for Understanding Deep Learning at the 14th International Conference on Learning Representations (ICLR 2026 Workshop Sci4DL)'
selected: true
paperurl: 'https://openreview.net/forum?id=tZszYSchmV'
authors: '<strong>Linghao Kong</strong>, Micah Adler, & Nir N. Shavit'
citation: '<strong>Kong, L.</strong>, Adler, M., & Shavit, N. N. (2026, April). The feature-space alignment hypothesis for neural network sparsity [Poster presentation]. The 2nd Workshop on Scientific Methods for Understanding Deep Learning at the 14th International Conference on Learning Representations (ICLR 2026 Workshop Sci4DL), Rio de Janeiro, RJ, Brazil'
---

Why does something as simple as magnitude pruning succeed even when most weights are removed, and why does it eventually fail? We study this in a controlled setting where the network's feature-space weights are explicit. We find that accuracy collapse under standard pruning coincides with divergence of this feature-space representation from its dense counterpart. We then introduce an optimization oracle that selects sparse weight matrices independent of the original that explicitly preserve the latent feature structure. Under identical retraining budgets, the oracle recovers performance at sparsities where standard pruning degrades across both logic and vision tasks. This suggests that sparsification limits can arise from misalignment between weight-space and feature-level structure, and points to feature-aware criteria as a path toward improved pruning methods.