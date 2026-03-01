# 🏠 Housing Price Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict **median housing prices** using Machine Learning regression techniques.  
The dataset includes demographic and housing-related features, and the goal is to build a model that accurately estimates house values.

This project demonstrates a complete end-to-end Machine Learning workflow including:

- Data preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Model training  
- Model evaluation  

---

## 🎯 Problem Statement

Accurate housing price prediction is important for:

- Real estate businesses  
- Property investors  
- Urban planning  
- Home buyers and sellers  

The objective is to develop a regression model that:

- Minimizes prediction error  
- Generalizes well to unseen data  
- Provides reliable housing price estimates  

---

## 📊 Dataset Description

The dataset contains both numerical and categorical features related to housing and population.

### 🔹 Numerical Features
- Median Income  
- Total Rooms  
- Total Bedrooms  
- Population  
- Households  
- Housing Median Age  

### 🔹 Categorical Feature
- Ocean Proximity  

### 🎯 Target Variable
- `median_house_value`

---

## 🛠️ Project Workflow

The project follows a structured Machine Learning pipeline:

1. Data Loading  
2. Data Cleaning and Handling Missing Values  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Encoding Categorical Variables  
6. Train-Test Split  
7. Model Training  
8. Model Evaluation  

---

## 🤖 Models Implemented

The following regression models were trained and evaluated:

- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  

---

## 📏 Evaluation Metrics

Since this is a regression problem, the models were evaluated using:

- **R² Score** – Measures how well the model explains variance  
- **Mean Squared Error (MSE)** – Measures average squared error  
- **Root Mean Squared Error (RMSE)** – Measures prediction error in the same unit as the target variable  

Higher R² and lower RMSE indicate better model performance.

---

## 🧠 Key Insights

- Median income has a strong positive correlation with housing prices.  
- Ensemble models (Random Forest and XGBoost) outperform Linear Regression.  
- Proper preprocessing and feature engineering significantly improve accuracy.  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  

