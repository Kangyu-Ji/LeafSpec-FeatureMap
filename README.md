# LeafSpec-Analytics

**Spatial Feature Mapping and Statistical Inference for Hyperspectral Leaf Transmittance Image**


## Overview

**LeafSpec-Analytics** is a data analysis pipeline built on the LeafSpec platform for processing **hyperspectral leaf transmittance data**. It enables spatially-resolved feature extraction, statistical analysis, and classification of plant responses to chemical treatments.

This repository focuses on transforming raw spectral measurements into **interpretable feature maps and quantitative indexes**.


## Key Features

### 1. Spatially-Resolved Feature Mapping
- Generate per-pixel feature maps from hyperspectral transmittance data
- Supported features:
  - **Single-band Transmittance (T)**
  - **Normalized Difference Index (ND)**  
- Enables visualization of intra-leaf heterogeneity


### 2. Feature Generation
- Compute statistical summaries over spatial maps:
  - Mean
  - Variance
- Converts high-dimensional spectral data into compact spectral descriptors


### 3. Classification
- Evaluate separability between treatment groups
- **t-test** for group comparison
- **ROC curve analysis**
  - Area Under Curve (AUC)
  - Threshold-based evaluation


## Repository Structure
```
leafspec-analytics/
├── dataset/        # Raw hyperspectral input datasets
├── processed/      # Preprocessed data, including masked and spectrally corrected hyperspectral images
├── results/        # Output figures and analysis results
├── FeatureMap.ipynb # Main execution notebook
└── README.md
```

## Getting Started

## Software dependencies
- scipy https://scipy.org/ (any version should work)
- sklearn https://scikit-learn.org/ (any version should work)
- scikit-image https://scikit-image.org/ (any version should work)

## Usage
- Install the dependencies
- Run the jupyter notebook FeatureMap.ipynb

## About us
- Dr. Kangyu Ji https://scholar.google.com/citations?user=Oej20eMAAAAJ
- Prof. Jian Jin https://scholar.google.com/citations?user=rt8TzCkAAAAJ
- ABE Plant Sensor Lab @Purdue https://engineering.purdue.edu/ABEPlantSensorLab
- This project is developed in the context of a DARPA-supported research effort on plant sensing and spectral intelligence.
- This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png

