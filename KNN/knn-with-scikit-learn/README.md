# ❤️ Heart Disease Prediction with KNN (Using Scikit-Learn)

This project applies the **K-Nearest Neighbors (KNN)** algorithm using **Scikit-Learn** to predict the likelihood of **heart disease** in patients based on clinical and diagnostic features.

It demonstrates an end-to-end workflow — from data cleaning and encoding to model tuning and evaluation — showing how KNN can be applied effectively in a real-world healthcare context.


## 🧾 Dataset

- **Source:** [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)
- Contains **920 patient records** collected from multiple hospitals (Cleveland, Hungary, Switzerland, VA Long Beach)
- Key medical features include:
  - `age` – Patient age in years  
  - `sex` – Male or Female  
  - `cp` – Chest pain type (typical, atypical, non-anginal, asymptomatic)  
  - `trestbps` – Resting blood pressure (mm Hg)  
  - `chol` – Serum cholesterol level (mg/dl)  
  - `fbs` – Fasting blood sugar (>120 mg/dl)  
  - `restecg` – Resting ECG results  
  - `thalch` – Maximum heart rate achieved  
  - `exang` – Exercise-induced angina  
  - `oldpeak` – ST depression induced by exercise relative to rest  
  - `slope`, `ca`, `thal` – Cardiac function indicators  
  - `num` – Target variable (0 = No Heart Disease, 1 = Heart Disease)


## 🧠 Project Highlights

- 🧹 Cleaned and processed 900+ medical records, handling missing and inconsistent data  
- 🔢 Encoded categorical variables using **binary, ordinal, and one-hot encoding** techniques  
- ⚖️ Scaled all numerical features using **StandardScaler** for distance-based learning fairness  
- 🔍 Explored **feature distributions** and **statistical significance** across heart disease classes  
- ⚙️ Trained and tuned a **KNN Classifier** using Scikit-Learn:
  - Baseline model evaluation  
  - Hyperparameter tuning (1 ≤ k ≤ 50)  
  - Binary target transformation for improved interpretability  
- 📈 Achieved **~81.5% accuracy** and **F1-score of 0.85** after tuning


## 📈 Model Performance (Example Results)

| Metric     | Score |
|-------------|--------|
| Accuracy    | 0.815 |
| Precision   | 0.814 |
| Recall      | 0.811 |
| F1-Score    | 0.812 |

**Best k-value range:** 13–16  
This range provided the optimal trade-off between bias and variance.


## 📂 Folder Structure

```
knn-with-scikit-learn/
├── heart_disease_uci.csv
├── knn-with-scikit-learn.ipynb
└── README.md
```


## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/erickhangati/machine-learning-projects.git
   cd machine-learning-projects/KNN/knn-with-scikit-learn
   ```
2. Install dependencies:
   ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3. Open the notebook:
   ```bash
    jupyter notebook knn-with-scikit-learn.ipynb
   ``` 


## ✍️ What I Learned

- How to apply KNN with Scikit-Learn to real healthcare data.
- The importance of feature scaling in distance-based models.
- How to balance bias vs. variance through hyperparameter tuning.
- How to evaluate classification models using precision, recall, and F1-score.
- The real-world implications of using KNN in medical diagnosis scenarios.


## 📘 Blog Article

A full, beginner-friendly walkthrough of this project is available on my blog:
[######](https://erickhangati.com/)