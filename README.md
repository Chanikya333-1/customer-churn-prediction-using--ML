# Customer Churn Prediction using Machine Learning

This project, focuses on predicting customer churn using a real-world Telco customer dataset. The goal is to apply machine learning techniques to understand key drivers of churn and help businesses improve customer retention strategies.

## Overview

- **Data Preprocessing**: Addressed missing values, encoded categorical variables, and handled class imbalance with SMOTE.
- **Exploratory Data Analysis (EDA)**: Conducted comprehensive analysis and visualizations to uncover trends and correlations in customer behavior.
- **Model Development**: Implemented and compared Logistic Regression, Random Forest, and XGBoost models to predict churn outcomes.
- **Evaluation**: Evaluated models using accuracy, precision, recall, and F1-score, selecting the best-performing model for deployment.

## Dataset

The analysis is based on the **Telco Customer Churn** dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`), which includes customer demographics, service details, and churn status.

## Project Workflow

1. Data loading and cleaning
2. Exploratory Data Analysis (EDA)
3. Feature engineering and balancing using SMOTE
4. Training machine learning models
5. Model evaluation and optimization
6. Saving the final model with `pickle` for future use

## Technologies & Libraries

- **Data Analysis**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Machine Learning**: `scikit-learn`, `xgboost`
- **Data Balancing**: `imbalanced-learn (SMOTE)`
- **Model Persistence**: `pickle`

## How to Run

1. Clone this repository:
   ```bash
   git clone <repository-url>
##Author
Chanikya Kothi
