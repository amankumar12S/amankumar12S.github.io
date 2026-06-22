---
layout: page
permalink: /publications/malaria-ssl/
title: "Beyond Limited Labels: Safe Semi-Supervised Learning for Malaria Diagnosis"
---

### Abstract
Deploying AI-based diagnostic tools in resource-constrained healthcare settings remains a critical challenge, where the scarcity of annotated medical images limits the viability of fully supervised approaches. Semi-supervised learning (SSL) offers a promising path forward, yet existing SSL methods trade deployment safety for annotation efficiency relying on fixed confidence thresholds that produce dangerously overconfident errors in clinical settings where expert oversight is minimal. We address this gap with an uncertainty-guided SSL framework that integrates Monte Carlo dropout-based epistemic uncertainty estimation with adaptive confidence weighting, enabling safe pseudo-label filtering without sacrificing learning efficiency. Evaluated on malaria cell classification under low-resource conditions (20% labeled data), our method achieves a statistically significant 29.2% reduction in silent failure rate over the strongest SSL baseline, while maintaining comparable diagnostic accuracy with 80% fewer labeled samples. Unlike standard SSL methods whose safety degrades sharply with threshold relaxation, our approach maintains consistent robustness across all operating points—a property essential for real-world deployment across diverse clinical environments.

### Key Methodologies & Contributions

* **Uncertainty-Guided SSL:** Engineered a framework integrating Monte Carlo dropout to estimate epistemic uncertainty, allowing the model to adaptively filter out dangerously overconfident pseudo-labels during training.
* **Reduction of Silent Failures:** Mathematically validated a 29.2% reduction in silent failure rates (from 2.50% to 1.77%) compared to the strongest SSL baselines, prioritizing clinical safety over raw accuracy inflation.
* **Extreme Low-Resource Efficiency:** Maintained diagnostic accuracy while operating on an extreme low-resource constraint of only 20% labeled data (an 80% reduction in annotation requirements).
* **Threshold Robustness:** Demonstrated that the architecture maintains consistent safety metrics across variable operating points, unlike standard fixed-threshold SSL methods that degrade upon relaxation.

### Code & Resources
[**Official PyTorch Implementation (GitHub)**](#)  
*Repository goes live soon. Please contact me via email for early access to the codebase.*

<hr>

**Status:** Under Review at IEEE DSAA, 2026.  
**Authors:** L. Chhetri, Aman Kumar
