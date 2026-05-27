# Subject-Level MRI Classification for Neurodegenerative Assessment

Deep learning framework for cognitive status classification using structural MRI data from the OASIS-3 dataset under rigorous subject-level evaluation conditions.

## Overview

This repository contains the experimental framework associated with the manuscript:

> *Subject-Level Axial MRI Classification with Clinical Marker-Guided Labeling under Rigorous Subject-Independent Evaluation Conditions*

The project investigates clinically realistic neuroimaging classification using axial MRI slices extracted from the OASIS-3 dataset while preventing subject leakage between training, validation, and testing cohorts.

## Main Features

- Subject-level cohort partitioning
- Leakage-controlled MRI evaluation
- Axial MRI slice extraction from NIfTI volumes
- ResNet18 and Vision Transformer (ViT-B/16) evaluation
- Weighted cross-entropy and focal-loss optimization
- ROC analysis and Grad-CAM explainability
- Clinically guided cognitive labeling

## Repository Structure

```text
data_preprocessing/   MRI preprocessing and axial slice extraction
models/               Deep learning training notebooks
evaluation/           Metrics, ROC, confusion matrix, Grad-CAM
results/              Generated figures and tables
docs/                 Manuscript-related material