# Crop Yield Analysis and Climate Change Impact

## Overview

This project explores the impact of climate change on crop yield by analyzing the relationships between climate variables (e.g., temperature, precipitation) and crop yield using machine learning techniques. The goal is to understand how climate factors influence crop production and uncover any trends related to climate change. The project focuses on regression models, feature importance, correlation analysis, and visualization to interpret these relationships, rather than solely predicting future crop yields.

### Data

The dataset used in this project includes climate variables (e.g., temperature, precipitation) and crop yield data (e.g., tons per hectare) for various years. The data is structured with climate factors as features and crop yield as the target variable.

### Approach

1. Data Preprocessing:
- The data is cleaned, and missing values are handled.
- Climate variables (e.g., temperature, precipitation) are used as features to predict crop yield.

2. Exploratory Data Analysis (EDA):
- Perform a correlation analysis to understand how climate factors relate to crop yield.
- Visualize scatter plots to examine the relationships between climate factors and crop yield.

3. Feature Importance:
- Use Random Forest and XGBoost models to identify the importance of each climate feature in predicting crop yield.
- Visualize feature importance to highlight which factors contribute most to crop yield.

4. Trend Analysis:
- Visualize crop yield trends over time.
- Plot climate factor trends (e.g., temperature and precipitation) over the same period.
- Analyze if there are any noticeable shifts in crop yield or climate variables that may be linked to climate change.

5. Modeling:
- Build regression models (Random Forest, XGBoost) to assess relationships between climate factors and crop yield.
- Perform model interpretation to better understand how each feature (e.g., temperature, precipitation) affects crop yield.

### Analysis and Results

- Feature Importance: The feature importance analysis revealed that factors like temperature and precipitation are critical in determining crop yield. These variables showed the highest importance in both Random Forest and XGBoost models.

- Correlation: A strong positive correlation was observed between temperature and crop yield in some regions, while precipitation had a varying impact depending on the crop type.

- Trends Over Time: The analysis of trends over time revealed shifts in temperature and precipitation patterns, with potential correlations to fluctuations in crop yield, which may indicate the effects of climate change.

- Climate Change Impact: The results suggest that increasing temperatures may lead to decreased crop yield, especially in regions where temperature rise is more pronounced.

### Source

https://www.kaggle.com/datasets/waqi786/climate-change-impact-on-agriculture

