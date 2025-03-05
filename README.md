# Climate-Smart-Precision-Agriculture

## Overview

This project aims to predict agricultural and environmental outcomes using machine learning models. We use various environmental factors such as average temperature, precipitation, CO2 emissions, crop yield, and more to forecast key agricultural and economic impacts. We evaluated the performance of two models: a baseline model and an advanced XGBoost model. The project includes data preprocessing, model training, and analysis of relationships between variables to derive insights that could improve prediction accuracy and inform agricultural practices.

### Key Objectives

- Model Building: Develop machine learning models to predict agricultural and environmental outcomes using features like temperature, precipitation, CO2 emissions, crop yield, and more.
- Evaluation: Evaluate the performance of the models using key metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.
- Feature Analysis: Explore relationships between key variables using correlation analysis to uncover insights into how environmental and agricultural factors influence each other.
- Model Comparison: Compare the baseline model with an advanced XGBoost model to determine the effectiveness of different modeling techniques.

### Dataset

The dataset includes various environmental and agricultural metrics over a period of time, such as:

- Average Temperature (°C)
- Total Precipitation (mm)
- CO2 Emissions (Metric Tons)
- Crop Yield (MT per HA)
- Extreme Weather Events
- Irrigation Access (%)
- Pesticide Use (kg per HA)
- Fertilizer Use (kg per HA)
- Soil Health Index
- Economic Impact (Million USD)

### Model Evaluation

1. Baseline Model:
- MAE: 0.7258
- MSE: 0.7398
- R² Score: 0.2990

XGBoost Model:
- MAE: 0.7360
- MSE: 0.7709
- R² Score: 0.2696

Both models demonstrate significant room for improvement, with the R² scores indicating that more sophisticated models or feature engineering are needed.

#### Key insights from the correlation analysis include:

- Average Temperature and Precipitation show a mild negative correlation, indicating that regions with higher temperatures tend to experience lower precipitation.

- Crop Yield is moderately correlated with the Economic Impact, suggesting that crop yield is a significant driver of economic outcomes in agriculture.

- There are notable correlations between Fertilizer Use and CO2 Emissions, highlighting the environmental costs of agricultural practices.

### Future Work

- Feature Engineering: Explore more granular data, such as region-based data or seasonal variations, to improve the model.
- Hyperparameter Tuning: Perform hyperparameter optimization for both the baseline and XGBoost models to enhance prediction accuracy.
- Advanced Models: Consider using ensemble methods or deep learning models to improve performance.
- Interpretable Models: Integrate model interpretation tools such as SHAP and LIME to better understand the contributions of each feature.

### Source

https://www.kaggle.com/datasets/waqi786/climate-change-impact-on-agriculture
