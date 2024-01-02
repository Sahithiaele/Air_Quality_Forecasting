**README.md**

---

# Air Quality Prediction using Regression Techniques

## Overview

This repository contains a dataset and Python code for predicting the Air Quality Index (AQI) using regression techniques. The AQI is a measure of air pollution's impact on health over a short time period, calculated based on average concentrations of specific pollutants.

## Dataset Description

- **Attributes**:
  - PM2.5-AVG
  - PM10-AVG
  - NO2-AVG
  - NH3-AVG
  - SO2-AVG
  - OZONE-AVG
  - air_quality_index (dependent attribute)

The dataset comprises eight attributes, seven of which represent chemical pollution quantities, and one is the dependent attribute, the air_quality_index.

## AQI Levels

The AQI is categorized into several levels based on the AQI value:
- Good: 0 – 50
- Moderate: 51 – 100
- Unhealthy: 101 – 150
- Unhealthy for Sensitive Groups: 151 – 200
- Hazardous: 201+

## Regression Techniques Explored

The regression techniques implemented in this project include:
- Random Forest Regressor
- Ada Boost Regressor
- Bagging Regressor
- Linear Regression

## How to Use the Repository

1. **Clone the Repository**:
   ```
   git clone https://github.com/yourusername/air-quality-prediction.git
   ```

2. **Navigate to the Directory**:
   ```
   cd air-quality-prediction
   ```

3. **Run the Code**:
   Execute the Python script to train the regression models and predict the AQI.

## Results

For given test data with PM2.5-AVG as 123 and PM10-AVG as 95, the predicted AQI value falls under the 'Unhealthy' category.

![image](https://github.com/Sahithiaele/Air_Quality_Forecasting/assets/134089299/77a8bab1-ea73-415d-8422-11a36f4ba437)
![image](https://github.com/Sahithiaele/Air_Quality_Forecasting/assets/134089299/6031e0c9-8d28-4eff-b4a8-101178f767f0)



---

Feel free to explore, contribute, or provide feedback!
