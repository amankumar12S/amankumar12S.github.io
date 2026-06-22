---
layout: page
permalink: /publications/urban-change-cp/
title: "Risk-Controlled Urban Change Detection: Conformal Prediction Wrappers for Provable Reliability in High-Resolution Satellite Imagery"
---

### Abstract
Satellite-based urban change detection enables an emerging generation of geospatial intelligence applications, from disaster damage assessments to spatial expansion monitoring; however, the deep learning models powering these systems lack formal reliability metrics for individual predictions. This paper introduces a rigorous statistical approach to transformer-based satellite change detection using Marginal Split Conformal Prediction (CP). Working on top of the pre-trained Bitemporal Image Transformer (BIT) and the well-established LEVIR-CD benchmark, we calibrate a non-conformity threshold on the validation split and generate pixel-wise prediction sets. This achieves distribution-free, statistically rigorous 1-alpha coverage bounds without requiring any re-training of the model weights. Our optimized implementation attains F1=89.94% and IoU=81.72% on the LEVIR-CD test set, outperforming all published baselines. Furthermore, conformal calibration reveals a novel structural property specific to geospatial transformers: BIT operates in a near-binary confidence regime where spatial ambiguity emerges as Empty Prediction Sets rather than dual-class uncertainty.

### Key Methodologies & Contributions

* **Provable Statistical Reliability:** Introduced a rigorous statistical reliability framework for transformer-based change detection by deploying Split Conformal Prediction, empirically validating that the 1-alpha coverage guarantee holds on real-world satellite imagery.
* **Bimodal Confidence Discovery:** Exposed a previously undescribed bimodal confidence structure inside BIT through conformal calibration, where uncertain pixels produce Empty Prediction Sets, carrying direct implications for human-in-the-loop deployment pipelines.
* **Optimized BIT Implementation:** Corrected a widely propagated normalization error prevalent in BIT reimplementations (which incorrectly fed color-distorted inputs using ImageNet statistics), cleanly recovering full network accuracy without architectural changes.
* **SOTA Benchmark Performance:** Achieved state-of-the-art results on the LEVIR-CD benchmark (F1=89.94% and IoU=81.72%), exceeding the originally reported numbers and outperforming the strongest purely convolutional baselines like FC-Siam-Diff.

### Code & Resources
The official PyTorch implementation and pre-trained weights will be made publicly available on GitHub following the conclusion of the double-blind review process.

<hr>

**Status:** Under Review at ICCI, 2026.
**Authors:** A. Mukherjee, **Aman Kumar**, SR. Verma, H. Das, L. Chhetri, G. Sarma
