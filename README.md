# 🔁 Customer Churn Prediction

This project is part of my **Machine Learning Internship at CodSoft**. The goal is to predict whether a customer is likely to **churn** (leave the service) using historical banking data.

---

## 📁 Dataset

- Source: [Kaggle – Bank Customer Churn Prediction](https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction)
- File: `Churn_Modelling.csv`
- Target variable: `Exited` (1 = churned, 0 = retained)

---

## 🧠 Objective

To train a machine learning model that can help businesses proactively identify customers who are likely to churn, so that retention strategies can be applied.

---

## 🛠 Technologies Used

- Python
- pandas, NumPy
- scikit-learn
- Random Forest Classifier
- Label Encoding, One-Hot Encoding
- StandardScaler
- Jupyter Notebook (VS Code)

---

## 🧪 ML Workflow

1. Load and explore the data
2. Drop irrelevant features (`RowNumber`, `CustomerId`, etc.)
3. Encode categorical columns (Gender, Geography)
4. Normalize features using `StandardScaler`
5. Split the data into training and testing sets
6. Train a **Random Forest Classifier**
7. Evaluate with accuracy, classification report, and confusion matrix

---

## 🔍 Results

- Achieved strong accuracy using Random Forest
- Gained insight into customer behavior and churn patterns
- Feature scaling and encoding significantly improved performance

---

