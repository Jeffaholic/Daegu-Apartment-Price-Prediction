# Daegu Apartment Price Prediction

## 📌 Project Overview
This project builds a Machine Learning regression model to predict apartment transaction prices in Daegu.

The model aims to support real estate agencies in setting competitive and data-driven property prices.

---

## 🏢 Business Problem
Real estate agents often rely on manual estimation when pricing apartments, which can lead to inconsistent or inaccurate pricing.

An inaccurate price may result in:
- Overpricing (property stays unsold)
- Underpricing (financial loss)

This project develops a predictive model to estimate apartment prices based on property characteristics.

---

## 🎯 Objective
Build a regression model that:
- Predicts apartment transaction prices
- Minimizes prediction error
- Supports pricing decisions

---

## 📊 Dataset
The dataset contains apartment transaction records in Daegu, including:
- Property features
- Structural information
- Transaction price (target variable)

Each row represents one apartment transaction.

---

## 🧹 Data Preprocessing
- Handled missing values
- Encoded categorical variables using one-hot encoding
- Split data into training and testing sets (80/20)

---

## 🤖 Modeling Approach

### Baseline Model
- Linear Regression

### Final Model
- Random Forest Regressor

Random Forest was selected as the final model due to better performance and ability to capture non-linear relationships.

---

## 📈 Evaluation Metrics

The model was evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

These metrics were selected because:
- MAE measures average prediction error in currency units.
- RMSE penalizes large errors.
- R² explains how much variance in price is captured by the model.

---

## 📌 Results
MAE: 32183.903744362582
RMSE: 41071.833312402654
R2 Score: 0.8435782938220653

The Random Forest model achieved strong predictive performance and can assist real estate agents in pricing decisions.

---

## ⚠ Limitations
- Model performance depends on historical data.
- May not generalize well to future market shifts.
- Does not include macroeconomic indicators.

---

## 🚀 Future Improvements
- Hyperparameter tuning
- Incorporate external economic data
- Try Gradient Boosting models

---

## 📂 Repository Structure

- `Daegu_Apartment_Capstone.ipynb` → Full project notebook
- `model.pkl` → Saved trained model
- `data_daegu_apartment.csv` → Dataset
- `README.md` → Project documentation

---

## 👤 Author
ZEVANYA MARCELLINO GINTING
Capstone Project – Machine Learning Module 3
