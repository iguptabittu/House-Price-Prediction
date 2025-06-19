# 🏠 House Price Prediction using XGBoost

Predicting house prices using a powerful gradient boosting regression model based on various house features like area, quality, and year built.

## 📌 Overview
This project aims to build an accurate regression model to predict house sale prices using the **XGBoost Regressor**. It includes complete steps such as data preprocessing, exploratory data analysis (EDA), model training, evaluation, and visualization.

## 📊 Problem Statement
House pricing is influenced by multiple factors — size, location, condition, etc. Accurately predicting the price helps both buyers and sellers make informed decisions.

## 📁 Dataset
- Dataset used: **Boston Housing Dataset** from `sklearn.datasets`
- Features include:
  - CRIM, ZN, RM, AGE, DIS, RAD, TAX, etc.
  - Target variable: `price`

## 🔧 Project Workflow

### 1. Data Preprocessing
- Loaded and converted dataset into a DataFrame
- Checked and confirmed no missing values
- Performed correlation analysis with heatmap

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions and relationships between variables
- Used `seaborn` and `matplotlib` for visualization

### 3. Model Building
- Model used: ✅ **XGBoost Regressor (`XGBRegressor`)**
- Trained on 80% of the data and tested on the remaining 20%

### 4. Model Evaluation
- **R² Score**
- **Mean Absolute Error (MAE)**
- Plotted Actual vs Predicted prices

## 📈 Results
- High R² score indicating strong model performance
- Visualization showed close alignment between actual and predicted prices

## 🛠️ Tech Stack
- **Language**: Python
- **Libraries**:
  - `xgboost`
  - `scikit-learn`
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
- **Environment**: Jupyter Notebook

## 🗂️ Project Structure
📦 House-Price-Prediction

├── House_Price_Prediction.ipynb

├── requirements.txt

├── README.md
