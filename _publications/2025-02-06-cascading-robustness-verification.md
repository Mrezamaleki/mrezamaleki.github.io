---
title: "Cascading Robustness Verification: Toward Efficient Model-Agnostic Certification"
collection: publications
year: 2026
category: conferences
excerpt: "A staged, model-agnostic verification framework that applies stronger certifiers only when cheaper methods cannot certify an input."
venue: "IEEE SaTML 2026"
paperurl: "https://arxiv.org/pdf/2602.04236"
citation: 'Mohammadreza Maleki, Rushendra Sidibomma, Arman Adibi, and Reza Samavi. "Cascading Robustness Verification: Toward Efficient Model-Agnostic Certification." IEEE Conference on Secure and Trustworthy Machine Learning (SaTML), 2026.'
---

## Summary

An incomplete neural-network verifier can fail to certify an input that is actually robust because its relaxation is too loose. Its reported certified accuracy therefore depends partly on the chosen verification method. This paper introduces *Cascading Robustness Verification* (CRV), which combines several sound verifiers without tying the result to how the network was trained. For each input, CRV starts with an inexpensive verifier and stops as soon as one method certifies robustness. Only unresolved inputs are passed to more costly methods.

The paper also develops *stepwise relaxation*: progressively tighter constraint sets within a verifier, with early exit after a successful certificate. This preserves the soundness of individual certificates while reducing unnecessary computation. Experiments with LP- and SDP-based methods show that the cascade can recover robust inputs missed by a single incomplete verifier and reduce verification time relative to applying the strongest method to every input. The paper distinguishes these gains in *certified* robustness from any change in the underlying model.

[Download the paper (PDF)](https://arxiv.org/pdf/2602.04236) · [Preprint and abstract](https://arxiv.org/abs/2602.04236)
