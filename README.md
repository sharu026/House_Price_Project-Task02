# House_Price_Project-Task02
# House Price Prediction using Machine Learning

## Project Overview
This project focuses on predicting house prices using Machine Learning regression algorithms. The dataset contains various housing features such as area, bedrooms, bathrooms, stories, parking, and furnishing status. The goal is to build an accurate regression model for predicting house prices.

## Dataset
Dataset used:
https://www.kaggle.com/datasets/bhanupratapbiswas/house-price-prediction

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Machine Learning Models
The following regression algorithms were trained and compared:
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Data Preprocessing
The following preprocessing techniques were performed:
- Handling missing values
- Label Encoding for categorical features
- Feature Scaling using StandardScaler
- Log Transformation on target variable
- Train-Test Split

## Exploratory Data Analysis (EDA)
Performed:
- House price distribution analysis
- Correlation heatmap
- Feature relationship analysis
- Residual analysis

## Evaluation Metrics
Models were evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Best Model
Random Forest Regressor achieved the best performance for house price prediction.

## Saved Model
The trained model is saved as:

```text
house_price_model.pkl
```

## Example Prediction Code

```python
import joblib
import numpy as np

# Load trained model
model = joblib.load("house_price_model.pkl")

# Example input
sample = [[7420, 4, 2, 3, 2]]

# Predict
prediction = model.predict(sample)

print("Predicted House Price:", prediction)
```

## Project Files

```text
House_Price_Project/
│
├── Housing.csv
├── house_price_prediction.ipynb
├── house_price_prediction.html
├── house_price_model.pkl
├── README.md
├── screenshots/


## Author
Sharanya N
