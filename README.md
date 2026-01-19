# Airline Passenger Satisfaction Prediction using Machine Learning and XAI

This repository contains the full analytical workflow supporting the MSc dissertation:

**“Predicting Airline Passenger Satisfaction Using Machine Learning:  
A Data-Driven Approach to Enhance Customer Retention.”**

The project applies supervised machine learning models (Logistic Regression, Decision Tree, and Random Forest) to predict passenger satisfaction and uses explainable AI techniques (SHAP) to improve model transparency and managerial interpretability.

## Research Motivation

Airline passenger satisfaction is a critical driver of customer retention, brand loyalty, and long-term profitability in an increasingly competitive and digitally mediated aviation industry. As airlines collect large volumes of passenger feedback data, there is growing demand for analytical approaches that not only predict satisfaction outcomes accurately, but also provide transparent and actionable insights for managerial decision-making.

This project demonstrates how machine learning, combined with explainable artificial intelligence (XAI), can be used to identify the service quality and journey-related factors that most strongly influence passenger satisfaction, supporting evidence-based service improvement and customer experience management.

---

## Repository Contents

- `airline_satisfaction_ml_xai.ipynb`  
  Full Jupyter Notebook including:
  - Exploratory Data Analysis (EDA)
  - Data preprocessing and feature engineering
  - Model training and evaluation
  - Feature importance analysis
  - SHAP explainability analysis

- `README.md`  
  Project overview and reproducibility instructions

- `.gitignore`  
  Prevents raw data and environment files from being committed

---

## Dataset

The analysis uses the **Airline Passenger Satisfaction** dataset, publicly available on Kaggle.

🔗 **Dataset link:**  
https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction

⚠️ Due to Kaggle licensing restrictions, the raw dataset is **not redistributed** in this repository.

---

## How to Reproduce the Analysis

1. Download the dataset from Kaggle using the link above.
2. Extract the CSV file (`train.csv`).
3. Create a folder named `data/` in the project root.
4. Place the CSV file inside the `data/` folder.
5. Open and run `airline_satisfaction_ml_xai.ipynb`.

The notebook uses relative file paths, so no further configuration is required.

---

## Ethical and Licensing Note

This project uses secondary, anonymized survey data for academic research purposes only.  
No personal identifiers are included, and all analysis complies with responsible data usage and institutional research ethics guidelines.
