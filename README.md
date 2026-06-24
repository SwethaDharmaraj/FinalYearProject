

# Explainable Transformer-Based Alzheimer's Disease Progression Forecasting

## Overview

Alzheimer's Disease (AD) is a progressive neurodegenerative disorder that affects memory, cognition, and daily functioning. Early identification of patients at risk of disease progression is essential for timely intervention and treatment planning.

This project proposes an Explainable Transformer-Based Framework for forecasting Alzheimer's disease progression using longitudinal MRI-derived biomarkers and clinical assessments from the OASIS-2 dataset. The system leverages Transformer networks to learn temporal disease progression patterns and integrates SHAP-based explainability to provide interpretable predictions for clinicians.

---

## Problem Statement

Traditional Alzheimer's prediction models often function as black-box systems, providing risk predictions without explaining the underlying factors influencing the outcome. This lack of interpretability limits clinical trust and practical adoption.

The objective of this project is to develop an explainable deep learning framework capable of forecasting dementia progression while identifying the most influential biomarkers contributing to the prediction.

---

## Objectives

* Predict future dementia progression using longitudinal patient data.
* Learn temporal disease patterns using Transformer architecture.
* Analyze MRI-derived biomarkers and clinical assessments.
* Provide explainable predictions using SHAP.
* Generate clinician-friendly risk interpretation.

---

## Dataset

**Dataset:** OASIS-2 Longitudinal MRI Dataset

Features Used:

* Age
* Gender
* Education
* MMSE (Mini-Mental State Examination)
* CDR (Clinical Dementia Rating)
* eTIV (Estimated Total Intracranial Volume)
* nWBV (Normalized Whole Brain Volume)
* ASF (Atlas Scaling Factor)

---

## Methodology

1. Data Collection and Preprocessing
2. Missing Value Handling
3. Longitudinal Sequence Construction
4. Transformer-Based Learning
5. Dementia Progression Prediction
6. SHAP Explainability Analysis
7. Clinical Report Generation

---

## System Architecture

OASIS-2 Dataset
→ Data Preprocessing
→ Longitudinal Sequence Generation
→ Transformer Encoder
→ Progression Prediction
→ SHAP Explainability
→ Clinical Risk Report

---

## Tech Stack

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-Learn
* PyTorch
* SHAP
* Matplotlib

### Development Environment

* Jupyter Notebook
* Google Colab

---

## Expected Output

Example Prediction:

Current CDR: 0.5

Predicted Future CDR: 1.0

Risk Level: High

Key Contributing Factors:

* Reduced Whole Brain Volume
* MMSE Decline
* Increased Cognitive Impairment

---

## Novelty

Unlike conventional Alzheimer's prediction systems, this project combines:

* Longitudinal Disease Progression Forecasting
* Transformer-Based Temporal Learning
* SHAP-Based Explainability
* Automated Clinical Risk Interpretation

This improves both predictive performance and clinical trust.

---

## Future Scope

* Integration with ADNI Dataset
* MRI Image-Based Feature Extraction using CNNs
* Multi-Modal Learning Framework
* Real-Time Clinical Decision Support System

---

## Authors

Final Year Computer Science Engineering Project

Kongu Engineering College

