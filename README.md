# DSAI 305 Project

# Interpretable Machine Learning for Classification

This project explores the interpretability of several machine learning models used for a classification task. We trained and analyzed six different classifiers using four distinct Explainable AI (XAI) techniques for each model.The problem is Fraud detection for ieee-fraud detection dataset.

## Models Used

The following machine learning models were implemented and evaluated:

1.  **Logistic Regression**
2.  **Naive Bayes**
3.  **Decision Tree**
4.  **Random Forest**
5.  **XGBoost**
6.  **SVC (Support Vector Classifier)**

## Explainable AI (XAI) Techniques

For each of the six models, we applied the following four interpretability techniques to gain insights into their decision-making processes:

1.  **Partial Dependence Plots (PDP):** Visualize the average effect of a feature on the model's prediction.
2.  **Individual Conditional Expectation (ICE):** Show the dependence of the prediction on a feature for each individual instance.
3.  **SHAP (SHapley Additive exPlanations):** Provide local explanations for individual predictions by quantifying the contribution of each feature.
4.  **Permutation Feature Importance (PFI):** Assess the global importance of features by measuring the decrease in model performance when a feature's values are randomly shuffled.
5.  **Desision Tree Visualization:**Visualize each step leads to the desicion predictied by the model.

## Project Structure

The project likely contains the following structure (adjust based on your actual implementation):
