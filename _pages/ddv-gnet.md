---
layout: page
permalink: /publications/ddv-gnet/
title: "DDV-GNet: High-Throughput Defect Detection for Space Manufacturing via Deep Delta Gated Networks"
---

### Abstract
Real-time defect detection for space manufacturing and satellite components’ quality control necessitate processing rates beyond 600 frames per second with high classification accuracy under severe computational constraints. State-of-the-art deep learning models face an inherent problem, where convolutional neural networks like ResNet50 achieve high accuracy but fall short of satisfying real-time constraints for synchronized production lines, while efficient models compromise on detection accuracy. In this paper, we propose a novel hierarchical gated convolutional architecture called Deep Delta Vision Gated Network (DDV-GNet) that resolves the inherent problem of existing models by achieving high accuracy with linear complexity processing and hardware-optimized design. Our proposed model uses gated linear transformations with Deep Delta operators across eight specialized blocks divided into four stages with progressive feature expansion from 64 to 512 dimensions. Our proposed DDV-GNet architecture achieves 95.9% classification accuracy with 1.34M parameters and a throughput of 853 FPS, outperforming standard CNN and Vision Transformer models.

### Key Methodologies & Contributions

* **Deep Delta Gated Architecture:** Designed a novel architecture (DDV-GNet) using Deep Delta operators and Spatial Gating Units (SGUs) within a hierarchical structure. This effectively manages spatial context while maintaining linear computational complexity.
* **Hardware-Optimized Throughput:** Achieved an ultra-high inference speed of 853 Frames Per Second (FPS) on standard hardware, far exceeding the 600 FPS threshold required for synchronized space manufacturing production lines.
* **Linear Complexity Processing:** Bypassed the quadratic complexity limitations of Vision Transformers and the high parameter counts of deep CNNs, delivering a lightweight model (1.34M parameters) optimized for edge deployment.
* **SOTA Efficiency-Accuracy Trade-off:** Demonstrated 95.9% classification accuracy on a highly imbalanced space manufacturing defect dataset, outperforming heavier models like ResNet-50 and standard Swin Transformers in both speed and efficiency.

<a href="https://github.com/HaloMind-Research/DDV-GNet-Space" target="_blank" style="display: inline-block; padding: 4px 14px; background-color: #21262d; color: #c9d1d9; border: 1px solid #30363d; border-radius: 6px; text-decoration: none; font-size: 14px; transition: 0.2s;">Code & Resources</a>


<hr>

**Status:** Accepted for Oral Presentation at IEEE SPACE, 2026.
**Authors:** L. Chhetri, A. Kumar
