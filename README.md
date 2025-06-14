
# Linear and Polynomial Regression with Scikit-Learn

## 🧾 Overview

This project applies both **Linear Regression** and **Polynomial Regression** techniques to model relationships between a dependent variable and one or more independent variables. It showcases the limitations of linear models on non-linear data and how polynomial terms help improve model performance.

---

## 🧠 Business Understanding

Predictive modeling is critical in many domains:
- Predicting housing prices
- Estimating production output
- Forecasting revenue growth

However, real-world data is rarely perfectly linear. This project demonstrates how polynomial regression can be used to model non-linear trends and improve accuracy without resorting to more complex models.

---

## 📊 Data Understanding

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
- Features transformed with `PolynomialFeatures`
- Linear regression model trained on expanded features

### Evaluation:
- R² Score and Mean Squared Error (MSE)
- Visual plots comparing model predictions with actual data
- Line of best fit plotted for both models

---

## 📌 Conclusion

- **Linear Regression** performs poorly on non-linear data
- **Polynomial Regression** provides a flexible and accurate approach for capturing curvature
- This project highlights the importance of understanding the data before choosing a model

---

## ✅ Tech Stack

- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn

---

