---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /project
---
## [ReflCtrl: Controlling LLM Reflection Efficiently via Representation Engineering](https://lilywenglab.github.io/ReflCtrl/)
<span style="font-size:13px margin-top=13px margin-bottom=13px"> *Conference on Language Modeling (COLM 2026)*; NeurIPS 2025 Mechanistic Interpretability Workshop (Spotlight) </span>

Large reasoning models often reflect on their answers more than they need to, which wastes reasoning tokens. In this project, we find a reflection direction in the model's latent space: we split the reasoning trace into steps, mark reflection steps by keywords, and take the mean difference between the hidden representations of reflection and non-reflection steps. We also find that activations along this direction are highly predictive of answer correctness, which suggests that self-reflection is driven by the model's internal uncertainty. ReflCtrl injects this direction only at the start of each new reasoning step. This stepwise steering gives fine-grained control over how often the model reflects without hurting generation quality. Suppressing unnecessary reflections reduces total reasoning tokens by up to 43.2% while preserving accuracy. [[Paper]](https://arxiv.org/abs/2512.13979) [[Code]](https://github.com/Trustworthy-ML-Lab/ReflCtrl)
## [VLG-CBM: Training Concept Bottleneck Models with Vision-Language Guidance](https://lilywenglab.github.io/VLG-CBM/)
<span style="font-size:13px margin-top=13px margin-bottom=13px"> *Conference on Neural Information Processing Systems (NeurIPS 2024)* </span>

Concept bottleneck models (CBMs) make predictions through human-understandable concepts, but existing CBMs suffer from inaccurate concept predictions and information leakage. VLG-CBM uses open-domain grounded object detectors (Grounding-DINO) together with LLMs to build visually grounded concept annotations, which makes concept predictions more faithful. We also propose a new metric, the Number of Effective Concepts (NEC), to control information leakage and improve interpretability. Across five standard benchmarks, VLG-CBM outperforms existing methods by at least 4.27% and up to 51.09% in accuracy at NEC=5 (ANEC-5), and by at least 0.45% and up to 29.78% in average accuracy (ANEC-avg). [[Paper]](https://arxiv.org/abs/2408.01432) [[Code]](https://github.com/Trustworthy-ML-Lab/VLG-CBM)
## [Provably robust conformal prediction with Improved efficiency](https://lilywenglab.github.io/Provably-Robust-Conformal-Prediction/)
<span style="font-size:13px margin-top=13px margin-bottom=13px"> *The Twelfth International Conference on Learning Representations (ICLR 2024)* </span>

Conformal prediction is a method that provides prediction sets with guaranteed coverage. However, this guarantee fails at adversarial attacks. In this project, we propose a novel framework called RSCP+ which provides guaranteed robustness against adversarial examples. Besides, we design two methods to boost the efficiency of conformal prediction (reduce the size of prediction sets). Our methods achieve 4.36x, 5.46x and 16.9x efficiency boost on CIFAR10, CIFAR100 and ImageNet, respectively.
## Failure probability estimation via Bayesian neural networks
Neural networks could be used as a PDE solver with much lower cost comparing to traditional finite elements methods, which makes them to be a possible kind of model when cheap approximation of PDE solution is needed. In this project I applied Bayesian neural networks as a PDE solution approximator in failure probability estimation. Details could be found in my [B.S. thesis](/files/finalThesis.pdf).
