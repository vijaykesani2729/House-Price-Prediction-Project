# House Price Prediction

## Project Overview

This project predicts house prices using machine learning techniques. The objective is to analyze housing data, identify important factors affecting property prices, and build regression models to estimate house prices accurately.

## Dataset

Dataset Source:
https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

File Used:
- Housing.csv

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Tasks Performed

### 1. Data Loading & Exploration
- Loaded dataset using Pandas
- Examined dataset structure
- Checked missing values
- Identified target and feature variables

### 2. Data Cleaning
- Removed duplicates
- Handled missing values
- Converted categorical variables using one-hot encoding

### 3. Model Building
#### Linear Regression
- Trained and evaluated using:
  - MAE
  - RMSE
  - R² Score

#### Random Forest Regressor
- Trained and compared against Linear Regression

### 4. Data Visualization
- House Price Distribution
- Correlation Heatmap
- Actual vs Predicted Prices
- Feature Importance Analysis

### 5. Insights
- Property area strongly influences house prices.
- Bathrooms and parking spaces contribute significantly to price.
- Furnishing status impacts overall valuation.
- Machine learning models can effectively estimate housing prices.

## Project Structure

```
HousePricePrediction/
│
├── Housing.csv
├── analysis.ipynb
├── summary.pdf
│
└── charts/
    ├── price_distribution.png
    ├── correlation_heatmap.png
    ├── actual_vs_predicted.png
    └── feature_importance.png
```

## Results

The models successfully predicted house prices and identified the most influential features affecting property value.

## Author

Vijay Kesani
