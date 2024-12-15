# Grocery Price Prediction in New York City: A Machine Learning Approach

## Introduction

### Problem Statement
New York City presents a complex and diverse retail landscape with significant variations in grocery pricing across different neighborhoods and stores. This project aims to develop a predictive model that:
- Estimates grocery item prices across different NYC stores and neighborhoods
- Compares pricing strategies, with a specific focus on Whole Foods
- Provides insights into factors influencing grocery pricing

### Key Objectives
1. Analyze price variations across different NYC neighborhoods and stores
2. Develop predictive models to estimate grocery item prices
3. Understand the key factors influencing price differences
4. Compare Whole Foods pricing with other NYC grocery stores

### Summary of Findings
- Multiple machine learning models were developed to predict grocery prices
- Random Forest and Linear Regression models demonstrated strong predictive capabilities
- Key factors influencing price include:
  - Specific grocery items (e.g., Cheese, Chicken, Milk)
  - Neighborhood location
  - Store type

## Data Description

### Data Sources
The project utilized two primary datasets(Scraped from the websites):
1. **NYC Grocery Prices Dataset**
   - Size: 250 rows
   - Columns: Store, Neighborhood, Item, Price
   - Represents grocery prices across different NYC stores

2. **Whole Foods Dataset**
   - Size: 1,657 rows
   - Columns: Company, Product, Regular Price, Sale Price, Prime Price, Category
   - Detailed pricing information from Whole Foods

### Data Preprocessing
- Cleaned and standardized product names
- Merged datasets based on matching item descriptions
- Created additional features like Price Difference and Percent Difference
- Handled missing values and performed one-hot encoding for categorical variables

## Models and Methods 

### Modeling Approaches
Several regression models were explored:
1. **Linear Regression**
   - Mean Squared Error (MSE): 0.658
   - R² Score: 0.846

2. **Random Forest Regression**
   - Mean Squared Error (MSE): 0.673
   - R² Score: 0.843

3. **K-Nearest Neighbors**
   - Mean Squared Error (MSE): 1.330
   - R² Score: 0.690

4. **Decision Tree**
   - Mean Squared Error (MSE): 0.989
   - R² Score: 0.769

### Feature Engineering
- One-hot encoding of categorical variables
- Created derived features like Price Difference and Percent Difference
- Analyzed feature importances to understand pricing dynamics

## Results and Interpretation 

### Price Variation Analysis
#### Neighborhood Price Comparison
Average Prices by Neighborhood (from highest to lowest):
1. Manhattan: $4.26
2. Brooklyn: $3.55
3. Queens: $2.94
4. Bronx: $2.59
5. Staten Island: $2.24

**Interpretation**: Manhattan consistently shows the highest grocery prices, likely due to higher living costs and store locations.

#### Store Price Comparison
Average Prices by Store:
1. Key Food: $3.26
2. Whole Foods: $3.14
3. Trader Joe's: $3.12
4. Associated Supermarket: $3.08
5. C-Town: $2.97

**Interpretation**: Prices are relatively consistent across stores, with minor variations.

### Feature Importance Insights
Top Influential Features in Price Prediction:
1. Cheese (Pound): 26.76%
2. Manhattan Neighborhood: 14.78%
3. Bananas (Pound): 14.78%
4. Chicken (Pound): 14.60%
5. Milk (Gallon): 8.36%

**Interpretation**: 
- Specific grocery items have the most significant impact on pricing
- Location (particularly Manhattan) plays a crucial role in price determination

### Whole Foods Price Comparison
- Created a Random Forest model to predict price differences
- R-squared: 0.83, indicating strong predictive power
- Key factors influencing Whole Foods price differences:
  - Regular price
  - Sale discounts
  - Prime member discounts

## Conclusion and Next Steps 

### Key Takeaways
1. Machine learning models can effectively predict grocery prices
2. Neighborhood and specific grocery items significantly influence pricing
3. Whole Foods pricing shows consistent patterns across different product categories

### Recommended Next Steps
1. Expand dataset with more stores and items
2. Develop a real-time pricing prediction web application
3. Investigate seasonal pricing variations
4. Create a consumer-facing price comparison tool

### Limitations
- Limited dataset size 
- Potential bias in data collection
- Snapshot of prices at a specific time

## Repository Structure
- `Final Project.ipynb`: Fully completed code
- `README.md`: Project documentation

## Programming language and libraries Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## How to Reproduce
1. Clone the repository
2. Install required dependencies
3. Run Jupyter notebooks in sequence
4. Explore findings and models

## Potential Applications
- Consumer price comparison
- Retail pricing strategy
- Economic research on urban grocery markets
