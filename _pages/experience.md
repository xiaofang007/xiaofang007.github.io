---
layout: archive
title: "Professional Experience"
permalink: /experience/
redirect_from:
  - /experience
---

# Research


### **Boosting Convolution with Efficient MLP-Permutation for Volumetric Medical Image Segmentation**
*Research Intern in HKUST* <br>
Sep. 2022 - Current | Advisor: [Prof. Hao CHEN](https://cse.hkust.edu.hk/~jhc/) <br>
Submitted to AAAI2024 [paper](https://arxiv.org/abs/2303.13111)
*	Analyzed the current limitations of volumetric image segmentation: 1) thick slice scanning  2) computationally expensive 
*	Proposed a **P**ermutable **H**ybrid **Net**work (PHNet) that fuses 2D CNN, 3D CNN, and MLP to enhance the efficiency and efficacy of segmentation by utilizing CNN to learn local features while replacing the heavy self-attention mechanism in Transformers with dimension permutations of feature maps so that voxels within the same axis across all channels are grouped to train using MLP to capture long-range dependencies.
* Compared with state-of-the-art CNN-based, Transformer-based, and MLP-based methods. Notably, PHNet surpassed the winner of [COVID-19-20 challenge](https://covid-segmentation.grand-challenge.org/evaluation/post-challenge-phase/leaderboard/).


### **Improve Medical Image Segmentation models with boundary detection operators**
*Research Intern in HKUST* <br>
Nov. 2022 - May. 2023 | Advisor: [Prof. Hao CHEN](https://cse.hkust.edu.hk/~jhc/) <br>
IPMI2023 accepted [paper](https://arxiv.org/abs/2305.00678) [code](https://github.com/xiaofang007/CTO)
*	Assisted in running experiments by validating CTO-Net on two public datasets and conducting data visualization.
* Published the official implementation on Github building upon the [MedISeg](https://github.com/hust-linyi/MedISeg) framework (200+ stars), and further contributed to the codebase of this framework

### **Automatic segmentation of fat metaplasia on sacroiliac joint using deep learning**
*Research Intern in HKUST* <br>
Mar. 2022 - Oct. 2022 | Advisor: [Prof. Hao CHEN](https://cse.hkust.edu.hk/~jhc/) <br>
Accepted by Insights into Imaging [paper](https://link.springer.com/article/10.1186/s13244-024-01659-y) [code](https://github.com/hust-linyi/2.5D-AttentionUNet)
* Collaborated with MD students from The Southern Medical University to finish data cleaning, including examining the labeling of patients and sifting samples with varying degrees of fat deposits to create the dataset.
* Proposed a novel 2.5D-AttentionUnet for segmentation that features a UNet-like encoder-decoder structure,CNN-based attention modules, and a mixed pooling module in the bottleneck layer.
* Compared with state-of-the-art methods like UNet, ResUNet, and UNETR.

# Internship
### **Data asset management consultancy for Mindray data platform**
*Digital Consultant* <br>
Jul. 2023 - Sep. 2023 | Deloitte Consulting (Guangzhou) Limited
* Involved in designing master data governance solution for Mindray data platform.
* Validated the classifications, definitions, formulas, and ownership of all master data metrics with clients.
* Designed a program using Excel VBA to streamline the extraction of all metrics and dimensions from worksheets.


