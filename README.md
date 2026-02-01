# 🏠 House Price Prediction: Linear Regression vs XGBoost

## 📌 Project Overview

This project focuses on predicting house prices using supervised machine learning techniques. The goal is to compare a **baseline linear model** with an **advanced ensemble model (XGBoost)** and understand how model complexity, feature importance, and evaluation strategies affect performance.

---

## 🎯 Objectives

* Build a baseline **Linear Regression** model
* Build an advanced **XGBoost Regressor**
* Compare performance using proper regression metrics
* Apply **cross-validation** and **hyperparameter tuning**
* Interpret the model using **feature importance**

---

## 📊 Dataset

The dataset contains housing-related features such as:

* Location (longitude, latitude, ocean proximity)
* Median income of the area
* House age
* Room, bedroom, household, and population counts

Target variable:

* **House price**

---

## 🧠 Models Used

### 1️⃣ Linear Regression (Baseline)

* Simple and interpretable
* Assumes linear relationships
* Used as a benchmark

### 2️⃣ XGBoost Regressor (Advanced Model)

* Ensemble of decision trees
* Handles non-linearity and feature interactions
* Tuned using GridSearchCV

---

## ⚙️ Model Evaluation

Metrics used:

* **R² Score**
* **Mean Absolute Error (MAE)**
* **Cross-validation (5-fold)**

Results showed:

* Linear Regression provided a reasonable baseline
* XGBoost significantly outperformed Linear Regression
* Cross-validation helped confirm model stability and reduce overfitting

---

## 🔍 Feature Importance (XGBoost)

The most influential features were:

1. Ocean proximity
2. Median income
3. Latitude & Longitude

This aligns well with real-world housing economics, where location and income strongly influence house prices.

---

## ✅ Key Learnings

* Advanced models capture complex patterns better than linear models
* Cross-validation is essential for reliable evaluation
* Feature importance helps build trust in black-box models
* High accuracy alone is not enough — interpretability matters

---

## 🛠 Tools & Libraries

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib / Seaborn

---

## 🚀 Future Improvements

* Add SHAP for deeper model explainability
* Perform error analysis on extreme predictions
* Deploy model using Streamlit or Flask

---

## 📬 Contact

Feel free to connect with me on LinkedIn to discuss Machine Learning, Data Science, and AI projects!
