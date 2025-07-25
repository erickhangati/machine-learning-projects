# 📉 Customer Churn Prediction using Random Forest & XGBoost

This project tackles the **Telco Customer Churn** problem using **tree ensemble methods** — specifically `RandomForestClassifier` and `XGBoostClassifier`. The goal is to predict whether a customer is likely to churn based on their service usage, contract type, billing, and demographics.

It’s a complete beginner-friendly implementation in a Jupyter Notebook — from data cleaning to model evaluation — designed to serve as both a portfolio project and a tutorial.

---

## 🧠 What You’ll Learn

- How to handle real-world churn data with missing values and mixed data types
- How to explore and visualize churn trends across different customer segments
- How to train and compare Random Forest and XGBoost models
- How to interpret feature importance to understand churn drivers
- How to tune hyperparameters using `RandomizedSearchCV`

---

## 📁 Dataset

- **Source**: [IBM Sample Data – Telco Customer Churn](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset)
- **Shape**: `7043 rows × 33 columns`
- **Target Column**: `Churn Label` (Yes/No)

---

## 🚀 Project Structure

| Step | Description |
|------|-------------|
| 📦 Load Data | Import the CSV dataset and preview structure |
| 🧹 Data Cleaning | Handle missing values (especially in `Total Charges` and `Churn Reason`) |
| 📊 Exploratory Data Analysis (EDA) | Understand churn distribution and feature relationships |
| 🔄 Data Preprocessing | Encode categorical variables and split data |
| 🌲 Random Forest Classifier | Train and evaluate a baseline tree ensemble model |
| ⚙️ XGBoost Classifier | Train and tune a more powerful gradient boosting model |
| 🔍 Feature Importance | Analyze top factors that drive churn behavior |
| 🎯 Final Model Evaluation | Compare models using accuracy, recall, F1-score, confusion matrix |

---

## 📈 Final Results

| Model               | Accuracy | F1-Score (Churn) |
|--------------------|----------|------------------|
| Random Forest       | 79.6%    | 0.56             |
| XGBoost (Default)   | 78.9%    | 0.57             |
| **XGBoost (Tuned)** | **80.6%**| **0.59**         |

✅ **Best Model**: Tuned XGBoost using `RandomizedSearchCV`

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (`RandomForestClassifier`, preprocessing, metrics)
- XGBoost (`XGBClassifier`, `RandomizedSearchCV`)
- Jupyter Notebook

---

## 📘 Blog Article

A beginner-friendly article based on this project will be published on [(Customer Churn Prediction With Random Forest and XGBoost)](https://erickhangati.com/customer-churn-prediction-with-random-forest-and-xgboost/) to walk through all the steps in-depth.

---

## 📂 Folder Structure

```
tree-ensembles/
├── telco-customer-churn.csv
├── customer-chun-prediction.ipynb
└── README.md
```