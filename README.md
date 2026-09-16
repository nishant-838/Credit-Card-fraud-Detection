# Credit-Card-fraud-Detection
# 💳 Credit Card Fraud Detection

A machine learning project focused on detecting **fraudulent credit card transactions** using classification algorithms. The project addresses the highly imbalanced nature of fraud datasets and evaluates models using metrics beyond accuracy.

## 📌 Overview

Credit card fraud detection is a challenging classification problem because fraudulent transactions represent only a small fraction of all transactions. This project applies **data preprocessing, SMOTE-based class balancing, exploratory data analysis, and multiple machine learning algorithms** to improve fraud detection.

## 🚀 Features

* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* Feature scaling
* Handling class imbalance using **SMOTE**
* Training multiple classification models
* Model comparison using fraud-focused evaluation metrics
* Confusion matrix visualization
* ROC-AUC evaluation
* Precision, Recall, and F1-score analysis

## 🤖 Machine Learning Models

The following models were trained and compared:

* Logistic Regression
* Random Forest
* XGBoost

## 📊 Evaluation Metrics

Since the dataset is highly imbalanced, **accuracy alone is not sufficient** for evaluating fraud detection performance.

The models are evaluated using:

* **Precision** – Percentage of predicted fraudulent transactions that are actually fraud.
* **Recall** – Percentage of actual fraudulent transactions correctly detected.
* **F1-Score** – Harmonic mean of precision and recall.
* **ROC-AUC** – Measures the model's ability to distinguish between fraudulent and legitimate transactions.
* **Confusion Matrix** – Shows True Positives, False Positives, True Negatives, and False Negatives.

## 🔄 Project Workflow

```text
Dataset
   ↓
Exploratory Data Analysis
   ↓
Data Cleaning & Preprocessing
   ↓
Feature Scaling
   ↓
SMOTE for Class Balancing
   ↓
Model Training
   ↓
Logistic Regression | Random Forest | XGBoost
   ↓
Model Evaluation
   ↓
Precision | Recall | F1-Score | ROC-AUC
```

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Imbalanced-learn
* XGBoost
* Jupyter Notebook

## 📂 Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── credit_card_fraud_detection.ipynb
├── README.md

```

## ⚙️ Installation

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn xgboost jupyter
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

## 📈 Key Learning Outcomes

* Understanding **imbalanced classification problems**
* Applying **SMOTE** for minority-class oversampling
* Comparing traditional and ensemble machine learning models
* Understanding why **precision and recall** are important in fraud detection
* Evaluating classification models using multiple performance metrics

