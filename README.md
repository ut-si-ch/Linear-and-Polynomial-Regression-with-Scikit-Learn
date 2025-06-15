
# Linear and Polynomial Regression with Scikit-Learn

## 🧾 Overview

This project focuses on **predicting housing prices** using the Boston Housing Dataset. The problem addressed is predicting the median value of owner-occupied homes in Boston using various features. The dataset used contains **506 instances** with **13 features** and a target variable representing the price. The modeling involved implementing and evaluating **Linear Regression** and **Polynomial Regression models**.

---

## 🧠 Business Understanding

The primary stakeholders for this project would be real estate professionals, urban planners, or potential homebuyers/sellers interested in understanding the factors influencing housing prices in Boston. The business problem is to build a model that can accurately predict housing prices, which can aid in property valuation, investment decisions, or policy-making related to urban development.

Predictive modeling is critical in many domains:
- Predicting housing prices
- Estimating production output
- Forecasting revenue growth

However, real-world data is rarely perfectly linear. This project demonstrates how polynomial regression can be used to model non-linear trends and improve accuracy without resorting to more complex models.

---

## 📊 Data Understanding

The dataset used is the Boston Housing Dataset, which contains information about housing in Boston. The data includes features like crime rate, the proportion of residential land, the proportion of non-retail business acres, the Charles River dummy variable, nitric oxides concentration, average number of rooms, proportion of owner-occupied units built prior to 1940, weighted distances to five Boston employment centers, index of accessibility to radial highways, full-value property-tax rate per $10,000, pupil-teacher ratio by town, proportion of black residents by town, and lower status of the population. A limitation is the dataset's age, as housing market dynamics may have changed since its collection. The notebook includes visualizations such as a scatter plot of true vs. predicted values and a correlation heatmap to understand relationships between features.

![image](https://github.com/user-attachments/assets/5b118bc3-d681-46e8-83f2-d15cddbfec3b)

![image](https://github.com/user-attachments/assets/109f6fac-3398-418a-8b64-00e80332a62a)



The dataset used in this project includes synthetic or real-world numerical input data with a continuous target variable. Key characteristics:
- 1D or 2D feature space
- Clearly observable non-linear trends
- Preprocessed and ready for modeling

### Steps:
- Load dataset (possibly via CSV or generated)
- Visualize data with scatter plots
- Detect non-linear relationships through plotting

---

## 🤖 Modelling & Evaluation

### 1. Linear Regression
- Applied using `LinearRegression` from scikit-learn
- Trained on the raw feature(s)

### 2. Polynomial Regression
- Features transformed with `PolynomialFeatures` of degree 2 were created from original features
- Linear regression model trained on expanded features

### Evaluation:
- R² Score, Root Mean Squarred Error (RMSE) and Mean Squared Error (MSE)
- Visual plots comparing model predictions with actual data
- Line of best fit plotted for both models

---

## 📌 Conclusion
Based on the evaluation metrics (RMSE, MAE, and R2 Score), Polynomial Regression has a lower RMSE (3.78 vs 4.93) and MAE (2.57 vs 3.19) compared to Linear Regression. This indicates that the polynomial model's predictions have smaller errors on average. Other than this, it has a higher R2 Score (0.81 vs 0.67) compared to Linear Regression. This means the polynomial model explains a larger proportion of the variance in housing prices.So comparitvely Polynomial Regression model performs better at predicting housing prices.  Future steps could include exploring other regression models (e.g., Ridge, Lasso, or more complex models), performing more in-depth feature engineering, addressing potential multicollinearity issues (as suggested by the OLS summary), or acquiring more recent housing data for improved accuracy and relevance.

- **Linear Regression** performs poorly on non-linear data
- **Polynomial Regression** provides a flexible and accurate approach for capturing curvature

This project highlights the importance of understanding the data before choosing a model

---

## ✅ Tech Stack

- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn

---

