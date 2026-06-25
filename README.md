# 🧠 Explainable Transformer-Based Alzheimer's Disease Progression Forecasting Using Longitudinal MRI and Clinical Data

> **An Explainable AI Framework for Forecasting Alzheimer's Disease Progression from Longitudinal Patient Records using Transformer Networks and SHAP-Based Biomarker Interpretation**

---

# 📌 Project Overview

Alzheimer's Disease (AD) is a progressive neurodegenerative disorder that gradually damages brain cells, resulting in memory loss, cognitive impairment, and reduced daily functioning. Since the disease progresses slowly over several years, early prediction of disease progression is essential for timely clinical intervention and treatment planning.

This project presents an **Explainable Transformer-Based Deep Learning Framework** that analyzes **longitudinal MRI-derived biomarkers and clinical assessments** collected across multiple patient visits. Unlike conventional prediction systems that simply generate a risk score, the proposed framework explains **why** the prediction was made by identifying the most influential biomarkers using Explainable Artificial Intelligence (SHAP) and automatically generating clinician-friendly risk reports.

The proposed work is inspired by the **LSM-AD (Longitudinal Survival Model for Alzheimer's Disease)** and extends it by integrating explainability and clinical decision-support capabilities.

---

# 🎯 Problem Statement

Existing Alzheimer's disease progression forecasting models such as **LSM-AD** successfully utilize Transformer networks and longitudinal patient history to predict disease progression. However, these models primarily function as **black-box systems**, providing prediction scores without explaining the underlying reasons behind the decision.

This lack of interpretability limits clinician trust, reduces transparency, and makes AI-assisted diagnosis difficult to adopt in real clinical practice.

To address this limitation, this project proposes an explainable Transformer-based framework capable of forecasting Alzheimer's disease progression while simultaneously identifying the MRI biomarkers and clinical features responsible for each prediction.

---

# 💡 Objectives

The primary objectives of this project are:

* Develop a Transformer-based longitudinal Alzheimer's disease progression forecasting model.
* Analyze patient progression using longitudinal MRI biomarkers and clinical assessments.
* Learn temporal disease progression patterns from multiple patient visits.
* Predict future dementia progression using sequential patient history.
* Provide feature-level explanations using SHAP Explainable AI.
* Generate automated clinician-friendly clinical risk reports.
* Improve transparency, interpretability, and trust in AI-assisted diagnosis.

---

## 🧠 Research Areas

- Healthcare AI
- Deep Learning
- Transformer Networks
- Explainable Artificial Intelligence (XAI)
- Medical Data Analytics
- Disease Progression Forecasting
- Clinical Decision Support

---

# ⚙️ Proposed Methodology

```text
OASIS-2 Longitudinal Dataset

        ↓

Data Collection

        ↓

Data Preprocessing

        ↓

Longitudinal Patient Sequence Construction

        ↓

Transformer Encoder Network

        ↓

Disease Progression Forecasting

        ↓

SHAP Explainability

        ↓

Clinical Risk Report Generation
```

---

# 🧠 Deep Learning Approach

## Transformer Encoder

Unlike traditional machine learning models that analyze each patient visit independently, the Transformer learns disease progression patterns from **multiple chronological patient visits**.

The model analyzes changes in:

* MMSE
* CDR
* eTIV
* nWBV
* ASF
* Age
* Education

across multiple visits to understand how Alzheimer's disease evolves over time.

This enables accurate progression forecasting rather than simple disease classification.

---

## Explainable AI (SHAP)

SHAP (SHapley Additive exPlanations) is integrated to explain the prediction made by the Transformer model.

Instead of producing only a disease risk score, SHAP identifies:

* Most influential biomarkers
* Clinical feature importance
* Patient-specific prediction explanation

This improves transparency and clinician trust.

---

# 📚 Literature Review

## Base Paper 1 (Primary Reference)

### **A Deep Survival Model for Predicting Alzheimer's Diagnosis Based on Multi-Modal Longitudinal Data (LSM-AD)**

**Concepts**

* Transformer Networks
* Longitudinal Learning
* Multi-modal Data
* Alzheimer's Progression Forecasting

**Limitation**

* Black-box prediction
* Limited explainability
* No clinician-oriented interpretation
* No automated clinical reports

---

## Base Paper 2

### **Longitudinal Multi-Modal Data Prediction Model for Mild Cognitive Impairment by Deep Survival Analysis**

**Concepts**

* Deep Survival Learning
* Longitudinal MRI
* Mild Cognitive Impairment Progression

**Limitation**

* No Explainable AI
* Limited clinical interpretability

---

## Base Paper 3

### **Predicting the Progression of MCI and Alzheimer's Disease on Structural Brain Integrity and Other Features with Machine Learning**

**Concepts**

* Structural Brain Biomarkers
* Machine Learning
* Alzheimer's Progression Prediction

**Limitation**

* Classical Machine Learning
* Limited temporal modeling capability
* Lower interpretability

---

# 🚀 Proposed Contribution

Compared with existing Transformer-based progression forecasting models, this work introduces:

* Explainable Transformer Architecture
* SHAP-Based Biomarker Interpretation
* Patient-Specific Feature Importance Analysis
* Automated Clinical Risk Report Generation
* Improved Clinical Transparency
* Better AI-Assisted Decision Support

---

# 📂 Dataset

## OASIS-2 Longitudinal MRI Dataset

Dataset consists of longitudinal patient visits containing:

### Clinical Features

* Age
* Gender
* Education
* MMSE
* CDR

### MRI Biomarkers

* eTIV
* nWBV
* ASF

The dataset enables learning of disease progression patterns over multiple follow-up visits.

---

# 🏗️ Project Workflow

### Step 1

Collect longitudinal patient records from OASIS-2.

↓

### Step 2

Perform data preprocessing.

* Missing value handling
* Feature normalization
* Sequence preparation

↓

### Step 3

Construct longitudinal patient visit sequences.

↓

### Step 4

Train Transformer Encoder model.

↓

### Step 5

Forecast Alzheimer's disease progression.

↓

### Step 6

Generate SHAP explanations.

↓

### Step 7

Generate clinician-friendly risk reports.

---

# 📊 Expected Outcome

The proposed framework is expected to:

* Forecast Alzheimer's disease progression.
* Learn temporal progression patterns from longitudinal patient history.
* Improve disease prediction accuracy.
* Explain predictions using SHAP.
* Identify clinically significant biomarkers.
* Generate transparent AI-assisted clinical reports.

---

# 🛠️ Technology Stack

### Programming Language

* Python

### Deep Learning

* PyTorch

### Machine Learning

* Scikit-Learn

### Explainable AI

* SHAP

### Data Processing

* Pandas
* NumPy

### Visualization

* Matplotlib

### Development Environment

* Google Colab
* Jupyter Notebook

---

# 📁 Repository Structure

```text
Explainable-Alzheimers-Progression-Forecasting/

│

├── Dataset/

├── Base_Papers/

├── notebooks/

├── models/

├── preprocessing/

├── reports/

├── results/

├── README.md

└── requirements.txt
```

---

# 🔮 Future Scope

* Integration with ADNI Multi-modal Dataset
* MRI Image Feature Extraction using 3D CNN
* Graph Neural Networks (GNN)
* Large Language Model (LLM)-based Clinical Report Generation
* Hospital Decision Support Dashboard
* Real-Time Clinical Deployment

---

# 👥 Project Team

* Swetha D
* Vinish S
* Srimathi S

---

# 📌 Keywords

Alzheimer's Disease • Transformer • Longitudinal Learning • Explainable AI • SHAP • Medical Image Analysis • Disease Progression Forecasting • Clinical Decision Support • Deep Learning • Healthcare AI
