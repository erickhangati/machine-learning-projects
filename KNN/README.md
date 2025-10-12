# 🧭 K-Nearest Neighbors (KNN) Projects

This directory contains **K-Nearest Neighbors (KNN)** projects that explore distance-based learning using both **from-scratch (NumPy)** and **Scikit-Learn** implementations.

> 🎯 Goal: Understand how KNN works internally — from computing distances to majority voting — and apply it to real-world healthcare prediction problems.

---

## 📁 Projects

### 🩹 [Diabetes Prediction – NumPy Only](./knn-with-numpy/)

- Predicts whether a patient is **diabetic** or **non-diabetic**.  
- Implemented **entirely from scratch using NumPy** to demonstrate:
  - Euclidean distance computation  
  - Manual neighbor selection and majority voting  
  - Data scaling and feature normalization  
- Dataset: **Kaggle Diabetes Dataset**  
- **Focus**: Learn KNN fundamentals and the math behind distance-based algorithms.

---

### 🩺 [Heart Disease Prediction – Scikit-Learn](./knn-with-scikit-learn/)

- Predicts whether a patient has **heart disease** using diagnostic and clinical indicators.  
- Built with **Scikit-Learn’s KNeighborsClassifier** and includes:
  - Data cleaning, encoding, and scaling  
  - Hyperparameter tuning for optimal `k`  
  - Evaluation with accuracy, precision, recall, and F1-score  
- Dataset: **UCI Heart Disease Dataset**  
- **Focus**: Apply KNN professionally to a real healthcare dataset and interpret results.

---

## 🧠 What I Learned

- How KNN uses distance metrics to classify new samples  
- Why feature scaling and normalization are critical for fair distance comparison  
- The trade-off between bias and variance when tuning `k`  
- How to evaluate classification models with **precision**, **recall**, and **F1-score**  
- The differences between **from-scratch** and **library-based** implementations

---

## 🚀 Getting Started

To explore these projects:

```bash
git clone https://github.com/erickhangati/machine-learning-projects.git
cd machine-learning-projects/KNN
