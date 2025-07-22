# 🚢 Titanic Survival Prediction with Decision Trees

This project uses the classic Titanic dataset to build a machine learning model that predicts whether a passenger survived or not — based on features like age, gender, class, and more. The model is trained using a **Decision Tree classifier**, with a focus on interpretability and understanding model behavior.

---

## 🧠 What You'll Learn

- How to explore and clean real-world tabular data
- Encoding categorical variables and handling missing values
- Training and visualizing a Decision Tree using `scikit-learn`
- Evaluating model performance with accuracy, precision, recall, and F1-score
- How pruning (e.g. `max_depth`) helps control overfitting

---

## 📁 File Structure

```
decision-tree/
├── titanic-dataset.csv
├── titanic-survival-prediction-project.ipynb
└── README.md # this file
```

---

## 📊 Dataset

We use the **Titanic dataset** from [Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset), which contains details of passengers like:

- `Pclass` – Ticket class (1st, 2nd, 3rd)
- `Sex` – Gender
- `Age` – Age in years
- `SibSp`, `Parch` – Family aboard
- `Fare` – Ticket fare
- `Embarked` – Port of embarkation
- `Survived` – 0 = No, 1 = Yes (target)

---

## 🔧 Techniques Used

- Data cleaning and preprocessing
- Label encoding of categorical variables
- Decision Tree Classifier (using `criterion='entropy'`)
- Tree visualization with `plot_tree()`
- Model evaluation: Accuracy, Precision, Recall, F1-score, Confusion Matrix
- Tree pruning (`max_depth`) for improved generalization

---

## ✅ Key Results

- **Initial model accuracy:** ~75%
- **After pruning (max_depth=3):** Accuracy improved to **82%**
- Balanced performance across classes using precision/recall/F1



