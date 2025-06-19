# 🏠 House Price Prediction using Machine Learning

Predicting house prices using various machine learning models based on features like area, quality, and year built.

## 📌 Overview
This project aims to build an accurate regression model that can predict house sale prices given various housing features. It follows a complete machine learning pipeline — including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and hyperparameter tuning.

## 📊 Problem Statement
House pricing is influenced by many factors — size, location, condition, etc. Accurately predicting the selling price of a house helps both buyers and sellers make informed decisions.

## 📁 Dataset
- A structured dataset containing features such as:
  - `LotArea`, `OverallQual`, `YearBuilt`, `TotalBsmtSF`, `GrLivArea`, etc.
  - Target variable: `SalePrice`

## 🔧 Project Workflow

### 1. Data Preprocessing
- Handled missing values (mean/mode imputation)
- Label Encoding / One-Hot Encoding for categorical features
- Feature scaling using `StandardScaler`

### 2. Exploratory Data Analysis (EDA)
- Visualized feature distributions and relationships
- Correlation heatmaps to identify important predictors

### 3. Model Building
Implemented and evaluated the following models:
- 🔹 Linear Regression
- 🌲 Decision Tree Regressor
- 🌳 Random Forest Regressor
- 🚀 Gradient Boosting Regressor

### 4. Model Evaluation
- Metrics used:
  - **R² Score**
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**
- Best model selected based on highest R² and lowest error

### 5. Hyperparameter Tuning
- Used GridSearchCV to improve model performance

## 📈 Results
- Achieved high prediction accuracy using ensemble models
- Random Forest and Gradient Boosting yielded the best performance

## 🛠️ Tech Stack
- **Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, seaborn, matplotlib
- **Environment**: Jupyter Notebook

## 🗂️ Project Structure
 House-Price-Prediction
├── Project_4_House_Price_Prediction.ipynb
├── data/
│ └── housing.csv (or similar)
├── requirements.txt
├── README.md
