# Car Price Prediction

## Project Overview

This project develops a machine learning model to predict used car selling prices based on vehicle characteristics.

The project includes data cleaning, exploratory data analysis, feature preprocessing, model training, evaluation, and feature importance analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Dataset

The dataset contains information about used cars, including:

- Year
- Present Price
- Driven Kilometers
- Fuel Type
- Selling Type
- Transmission
- Owner

The target variable is **Selling Price**.

## Machine Learning Model

A **Random Forest Regression** model was used after preprocessing the numerical and categorical features.

### Model Performance

| Metric | Result |
|---|---:|
| MAE | 1.49 lakhs |
| RMSE | 3.54 lakhs |
| R² Score | 0.51 |

## Key Insights

- Most cars in the dataset have selling prices below ₹10 lakhs.
- Present Price has a strong positive relationship with Selling Price.
- Newer cars generally have higher selling prices.
- Present Price is the most influential feature in the Random Forest model.
- The model performs reasonably well for many cars but has larger errors for some higher-priced vehicles.

## Project Structure

```text
CodeAlpha_Car_Price_Prediction/
│
├── CodeAlpha_Car_Price_Prediction.ipynb
├── car data.csv
└── README.md
