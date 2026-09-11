# House Price Prediction using Simple Linear Regression

## 📌 Project Overview
This project explores the relationship between a house's living space square footage (`sqft_living`) and its sale price. Built using Python, Pandas, and Scikit-Learn, this model demonstrates how data-driven filtering improves predictive accuracy in real estate modeling.

## 📊 The Problem & The Solution
* **The Baseline Flaw:** Initially, feeding raw data into the linear regression model yielded a poor **R-squared score of 0.0291 (2.9%)**. Visual analysis revealed that extreme luxury outliers heavily skewed the regression line.
* **The Engineering Fix:** By implementing custom filters to target the core consumer market (restricting data to properties under \$3,000,000 and under 6,000 sqft), data noise was removed.
* **The Result:** The refined model's predictive power **surged to an R-squared score of 0.3767 (37.7%)**.

## 🔑 Key Insights
* **The Formula:** `Price = ($267.22 * sqft_living) - $26,048.21`
* Within the target housing market segment, each additional square foot of living space increases a home's predictive valuation by an average of **\$267.22**.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Kaggle Notebooks
