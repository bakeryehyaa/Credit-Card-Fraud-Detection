# 💳 Credit Card Fraud Detection

An unsupervised machine learning project to detect fraudulent credit card transactions using Isolation Forest and One-Class SVM. The dataset is highly imbalanced, reflecting real-world fraud scenarios.

---

## 📁 Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Records:** 284,807 transactions
- **Features:** 30 features including PCA-transformed data (V1-V28), `Time`, `Amount`, and `Class` (fraud or not)

---

## 🧠 Models Used

- **Isolation Forest**
- **One-Class SVM**

These unsupervised learning models were used to identify anomalies in the dataset (i.e., frauds) without using class labels during training.

---

## 📊 Evaluation Metrics

| Model            | Precision | Recall | F1-Score | Accuracy |
|------------------|-----------|--------|----------|----------|
| Isolation Forest | 0.2967    | 0.2967 | 0.2967   | 0.9976   |
| One-Class SVM    | 0.1348    | 0.5467 | 0.2163   | 0.9932   |

---

## 🎯 Objectives

- Detect rare fraud cases using unsupervised learning
- Handle imbalanced datasets
- Visualize performance using confusion matrices and classification reports

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---
