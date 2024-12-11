# Predicting Grocery Prices in New York City

Introduction
This project aims to develop a predictive model for grocery prices across different neighborhoods in New York City. By analyzing factors such as store type, neighborhood, and specific grocery items, we seek to understand the dynamics of food pricing in the city.
Data Description
Our dataset includes the following key features:

Store: Different grocery stores across NYC
Neighborhood: Five NYC boroughs
Item: Ten common grocery items
Price: The cost of each item

Dataset Characteristics

Total Entries: 250 (50 entries per neighborhood)
Features: Categorical (Store, Neighborhood, Item) and Numerical (Price)
Date Range: Current snapshot of prices

Modeling Approaches
We implemented four different regression models to predict grocery prices:

Multiple Linear Regression
K-Nearest Neighbors (KNN)
Decision Tree Regression
Random Forest Regression

Model Evaluation Metric: Mean Squared Error (MSE)
Key Findings
1. Price Distribution

Average Price: $3.50
Price Range: $0.60 - $6.50
Moderate price variability across stores and neighborhoods

2. Neighborhood Price Variations

Manhattan shows the highest average prices
Staten Island demonstrates the lowest price points
Brooklyn and Queens show moderate pricing

3. Model Performance Comparison

Random Forest: Best performing model

Lowest Mean Squared Error
Most robust in capturing price variations


K-Nearest Neighbors: Strong performance
Decision Tree: Moderate performance
Linear Regression: Least effective

4. Feature Importance
Top influential features in predicting prices:

Store Type
Neighborhood
Specific Grocery Item

Conclusions

Grocery prices in NYC vary significantly based on location and store type
Random Forest models can effectively capture these complex pricing dynamics
Neighborhood and store selection substantially impact grocery expenses

Recommendations

Budget-conscious consumers: Compare prices across different neighborhoods
Retailers: Consider location-specific pricing strategies
Policymakers: Investigate price disparities across city regions

Future Research

Incorporate more granular neighborhood data
Include seasonality and time-based price variations
Expand dataset with more stores and items
