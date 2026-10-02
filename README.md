# PRODIGY_ML_01 – House Price Prediction

Task 1 of my Machine Learning internship at **Prodigy InfoTech**.

## Objective
Predict house prices using a **Linear Regression** model based on square footage, number of bedrooms and bathrooms.

## Dataset
[House Prices – Advanced Regression Techniques (Kaggle)](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

## Steps
1. Data loading and exploration
2. Feature engineering (TotalBath = full + 0.5 × half baths, incl. basement)
3. Outlier removal (GrLivArea > 4000 & SalePrice < 300k)
4. Train/validation split (80/20)
5. Linear Regression training and evaluation
6. Predictions on the test set

## Results
| Metric | Value |
|---|---|
| R² | 0.60 |
| RMSE | ~46,935 $ |

## Tools
Python, Pandas, NumPy, Matplotlib, Scikit-learn
