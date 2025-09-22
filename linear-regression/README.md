# 📈 Linear Regression Projects

This directory contains **Linear Regression projects** that explore predictive modeling using both **from-scratch implementations (NumPy)** and **library-based approaches (scikit-learn)**.  

> 🎯 Goal: Understand linear regression deeply by building it from the ground up, then apply it to real-world datasets with advanced techniques like polynomial features and regularization.

---

## 📁 Projects

### 🏡 [House Price Prediction – NumPy Only](./house-price-prediction/)
- Predict Seattle house prices based on house size (`size_sqft`)
- Implemented **linear regression from scratch using NumPy**
- Covers:
  - Mean Squared Error (MSE) cost function
  - Gradient descent optimization
  - Feature scaling (Z-score normalization)
- **Focus**: Learn the math and logic behind linear regression without ML libraries

---

### 🏥 [Medical Cost Prediction – scikit-learn](./medical-cost-prediction/)
- Predict **individual medical insurance costs** using demographic and lifestyle features
- Built with **scikit-learn** using:
  - Linear Regression with Polynomial Features
  - Ridge Regression (L2 regularization)
  - Lasso Regression (L1 regularization)
- Includes:
  - Data preprocessing & hypothesis testing
  - Cross-validation & hyperparameter tuning
  - Model comparison using R² Score and RMSLE
- **Focus**: Apply linear models to a real healthcare dataset and explore regularization

---

## 🧠 What I Learned

- The step-by-step math behind linear regression  
- How to optimize with gradient descent  
- The role of feature scaling in model training  
- How polynomial features extend linear models to capture non-linear relationships  
- The importance of Ridge and Lasso for controlling complexity and avoiding overfitting  

---

## 🚀 Getting Started

To explore the projects:  

```bash
git clone https://github.com/erickhangati/machine-learning-projects.git
cd machine-learning-projects/linear-regression
