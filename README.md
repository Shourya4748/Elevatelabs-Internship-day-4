# Elevatelabs-Internship-day-4
# Elevatelabs-Internship-day-4

# 🔍 Logistic Regression Binary Classifier

This repository contains a step-by-step implementation of a **binary classification task using Logistic Regression** in Python. The project utilizes the Breast Cancer dataset from Scikit-learn and demonstrates essential concepts of classification, evaluation metrics, and threshold tuning.

## 📌 Objective

To build and evaluate a binary classifier using Logistic Regression to predict whether a tumor is malignant or benign based on several input features.

---

## 🚀 Tools & Libraries

- **Scikit-learn** – for model training, dataset handling, and metrics  
- **Pandas & NumPy** – for data manipulation  
- **Matplotlib** – for data visualization  
- **Jupyter Notebook** – for a structured, interactive coding environment  

---

## 📊 Steps Covered

1. **Load Dataset**  
   Uses Scikit-learn’s `load_breast_cancer()` dataset.

2. **Data Preprocessing**  
   - Train-test split (80/20)
   - Feature standardization using `StandardScaler`

3. **Model Training**  
   Logistic Regression is trained using the standardized data.

4. **Model Evaluation**  
   - Confusion matrix
   - Classification report (Precision, Recall, F1-score)
   - ROC Curve and AUC Score

5. **Threshold Tuning**  
   Demonstrates how changing the decision threshold affects performance, with a custom threshold example.

6. **Sigmoid Function Visualization**  
   Explains how Logistic Regression outputs probabilities using the sigmoid activation function.

---

## 📁 Files

- `logistic_regression_classifier.ipynb` – The complete Jupyter Notebook with step-by-step code and comments.
- `README.md` – Project overview and instructions.

---

## ✅ How to Run

1. Clone this repository  
   `git clone https://github.com/your-username/logistic-regression-classifier.git`

2. Navigate to the project folder  
   `cd logistic-regression-classifier`

3. Open Jupyter Notebook  
   `jupyter notebook logistic_regression_classifier.ipynb`


