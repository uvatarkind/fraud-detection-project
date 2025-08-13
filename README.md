# 🛡️ Fraud Detection: E-commerce & Banking Transactions  
_A 10 Academy Week 8&9 Challenge Project_  

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen)

## 📌 Overview

This project aims to build machine learning models that **detect fraudulent e-commerce and bank transactions** using structured transaction data. It addresses core challenges in fraud detection such as **class imbalance**, **real-time prediction**, and **model interpretability**.

Developed as part of the [10 Academy](https://10academy.org/) Artificial Intelligence Mastery program (Week 8&9), under the guidance of Adey Innovations Inc.

---

## 🚀 Project Objectives

- Detect fraud in e-commerce and banking transaction datasets.
- Handle significant class imbalance effectively.
- Engineer informative time-based and user behavior features.
- Build baseline and ensemble machine learning models.
- Interpret model predictions using SHAP explainability tools.
- Deliver clean, production-ready, and well-documented code.

---

## 🗃️ Datasets Used

1. **Fraud_Data.csv**: E-commerce transactions  
2. **IpAddress_to_Country.csv**: Maps IP ranges to country  
3. **creditcard.csv**: Bank transaction dataset (PCA-transformed)

---

## 📁 Repository Structure

```

fraud-detection/
│
├── data/                   # Raw datasets (not pushed to GitHub)
├── notebooks/              # Jupyter notebooks for EDA, modeling, explainability
├── src/                    # Source code: preprocessing, features, training
│   ├── preprocessing.py
│   ├── feature\_engineering.py
│   └── train\_models.py
├── reports/                # Final report or blog post
├── requirements.txt        # Project dependencies
├── README.md               # This file
└── .gitignore

````

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/DagmMesfin/fraud-detection-week8&9.git
   cd fraud-detection-week8&9
````

2. **Create and activate virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebooks or scripts**
   Start with:

   ```bash
   jupyter notebook notebooks/EDA_FraudData.ipynb
   ```

---

## 🔍 Key Features

* 🧹 Data cleaning & merging (IP to Country)
* ⏱️ Time-based feature engineering
* 📉 Class imbalance handling with SMOTE
* 📊 Model training (Logistic Regression, XGBoost/Random Forest)
* ✅ Evaluation with AUC-PR, F1-Score, Confusion Matrix
* 💡 Explainability with SHAP (force plots, summary plots)

---

## 🧪 Models

| Model               | Dataset         | F1 Score | AUC-PR  |
| ------------------- | --------------- | -------- | ------- |
| Logistic Regression | Fraud\_Data.csv | `xx.xx`  | `xx.xx` |
| XGBoost             | Fraud\_Data.csv | `xx.xx`  | `xx.xx` |
| Logistic Regression | creditcard.csv  | `xx.xx`  | `xx.xx` |
| XGBoost             | creditcard.csv  | `xx.xx`  | `xx.xx` |

*Results filled in after training & evaluation.*

---

## 📈 SHAP Explainability

We used SHAP (Shapley Additive Explanations) to:

* Analyze global feature importance.
* Understand local decisions (individual predictions).
* Highlight the most influential features driving fraud detection.

Plots available in `notebooks/shap_analysis.ipynb`.

---

## ✍️ Author

**Dagim Mesfin Seifu**
