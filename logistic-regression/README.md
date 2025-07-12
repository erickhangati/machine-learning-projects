# 📧 Spam Email Classification with Logistic Regression (From Scratch Using NumPy)

This project demonstrates how to build a **logistic regression model from scratch using NumPy** to classify emails as spam (1) or ham (0), based on real-world datasets.

We apply classic machine learning techniques to text data without relying on machine learning libraries — showcasing a full understanding of the math and workflow behind logistic regression.

---

## 🧾 Dataset

- Combined from:
  - **2007 TREC Public Spam Corpus**
  - **Enron-Spam Dataset**
- Each record contains:
  - `text`: Raw email content
  - `label`: 1 for spam, 0 for ham

Source: [Kaggle - Spam Email Classification Dataset](https://www.kaggle.com/datasets/purusinghvi/email-spam-classification-dataset)

---

## 🧠 Project Highlights

- 🧹 Cleaned and preprocessed 10,000+ raw email texts
- 🧮 Transformed text to numerical vectors using Bag-of-Words (`CountVectorizer`)
- 🔁 Implemented **logistic regression manually** (NumPy only)
- 📉 Computed binary cross-entropy loss and gradient updates
- 🔒 Added **L2 regularization** to improve generalization
- 📊 Evaluated accuracy, confusion matrix, and classification report
- 🧪 Visualized data with PCA for interpretation

---

## 📈 Model Performance

| Metric     | Value (Example Run) |
|------------|---------------------|
| Accuracy   | ~93% (after tuning) |
| Model      | Logistic Regression |
| Features   | Top 3,000 words     |
| Regularization | L2 (`lambda=10.0`)  |

---

## 📂 Folder Structure

```
logistic-regression/
├── combined-data.csv 
├── email-spam-classification.ipynb # Jupyter notebook (main project)
└── README.md # This file
```
---

## 🚀 How to Run

1. Download the dataset from Kaggle and place it as `combined-data.csv` inside the `logistic-regression/` folder.
2. Install required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## ✍️ What I Learned
- Implementing ML algorithms from first principles.
- Applying NLP preprocessing on real-world text.
- How logistic regression makes probabilistic predictions.
- The role of regularization in preventing overfitting.