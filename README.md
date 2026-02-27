# Demand Forecasting Project

## Overview
This project builds machine learning models to forecast monthly product demand using historical sales data. It demonstrates the complete data science workflow from data generation to model deployment.

## Dataset
- 24 months of simulated sales data (2024-2025)
- Features: price, promotions, seasonality patterns
- Target variable: monthly demand (units)

## Methods
- **Feature Engineering**: Lag variables, rolling averages, seasonal encoding (sin/cos transforms)
- **Models Tested**: Linear Regression, Ridge Regression
- **Evaluation Metrics**: R² Score, Mean Absolute Error (MAE)

## Key Results
| Model | Training R² | Test R² | Test MAE |
|-------|-------------|---------|----------|
| Linear Regression | 0.88 | -0.20 | 1.49 units |
| Ridge Regression | 0.87 | 0.18 | 1.35 units |

## Business Insights
- Average monthly demand: 57 units
- Promotions increase sales by 8.4% (+4.7 units)
- Ridge Regression selected as final model (better generalization)

## Technologies Used
- Python (Pandas, NumPy, Scikit-learn, Matplotlib)
- Jupyter Notebook
- Git/GitHub

## Files
- `demand_forecasting.ipynb`: Complete analysis notebook
- `README.md`: This file

## How to Run
1. Clone this repository
2. Install requirements: `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Open and run the Jupyter notebook
