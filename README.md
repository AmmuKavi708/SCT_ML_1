# 🏡 House Price Prediction Using Linear Regression

## 📌 Project Overview
This project uses a **Linear Regression** model to predict house prices based on:
- Square footage of the living area
- Number of bedrooms
- Number of bathrooms

The model is trained and evaluated using real-world housing data.

---

## 🎯 Objective
Build a machine learning model that can estimate the price of a house using key features that are easy to obtain.

---

## 📁 Dataset
The dataset (`House Prices.csv`) includes:
- `Sqft_living`: Square feet of the living area
- `Bedrooms`: Number of bedrooms
- `Bathrooms`: Number of bathrooms
- `Price`: Target variable (house price)

---

## 🧠 Model
- **Algorithm**: Linear Regression
- **Libraries Used**:
  - `pandas`
  - `scikit-learn`

---

## 🧪 Results
- **Mean Squared Error**: ₹64,14,88,82088.94
- **R-squared Score**: 0.464 (about 46.4% of the price variability is explained)

### 🔢 Model Coefficients:
| Feature        | Coefficient           |
|----------------|------------------------|
| Sqft_living     | + ₹320.32 per sqft     |
| Bedrooms        | − ₹66,861.82 per room  |
| Bathrooms       | + ₹6,040.72 per room   |
| **Intercept**   | ₹86,809.07             |

---

## 📈 Insights
- ✅ Larger living space significantly increases price.
- ⚠️ More bedrooms slightly **decrease** predicted price — possibly due to overlapping space or multicollinearity.
- ✅ More bathrooms contribute positively to price.

---

## 🚀 Future Work
- Include more features (location, year built, condition, etc.)
- Apply regularization techniques (Ridge, Lasso)
- Try non-linear models like Random Forest or XGBoost
- Perform data preprocessing and feature scaling

---
