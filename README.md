Collecting workspace informationFiltering to most relevant information# Credit Risk Prediction Project Documentation

## Overview

This project is the final task of a Data Science internship program at **ID/X Partners X Rakamin Academy**. As an intern, you are tasked to collaborate with multiple departments to deliver a technology solution for a lending company. The main objective is to build a predictive model that can assess credit risk using a provided dataset containing both accepted and rejected loan applications. The solution aims to help the company automate and optimize its credit evaluation process, reduce default rates, and improve customer acquisition.

---

## Key Features

- **End-to-End Data Science Pipeline:**
  Covers data understanding, cleaning, feature engineering, model building, evaluation, and interpretation.

- **Multiple Model Comparison:**
  Implements and compares several machine learning algorithms, including Logistic Regression, Naive Bayes, and Random Forest, with hyperparameter tuning.

- **Automated Credit Risk Classification:**
  Predicts the risk level (high/low) for each loan application, supporting automated and consistent decision-making.

- **Feature Importance Analysis:**
  Provides insights into the most influential factors affecting credit risk, supporting business interpretability.

---

## Key Steps

1. **Business Understanding**
   - Identified business problems: high default rate, inefficient manual evaluation, and potential customer loss.
   - Defined project goals: accurate risk identification, process automation, and optimized lending decisions.

2. **Data Understanding**
   - Explored the dataset structure, sample records, and feature types.
   - Assessed data quality, missing values, and potential inconsistencies.

3. **Data Preparation**
   - Removed duplicates, irrelevant columns, and single-value columns.
   - Handled missing values and inconsistent data entries.
   - Encoded categorical variables and engineered new features (e.g., credit age, months since last payment).

4. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions and outliers using histograms and boxplots.
   - Analyzed feature correlations to address multicollinearity.

5. **Feature Selection**
   - Removed highly correlated and redundant features to improve model performance.

6. **Model Building & Training**
   - Split data into training and testing sets (80/20).
   - Trained and tuned Logistic Regression, Naive Bayes, and Random Forest models using cross-validation.
   - Recorded best parameters and scores for each model.

7. **Model Evaluation**
   - Selected the best-performing model based on recall score.
   - Evaluated model performance on the test set using accuracy, recall, precision, F1-score, confusion matrix, and classification report.

8. **Feature Importance & Interpretation**
   - Analyzed and visualized feature importances to provide business insights.

---

## Acknowledgements

- **ID/X Partners** and **Rakamin Academy** for organizing and mentoring the internship program.
- The lending company for providing the dataset and business context.
- All collaborating departments and mentors for their guidance and support throughout the project.

---

For further details, refer to the main notebook: credit_risk_prediction.ipynb