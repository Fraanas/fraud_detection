# Financial Fraud Detection

## Introduction

In this project, we aim to build a machine learning model to detect financial fraud. The dataset used is highly imbalanced, with 99% of the transactions being non-fraudulent. We will experiment with various techniques for handling this imbalance, such as:
* Undersampling,
* Oversampling,
* SMOTE (Synthetic Minority Over-sampling Technique),
* Anomaly detection using clustering, (will be developed at a later stage)
* Synthetic data generation using GANs, (will be developed at a later stage).

The goal is to develop a classifier that can effectively identify fraudulent transactions, despite the significant class imbalance.

## Notebook Contents

1. Data Overview
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing 
4. Data Scaling
5. Addressing Class Imbalance
6. Model Building and Evaluation
7. Model Tuning
8. Conclusions

## Data Overview

The dataset consists of transaction records with the following features:

- **Class**: Label indicating whether the transaction is fraudulent (1) or not (0).
- **Amount**: The transaction amount.
- **Time**: Time elapsed since the first transaction in the dataset.
- **V1-V28**: PCA-transformed features representing anonymized data.

## Model Building and Evaluation


"LogisiticRegression": LogisticRegression(),
    "KNearest": KNeighborsClassifier(),
    #"Support Vector Classifier": SVC(),
    "DecisionTreeClassifier": DecisionTreeClassifier()

Multiple machine learning algorithms are used to build models, including:

- Logistic Regression
- KNeighbors Classifier
- Decision Tree Classifier
- Anomaly detection methods (e.g., Isolation Forest, One-class SVM, K-means), (will be developed at a later stage)

We evaluate the models using metrics such as precision, recall, F1-score, and the ROC-AUC score.

## Model Tuning

We use GridSearchCV to fine-tune the hyperparameters of the best-performing models to further enhance their predictive power. (will be developed at a later stage)

## Conclusions

(will be developed at a later stage)
