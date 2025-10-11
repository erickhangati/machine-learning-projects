# 🩺 Diabetes Prediction with KNN (Built from Scratch Using NumPy)

This project builds a **K-Nearest Neighbors (KNN)** classifier **from scratch using NumPy** to predict whether a patient has diabetes based on key medical features.  

It demonstrates how KNN works internally, from distance calculation to majority voting, without using pre-built machine learning libraries.

---

## 🧾 Dataset

- **Source:** [Kaggle - Diabetes Dataset](https://www.kaggle.com/datasets/nanditapore/healthcare-diabetes)
- Each record contains medical measurements such as:
  - `Pregnancies` – Number of times pregnant  
  - `Glucose` – Plasma glucose concentration  
  - `BloodPressure` – Diastolic blood pressure  
  - `SkinThickness` – Triceps skin fold thickness  
  - `Insulin` – Serum insulin level  
  - `BMI` – Body Mass Index  
  - `DiabetesPedigreeFunction` – Genetic risk measure  
  - `Age` – Patient age in years  
  - `Outcome` – 1 = Diabetic, 0 = Non-diabetic

---

## 🧠 Project Highlights

- 🧹 Cleaned and prepared 2,700+ patient records  
- 🔍 Replaced biologically implausible zeros with missing values and filled them using the median  
- 📊 Explored feature distributions and relationships with the target variable  
- 📈 Implemented **KNN from scratch using only NumPy**:
  - Custom Euclidean distance function  
  - Manual distance computation and majority voting  
  - Feature scaling for distance fairness  
- 🧮 Achieved **83.5% accuracy** on the test data  
- 📋 Evaluated performance using **confusion matrix**, **precision**, **recall**, and **F1-score**

---

## 📈 Model Performance (Example Results)

| Metric     | Score |
|-------------|--------|
| Accuracy    | 0.835 |
| Precision (Diabetic) | 0.73 |
| Recall (Diabetic) | 0.78 |
| F1-Score (Diabetic) | 0.75 |

**Confusion Matrix**

```
[[484 78]
 [59 210]]
```


- 484 true negatives (non-diabetic correctly predicted)  
- 210 true positives (diabetic correctly predicted)  
- 78 false positives and 59 false negatives  

The model performs strongly across both classes, slightly favoring non-diabetic predictions due to class imbalance.

---

## 📂 Folder Structure

```
knn-with-numpy/
├── diabetes.csv # Dataset (from Kaggle)
├── knn-with-numpy.ipynb # Jupyter Notebook
└── README.md # This file
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/erickhangati/machine-learning-projects.git
   cd machine-learning-projects/KNN/knn-with-numpy
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Install dependencies:
   ```bash
   jupyter notebook knn-with-numpy.ipynb
   ```
 
## ✍️ What I Learned

- How to manually implement KNN using NumPy without scikit-learn.
- How Euclidean distance drives similarity-based learning.
- The importance of data scaling in distance-based algorithms.
- How to analyze feature relationships and validate statistical significance.
- How to evaluate classification performance using multiple metrics.

## 📘 Blog Article

A full, beginner-friendly walkthrough of this project is available on my blog:
[KNN with NumPy: A Beginner’s Guide to K – Nearest Neighbors](https://erickhangati.com/knn-with-numpy-beginners-guide-k-nearest-neighbor/)