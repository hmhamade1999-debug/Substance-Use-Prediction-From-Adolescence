Substance Use Prediction From Adolescence
Project Overview

This project builds machine learning models to predict adult substance use outcomes from adolescent behavioral and environmental factors. Using longitudinal survey data, the goal is to identify early predictors of alcohol and marijuana use later in life and evaluate the predictive power of different modeling approaches.

The study applies multiple machine learning models and interpretability techniques to understand which adolescent characteristics contribute most strongly to long-term substance use risk.

This project demonstrates practical skills in data preprocessing, feature selection, model training, evaluation, and explainable machine learning.

Research Question

Can adolescent behavioral, social, and demographic factors predict substance use outcomes in adulthood?

Specifically:

Can we predict adult alcohol use

Can we predict adult marijuana use

Which early-life factors are the strongest predictors of long-term substance use?

Dataset

The project uses a longitudinal health survey dataset containing adolescent responses and later adult outcomes.

Data Structure

Predictors include adolescent variables such as:

Demographics

Family environment

School experiences

Social relationships

Behavioral indicators

Early substance exposure

Outcomes measure substance use in adulthood.

The dataset was processed to:

Remove missing and redundant variables

Reduce multicollinearity

Ensure consistent feature encoding

Prepare predictors for machine learning models

Methodology

The workflow followed a typical machine learning pipeline:

Data cleaning and preprocessing

Feature engineering and variable selection

Train–validation split

Model training

Hyperparameter tuning

Performance evaluation

Model interpretation using SHAP

Evaluation metrics included:

ROC–AUC

Precision

Recall

Confusion Matrix

Threshold optimization using Youden Index

Models Implemented

Several models were trained and compared:

Logistic Regression (L2 Regularization)

Random Forest

XGBoost

CatBoost

Tree-based models allow capturing nonlinear relationships and variable interactions, which are common in behavioral datasets.

Model Performance

Model performance was evaluated using ROC–AUC and classification metrics.

Best models achieved approximately:

AUC ≈ 0.71

This indicates moderate predictive ability, which is expected for complex behavioral outcomes influenced by many factors.

Model Interpretation

To understand model behavior, SHAP (SHapley Additive exPlanations) was used.

SHAP analysis helped identify:

The most influential predictors

The direction of their influence

Different risk archetypes associated with substance use

This step is important for translating machine learning results into interpretable insights.

Tools and Technologies

Python libraries used in this project:

Python

Pandas

NumPy

Scikit-learn

XGBoost

CatBoost

SHAP

Matplotlib

Seaborn
Key Skills Demonstrated

This project demonstrates practical experience in:

Data cleaning and preprocessing

Feature selection

Machine learning model comparison

Hyperparameter tuning

Model evaluation and validation

Explainable AI using SHAP

Data visualization

Reproducible machine learning workflows

Future Improvements

Potential extensions of this project include:

Incorporating additional waves of longitudinal data

Exploring deep learning models

Improving feature engineering

Investigating causal relationships between predictors and outcomes

Applying the model to policy-relevant risk identification
