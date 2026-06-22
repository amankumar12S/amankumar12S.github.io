---
layout: page
permalink: /publications/tec-forecasting/
title: "Ionospheric TEC Forecasting via Deep Delta Learning and Conformal Prediction"
---

### Abstract
Accurate forecasting of ionospheric Total Electron Content (TEC) during severe geomagnetic storms is critical for maintaining the integrity of Global Navigation Satellite System (GNSS) services and satellite communication links. Existing deep learning approaches suffer from chronological overfitting, where models implicitly memorize epoch-specific plasma climatology rather than learning universal physical perturbation mechanisms. We present the Convolutional Neural Network with Deep Delta Learning (CNN-DDL), a novel architecture that addresses this limitation through a physics-informed residual decomposition strategy. Rather than predicting absolute TEC, the model learns to forecast the perturbation delta over a physical persistence baseline, modulated by a dynamic beta-gate that scales corrections based on the geomagnetic state. Trained exclusively on the extreme May 2024 superstorm (Solar Cycle 25), the model was evaluated in a zero-shot manner on historical benchmark events from Solar Cycle 24. CNN-DDL achieves storm-time root mean square errors of 2.30, 3.92, and 1.10 TECU on May 2024, March 2015, and September 2017 respectively, consistently outperforming standard sequential and transformer baselines.

### Key Methodologies & Contributions

* **Zero-Shot Cross-Solar Cycle Generalization:** Proved that the CNN-DDL framework captures universal perturbation physics by training exclusively on Solar Cycle 25 data and successfully generalizing to unseen Solar Cycle 24 storms without any fine-tuning or parameter updates.
* **Dynamic beta-Gate:** Engineered a learnable gate that conditions correction magnitudes on real-time solar wind drivers, effectively amplifying corrections during active storm conditions ($Kp \ge 5$) while suppressing noise during quiet periods.
* **Conformal Prediction Integration:** Utilized split conformal prediction to provide distribution-free uncertainty quantification, achieving a guaranteed 90% in-distribution coverage and a robust 92.65% empirical coverage on out-of-distribution cross-cycle events.
* **Spatial Error Decomposition:** Demonstrated that prediction accuracy aligns with known plasma bubble physics, achieving the highest precision in polar regions (0.57 TECU) while accurately capturing complex storm-time plasma irregularities near the geomagnetic equator.

### Code & Resources
[**Official PyTorch Implementation (GitHub)**](#)  
*Repository goes live soon. Please contact me via email for early access to the codebase.*

<hr>

**Status:** Under Review at Journal: Advances in Space Research (SCIE Q2), 2026.
**Authors:** **Aman Kumar**, L. Chhetri,P.Ghosal
