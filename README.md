# House Price Prediction – Kaggle Competition

This repository contains my solution for the [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) competition on Kaggle.  
Using an ensemble of **Support Vector Regression (SVR)** and **XGBoost**, I achieved a Kaggle **score of 0.12274** and ranked **451 out of 4200+ participants**.

---

## 📌 Project Overview
The objective of this competition is to predict the final price of homes based on a dataset containing **79 explanatory variables** describing almost every aspect of residential homes in Ames, Iowa.

My approach involved:
- Extensive **data preprocessing**
- Comparing multiple models:
  - XGBoost
  - SVR
  - CatBoost
  - Gradient Boosting Regressor (GBR)
- Selecting **XGBoost** and **SVR** as the best-performing models
- Applying **hyperparameter tuning** for optimal performance
- Ensembling SVR + XGBoost for the final predictions
  
---

## 🚀 Model & Techniques
- **Data Preprocessing:**
  - Handling missing values
  - Encoding categorical variables
  - Scaling numerical features
- **Model Evaluation & Selection:**
  - Compared XGBoost, SVR, CatBoost, and GBR
  - Chose XGBoost & SVR based on cross-validation performance
- **Hyperparameter Tuning:**
  - Grid Search and Random Search to optimize model parameters
- **Ensembling:**
  - Blending predictions from SVR & XGBoost for improved accuracy

---

## 🏆 Performance
- **Kaggle Public Score:** 0.12274  
- **Leaderboard Rank:** 451 / 4200+ participants

---

## 📖 Usage
1. Open the notebook in Google Colab or Jupyter.
2. Ensure the dataset is available in the correct path or load it directly from Kaggle.
3. Run all cells to reproduce the results.

---
