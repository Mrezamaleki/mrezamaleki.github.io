---
title: "Certified Robustness via Sparse Second-Order Cone Relaxations"
collection: publications
year: 2026
category: preprints
excerpt: "Sparse SOCP relaxations and a class-wise verification cascade for neural-network robustness. Joint work with Johns Hopkins University and Augusta University."
venue: "arXiv preprint · arXiv:2610.16016"
paperurl: "https://arxiv.org/pdf/2610.16016"
citation: 'Mohammadreza Maleki, Daniel Sadig, Rushendra Sidibomma, Mahyar Fazlyab, Arman Adibi, and Reza Samavi. "Certified Robustness via Sparse Second-Order Cone Relaxations." arXiv:2610.16016, 2026.'
---

**Authors:** Mohammadreza Maleki, Daniel Sadig, Rushendra Sidibomma, Mahyar Fazlyab, Arman Adibi, and Reza Samavi.  
**Affiliations:** Toronto Metropolitan University (Mohammadreza Maleki, Daniel Sadig, and Reza Samavi); University of Minnesota Twin Cities (Rushendra Sidibomma); Johns Hopkins University (Mahyar Fazlyab); Augusta University (Arman Adibi); Vector Institute (Reza Samavi).  
**Status:** arXiv preprint, submitted October 12, 2026.

## Summary

Certifying a neural network requires bounding its predictions over an entire perturbation set. Linear programming relaxations can be inexpensive but conservative, while semidefinite programming relaxations capture interactions at greater computational cost. This paper develops sparse second-order cone programming (SOCP) relaxations as an intermediate approach.

The construction combines convex-hull ReLU constraints, selective McCormick lifting over certified bounds, and local second-order constraints derived from 2 × 2 positive-semidefinite principal submatrices. Adding selected constraints tightens the bounds monotonically, allowing control over the balance between certificate quality and computation.

The paper also introduces class-optimized robust evaluation (CORE), which escalates verification only for target classes unresolved by cheaper methods. Experiments cover fully connected and convolutional networks on MNIST and CIFAR-10. In the reported fully connected MNIST benchmark, CORE variants match the evaluated SDP verifier's certified robust accuracy while reducing average verification time by up to 86.30%. The empirical comparisons depend on the tested networks, perturbation levels, and solver configurations.

[Download the paper (PDF)](https://arxiv.org/pdf/2610.16016) · [arXiv abstract](https://arxiv.org/abs/2610.16016) · [Read online](https://arxiv.org/html/2610.16016v1)
