# 🏠 Simple House Price Prediction using Linear Regression

This project demonstrates a basic application of **Linear Regression** to predict house prices based on square footage using a small, clean dataset. This project is part of the **Lenovo LEAP Learning Program – AI Week 2 Assignment**, focused on understanding core supervised learning concepts.

---

## 📌 Overview

- **Objective**: Predict house prices (in INR Lakhs) using only the square footage (SqFt Area).
- **Model Used**: Linear Regression from `scikit-learn`
- **Platform**: Google Colab / Jupyter Notebook

---

## 📁 Dataset

The dataset used contains the following columns:

| Column         | Description                    |
|----------------|--------------------------------|
| `SqFt Area`    | Total square footage of house  |
| `Price (INR in Lakhs)` | Selling price in INR lakhs  |

### ✅ Preprocessing Steps
- Renamed columns for ease of use (`sqft`, `price`)
- Removed missing values
- Removed outliers using Z-score method

---

## 🧠 Model & Training

- Train-test split: **80% training**, **20% testing**
- Trained using `LinearRegression()` from `sklearn.linear_model`
- Single-feature regression (`sqft → price`)

---

## 📊 Evaluation Metrics

| Metric | Value |
|--------|-------|
| **MSE** (Mean Squared Error) | `3.10` |
| **RMSE** (Root Mean Squared Error) | `1.76` |
| **R² Score** | `1.00` |

> The R² score of 1.00 suggests a perfect linear fit. This indicates that the dataset likely has a direct linear relationship without noise or complex interactions.

---

## 📈 Visualization

The notebook includes a scatter plot comparing the **actual vs. predicted prices**:

- Ideal predictions would lie on the red dashed line
- Most predictions in this model align closely with the actual values

---

## 💡 Key Takeaways

- Learned how to prepare and clean a real dataset
- Explored linear regression with only one input feature
- Gained experience with evaluation metrics specific to regression
- Understood how to visually assess prediction quality

---

## ▶️ How to Run

1. Open the notebook `Simple_House_Price_Prediction.ipynb` in **Google Colab** or Jupyter
2. Upload the dataset: `house_price_data.csv`
3. Run all cells to:
   - Preprocess data
   - Train and evaluate the model
   - Visualize the output

---
