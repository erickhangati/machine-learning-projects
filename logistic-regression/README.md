# 🔍 Logistic Regression Projects

This directory contains **Logistic Regression projects** built to explore binary classification using both **from-scratch implementations (NumPy)** and **library-based approaches (Scikit-Learn)**.

> 🎯 Goal: Understand logistic regression from its mathematical foundation to its practical use in real-world problems.

---

## 📁 Projects

### 📧 [Email Spam Classification – NumPy Only](./email-spam-classification/)
- Classify emails as **spam (1)** or **ham (0)** using text data.
- Implemented **logistic regression from scratch with NumPy** to understand:
  - Sigmoid activation and decision boundary  
  - Binary cross-entropy loss  
  - Gradient descent optimization  
  - L1 and L2 regularization
- Dataset: Combined **TREC 2007** and **Enron-Spam** corpora  
- **Focus**: Learn the core math and logic behind logistic regression.

---

### 🏥 [Healthcare Appointment No-Show Prediction – Scikit-Learn](./healthcare-appointment/)
- Predict whether a patient will **show up** for their medical appointment.  
- Built using **Scikit-Learn’s Logistic Regression** with regularization (L1, L2).
- Covers:
  - Real-world data cleaning and feature engineering  
  - Handling categorical and date-time data  
  - Model training and evaluation with AUC-ROC, precision, recall, and F1-score  
- **Focus**: Apply logistic regression to a real healthcare problem.

---

## 🧠 What I Learned

- The math behind logistic regression and its decision boundaries  
- How to implement logistic regression manually using NumPy  
- How to use Scikit-Learn for efficient model training and evaluation  
- The importance of regularization (L1, L2) in reducing overfitting  
- How to interpret performance metrics for classification problems  

---

## 🚀 Getting Started

To explore these projects:

```bash
git clone https://github.com/erickhangati/machine-learning-projects.git
cd machine-learning-projects/logistic-regression
```

<br>

Each project folder includes:

- The Jupyter notebook (.ipynb)
- Dataset (if applicable)
- README explaining setup and workflow
