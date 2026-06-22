---
layout: page
permalink: /publications/brain-tumor/
title: "Optimizing Deep Learning for Brain Tumor Classification: A Comparative Ablation Study of Preprocessing and Augmentation Strategies"
---

### Abstract
This work fills an important gap in the literature on brain tumor classification, where the overlap of patients between the training and test datasets has been artificially reducing reported accuracy. We have performed eight controlled experiments on 3,064 T1-weighted MRI images from 233 patients with strict patient-level splitting. Our ablation study compared skull stripping, CLAHE image enhancement, and bilateral filtering with geometric augmentation using VGG16 transfer learning. Our results show that skull stripping and CLAHE have a detrimental effect on accuracy when combined with augmentation (accuracy of 82 percent), while bilateral filtering with augmentation has an accuracy of 93.86 percent and AUC of 0.991 ($p=0.05$ compared to augmentation alone). We propose a new “destructive vs. constructive” taxonomy for image preprocessing, which indicates that image preprocessing techniques that preserve anatomical context are more effective than those that remove spatial information.

### Key Methodologies & Contributions

* **Exposing the Skull Boundary Paradox:** Demonstrated that “destructive” preprocessing methods (like skull-stripping) eliminate essential high-contrast spatial anchors, causing a 10-point performance degradation when combined with geometric augmentation.
* **Systematic Ablation Framework:** Executed eight highly controlled experiments isolating the individual and interaction effects of specific preprocessing techniques (CLAHE, Bilateral Filtering) and augmentation on model performance.
* **Constructive Preprocessing Paradigm:** Validated that edge-aware bilateral filtering acts as a “constructive” preprocessing step, suppressing noise without blurring anatomical boundaries, achieving an optimal 93.86% accuracy.
* **Algorithmic Patient-Level Splitting:** Implemented strict regex-based patient ID grouping and perceptual hash checking to guarantee zero patient overlap between splits, providing realistic performance metrics over inflated baseline claims.

### Code & Resources
[**Official Jupyter/PyTorch Pipeline (GitHub)**](#)  
*Repository goes live soon. Please contact me via email for early access to the codebase.*

<hr>

**Status:** Accepted at IEEE GCON, 2026.  
**Authors:** L. Chhetri, **Aman Kumar**
