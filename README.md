# Car Price Prediction

## Overview
This project predicts the price of cars based on various features such as brand, model, year, mileage, engine size, fuel type, and transmission. It utilizes regression models to analyze and estimate car prices.

## Features
- **Data Preprocessing:**  
  - Handling categorical variables with Label Encoding.  
  - Feature scaling using MinMaxScaler and StandardScaler.  

- **Exploratory Data Analysis (EDA):**  
  - Histograms for visualizing distributions of key numerical features.  
  - Correlation matrix heatmap to understand feature relationships.  

- **Model Training:**  
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
  - Support Vector Regression (SVR)  

## Dataset
The dataset used is `car_price_dataset.csv`, containing features like:
- Brand
- Model
- Year
- Mileage
- Engine Size
- Fuel Type
- Transmission
- Price (Target variable)

## Dependencies
To run this notebook, install the required Python libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
