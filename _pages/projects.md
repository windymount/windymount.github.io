---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /project
---
## ReflCtrl: Controlling LLM Reflection Efficiently via Representation Engineering
<span style="font-size:13px margin-top=13px margin-bottom=13px"> *Conference on Language Modeling (COLM 2026)*; NeurIPS 2025 Mechanistic Interpretability Workshop (Spotlight) </span>

Large reasoning models often reflect on their answers more often than they need to, which wastes reasoning tokens. In this project, we develop stepwise representation steering to control how often the model reflects. This saves up to 33.6% of reasoning tokens while largely preserving accuracy in the settings we evaluated.
## VLG-CBM: Training Concept Bottleneck Models with Vision-Language Guidance
<span style="font-size:13px margin-top=13px margin-bottom=13px"> *Conference on Neural Information Processing Systems (NeurIPS 2024)* </span>

Concept bottleneck models make predictions through human-understandable concepts, but the learned concepts are not always faithful. We propose vision-language guidance to train more faithful concept bottleneck models, and the Number of Effective Concepts (NEC) metric to control information leakage. The method improves concept faithfulness across five benchmarks.
## [Provably robust conformal prediction with Improved efficiency](https://lilywenglab.github.io/Provably-Robust-Conformal-Prediction/)
<span style="font-size:13px margin-top=13px margin-bottom=13px"> *The Twelfth International Conference on Learning Representations (ICLR 2024)* </span>

Conformal prediction is a method that provides prediction sets with guaranteed coverage. However, this guarantee fails at adversarial attacks. In this project, we propose a novel framework called RSCP+ which provides guaranteed robustness against adversarial examples. Besides, we design two methods to boost the efficiency of conformal prediction (reduce the size of prediction sets). Our methods achieve 4.36x, 5.46x and 16.9x efficiency boost on CIFAR10, CIFAR100 and ImageNet, respectively.
## Failure probability estimation via Bayesian neural networks
Neural networks could be used as a PDE solver with much lower cost comparing to traditional finite elements methods, which makes them to be a possible kind of model when cheap approximation of PDE solution is needed. In this project I applied Bayesian neural networks as a PDE solution approximator in failure probability estimation. Details could be found in my [B.S. thesis](/files/finalThesis.pdf).
