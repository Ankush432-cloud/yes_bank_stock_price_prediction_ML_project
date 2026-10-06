# YES BANK Stock Closing Price Prediction

## 📌 Project Overview

This project focuses on predicting the **monthly closing price of YES BANK** using historical stock-market data and machine learning regression techniques.

The project follows a complete end-to-end data science workflow, starting from data preprocessing and exploratory data analysis (EDA) to feature engineering, statistical analysis, model development, hyperparameter tuning, evaluation, and model persistence.

The primary objective is to develop a machine learning model that can learn patterns from historical stock-price data and predict the closing price while maintaining a proper time-series methodology and avoiding data leakage.

> **Note:** This project is developed for educational, analytical, and portfolio purposes. Stock-price predictions should not be considered financial or investment advice.

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze historical YES BANK stock-price data.
- Perform data cleaning and preprocessing.
- Explore stock-price distributions and trends.
- Identify relationships between stock-price variables.
- Perform statistical hypothesis testing.
- Create meaningful time-series features.
- Handle multicollinearity using correlation and VIF analysis.
- Use a chronological train-test split.
- Develop multiple regression models.
- Perform hyperparameter tuning.
- Compare model performance using regression metrics.
- Select the best-performing model.
- Save the final trained model for future predictions.
- Validate the saved model on unseen historical data.

---

## 📊 Dataset

The dataset contains monthly historical stock-price information for YES BANK.

### Dataset Information

| Property | Details |
|---|---|
| Dataset | YES BANK Stock Prices |
| Frequency | Monthly |
| Time Period | July 2005 – November 2020 |
| Total Records | 185 |
| Original Features | 5 |
| Target Variable | `Close` |
| Problem Type | Regression |

### Features

| Feature | Description |
|---|---|
| `Date` | Month and year of the observation |
| `Open` | Opening stock price |
| `High` | Highest stock price during the month |
| `Low` | Lowest stock price during the month |
| `Close` | Closing stock price and prediction target |

---

## 🛠️ Technologies and Libraries

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- XGBoost
- Statsmodels
- Joblib

### Tools

- Jupyter Notebook
- VS Code
- Git
- GitHub

---

# 🔄 Project Workflow

```text
Data Loading
     ↓
Data Preprocessing
     ↓
Exploratory Data Analysis
     ↓
Statistical Hypothesis Testing
     ↓
Feature Engineering
     ↓
Feature Selection
     ↓
Time-Based Data Splitting
     ↓
Model Development
     ↓
Cross-Validation
     ↓
Hyperparameter Tuning
     ↓
Model Evaluation
     ↓
Final Model Selection
     ↓
Model Saving
     ↓
Sanity Check / Prediction