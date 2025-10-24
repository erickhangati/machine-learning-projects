# ⚙️ Support Vector Machine (SVM) Projects

This directory contains **Support Vector Machine (SVM)** projects designed to build a deep understanding of SVMs, from the **mathematical foundations implemented with NumPy** to **practical applications using Scikit-Learn**.

> 🎯 **Goal:** Master how SVMs maximize the decision boundary margin and apply them to real-world classification problems.

---

## 📁 Projects

### 🧬 [Breast Cancer Detection – NumPy Only](./svm-with-numpy/)
- Predict whether a tumor is **benign** or **malignant** using the Breast Cancer Wisconsin dataset.  
- Implemented **Linear SVM from scratch using NumPy** to understand:
  - Hinge Loss computation and gradient descent optimization  
  - Regularization and margin maximization  
  - Weight and bias updates without any ML libraries  
- Dataset: Built-in **Breast Cancer Wisconsin (Diagnostic)** dataset from Scikit-Learn  
- **Focus:** Grasp the algorithmic mechanics and math behind Support Vector Machines.

---

### ❤️ [Heart Failure Death Prediction – Scikit-Learn](./svm-with-scikit-learn/)
- Predict whether a heart failure patient is likely to experience a **death event** based on clinical records.  
- Built using **Scikit-Learn’s LinearSVC** within a `Pipeline` and optimized via **GridSearchCV**.  
- Covers:
  - Data cleaning, scaling, and feature preprocessing  
  - Hyperparameter tuning (`C`, `loss`, `penalty`)  
  - Model evaluation with precision, recall, F1-score, and confusion matrix  
- Dataset: **Heart Failure Clinical Records** from the UCI Repository  
- **Focus:** Apply SVMs to healthcare data for real-world prediction tasks.

---

## 🧠 What I Learned

- How SVMs find the optimal hyperplane that maximizes the decision boundary margin  
- How to implement Linear SVMs manually using NumPy  
- How to apply and tune SVMs efficiently using Scikit-Learn  
- The importance of feature scaling and regularization (`C` parameter)  
- How to interpret SVM results in both educational and practical contexts  

---

## 🚀 Getting Started

To explore these projects:

```bash
git clone https://github.com/erickhangati/machine-learning-projects.git
cd machine-learning-projects/SVM
```
<br>

Each project folder includes:

- 📓 A Jupyter Notebook (.ipynb)
- 📘 A detailed README explaining setup, workflow, and results
