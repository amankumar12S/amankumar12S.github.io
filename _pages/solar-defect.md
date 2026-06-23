---
layout: page
permalink: /publications/solar-defect/
title: "Interpretable Solar Panel Defect Detection via Fuzzy Rule Extraction from Deep Learning Architectures"
---

### Abstract
The reliability of solar energy infrastructure depends heavily on early detection of panel defects, yet most deep learning models remain opaque, which is a serious concern when operators must trust and act on automated decisions. Motivated by this gap, we propose a novel framework that automatically extracts human-readable fuzzy logic rules from trained convolutional and transformer-based classifiers, providing transparent defect severity predictions without any manual rule engineering. We evaluate our approach on the ELPV benchmark dataset of 2,624 electroluminescence images. Results show that modern hierarchical architectures, namely Swin Transformer and ConvNeXt, achieve substantially higher feature-to-severity correlations (0.78 to 0.82) compared to classical CNNs (0.64), yielding more reliable and consistent fuzzy inference rules. Our best model, Swin-Tiny, achieves 80.96% overall accuracy while simultaneously generating interpretable IF-THEN decision boundaries, directly bridging the gap between high-performing black-box models and the transparency standards demanded by real-world solar farm operations.

### Key Methodologies & Contributions

* **Automated Rule Extraction:** Proposed an end-to-end interpretable framework that automatically extracts fuzzy logic rules from deep learning features, eliminating manual rule engineering while preserving human-readable decision boundaries.
* **Architecture Impact Analysis:** Demonstrated that modern hierarchical transformers (Swin-Tiny) achieve a 28% higher feature-severity correlation than classical ResNet50, yielding significantly more reliable fuzzy inference rules.
* **Graded Confidence Calibration:** Validated that graded fuzzy membership naturally resolves the inherent ambiguity in mild-defect classification, improving confidence calibration over hard softmax boundaries.
* **Optimal Accuracy-Transparency Trade-off:** Achieved 80.96% overall accuracy with the Swin-Tiny architecture while simultaneously generating transparent IF-THEN decision boundaries for real-world solar farm operations.

<a href="https://github.com/HaloMind-Research/Interpretable-Solar-Defect-Detection" target="_blank" style="display: inline-block; padding: 4px 14px; background-color: #21262d; color: #c9d1d9; border: 1px solid #30363d; border-radius: 6px; text-decoration: none; font-size: 14px; transition: 0.2s;">Code & Resources</a>
<hr>

**Status:** Under Review at ICCI, 2026.
**Authors:** **Aman Kumar**, SR. Verma, H. Das, L. Chhetri, G. Sarma
