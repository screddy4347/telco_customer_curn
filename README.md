


# Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn refers to customers leaving a service or company. This project builds an **end-to-end Machine Learning classification model** to predict whether a customer will churn based on historical customer data.

This is an **intermediate-level ML project**, suitable for:

* College mini/major projects
* Resume and GitHub portfolio
* Understanding complete ML workflow

---

## 🎯 Problem Statement

Predict whether a customer will **Churn (Yes/No)** using customer demographics, service usage, and billing information.

* **Type**: Supervised Learning
* **Task**: Classification
* **Target Variable**: `Churn`

---

## 📂 Dataset

**Telco Customer Churn Dataset (Kaggle)**

Key features include:

* Gender, SeniorCitizen
* InternetService, Contract
* MonthlyCharges, TotalCharges

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔄 Project Workflow

1. Import required libraries
2. Load and inspect dataset
3. Data cleaning and type conversion
4. Handle missing values
5. Exploratory Data Analysis (EDA)
6. Feature encoding and scaling
7. Train–test split
8. Model training
9. Model evaluation
10. Feature importance analysis

---

## 📊 Machine Learning Models Used

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier (Best Model)

---

## 📈 Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Precision, Recall, F1-score

---

## ✅ Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~80%     |
| Decision Tree       | ~78%     |
| Random Forest       | ~85%     |

✔ Random Forest performed best.

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── data/
│   └── churn.csv
├── notebooks/
│   └── churn_analysis.ipynb
├── README.md
├── requirements.txt
└── model/
    └── churn_model.pkl
```

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook and run step by step

---

## 🧠 Key Learnings

* Data preprocessing and cleaning
* Feature encoding and scaling
* Model comparison
* Evaluation using confusion matrix
* Feature importance analysis

---
