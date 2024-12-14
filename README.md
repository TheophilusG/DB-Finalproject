# Grocery Price Prediction in New York City: A Machine Learning Approach

# Introduction: 

In an era of fluctuating food prices and diverse urban markets, understanding grocery pricing dynamics becomes crucial for consumers, retailers, and urban economists. This project focuses on developing predictive models to estimate grocery prices across different neighborhoods, stores, and items in New York City. The primary predictive task is to build machine learning models that can accurately predict grocery item prices based on categorical features such as store location, neighborhood, and specific grocery items. By leveraging various regression techniques, we aim to:

Understand the key factors influencing grocery prices
Develop models with high predictive accuracy
Provide insights into price variations across different urban contexts

Key summary findings include:

Random Forest and Linear Regression models demonstrated high predictive accuracy, with R² scores around 0.89-0.90
Item type emerged as the most significant feature in price prediction
Significant price variations exist across neighborhoods and stores in New York City

Data Description: Data Source and Description
Dataset: NYC Grocery Prices Dataset
Source: Generated synthetic dataset simulating grocery prices
Size: 250 observations
Features: 
Date: Timestamp of price recording
Store: Grocery store name (Whole Foods, Trader Joe's, Key Food, C-Town, etc.)
Neighborhood: NYC borough (Manhattan, Brooklyn, Queens, Bronx, Staten Island)
Item: Specific grocery items (Cheese, Bananas, Chicken, Milk, Eggs, etc.)
Price: Target variable representing item price

Descriptive Statistics:

Mean Price: $3.05
Price Standard Deviation: $1.74
Price Range: $0.31 - $9.21

Models and Methods: Overview of Models and Implementation Preprocessing

Categorical feature encoding using OneHotEncoder
Train-test split (80% training, 20% testing)
Handling categorical variables: Store, Neighborhood, Item

Regression Models Evaluated

Linear Regression
Random Forest Regression
K-Nearest Neighbors Regression
Decision Tree Regression

# Evaluation Metrics

Mean Squared Error (MSE)
R² Score

Results and Interpretation: Review of Modeling Results
Model Performance Comparison

Random Forest

MSE: 0.383
R² Score: 0.898
Best overall performance


Linear Regression

MSE: 0.391
R² Score: 0.896
Close second-best performance


Decision Tree

MSE: 0.537
R² Score: 0.857
Moderate performance


K-Nearest Neighbors

MSE: 1.571
R² Score: 0.581
Lowest predictive accuracy



Feature Importance Analysis
Top features influencing price prediction:

Cheese (Pound): 29.3%
Bananas (Pound): 18.4%
Chicken (Pound): 13.2%
Manhattan Neighborhood: 12.0%
Milk (Gallon): 7.3%

Neighborhood and Store Price Insights
Average Prices by Neighborhood:

Manhattan: $4.13
Brooklyn: $3.30
Queens: $3.01
Bronx: $2.58
Staten Island: $2.24

Average Prices by Store:

Whole Foods: $3.14
Key Food: $3.09
C-Town: $3.08
Associated Supermarket: $3.00
Trader Joe's: $2.95

# Conclusion and Next Steps: Summary and Future Analysis

Machine learning models can effectively predict grocery prices 
Item type is the most critical factor in price determination
Significant price variations exist across NYC neighborhoods and stores

# Recommended Next Steps

Collect more granular data on:

Seasonal price variations
Specific product attributes
Detailed store inventory


# Enhance models by:

Incorporating time-series analysis
Exploring advanced ensemble methods
Collecting more feature-rich data


# Potential Applications:

Consumer price comparison tools
Retail pricing strategy optimization
Urban economic research



# Limitations

Limited feature set
Potential manual data scrapping and collection biases

This analysis provides a foundation for understanding grocery pricing dynamics in New York City, offering insights for consumers, retailers, and researchers interested in urban food economics.
