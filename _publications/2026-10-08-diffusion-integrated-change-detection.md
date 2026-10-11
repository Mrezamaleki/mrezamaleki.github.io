---
title: "Quickest Change Detection with Diffusion-Integrated Scores"
collection: publications
year: 2026
category: preprints
excerpt: "DI-SCUSUM: training-free sequential change detection. Joint work with Augusta University and Princeton University; equal contribution with Arman Adibi."
venue: "arXiv preprint · arXiv:2610.12200"
paperurl: "https://arxiv.org/pdf/2610.12200"
citation: 'Arman Adibi, Mohammadreza Maleki, Sanjeev Kulkarni, and H. Vincent Poor. "Quickest Change Detection with Diffusion-Integrated Scores." arXiv:2610.12200, 2026.'
---

**Authors:** Arman Adibi, Mohammadreza Maleki, Sanjeev Kulkarni, and H. Vincent Poor.  
**Equal contribution:** Arman Adibi and Mohammadreza Maleki.  
**Affiliations:** Augusta University (Arman Adibi), Toronto Metropolitan University (Mohammadreza Maleki), and Princeton University (Sanjeev Kulkarni and H. Vincent Poor).  
**Status:** arXiv preprint, posted October 8, 2026.

## Summary

Detecting a distribution change from a stream requires evidence that can be computed from available data. Classical CUSUM uses a likelihood ratio, which is generally unavailable when only finite reference samples are given. DI-SCUSUM constructs Gaussian-smoothed empirical models and evaluates their Hyvärinen scores in closed form, without training a score network. It combines evidence across diffusion scales through importance weighting and accumulates it using a CUSUM recursion.

Under the fixed empirical-model assumptions, the mean increments are linked to directed Kullback–Leibler divergences. The analysis establishes exponential false-alarm scaling and a first-order detection-delay bound under the stated conditions. These guarantees concern the empirical plug-in model rather than arbitrary unknown population distributions.

Experiments include an anisotropic Gaussian simulation, MNIST, and Oxford-IIIT Pet. At comparable false-alarm levels, the evaluated method reduces detection delay relative to single-scale score-based CUSUM; the approximately 91% reduction is specific to the calibrated Gaussian experiment.

[Download the paper (PDF)](https://arxiv.org/pdf/2610.12200) · [arXiv abstract](https://arxiv.org/abs/2610.12200) · [Read online](https://arxiv.org/html/2610.12200v1)
