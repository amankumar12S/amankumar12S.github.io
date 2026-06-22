---
layout: page
title: Ionospheric TEC Forecasting
description: CNN-DDL architecture for real-time solar wind drivers and extreme geomagnetic superstorms.
img: /assets/img/1_tec_forecasting.md.png
importance: 1
category: research
---

### Project Overview
Co-authored a CNN-DDL architecture featuring a dynamic gate that conditions real-time solar wind drivers to scale non-linear corrections over physical persistence baselines.

### Key Achievements
* **Zero-Shot Testing:** Evaluated via zero-shot cross-solar-cycle testing (SC25 to SC24), achieving SOTA storm-time error rates (2.30 RMSE) and outperforming deep sequential baselines and IRI-2020.
* **Uncertainty Quantification:** Integrated Marginal Split Conformal Prediction to establish distribution-free uncertainty quantification, providing a mathematically reliable 90% empirical coverage bound during extreme geomagnetic superstorms.

**Technologies Used:** `PyTorch`, `Deep Delta Learning`, `Conformal Prediction`, `CNNs`
