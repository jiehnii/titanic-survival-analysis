# Titanic Survival Prediction

This project analyzes the **Titanic dataset** from Kaggle to predict passenger survival using multiple machine learning models. The workflow includes **data cleaning, exploratory data analysis, feature engineering, model training, and model comparison**.

---

## Project Overview

The objective of this project is to build predictive models that classify whether a passenger survived the Titanic disaster based on demographic and travel information.

The project follows a typical machine learning pipeline:

1. Exploratory Data Analysis (EDA)
2. Data preprocessing and feature engineering
3. Model training and evaluation
4. Feature importance analysis
5. Kaggle submission generation

---

## Models Implemented

The following machine learning models were trained and evaluated:

- Logistic Regression  
- Random Forest  
- K-Nearest Neighbours (KNN)

---

## Model Performance

| Model | Accuracy |
|------|------|
| Logistic Regression | 0.821 |
| Random Forest | 0.838 |
| KNN | 0.827 |

**Random Forest achieved the best validation accuracy.**

---

## Feature Insights

Feature importance analysis across the models shows that:

- **Sex** is the strongest predictor of survival.
- **Passenger class (Pclass)** also significantly affects survival likelihood.
- **Fare and Age** have moderate influence.
- **SibSp, Parch, and Embarked** contribute less to prediction.

These findings align with historical observations that **women and higher-class passengers had higher survival rates**.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## Dataset

Dataset sourced from the **Kaggle Titanic Competition**: https://www.kaggle.com/competitions/titanic
