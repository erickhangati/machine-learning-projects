# 🏥 Linear Regression – Medical Cost Prediction

This project applies **Linear, Ridge, and Lasso Regression** models (with Polynomial Features) to predict **individual medical insurance costs** based on personal attributes such as age, BMI, smoking habits, and region.  

> 🎯 Goal: Build and compare regression models to understand how personal and lifestyle factors affect healthcare expenses.  



## 📂 Project Structure

```
medical-insurance-charges-prediction/
├── insurance.csv # Original dataset (not committed to Git)
├── medical-cost-prediction.ipynb # Complete Jupyter Notebook
└── README.md # This file
```


## 📊 Dataset

- **Source**: [Kaggle – Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- Contains demographic and lifestyle information:
  - `age`
  - `sex`
  - `bmi` (Body Mass Index)
  - `children` (number of dependents)
  - `smoker` (yes/no)
  - `region` (geographical region in the US)
  - `charges` (medical cost – target variable)

---

## 📌 Highlights of This Project

- ✅ Data preprocessing and exploratory data analysis (EDA)  
- 🔍 Hypothesis testing and correlation analysis  
- 📈 Feature scaling and polynomial feature engineering  
- 🤖 Model training with **Linear, Ridge, and Lasso Regression**  
- 🔁 Cross-validation and hyperparameter tuning  
- 📊 Performance evaluation using **R² Score** and **RMSLE**  
- 📉 Side-by-side model comparison and visualization  

---

## 📈 Model Overview

| Model           | R² Score | RMSLE |
|-----------------|----------|-------|
| Linear (Poly)   | ~0.831   | ~0.370 |
| Ridge (Poly)    | ~0.830   | ~0.371 |
| Lasso (Poly)    | ~0.824   | ~0.372 |

> Polynomial Linear Regression performed best, but Ridge and Lasso provided useful insights into regularization and feature selection.  

---

## 🧠 What I Learned

- How **linear models** can be extended with polynomial features to capture non-linear relationships.  
- The importance of **regularization (Ridge & Lasso)** in controlling model complexity.  
- How to evaluate regression models using **cross-validation and multiple metrics**.  
- The role of **EDA and hypothesis testing** in guiding model design.  

---

## 🚀 How to Run the Notebook

1. Download the dataset (`insurance.csv`) from the [Kaggle page](https://www.kaggle.com/datasets/mirichoi0218/insurance) and place it inside this folder.

2. Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
