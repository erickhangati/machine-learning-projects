# 🌳 Decision Tree Projects

This directory contains **Decision Tree** projects that explore both **from-scratch (NumPy)** and **Scikit-Learn** implementations of one of the most interpretable and foundational machine learning algorithms.

> 🎯 **Goal:** Understand how Decision Trees make data-driven splits using entropy and information gain, and apply them to real-world healthcare prediction tasks.

---

## 📁 Projects

### 🧬 [5-Year Survival Prediction – NumPy Implementation](./decision-trees-scikit-numpy/)

- Predicts whether a **patient survived 5 years** after treatment using tumor and demographic characteristics.  
- Implemented **completely from scratch using NumPy** to show:
  - Manual computation of **entropy** and **information gain**  
  - Recursive **tree-building** logic  
  - Custom **prediction function** for new samples  
- Dataset: **Healthcare Survival Dataset**  
- **Focus:** Learn how Decision Trees operate internally — without relying on Scikit-Learn.

---

### ⚕️ [Titanic Survival Prediction – Scikit-Learn](./decision-trees-scikit-learn/)

- Predicts whether a **Titanic passenger survived** or not based on personal and travel details.  
- Built using **Scikit-Learn’s DecisionTreeClassifier**, featuring:
  - Data cleaning and encoding  
  - Model training and pruning (`max_depth`)  
  - Tree visualization with `plot_tree()`  
  - Evaluation using accuracy, precision, recall, and F1-score  
- Dataset: **Kaggle Titanic Dataset**  
- **Focus:** Apply Decision Trees professionally using Scikit-Learn and understand how pruning controls overfitting.

---

## 🧠 What I Learned

- The step-by-step logic of **how Decision Trees split data** using **entropy** and **information gain**  
- How to **implement and visualize** tree-based models  
- The trade-off between **interpretability** and **performance**  
- Why pruning is essential to prevent overfitting  
- Key differences between **from-scratch** and **library-based** implementations  

---

## 🚀 Getting Started

To explore these projects:

```bash
git clone https://github.com/erickhangati/machine-learning-projects.git
cd machine-learning-projects/decision-trees
```

Then open each project folder (e.g. decision-trees-scikit-numpy/ or decision-trees-scikit-learn/) to view the Jupyter notebooks and source code.