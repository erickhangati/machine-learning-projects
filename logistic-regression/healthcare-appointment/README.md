# 🏥 Predicting Patient No-Shows with Logistic Regression (Using Scikit-Learn)

This project uses **logistic regression with Scikit-Learn** to predict whether a patient will show up for their healthcare appointment.  
It explores a real-world dataset to understand patient behavior and build a simple yet effective classification model.

---

## 🧾 Dataset

- **Source:** [Kaggle - Medical Appointment No Shows Dataset](https://www.kaggle.com/datasets/wajahat1064/healthcare-appointment-dataset)
- Each record includes:
  - Patient demographics (age, gender)
  - Health-related data (hypertension, diabetes, alcoholism, handicap)
  - Appointment details (scheduled date, appointment date, SMS received)
  - Target variable: `Showed_up` (1 = Did not show up, 0 = Showed up)

---

## 🧠 Project Highlights

- 🧹 Cleaned and processed 100,000+ appointment records  
- 🧾 Converted categorical and date fields into model-ready numerical features  
- ⚙️ Engineered new features such as `Days between scheduling and appointment` and `Condition count`  
- 📊 Explored relationships between patient features and show-up behavior  
- 🧮 Trained **three logistic regression models**:
  - Baseline Logistic Regression  
  - Logistic Regression with L1 Regularization (Lasso)  
  - Logistic Regression with L2 Regularization (Ridge)
- 📈 Compared performance using **accuracy, precision, recall, F1-score**, and **AUC-ROC**

---

## 📈 Model Performance (Example Results)

| Metric     | Logistic Regression | L1 | L2 |
|-------------|--------------------|----|----|
| Accuracy    | 0.66               | 0.66 | 0.66 |
| Precision   | 0.86               | 0.86 | 0.86 |
| Recall      | 0.69               | 0.69 | 0.69 |
| F1-Score    | 0.76               | 0.76 | 0.76 |
| AUC-ROC     | 0.62               | 0.62 | 0.62 |

All models performed similarly, indicating well-preprocessed features and balanced model setup.

---

## 📂 Folder Structure

```
healthcare-appointment/
├── healthcare_noshows.csv # Dataset (from Kaggle)
├── healthcare-appointment.ipynb # Jupyter Notebook
└── README.md # This file
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/erickhangati/machine-learning-projects.git
   cd machine-learning-projects/logistic-regression/healthcare-appointment

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

3. Open the notebook:
   ```bash
   jupyter notebook healthcare-appointment.ipynb

---

## ✍️ What I Learned

- How to clean and prepare real-world healthcare data.
- How logistic regression works with `Scikit-Learn`.
- The importance of data scaling and feature engineering.
- How to evaluate and compare regularized logistic regression models.

---

## 📘 Blog Article

A full beginner-friendly walkthrough of this project is available on my blog:
[Predict Appointments — Logistic Regression with Scikit-Learn](https://erickhangati.com/predict-appointments-logistic-regression-with-scikit-learn/)