# ❤️ Heart Failure Death Prediction with Support Vector Machine (SVM)

This project uses a **Support Vector Machine (SVM)** classifier built with **scikit-learn** to predict whether a patient with heart failure is likely to experience a **death event** based on key clinical features.  

It demonstrates a **complete end-to-end machine learning workflow**, from data preprocessing and model training to hyperparameter tuning and evaluation, applied to a **real-world medical dataset**.



## 🧾 Dataset

- **Source:** [Heart Failure Clinical Records Dataset from Kaggle](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data)
- **Samples:** 299 patients  
- **Features:** 12 clinical features  
- **Target Variable:** `DEATH_EVENT`  
  - `1` → Death occurred  
  - `0` → Patient survived  

**Key Features Include:**
- `age` – Patient’s age in years  
- `anaemia` – Decrease of red blood cells (boolean)  
- `creatinine_phosphokinase` – Level of CPK enzyme in the blood  
- `ejection_fraction` – Percentage of blood leaving the heart each time it contracts  
- `high_blood_pressure` – Whether the patient has hypertension  
- `platelets` – Platelet count in the blood  
- `serum_creatinine` – Level of creatinine in the blood (kidney function indicator)  
- `serum_sodium` – Level of sodium in the blood  
- `sex` – Male (1) or Female (0)  
- `smoking` – Whether the patient smokes  
- `time` – Follow-up period (days)  



## 🧠 Project Highlights

- 🔍 Performed **data cleaning and preprocessing**:
  - Handled missing and skewed values  
  - Scaled numerical features using `StandardScaler`  
  - Encoded categorical variables where necessary  
- 📊 Conducted **correlation and collinearity analysis**  
- 🧩 Built a **Pipeline** combining scaling and `LinearSVC` model  
- ⚙️ Optimized hyperparameters (`C`, `loss`, `penalty`) using **GridSearchCV**  
- 📈 Evaluated performance with:
  - Accuracy  
  - Precision, Recall, F1-Score  
  - Confusion Matrix and Classification Report  
- 💡 Interpreted model behavior to identify important clinical predictors



## 📈 Model Performance (Example Results)

| Metric     | Score |
|-------------|--------|
| Accuracy    | 0.82 |
| F1-Score    | 0.67 |
| Precision (Death Event) | 0.79 |
| Recall (Death Event) | 0.58 |

<br>

**Confusion Matrix**

```
[[38 3]
 [8 11]]
```
<br>

✅ **Interpretation:**
- The model correctly identified **38 survivors** and **11 death events**.  
- Misclassifications mainly occurred for the minority class (death events), which is common with imbalanced datasets.  
- The linear SVM provided good generalization while avoiding overfitting.


## 📂 Folder Structure

```
/svm-with-scikit-learn/
├── heart_failure_clinical_records_dataset.csv
├── heart-failure-prediction.ipynb
└── README.md
```

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/erickhangati/machine-learning-projects.git
   cd machine-learning-projects/SVM/heart-failure-svm
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Install dependencies:
   ```bash
   jupyter notebook heart-failure-prediction.ipynb
   ```

## ✍️ What I Learned

- How to use LinearSVC within a Pipeline for clean and reproducible modeling.
- How to perform hyperparameter tuning using GridSearchCV.
- The importance of feature scaling for SVM convergence.
- How regularization (C) controls the trade-off between margin width and misclassification.
- How to interpret SVM results in a healthcare context, focusing on recall and precision for life-critical predictions.

## 📘 Blog Article

A full, beginner-friendly walkthrough of this project is available on my blog:
[XXX](https://erickhangati.com)