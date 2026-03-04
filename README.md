# 🏥 Clinical Risk Predictor

Machine Learning system for cardiovascular risk prediction using clinical variables.
This project focuses on model validation, ROC analysis, and clinical interpretability.

---

## 🎯 Objective

Build and evaluate multiple machine learning models to predict 10-year coronary heart disease (CHD) risk using the Framingham Heart Study dataset.

The goal is not only predictive accuracy, but also:

- Clinical relevance
- ROC-AUC optimization
- Threshold analysis
- Interpretability
- API deployment readiness

---

## 📊 Dataset

**Framingham Heart Study Dataset**

Source:
https://www.kaggle.com/datasets/amanajmera1/framingham-heart-study-dataset

Target variable:
- `TenYearCHD` → 1 if patient develops CHD within 10 years

Features include:

- Age
- Sex
- Smoking status
- Blood pressure
- Cholesterol
- BMI
- Glucose
- Diabetes
- Stroke history

---

## 🧠 Models Implemented

- Logistic Regression
- Random Forest
- Support Vector Machine
- Neural Network (PyTorch)

---

## 📈 Evaluation Metrics

- Accuracy
- ROC-AUC
- Precision
- Recall
- F1 Score
- Sensitivity
- Specificity
- Confusion Matrix
- Precision-Recall Curve

Clinical interpretation of threshold selection is included.

---

## 🏗 Project Structure
