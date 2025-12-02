# 🎓 Student Performance Predictor

**Machine Learning Project | UCI Student Dataset**

## ✳ Short abstract (one-line)

A machine learning pipeline that analyzes and predicts student final grades using the UCI Student dataset, with model explainability via SHAP and LIME.

## 📌 Abstract

This project analyzes and predicts students’ academic performance using machine learning techniques applied to the UCI Student Performance dataset. A combined dataset of 682 students (68 features) was created by merging the Math and Portuguese student files. After preprocessing, exploratory analysis, and feature engineering, several regression models were trained — including Linear Regression, Decision Tree, Random Forest, SVR, MLP Regressor, and a Voting Ensemble.

Random Forest and the Voting Ensemble demonstrated the strongest predictive performance, achieving the lowest mean squared error (MSE) and the highest R² values. To improve interpretability, SHAP and LIME techniques were applied, allowing detailed insight into which features most influenced model predictions (e.g., number of past class failures, study time, parental involvement, absences).

This project provides a complete pipeline from data cleaning to model evaluation and explainability, offering practical insights into factors affecting student academic outcomes.

---

## 📘 Project Report

You can read the full project report here:

👉 **[Download Full Report (PDF)](./Student_Performance_Predictor-1.pdf)**
*(Upload `Student_Performance_Predictor-1.pdf` to the repository root for this link to work.)*

---

## 📂 Repository Structure

```
.
├── notebooks/              # Jupyter notebooks (EDA, models)
├── data/                   # Dataset (or sample)
├── assets/                 # Plots / visuals
├── Student_Performance_Predictor-1.pdf   # Full project report
└── README.md               # You're reading it
```

---

## ⭐ My Contribution

I contributed to the project by working on analysis, documentation, and report preparation.
This fork includes the report and improved documentation for better visibility on my GitHub profile.

---

## 📊 Key Features

* Full ML pipeline (preprocessing → EDA → modeling → evaluation)
* Models: Linear Regression, Decision Tree, Random Forest, SVR, MLP, Voting Ensemble
* Interpretability using **SHAP** and **LIME**
* Insights into academic performance factors
* Full project report included for interview reference

---

## 🏷️ Technologies Used

* Python, scikit-learn, pandas, numpy, matplotlib, seaborn, SHAP, LIME

---
