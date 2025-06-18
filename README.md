# Ames Housing Price Prediction: Regression & Statistics

Modeling house prices using OLS regression, Ridge, and Lasso with multicollinearity analysis.

---

## 🚀 Project Goals
- Perform regression analysis on a real estate dataset
- Interpret coefficients and p-values from OLS
- Compare regularized models using `Ridge` and `Lasso`

---

## 📦 Dataset
- Source: [Ames Housing Dataset](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)
- Target: `SalePrice`

---

## 📌 Coding Exercises

### 1. EDA & Preprocessing
- Clean nulls, drop outliers (e.g. above 4000 sqft or below $50,000)
- Create boxplots of `GrLivArea`, `OverallQual`, and `SalePrice`
- Log-transform `SalePrice` and `GrLivArea` if skewed

### 2. Feature Selection & OLS
- Select 5–10 features to model with `statsmodels`
- Fit an OLS model and interpret:
  - Coefficients
  - p-values
  - R²
- Plot residuals vs fitted values

### 3. Multicollinearity Check
- Calculate VIF (Variance Inflation Factor)
- Drop/reduce features with high multicollinearity

### 4. Regularization Comparison
- Train and compare:
  - `LinearRegression`
  - `RidgeCV`
  - `LassoCV`
- Plot RMSE for each
- Plot Ridge and Lasso coefficient shrinkage

---

## 🧠 Key Questions
- Which variables best predict price?
- What does multicollinearity tell us about the model?
- When should you prefer Ridge over Lasso?

---
