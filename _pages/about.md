---
layout: about
title: about
permalink: /
subtitle: AI Researcher @ <a href="https://www.isical.ac.in/">ISI Kolkata</a> & <a href="https://www.salford.ac.uk/">Univ. of Salford (UK)</a> | Co-Founder @ <a href="https://halomind-research.github.io/">Halo Mind Research</a> | Computer Vision, Deep Delta Learning & Conformal Prediction | Fall '27 MS/PhD Applicant

profile:
  align: right
  image: prof_pic.jpeg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Sikkim Manipal Institute of Technology</p>
    <p>Sikkim, India</p>

selected_papers: false # Disables the clunky auto-generated list
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # this disables the news section
  scrollable: true 
  limit: 5 

latest_posts:
  enabled: false # this disables the latest posts section
  scrollable: true 
  limit: 3
---

## About Me

I am a computer vision and deep learning researcher focused on a core question: **how do we make neural networks trustworthy when real-world data is scarce, physically degraded, or out-of-distribution?**

Rather than scaling model size on clean benchmarks, I design systems that hold up in constrained, high-stakes environments. My work spans multiple physical and clinical regimes—including **medical imaging and clinical diagnostics, space-weather forecasting, aerospace manufacturing inspection, satellite remote sensing, underwater visual restoration, and degraded ancient script recognition**.

Currently, I serve as a Research Intern in the **CVPR Unit at the Indian Statistical Institute (ISI), Kolkata** under **Prof. Umapada Pal**, and at **The University of Salford, UK** under **Dr. Shivakumara Palaiahnakote**. Alongside these appointments, I lead an undergraduate research team in the Department of AI & Data Science at **SMIT** under **Dr. Palash Ghosal** and co-founded the **[Halo Mind Research Group](https://halomind-research.github.io/)**.

***

## What I Bring to the Table

* **Architecture Design & Efficiency:** Building lightweight, physics-informed vision backbones, Deep Delta Gated networks, and frequency-spatial fusion modules that generalize strongly without massive compute overhead.
* **Learning Under Scarcity:** Engineering physically motivated synthetic data pipelines (WGAN-GP) and self-supervised pretraining strategies (SimCLR) when ground-truth annotations are scarce or expensive to curate.
* **Provable Reliability & Rigor:** Stress-testing models beyond standard accuracy metrics through strict ablation studies, zero-shot cross-domain evaluation, and distribution-free **Conformal Prediction** for guaranteed uncertainty bounds.
* **Cross-Domain Versatility:** Translating foundational computer vision and multimodal representation learning principles across clinical dermatology, orbital space weather, turbid underwater optics, historical epigraphy, and socio-political media.

I am actively applying to **Master's and Direct Ph.D. programs for the Fall 2027 intake**. Feel free to reach out for research collaborations or graduate opportunities at **[ak2281198@gmail.com](mailto:ak2281198@gmail.com)**.

***

## Research Experience

**Research Intern — Computer Vision & Pattern Recognition (CVPR) Unit**  
*Indian Statistical Institute (ISI), Kolkata | Supervisor: Prof. Umapada Pal | Jun 2026 – Present (Hybrid)*
* Co-leading recognition of degraded ancient Ashokan Brahmi inscriptions under extreme real-label scarcity by building a physically motivated **WGAN-GP** synthetic pipeline (20K+ synthetic characters, 150K degraded sequences) and a **SimCLR-pretrained ResNet-34 + BiLSTM-CTC** recognizer (Target: ICDAR 2027).
* Exploring segmentation-free visual restoration of weathered stone inscriptions and establishing the first degradation-graded Character Error Rate (CER) benchmark for ancient Indic scripts.

**Research Intern — Multimodal Vision & Sequence Modeling**  
*The University of Salford, UK | Supervisor: Dr. Shivakumara Palaiahnakote | Jun 2026 – Present (Remote)*
* Modeling unconstrained scene and document text lines as continuous sequences to bypass brittle character-level segmentation bottlenecks.
* Building a multimodal **Vision-Language Model (VLM)** pipeline that jointly reasons over visual caricatures and written captions in Indian editorial cartoons to classify satire, political criticism, and social conflict.

**Research Assistant & Undergraduate Team Lead**  
*Dept. of AI & Data Science, Sikkim Manipal Institute of Technology (SMIT) | Supervisor: Dr. Palash Ghosal | Aug 2024 – Present (On-site)*
* Lead a student research team from problem formulation and ablation design to manuscript preparation across space weather, remote sensing, defect detection, and medical imaging.
* Spearheaded first-author research on zero-shot cross-solar-cycle ionospheric TEC forecasting using **Deep Delta Learning (CNN-DDL)** and split conformal prediction (achieving 2.30 TECU RMSE and 90% empirical storm coverage; *Under Review, WACV 2027*), alongside accepted papers at **ICVGIP 2026** and **WIN 6.0**.

**Co-Founder & Lead AI Researcher**  
*[Halo Mind Research Group](https://halomind-research.github.io/) | Co-founded with L. Chhetri | Jan 2026 – Present (Independent)*
* Co-founded an independent undergraduate research group focused on hardware-efficient vision models, physics-guided restoration, and rigorous uncertainty quantification.
* Group output includes equal-first-author work at **IEEE DSAA 2026** (*SPECTRAFORGE*), **ICVGIP 2026** (*Fuzzy Rule Extraction*), **IEEE SPACE 2026** (*DDV-GNet*), **ICCI 2026**, and the **Halo-Hydra** patent.

***

## Academic Service

* **Technical Peer Reviewer:** Indian Conference on Computer Vision, Graphics and Image Processing (**ICVGIP 2026**); **IEEE GCON 2026**.
* **Conference Presentations (2026):** Short Oral Presentation at **IEEE DSAA 2026** (New Delhi); Oral Presentation at **IEEE SPACE 2026** (Bengaluru); Paper Presentation at **IEEE GCON 2026** (IIT Guwahati).
### Experience

**Research Intern (Computer Vision & Deep Learning)**  
*Indian Statistical Institute (ISI), Kolkata* | Hybrid | Jun 2026 – Present  
* Conducting research in complex spatial analysis and image restoration under the supervision of Prof. Umapada Pal, bypassing traditional segmentation bottlenecks.

**Research Intern (Deep Learning & Sequence Modeling)**  
*The University of Salford, UK* | Remote | Jun 2026 – Present  
* Collaborating internationally on deep learning architectures for text recognition and visual sequence modeling frameworks under the supervision of Dr. Shivakumara Palaiahnakote

**Undergraduate AI Researcher & Team Lead**  
*Sikkim Manipal Institute of Technology (SMIT)* | On-site | Aug 2024 – Present  
* Directing multi-disciplinary deep learning research spanning medical image segmentation, remote sensing, and NLP-driven document analysis.
* Integrating advanced statistical frameworks (Conformal Prediction, Deep Delta Learning) to establish provable reliability and uncertainty quantification in complex physical and visual systems.

<br>

### Core Research Themes
* **Medical Image Analysis & Diagnostics:** Optimizing deep learning pipelines for clinical reliability, including brain tumor classification, domain-equalized spatial-frequency fusion for synthetic dermatology detection, and safe semi-supervised learning for malaria diagnosis.
* **Edge AI & Hardware Optimization:** Engineering low-latency, high-throughput convolutional networks (like DDV-GNet) optimized specifically for constrained IoT devices and space manufacturing hardware.
* **Cyber-Physical Systems (CPS) Security:** Developing robust anomaly rejection frameworks and intrinsic neural firewalls to protect critical industrial infrastructure from False Data Injection Attacks without relying on post-hoc detectors.
* **Uncertainty Quantification & Remote Sensing:** Integrating Marginal Split Conformal Prediction into deep learning architectures to establish rigorous, distribution-free reliability in high-stakes domains like high-resolution urban change detection and ionospheric TEC forecasting.
* **NLP & Computational Linguistics:** Utilizing BERTopic, SBERT, and advanced regression statistics (OLS, Chi-Square) to quantify long-term semantic evolution, socio-emotional shifts, and human behavior within an 89K+ document corpus.
* **Computer Vision & OCR:** Designing complete ETL pipelines and end-to-end architectures leveraging SimCLR and WGAN-GP for degraded ancient Brahmi script recognition.

<br>

### Independent Research Group: [Halo Mind](https://halomind-research.github.io/)
*Hybrid Architectures & Lightweight Optimization | Machine Intelligence & Neural Dynamics*

I am the **Lead ML Systems Engineer** and co-founder of **[Halo Mind](https://halomind-research.github.io/)**, an independent, interdisciplinary research group alongside Lead Research Architect Latchan Chhetri. We bridge continuous physical dynamics with discrete neural computation, engineering hardware-efficient neural mechanisms like sub-quadratic **State Space Models (Mamba)** and **Deep Delta Learning (DDL)** to process high-throughput, volatile data streams. 

Operating outside traditional, heavily funded academic pipelines, our methodology is strictly driven by absolute resource constraints. This environment forces rigorous architectural innovation, exhaustive ablation, and mathematically bounded efficiency. 

> **My Role: Lead ML Systems Engineer**
> * **Focus:** Pipeline Optimization, Conformal Prediction, Applied Frameworks.
> * **Execution:** I translate theoretical architectures into robust, hardware-optimized code. I manage complex spatial data pipelines and integrate advanced statistical frameworks to establish provable reliability and distribution-free uncertainty quantification.

Our applied domains span extreme space weather forecasting (Ionospheric TEC), robust medical image analysis (Brain Tumor & Synthetic Dermatology), and low-resource sequence modeling for ancient epigraphy (Ashokan Brahmi). Prioritizing mathematical truth over brute-force computation, we design self-contained, uncertainty-aware frameworks capable of autonomous anomaly rejection and real-time distribution shift adaptation.

*Visit our Research Group at:* [halomind-research.github.io](https://halomind-research.github.io/)  
*Contact:* `halomind.research.group@gmail.com`
<hr>


