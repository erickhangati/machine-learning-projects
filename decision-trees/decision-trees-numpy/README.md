# 🌳 Predicting 5-Year Survival in Patients using a Decision Tree (From Scratch with NumPy)

This project implements a **Decision Tree Classifier completely from scratch using NumPy**, applied to a healthcare dataset that predicts whether a patient **survived for 5 years** after treatment.  
It demonstrates how core Decision Tree concepts such as **entropy**, **information gain**, and **recursive splitting**, can be built manually without using machine learning libraries like Scikit-Learn.

## 🧠 What You'll Learn

- How a Decision Tree works internally  
- Implementation of entropy and information gain functions  
- Recursive tree construction using NumPy  
- How to make predictions using a manually built tree  
- Evaluating the performance of a custom-built ML model  
- Comparison between from-scratch and Scikit-Learn implementations


## 📁 File Structure

```
decision-trees-numpy/
├── Breast_Cancer.csv
├── descision-trees-numpy.ipynb
└── README.md # this file
```

## 📊 Dataset

We use a healthcare dataset that contains various **patient and tumor characteristics**, such as:

- `Age` – Age of the patient  
- `Race` – Ethnic background of the patient  
- `Marital Status` – Marital status at diagnosis  
- `T Stage`, `N Stage`, `6th Stage` – Cancer staging information  
- `Differentiation`, `Grade` – Tumor grade and differentiation  
- `A Stage`, `Tumor Size` – Tumor size and anatomical stage  
- `Estrogen Status`, `Progesterone Status` – Hormone receptor information  
- `Regional Node Examined`, `Reginol Node Positive` – Lymph node examination results  
- `Survival Months` – Duration of survival  
- `Status` – Alive/Dead status (used to derive target variable)  
- **Target variable:** `Survived 5 Years` (0 = No, 1 = Yes)

## 🔧 Techniques Used

- Manual calculation of **entropy** for measuring node impurity  
- Computation of **information gain** for finding optimal splits  
- Implementation of **recursive tree building** using NumPy  
- **Predict function** for classifying new samples using the trained tree  
- Evaluation using **Accuracy**, **Precision**, **Recall**, **F1-score**, and **Confusion Matrix**  
- Comparison between from-scratch model and Scikit-Learn’s implementation

## ✅ Key Results

- **Accuracy:** ~69.4% on the test set  
- Strong recall on the positive class (patients who survived 5 years)  
- Model shows a bias toward predicting survival — likely due to dataset imbalance  
- Confirms the working principles of entropy and information gain in real-world data

## 🧩 Insights

This implementation provides a hands-on understanding of how Decision Trees split data and make predictions.  
Although performance is lower than Scikit-Learn’s optimized version, it’s a valuable educational exercise to:

- Understand **how tree decisions are computed mathematically**  
- Visualize **information gain and entropy reduction** step-by-step  
- Appreciate the efficiency of optimized implementations in Scikit-Learn  

## 📘 Blog Article

A detailed beginner-friendly blog article based on this project is available on my blog:  
👉 [XXX](https://erickhangati.com/)

It walks through every step — from entropy calculation to final evaluation — with detailed explanations, formulas, and visuals.
