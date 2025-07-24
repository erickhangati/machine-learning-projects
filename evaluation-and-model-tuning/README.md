# 🎯 Polynomial Regression: Understanding Model Complexity and Generalization

This beginner-friendly project explores how **polynomial regression** models of varying complexity perform on real-world data. By analyzing **training and validation errors** across polynomial degrees, we demonstrate key machine learning concepts like:

- Underfitting vs Overfitting
- Bias-Variance Tradeoff
- Model Selection via Learning Curves

---

## 📦 Dataset

We use the **California Housing dataset** from `scikit-learn`, which includes features such as:

- `MedInc`: Median income in a district (used as input)
- `MedHouseVal`: Median house value (used as the target)

To simplify and visualize model behavior, we focus on a **single feature regression**: predicting house value from income.

---

## 📌 Project Workflow

1. **Data Preparation**
   - Load and explore the California Housing dataset
   - Select one input feature for interpretability
   - Split data into training and validation sets

2. **Model Training**
   - Train multiple polynomial regression models (degrees 1 to 15)
   - Use pipelines with polynomial feature expansion and scaling

3. **Model Evaluation**
   - Plot learning curves: Training vs Validation RMSE
   - Identify underfitting and overfitting zones
   - Select best degree based on lowest validation error

4. **Prediction Visualization**
   - Plot prediction curve of the best-fit model
   - Overlay it on actual training and validation data

---

## 📈 Output

- 📊 Learning curve comparing training and validation errors
- ✅ Selected best polynomial degree
- 🧠 Visual interpretation of model performance

---

## 📂 File Structure

```
evaluation-and-model-tuning/
├── underfitting-and-overfitting-with-polynomial-regression.ipynb
└── README.md (this file)
```

---

## 🛠️ Technologies Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- scikit-learn

---

## 📚 What You'll Learn

- How polynomial regression works
- How to visualize and interpret model complexity
- Diagnosing bias and variance with learning curves
- Choosing the best model using validation error
- Building explainable ML visualizations from scratch

---

## 📘 Blog Article

A beginner-friendly article based on this project is published on my blog ([Underfitting and Overfitting with Polynomial Regression](https://erickhangati.com/underfitting-and-overfitting-with-polynomial-regression/)) to walk through all the steps in-depth.

---