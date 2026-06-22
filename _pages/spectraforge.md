---
layout: page
permalink: /publications/spectraforge/
title: "SPECTRAFORGE: Domain-Equalized Frequency-Spatial Fusion for Synthetic Dermatology Detection"
---

### Abstract
Spatial deepfake detectors in medical imaging typically exploit dataset-level flaws, such as JPEG compression history, edge statistics, and color biases, rather than identifying authentic generative footprints. Consequently, these models suffer severe performance degradation when evaluated on images from unseen generators. To address this vulnerability, we introduce SPECTRAFORGE, a two-stream CNN framework that explicitly decouples the detection task. A Gaussian-bottlenecked spatial stream isolates macroscopic lesion morphology, while a parallel FFT-magnitude stream maps the periodic upsampling artifacts inherently produced by diffusion decoders. Prior to training, our Extreme Equalizer preprocessing pipeline systematically eliminates dataset spatial leakage. Evaluated on a strictly controlled 2,000-image forensic cohort, SPECTRAFORGE yields an AUC of $0.9971\pm0.0016$ and a Precision of $0.9931\pm0.0056$ across three-seed cross-validation, outperforming the EfficientNet-B0 baseline across all metrics. Crucially, under cross-checkpoint out-of-distribution (OOD) stress testing, EfficientNet-B0 suffers catastrophic domain collapse (AUC dropping to 0.5494), whereas SPECTRAFORGE maintains robust detection capabilities (AUC 0.9277). This +0.3783 AUC margin demonstrates strong frequency-domain generalization, while Grad-CAM and t-SNE projections on the OOD data visually confirm the successful decoupling of clinical anatomy from synthetic artifacts.

### Key Methodologies & Contributions

* **Extreme Equalizer:** Designed an in-memory pre-processing pipeline crafted to eliminate dataset-level confounders such as JPEG compression, color bias, and border effects before feature extraction.
* **Dual-Stream Architecture:** Engineered a dual-stream ResNet-50 architecture that physically splits spatial and spectral information into different streams.
* **Macroscopic and Spectral Decoupling:** Implemented a Gaussian blur bottleneck to force the spatial stream to extract macroscopic lesion characteristics, while the frequency stream extracts the frequency spectrum of log-magnitude FFT analysis.
* **Out-of-Distribution Generalization:** Conducted a methodological evaluation using out-of-distribution data from an unseen generator, demonstrating a +0.3783 AUC improvement through frequency-domain processing over current single-stream architectures.

### Code & Resources
[**Official PyTorch Pipeline (GitHub)**](#)  
*Repository goes live soon. Please contact me via email for early access to the codebase.*

<hr>

**Status:** Under Review at IEEE DSAA, 2026.
**Authors:** **Aman Kumar**, L. Chhetri, D. Das
