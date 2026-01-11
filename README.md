# SWFN: A Bio-Inspired Spiking-Wavelet Network for Compressed 360-Degree Video Enhancement


This repository is the official implementation of the paper: **"SWFN: A Bio-Inspired Spiking-Wavelet Network for Compressed 360-Degree Video Enhancement"**.



## 🚀 Overview

**SWFN** is a neuromorphic-inspired architecture designed for enhancing compressed 360-degree videos. Guided by the primate **Magnocellular-Parvocellular (M-P) dual-stream theory**, the network effectively mitigates geometric distortions (from Equirectangular Projection) and restores high-frequency details.

### Key Features:
* **Bio-Inspired M-P Pathways:** Decouples global structural modeling (M-pathway) from fine-grained texture refinement (P-pathway).
* **Transformer-SNN Block (TSB):** Captures global dependencies using energy-efficient sparse spiking dynamics.
* **Residual Wavelet Fusion Block (RWFB):** Emulates hierarchical frequency tuning (V1, V2, V4) to resolve high-frequency details.
* **SOTA Efficiency:** Achieves state-of-the-art performance on 4K/8K datasets with only **1.48M parameters** and **2.32 GFLOPs**.


## 🖼️ Model Architecture


*Figure: The overall architecture of the proposed SWFN framework. It mimics the functional division of the primate visual system using a dual-stream design.*
![Uploading model.jpg…]()

> **Note:** For a detailed view of the modules (TSB, RWFB), please refer to the paper.

