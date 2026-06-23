---
layout: page
permalink: /publications/ddv-mamba/
title: "Deep Delta Vision Mamba: A Lightweight State Space Architecture with Deep Delta Learning for Efficient Remote Sensing"
---

### Abstract
Real-time land cover classification on autonomous satellites requires models that are accurate, lightweight, and computationally efficient within strict hardware constraints. Vision Transformers and convolutional neural networks reach state-of-the-art results on benchmarks, but their quadratic self-attention cost and large numbers of parameters make them unsuitable for edge computing. We propose Deep Delta Vision Mamba (DDV-Mamba), a hierarchical model consisting of two principled components. First, we extend the Deep Delta operator from one-dimensional to two-dimensional feature maps: each DDV block chooses to erase redundant spectral data along a learned projection direction and write discriminative data through an SSM-gated pathway. Second, an SSM-inspired gated aggregation module substitutes self-attention with depthwise convolution and channel-wise gating, restoring global context at linear rather than quadratic complexity. Assessed on EuroSAT, DDV-Mamba reaches 96.95% accuracy with 5.08 M parameters at 510 frames per second.

### Key Methodologies & Contributions

* **Deployment Efficiency Score (DES):** Introduced a novel multi-criteria metric (DES = Accuracy × FPS / Parameters) to quantify hardware-centric edge deployment suitability, balancing accuracy, throughput, and memory footprint.
* **2D Deep Delta Operator:** Successfully transitioned the Deep Delta framework to 2D spatial feature maps, enabling active, content-addressable routing that erases redundant spectral data and writes discriminative features.
* **Unmatched Edge Performance:** Achieved a DES of 9733.2 on the EuroSAT dataset, establishing a 13.1x relative deployment improvement over ResNet50 and an incredible 166.9x improvement over ViT-B/16.
* **Architectural Necessity (Ablation):** Conducted rigorous ablation studies proving the structural necessity of the Deep Delta block; removing it completely abolishes residual connections and causes a catastrophic 58.38 percentage-point accuracy collapse.

<a href="https://github.com/HaloMind-Research/DDV-Mamba_for_Efficient_Remote_Sensing" target="_blank" style="display: inline-block; padding: 4px 14px; background-color: #21262d; color: #c9d1d9; border: 1px solid #30363d; border-radius: 6px; text-decoration: none; font-size: 14px; transition: 0.2s;">Code & Resources</a>

<hr>

**Status:** Accepted at IEEE CONECCT, 2026.  
**Authors:** L. Chhetri, Aman Kumar
