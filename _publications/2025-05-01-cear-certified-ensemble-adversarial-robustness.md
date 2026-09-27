---
title: "CEAR: Certified Ensemble Adversarial Robustness in DNNs"
collection: publications
year: 2026
category: conferences
excerpt: "An ensemble method combining noise-trained networks, voting rules, and randomized-smoothing certificates."
venue: "Canadian AI 2026 · PMLR 318:624–635"
paperurl: "https://raw.githubusercontent.com/mlresearch/v318/main/assets/sadig26a/sadig26a.pdf"
citation: 'Daniel Sadig, Mohammadreza Maleki, Hamed Karimi, and Reza Samavi. "CEAR: Certified Ensemble Adversarial Robustness in DNNs." Proceedings of the 39th Canadian Conference on Artificial Intelligence, PMLR 318:624–635, 2026.'
---

## Summary

Adversarial perturbations can change a deep network's predictions, while empirical defenses alone do not establish a formal guarantee. CEAR studies whether combining diverse networks can improve both observed resistance to attacks and *certified* robustness. Its ensemble members are trained with different Gaussian-noise levels and temperatures. Their noisy outputs are combined through two voting mechanisms, and randomized smoothing is extended to produce robustness certificates for the ensemble.

The evaluation covers MNIST, CIFAR-10, and Tiny ImageNet. Across the reported comparisons, CEAR improves average certified accuracy and certified radius while reducing attack transferability relative to the evaluated baselines. The paper's contribution is the combination of ensemble diversity, voting, and a formal smoothing-based certificate; empirical attack performance and certified guarantees are evaluated separately.

[Download the published paper (PDF)](https://raw.githubusercontent.com/mlresearch/v318/main/assets/sadig26a/sadig26a.pdf) · [Proceedings page](https://proceedings.mlr.press/v318/sadig26a.html)
