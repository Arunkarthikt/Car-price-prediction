🚗 Car Price Prediction
📌 Project Overview

This project combines Exploratory Data Analysis (EDA) and Machine Learning to analyze used car data and predict selling prices.

The project is divided into two parts:
An interactive dashboard was built in Power BI to visualize car resale trends and key influencing factors.

🔎 Dashboard Features
📌 KPI Cards

Total Brands: 29

Total Models: 1,475

Average Selling Price: ₹473.91K

📈 Visualizations Included

Average Selling Price by Year

Shows increasing price trend for newer vehicles

Average Selling Price by Owner Type

First-owner cars have highest resale value

Average Selling Price by Fuel Type

Diesel cars have highest average price

Average Selling Price by Brand

Luxury brands (Land Rover, Mercedes-Benz, BMW, Audi) show highest prices

Transmission Comparison

Automatic cars generally priced higher than manual

Scatter Plot (KM Driven vs Selling Price)

Higher KM driven reduces resale value

🎛 Interactive Filters (Slicers)

Year & Brand

Transmission

Model

KM Driven range slider

These slicers allow dynamic filtering and real-time insights.

🤖 Machine Learning – Car Price Prediction
📊 Dataset Summary

Original Records: 4,340

Duplicates Removed: 763

Final Records Used: 3,577

No missing values

⚙️ Feature Engineering

Log transformation on Selling_Price

Created Car_Age feature

Encoded categorical variables

Converted Owner to numeric

Removed high-cardinality columns (Brand, Model)

📈 Model Used

Linear Regression

80–20 Train-Test Split

5-Fold Cross Validation

📊 Model Performance
Model Accuracy	~70%

✅ The model explains approximately 70% of price variation.

🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Power BI

📌 Key Business Insights

Diesel vehicles retain better resale value.

First-owner cars sell at higher prices.

Automatic transmission cars have premium pricing.

Newer vehicles show strong upward price trend.

KM Driven negatively impacts price.
