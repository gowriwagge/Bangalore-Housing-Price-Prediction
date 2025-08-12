# Bangalore-Housing-Price-Prediction

## 📌 Overview
This project predicts housing prices in Bengaluru using **supervised machine learning**. The primary objective is to build a regression model that can estimate property prices based on features like location, size, and amenities.

## 🎯 Objective
- Perform **data preprocessing** and **feature engineering**.
- Train and evaluate multiple regression models.
- Identify the best-performing model for accurate price prediction.

## 🛠 Tech Stack
- **Machine Learning**
- **Python**
- **Scikit-learn**
- **XGBoost**

## 📊 Model Development
### Steps Followed:
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Outlier detection and removal

2. **Exploratory Data Analysis (EDA)**
   - Visualizing data trends and correlations
   - Feature importance analysis

3. **Model Training**
   - Models tried: Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, AdaBoost, Gradient Boosting, XGBoost
   - Evaluation metric: **R² Score**

4. **Best Model**
   - **Model:** XGBoost Regressor
   - **R² Score (Test Set):** 0.8291 (~82.91%)
   - **R² Score (Full Data):** 0.9131 (~91.31%)

## 📈 Results & Impact
- The **XGBoost Regressor** provides the most accurate predictions.
- Helps **buyers, sellers, and real estate agencies** make informed, data-driven pricing decisions.

## 📂 Dataset
Source: [Bengaluru House Price Data - Kaggle](https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data)

## 🚀 Future Enhancements
- Deploy the model as a web application.
- Integrate real-time property listings for live predictions.
- Experiment with deep learning regression models.
