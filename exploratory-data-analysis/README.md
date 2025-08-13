# 📊 Telco Customer Churn: EDA, Feature Engineering & Hypothesis Testing

This beginner-friendly project analyzes a [**Telco Customer Churn**](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) dataset to uncover the factors most associated with customer attrition.  
We perform **Exploratory Data Analysis (EDA)**, **Feature Engineering**, and **Hypothesis Testing** to draw actionable insights for business decision-making.

Key concepts demonstrated:

- Data Cleaning & Preprocessing
- Feature Engineering for Business Context
- Exploratory Data Analysis (Univariate & Bivariate)
- Hypothesis Formulation & Statistical Significance Testing
- Communicating Findings to Stakeholders

---

## 📦 Dataset

We use the [**Telco Customer Churn dataset**](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) (IBM sample dataset), which contains:

- **Demographics**: `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- **Services**: `PhoneService`, `InternetService`, `StreamingTV`, `TechSupport`, etc.
- **Contract & Billing**: `Contract`, `PaperlessBilling`, `PaymentMethod`
- **Charges**: `MonthlyCharges`, `TotalCharges`
- **Target variable**: `Churn` (Yes / No)

The dataset has **7,043 customers** and **21 columns**.

---

## 📌 Project Workflow

1. **Dataset Summary**
   - Overview of dataset size, structure, and target variable distribution

2. **Data Cleaning**
   - Handle missing values (e.g., `TotalCharges`)
   - Standardize categorical labels
   - Convert datatypes
   - Remove irrelevant columns (`customerID`)

3. **Feature Engineering**
   - `TotalServices` = count of subscribed services
   - `HasMultipleServices` = binary flag for service bundling
   - `tenure_group` = customer tenure bins (ordinal)
   - `AverageChargesPerService` = average monthly cost per service

4. **Exploratory Data Analysis (EDA)**
   - Univariate: Distributions & summary stats
   - Bivariate: Churn rates by category, numerical features vs churn
   - Correlation analysis including engineered features

5. **Hypothesis Testing**
   - **H1**: MonthlyCharges differ between churned and retained customers (Welch’s t-test)
   - **H2**: Churn is associated with contract type (Chi-square test)
   - **H3**: TechSupport availability affects churn rates (Two-proportion z-test)

6. **Insights & Recommendations**
   - Highlight actionable business findings
   - Suggest retention strategies based on results

---

## 📈 Output

- 📊 Class distribution chart for churned vs retained customers
- 📈 Distributions and boxplots for tenure, charges, and services
- 📉 Churn rate comparisons by contract type, tech support, and payment method
- ✅ Statistical test results with effect sizes and business interpretations
- 🧠 Actionable recommendations for churn reduction

---

## 📂 File Structure

```
telco-customer-churn-eda/
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── telco-customer-churn-eda.ipynb
└── README.md # This file
```


---

## 🛠️ Technologies Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- SciPy (stats tests)
- scikit-learn (encoding)

---

## 📚 What You'll Learn

- How to structure an EDA for business-driven questions
- How to create meaningful features from raw data
- How to visualize relationships between variables and the target
- How to design and run statistical hypothesis tests
- How to communicate findings in a professional report

---

## 📘 Blog Article

A beginner-friendly article based on this project will be published on my blog to walk through every step in depth, including business context, code, and interpretations.
