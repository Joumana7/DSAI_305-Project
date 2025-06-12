## Credit Card Fraud Detection using Machine Learning and Explainable AI

Credit Card Fraud Detection on IEEE-CIS Dataset: A Comparative and Explainable Machine Learning Approach

Abstract

This project performs a comparative analysis of several machine learning models applied to the IEEE-CIS Fraud Detection dataset. We explore the efficacy of Logistic Regression, Random Forest, SVM, Decision Tree, Naive Bayes, MLP, and XGBoost in identifying fraudulent transactions in a highly imbalanced dataset. We also incorporate interpretability techniques like SHAP, LIME, PDP, ICE, and PFI to explain and justify model decisions. Our results highlight the effectiveness of ensemble models and the importance of explainable AI in fraud detection.

Table of Contents

Introduction

Related Work

Methodology

Installation

Usage

Results and Findings

Explainability & Interpretability

Conclusion

References

Introduction

This project addresses the real-world problem of credit card fraud detection using machine learning and explainable AI. It focuses on answering two research questions:

RQ1: How do traditional ML models perform on a highly imbalanced dataset compared to previous research?

RQ2: Which model balances accuracy and interpretability effectively?

Dataset

We use the IEEE-CIS dataset from Kaggle, containing over 590,000 transaction records, with anonymized features and a binary target indicating fraudulent or legitimate transactions.

Related Work

Previous research has shown high accuracy with models like Random Forest and XGBoost, but most studies neglect interpretability. Our project bridges this gap by integrating XAI tools.

Methodology

Preprocessing

Missing Value Handling: Dropped or imputed.

Feature Scaling: Standard Scaler / MinMax.

Categorical Encoding: Label/One-Hot.

Train-Test Split: 80-20 split with stratification.

Imbalance Handling: SMOTE, class weighting.

Models Implemented

Logistic Regression

Random Forest

Decision Tree

Naive Bayes

Multi-Layer Perceptron


Hyperparameter Tuning

Grid Search / Randomized Search + 5-fold CV.


Install dependencies:

pip install -r requirements.txt

Usage

Run the colab files 


Results and Findings

Best Performance: XGBoost and Random Forest achieved the highest AUC and F1 scores.

Interpretability: Decision Trees and Logistic Regression were easier to explain but less accurate.

Class Imbalance: SMOTE improved model sensitivity significantly.

Explainability & Interpretability

SHAP: Revealed top influencing features like TransactionAmt and ProductCD.

LIME: Explained individual high-risk transactions.

PDP & ICE: Showed marginal and individual feature effects.

PFI: Validated feature importance rankings.

Visual outputs are saved in the outputs/ folder.

Conclusion

This study confirms that ensemble models like XGBoost outperform others in fraud detection tasks but at the cost of interpretability. Explainable AI tools are essential for real-world deployment, enhancing model transparency and trust.

References

Dornadula & Geetha (2019)

Varmedja et al. (2019)

Thennakoon et al. (2019)

Alarfaj et al. (2022)

Vuppula (2021)

Mittal & Tyagi (2019)
