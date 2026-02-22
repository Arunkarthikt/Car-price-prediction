# Car-price-prediction
Project Overview

This project analyzes used car data and builds a Machine Learning model to predict car selling prices. The goal is to understand key factors influencing resale value and develop a predictive model with good accuracy.
 Dataset Information

Duplicate Records Removed: 763

Target Variable: Selling_Price

Features:

Brand

Model

Year

KM_Driven

Fuel

Seller_Type

Transmission

Owner

✔ No missing values were found in the dataset.

🔍 Data Preprocessing

Removed 763 duplicate records

Applied Log Transformation to Selling_Price (to handle skewness)

Created new feature:
Car_Age = Current Year − Year

Encoded categorical variables using One-Hot Encoding

Converted Owner category into numeric format

Dropped Brand and Model (high cardinality)

 Model Building

Selected important features based on Linear Regression coefficients

Train-Test Split: 80% – 20%

Model Used: Linear Regression

Applied 5-Fold Cross Validation

📈 Model Performance
Metric	Score
Train R²	0.69
Test R²	0.67
Cross Validation R²	0.68
Model Accuracy (Approx.)	~70%
RMSE	0.47

✅ The model explains approximately 70% of the variance in car prices.

 Key Insights

Diesel cars generally have higher resale value

Manual transmission slightly reduces price

Car age negatively impacts selling price

First-owner vehicles retain better value

Kilometers driven negatively affects price

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn
