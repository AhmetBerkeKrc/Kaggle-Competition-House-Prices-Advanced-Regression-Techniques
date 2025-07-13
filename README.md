# 🏠 House Price Prediction – Advanced Regression Techniques

This repository contains my end-to-end machine learning pipeline for predicting house prices using Kaggle's "House Prices: Advanced Regression Techniques" dataset.

## 📌 Problem Statement

Given various features describing residential homes in Ames, Iowa, the goal is to predict the final sale price of each home.

## 📊 Techniques Used

- **Exploratory Data Analysis (EDA)**
- **Feature Engineering**
- **Outlier Detection & Handling**
- **Missing Value Imputation**
- **Skewness Correction & Normalization**
- **Modeling with Ridge, Lasso, CatBoost, etc.**
- **Model Ensembling via Stacking Regressor**
- **Evaluation using Root Mean Squared Logarithmic Error (RMSLE)**

## 🧠 Final Model

> **Stacking Regressor**  
> Base Models: Ridge, CatBoost  
> Meta Model: Ridge  
>  
> 📉 Train RMSE (log): `0.08682`  
> 📈 Validation RMSE (log): `0.11639`

## 📝 Note

This solution represents my initial approach to the "House Prices - Advanced Regression Techniques" project. Naturally, there are still areas that can be improved, refined,
or revisited. 
