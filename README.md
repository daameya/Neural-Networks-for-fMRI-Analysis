# Neural-Networks-for-Functional-Connectivity-Classification-in-fMRI

This repository contains the code and methodology for classifying ADHD subjects using functional connectivity derived from resting-state fMRI data. The project demonstrates the use of Independent Component Analysis (ICA), functional connectivity analysis, and neural networks for binary classification between ADHD and control groups.

---

## Overview

The ADHD-200 dataset is used to explore the differences in functional connectivity between ADHD and control subjects. Key steps include:

1. **Dataset Preprocessing**: Leveraging the Nilearn library to load and preprocess fMRI data.
2. **Independent Component Analysis (ICA)**: Identifying brain regions of interest (ROIs) using CanICA for functional network extraction.
3. **Functional Connectivity Analysis**: Calculating correlation matrices between ROIs to quantify connectivity.
4. **Neural Network Classification**: Building and training a neural network to classify subjects based on connectivity patterns.

---

## Key Results

- **Accuracy**: 56% on the test dataset.
- **False Negatives**: 4
- **False Positives**: 0
- Insights from functional connectivity differences align with previous research on ADHD-related neural activity.
