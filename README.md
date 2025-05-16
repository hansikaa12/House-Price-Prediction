# 🏠 House Price Prediction using Machine Learning

## 📌 Problem Statement

Accurately predicting house prices is essential for buyers, sellers, and real estate agencies. With the help of historical housing data and machine learning algorithms, we can estimate the price of a property based on various influencing factors such as location, area, number of rooms, and more.

This project builds regression models to predict house prices based on features extracted from a housing dataset.

---

## 🎯 Objectives

- Perform exploratory data analysis (EDA) to understand key features affecting house prices.
- Clean and preprocess the dataset for model training.
- Build multiple regression models to predict house prices.
- Evaluate and compare model performance using appropriate metrics.
- Identify the most influential features for house pricing.

---

## 🎯 Aim

To develop an accurate and robust regression model that can predict house prices based on various housing attributes.

---

## 📚 Dataset Description

The dataset includes variables such as:

- **Numerical Features**: `LotArea`, `GrLivArea`, `OverallQual`, `YearBuilt`, `GarageArea`, etc.
- **Categorical Features**: `Neighborhood`, `HouseStyle`, `SaleCondition`, etc.
- **Target Variable**: `SalePrice`

---

## 🧪 Exploratory Data Analysis (EDA)

- Distribution plots for numeric features
- Correlation heatmap to identify multicollinearity
- Boxplots to compare price with categorical features
- Outlier detection and handling

---

## 🧼 Data Preprocessing

- Handled missing values via imputation
- One-hot encoded categorical variables
- Feature scaling using StandardScaler
- Train-test split (typically 80/20)
- Optional: log transformation of `SalePrice` to normalize skewed distribution

---

## 🤖 Regression Models Used

- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **XGBoost Regressor** *(if implemented)*

---

## ✅ Model Evaluation

Evaluation metrics used:

- **R² Score**
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

| Model                | R² Score |
|---------------------|----------|
| Linear Regression   | ~78%     |
| Ridge Regression    | ~80%     |
| Lasso Regression    | ~81%     |
| Decision Tree       | ~85%     |
| Random Forest       | **~89%** ✅ |
| XGBoost             | ~88%     |

🏆 **Best Model**: **Random Forest Regressor** with ~89% R² score

---

## 📈 Visualizations

- Actual vs. Predicted Price plots
- Feature importance from tree-based models
- Heatmap of feature correlations
- Distribution of residuals

---

## 🔧 Tools & Libraries

- Python (Jupyter Notebook)
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn
- XGBoost (optional)

---
