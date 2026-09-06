# House Price Prediction

## Project Overview

A machine learning project that predicts house prices using Linear Regression.

## Dataset

Housing Dataset with 1,460 houses.

### Features Used

- Overall Quality
- Living Area
- Basement Area
- Garage Capacity
- Full Bathrooms
- Total Rooms
- Year Built

**Target:** Sale Price

## ML Workflow

1. Load and explore the data
2. Select important features
3. Handle missing values
4. Split data into training and testing sets
5. Scale the features
6. Train a Linear Regression model
7. Evaluate using MAE, RMSE, and R²
8. Predict house prices

## Model Performance

| MAE | ~$25,319 |
| RMSE | ~$39,716 |
| R² Score | ~0.794 |

## Run the Project

```bash
pip install -r requirements.txt
jupyter notebook House_Price_Prediction.ipynb
```

## Project Files

- `house_prices.csv`
- `House_Price_Prediction.ipynb`
- `requirements.txt`
- `README.md`
