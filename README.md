

# 🛡️ Fraud Detection: E-commerce & Banking Transactions

*A 10 Academy Week 8&9 Challenge Project*

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen)

## 📌 Overview

This project builds **machine learning models to detect fraudulent e-commerce and banking transactions** using structured transaction data. It tackles key challenges such as **class imbalance**, **real-time prediction**, and **model interpretability**.

Developed as part of the [10 Academy](https://10academy.org/) AI Mastery program (Week 8&9) under the guidance of Adey Innovations Inc.

---

## 🚀 Objectives

* Detect fraud in e-commerce and banking datasets.
* Handle class imbalance effectively using techniques like SMOTE.
* Engineer time-based and user-behavior features.
* Build baseline and ensemble machine learning models.
* Interpret model predictions using SHAP explainability.
* Deliver clean, production-ready, and well-documented code.

---

## 🗃️ Datasets

1. **Fraud\_Data.csv** – E-commerce transactions
2. **IpAddress\_to\_Country.csv** – Maps IP ranges to countries
3. **creditcard.csv** – Bank transaction dataset (PCA-transformed)

---

## 📁 Repository Structure

```
fraud-detection/
│
├── data/                   # Raw datasets (not included in repo)
├── notebooks/              # Jupyter notebooks for EDA, modeling, SHAP analysis
├── src/                    # Source code
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   └── train_models.py
├── reports/                # Final report or blog post
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── .gitignore
```

---

## ⚙️ Setup

1. **Clone repository**

   ```bash
   git clone https://github.com/DagmMesfin/fraud-detection-week8&9.git
   cd fraud-detection-week8&9
   ```

2. **Create & activate virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate      # Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run notebooks or scripts**

   ```bash
   jupyter notebook notebooks/EDA_FraudData.ipynb
   ```

---

## 🔍 Key Features

* 🧹 Data cleaning & merging (IP → Country)
* ⏱️ Time-based feature engineering
* 📉 Handling class imbalance (SMOTE)
* 📊 Model training: Logistic Regression, Random Forest, XGBoost
* ✅ Evaluation: F1-Score, AUC-PR, Confusion Matrix
* 💡 Explainability: SHAP (summary & force plots)

---

## 🧪 Models & Performance

| Model               | Dataset         | F1 Score | AUC-PR  |
| ------------------- | --------------- | -------- | ------- |
| Logistic Regression | Fraud\_Data.csv | `xx.xx`  | `xx.xx` |
| XGBoost             | Fraud\_Data.csv | `xx.xx`  | `xx.xx` |
| Logistic Regression | creditcard.csv  | `xx.xx`  | `xx.xx` |
| XGBoost             | creditcard.csv  | `xx.xx`  | `xx.xx` |

*Results to be updated after training.*

---

## 📈 SHAP Explainability

SHAP (Shapley Additive Explanations) was used to:

* Analyze **global feature importance**
* Understand **individual predictions**
* Identify key features driving fraud detection

Plots available in `notebooks/shap_analysis.ipynb`.

---
