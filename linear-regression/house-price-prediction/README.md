# 🏡 Linear Regression – Seattle House Price Prediction (NumPy Only)

This project demonstrates how to build and train a **linear regression model from scratch using NumPy**, without using any machine learning libraries.

> 🎯 Goal: Predict house prices in Seattle using a single feature — `size_sqft` — and implement the full linear regression pipeline manually to understand the math and logic behind the algorithm.

---

## 📂 Project Structure
```
/house-price-prediction/
├── seattle-housing-test-data.csv 
├── seattle-housing-train-data.csv 
├── house-price-prediction.ipynb
└── README.md # This file
```
---

## 📊 Dataset

- **Source**: [Kaggle – Seattle House Price Prediction](https://www.kaggle.com/datasets/samuelcortinhas/house-price-prediction-seattle)
- Contains real estate data with features like:
  - `beds`, `baths`
  - `size` and `size_units`
  - `lot_size` and `lot_size_units`
  - `zip_code`
  - `price` (target variable)

---

## 📌 Highlights of This Project

- ✅ Real-world data cleaning and preprocessing
- 📉 Cost function (Mean Squared Error) implemented from scratch
- 🔁 Manual gradient descent optimization
- ⚙️ Feature scaling using Z-score normalization
- 📈 Custom prediction and visualization (matplotlib)
- 🧪 Evaluation using RMSE and R² score

---

## 📈 Model Overview

- **Input feature**: `size_sqft` (standardized)
- **Target**: `price` (rescaled after prediction)
- **Final evaluation**:
  - RMSE: \$923,043.35
  - R² Score: 0.1609

> The model explains ~16% of the variation in house prices using only one feature — making this a great educational project, not a production-ready solution.

---

## 🧠 What I Learned

- How linear regression really works under the hood
- How to optimize using gradient descent (not just call `.fit()`)
- The importance of feature scaling for optimization
- How real-world data often needs thoughtful preprocessing

---

## 🚀 How to Run the Notebook

1. Download the dataset (`train.csv`) from the [Kaggle page](https://www.kaggle.com/datasets/samuelcortinhas/house-price-prediction-seattle) and place it inside this folder.

2. Install required libraries:

```bash
pip install numpy pandas matplotlib
```

---

## 📘 Blog Article

A beginner-friendly article based on this project is published on my blog ([Linear Regression With NumPy: House Price Prediction](https://erickhangati.com/linear-regression-with-numpy-house-price-prediction/)) to walk through all the steps in-depth.

---
