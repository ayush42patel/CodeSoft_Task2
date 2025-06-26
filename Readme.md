# 🎬 Movie Rating Prediction using Machine Learning

This project aims to predict IMDb-style movie ratings using machine learning techniques. It is completed as part of a Data Science Internship Task.

---

## 📌 Project Objective

> Build a regression model that predicts the rating given to a movie by users or critics based on historical data like genre, director, votes, and duration.

---

## 🗂️ Dataset

- Dataset: `IMDb_Movies_India.csv`
- Source: Provided in internship or available via Kaggle
- Columns used:
  - `Genre` (categorical)
  - `Director` (categorical)
  - `Votes` (numeric, cleaned)
  - `Duration` (numeric, cleaned)
  - `Rating` (target variable)

---

## ⚙️ Techniques Used

- Data Preprocessing
  - Cleaning `Votes` and `Duration`
  - Handling missing values
  - Label Encoding categorical data
- Model: `RandomForestRegressor`
- Evaluation:
  - R² Score
  - Mean Absolute Error
  - Root Mean Squared Error

---

## 📊 Results

| Metric     | Value        |
|------------|--------------|
| R² Score   | ~0.16        |
| MAE        | ~0.99        |
| RMSE       | ~1.25        |

✅ Model estimates ratings but accuracy can be improved by including more features like actors, release year, etc.

---

## ▶️ Run in Google Colab

https://colab.research.google.com/drive/1lX2mzilszKKWeI25QzVupnq3tgmE6WF-?usp=sharing

---

---
