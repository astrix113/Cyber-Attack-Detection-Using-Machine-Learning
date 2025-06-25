# 🛡️ Cyber Attack Detection using Machine Learning

A machine learning-based Intrusion Detection System (IDS) designed to detect various network attacks using the CICIDS2018 dataset. The project leverages classification models, explainability tools like SHAP, and dimensionality reduction techniques to accurately predict malicious traffic and interpret model decisions.

## 🔍 Overview

This project aims to identify cyber attacks in network traffic using supervised ML algorithms. It involves end-to-end development of a scalable ML pipeline with real-time prediction capability, model explainability, and deployment via Flask.

---

## 🧪 Features

- ✅ Trained on the CICIDS2018 dataset with 15+ types of attacks.
- 📊 Achieved **98.4% accuracy** and **AUC-ROC of 0.993** using XGBoost.
- 📉 Used **PCA** to reduce dimensions from 80+ to 20, speeding up training by 60%.
- 🔍 Model interpretability using **SHAP** to visualize feature impacts.

---

## 🧠 Machine Learning Models

- **XGBoost** – Best performance across metrics.
- **Random Forest** – Strong baseline with fast inference.
- **Support Vector Machine (SVM)** – Tested with tuned kernels.
- **Logistic Regression** – Interpretable, used for benchmarking.

---


## 📈 Evaluation Metrics

| Metric       | Value   |
|--------------|---------|
| Accuracy     | 98.4%   |
| AUC-ROC      | 0.993   |
| Precision    | 97.8%   |
| Recall       | 98.9%   |
| F1-Score     | 98.3%   |

---

## 🧰 Tech Stack

- **Languages**: Python
- **ML Libraries**: Scikit-learn, XGBoost, SHAP, PCA
- **Deployment**: Flask, Render
- **Visualization**: Matplotlib, Seaborn
- **Notebook Tools**: Jupyter, Pandas, NumPy

---


