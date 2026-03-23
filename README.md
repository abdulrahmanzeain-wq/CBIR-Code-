# CBIR-Code-
Causality-enhanced multiresolution residual learning framework for image retrieval. Combines causal feature refinement with hierarchical representations and Fast Osprey Optimization to improve robustness, efficiency, and retrieval accuracy across diverse datasets.
# CBIR Causality-Enhanced Framework

This repository contains the implementation of the paper:

"A Causality-Enhanced Multiresolution Residual Learning Framework for Image Retrieval with Fast Osprey Optimization"

## Authors
Abdulrahman Yousif Zeain, Abdullahi Abdu Ibrahim  
Altınbaş University, Istanbul, Turkey

## Overview
This work proposes a novel content-based image retrieval (CBIR) framework that integrates:

- Multiresolution feature extraction using ResNet-50
- Causal Variational Autoencoder (CausalVAE) for latent representation learning
- Fast Osprey Optimization Algorithm (FOOA) for feature selection

The framework enhances semantic consistency, reduces redundancy, and improves retrieval accuracy and efficiency.

## Methodology
The proposed pipeline consists of:
1. Multiscale feature extraction using ResNet-50
2. Latent representation learning via CausalVAE
3. Feature optimization using Fast Osprey Optimization
4. Similarity computation using:
   - Structural Similarity Index (SSIM)
   - Histogram Intersection

## Datasets
The experiments are conducted on publicly available datasets:
- CIFAR-10
- Oxford Flowers (102 categories)
- Corel-1000

## Requirements
- Python 3.8+
- TensorFlow 2.8
- NumPy
- Pandas
- Scikit-learn

Install dependencies:
python main.py

## Experimental Setup
- Ubuntu 20.04 LTS
- NVIDIA GPU (≥12 GB)
- 64 GB RAM

## Notes
- This repository provides a clean and reproducible implementation of the core framework.
- Large intermediate files and additional experimental outputs are available upon reasonable request.

## Citation
If you use this work, please cite:

Zeain, A.Y., Ibrahim, A.A.  
"A Causality-Enhanced Multiresolution Residual Learning Framework for Image Retrieval with Fast Osprey Optimization"
