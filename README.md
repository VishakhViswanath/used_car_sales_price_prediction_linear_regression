# used_car_sales_price_prediction_linear_regression
## Overview

This project focuses on estimating the price of used cars based on a real-life dataset from a used car sales company. The dataset contains information about various cars sold by the company, including their specifications and sales prices. The goal of this project is to identify key factors that influence car prices and develop a predictive model using Linear Regression.

The dataset provided is raw and requires extensive preprocessing, which includes Exploratory Data Analysis (EDA), data cleaning, transformation, and visualization. We will then build a Linear Regression model to predict used car prices based on the available features.

## Project Steps

1. **Exploratory Data Analysis (EDA)**:
   - Understand the dataset by exploring the relationships between features and prices.
   - Identify missing values, outliers, and distribution of data.

2. **Data Cleaning and Preprocessing**:
   - Handle missing values, encode categorical variables, and remove irrelevant features.
   - Apply necessary transformations (such as log transformations) to improve model accuracy.

3. **Data Visualization**:
   - Visualize correlations between different car features (e.g., brand, year, mileage, engine size) and car prices.
   - Create informative plots to understand the data distribution and relationships.

4. **Model Construction**:
   - Build a Linear Regression model using `Scikit-learn` to predict car prices.
   - Evaluate the model's performance with metrics like R² (R-squared) score, Mean Squared Error (MSE), and residuals.

5. **Model Evaluation**:
   - The model achieved an **R² score of 75%**, indicating that it explains 75% of the variance in the dataset's car prices, which is a strong predictive performance based on the available features.

## Dataset Information

The dataset consists of the following features:
- `Brand`
- `Body`
- `Model`
- `Year`
- `Mileage`
- `Engine V`
- `Engine Type`
- `Registration`
- `Price` (target variable)

## Tools and Libraries Used

- Python
- Pandas (Data manipulation)
- Matplotlib and Seaborn (Data visualization)
- Scikit-learn (Machine learning and model building)
- NumPy (Mathematical operations)

## How to Run the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/VishakhViswanath/used_car_sales_price_prediction_linear_regression.git

2. Results

The Linear Regression model built in this project achieved an R² score of 75%, indicating a good fit to the data. The model successfully predicts used car prices based on the historical data provided. Further improvements can be made by exploring more advanced regression techniques or using additional features.
Conclusion

This project demonstrates how to apply basic machine learning techniques, including Linear Regression, to predict car prices based on various car specifications. The results are promising, and further refinements to the model could improve predictive accuracy.

    Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
   
   
