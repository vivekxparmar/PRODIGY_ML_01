# 🏠 House Price Prediction using Linear Regression

A simple yet effective machine learning project that predicts house prices based on key features from the Ames Housing dataset using Linear Regression.

---

## 📌 Project Overview

This project focuses on predicting the **SalePrice** of homes using just 6 core features. It demonstrates how minimal, well-preprocessed data can produce valuable predictions with a linear model.

---

## 🚀 Tech Stack

- Python 🐍  
- Pandas & NumPy  
- scikit-learn  
- Google Colab 
- Dataset from Kaggle

---

## 🧠 Features Used

- `GrLivArea` – Above ground living area (sq ft)  
- `BedroomAbvGr` – Number of bedrooms above ground  
- `BsmtFullBath` – Basement full bathrooms  
- `BsmtHalfBath` – Basement half bathrooms  
- `FullBath` – Full bathrooms above ground  
- `HalfBath` – Half bathrooms above ground

---

## 🧰 Steps Involved

1. **Load and preprocess data**
   - Drop rows with missing `SalePrice`
   - Remove outliers in `GrLivArea`
   - Fill missing values using median imputation

2. **Transform & Scale**
   - Apply log transformation on `SalePrice` for normality
   - Standardize features using `StandardScaler`

3. **Modeling**
   - Train/test split
   - Fit a `LinearRegression` model
   - Evaluate using RMSE on validation data

4. **Prediction**
   - Apply the model on the test dataset
   - Generate final predictions and save to `submission.csv`

---

## 📊 Results

- 📈 Achieved strong validation results using RMSE
- 🧾 Generated clean `submission.csv` with predicted house prices
- 🔁 Ready for further improvement via Ridge, Lasso, or Ensemble models

---

## 📁 Files in This Repo

| File               | Description                            |
|--------------------|----------------------------------------|
| `train.csv`        | Training dataset                       |
| `test.csv`         | Test dataset (no target values)        |
| `.ipynb`           | Python file for training/prediction    |
| `submission.csv`   | Output file with predicted `SalePrice` |

---

## 🤝 Let's Connect!

Feel free to fork this repo, open issues, or reach out for collaboration.  
If you like this project, give it a ⭐️ and share your feedback!

---
