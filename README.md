# Customer Churn Prediction – Machine Learning

## 📌 Project Overview

This project focuses on predicting customer churn in an e-commerce business using Machine Learning classification algorithms.

The goal is to analyze customer behavior, identify patterns associated with customer churn, and compare different machine learning models to evaluate their predictive performance.

## 🎯 Objectives

- Explore and understand the e-commerce dataset.
- Perform Exploratory Data Analysis (EDA).
- Handle missing values and duplicate records.
- Detect and analyze outliers.
- Apply feature preprocessing and encoding.
- Train and evaluate multiple classification models.
- Compare model performance using evaluation metrics.
- Understand overfitting and the effect of model complexity.

## 📂 Project Structure

```text
Machine-Learning-Model/
│
├── Machine-Learning-Model Task1.ipynb
├── dataset/
│   └── E Commerce Dataset.xlsx
├── requirements.txt
└── README.md
```

## 📊 Dataset

**Dataset:** E-Commerce Customer Churn Dataset

**Target Variable:** `Churn`

The dataset contains customer-related information used to predict whether a customer will leave the e-commerce platform.

## ⚙️ Technologies & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Exploration
- Dataset inspection.
- Duplicate detection and removal.
- Missing value analysis.
- Outlier detection.
- Data visualization.

### 2. Data Preprocessing
- Train-test splitting.
- Median imputation for numerical features.
- Most frequent imputation for categorical features.
- Min-Max Scaling.
- One-Hot Encoding.
- Scikit-learn Pipelines and ColumnTransformer.

### 3. Machine Learning Models

The following models and techniques were implemented:

- Decision Tree (Stump and Full Tree).
- Logistic Regression (L1, L2, and Elastic Net).
- Bagging.
- Pasting.
- AdaBoost.
- Voting Classifier (Hard Voting and Soft Voting).

### 4. Model Evaluation

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Training Accuracy
- Testing Accuracy

Additional experiments investigate model complexity, training data size, regularization, and overfitting.

## 🚀 How to Run

1. Clone this repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `Machine-Learning-Model Task1.ipynb`.

5. Make sure the dataset is available and update its file path if necessary.

6. Run all cells.

## 📈 Expected Outcome

A comparative analysis of different machine learning classification algorithms to understand their performance in predicting customer churn and identify the most suitable approach based on evaluation metrics.

## 👨‍💻 Author

**Hossam Al-Azony**

Computer Engineering Student  
Machine Learning Project – Task 1

---

*This project was developed for educational purposes as part of Machine Learning studies.*
