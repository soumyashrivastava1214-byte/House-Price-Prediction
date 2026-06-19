# House Price Prediction

## Project Overview

This project predicts house prices using Machine Learning techniques. The dataset was cleaned, analyzed, and used to train regression models that estimate house prices based on property features such as area, bedrooms, bathrooms, parking, and amenities.

## Problem Statement

Real estate buyers and sellers often rely on guesswork to estimate property prices. This project aims to build a predictive model that can estimate house prices and identify the factors that most strongly influence them.

## Dataset Information

* Dataset: Housing.csv
* Total Records: 545
* Total Features: 13
* Target Variable: Price

## Data Preprocessing

* Checked for missing values
* Checked for duplicate records
* Applied One-Hot Encoding to categorical features
* Prepared the dataset for machine learning models

## Models Used

### Linear Regression

* MAE: 970,043
* RMSE: 1,324,507
* R² Score: 0.653

### Random Forest Regressor

* MAE: 1,021,546
* RMSE: 1,400,566
* R² Score: 0.612

## Visualizations

* House Price Distribution Histogram
* Correlation Heatmap
* Actual vs Predicted Price Scatter Plot

## Key Findings

* Area was the most influential factor affecting house prices.
* Bathrooms, air conditioning, parking, and stories also contributed significantly.
* Linear Regression performed better than Random Forest Regressor on this dataset.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Structure

House-Price-Prediction/
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
├── requirements.txt
├── README.md
└── charts/
├── price_distribution.png
├── correlation_heatmap.png
└── actual_vs_predicted.png

## Author

Soumya Shrivastava

B.Tech - Artificial Intelligence & Data Science
