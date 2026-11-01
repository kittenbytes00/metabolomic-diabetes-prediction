# Metabolomic Prediction of Type 2 Diabetes Following Gestational Diabetes

**Course:** DS8002: Machine Learning (Toronto Metropolitan University)  
**Project Type:** Replication + Extension  

---

## 📌 Project Overview
Women with a history of gestational diabetes mellitus (GDM) face an elevated risk of developing type 2 diabetes (T2D later in life). This project **replicates and extends** the metabolomics-based machine learning analysis reported by *Allalou et al. (2016)*. 

The primary goals are:
1. **Replicate** the published decision-tree prediction model using the supplied clinical and metabolomic dataset.
2. **Extend** the analysis by evaluating alternative multivariate classifiers (**Gaussian Naive Bayes**, **Linear Discriminant Analysis (LDA)**, and **Quadratic Discriminant Analysis (QDA)**) under a strict, leakage-free validation protocol.
3. **Analyze** the trade-offs between model flexibility, estimation variance, and feature stability across cross-validation folds.

---

## 📂 Repository Structure
```text
metabolomic-diabetes-prediction/
│
├── data/
│   └── Publication_used_data_extracted.xlsx   # Dataset (244 patients, paired strata)
│
├── notebooks/                                 # Exploratory and development notebooks
│
├── src/                                       # Modular Python source files (.py)
│   ├── __init__.py
│   ├── preprocessing.py                       # Imputation, scaling, and pipeline setup
│   └── models.py                              # Model training and evaluation scripts
│
├── README.md                                  # Project documentation
└── requirements.txt                           # Python dependencies
