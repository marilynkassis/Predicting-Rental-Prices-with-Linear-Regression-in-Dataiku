# Predicting-Rental-Prices-with-Linear-Regression-in-Dataiku
A comprehensive linear regression model developed in Dataiku to predict rental prices using property characteristics and provide actionable insights for real estate market optimization.

# Predicting Rental Prices with Linear Regression in Dataiku

This project demonstrates the application of linear regression analysis to predict rental prices based on key property characteristics. Leveraging Dataiku's platform, the project refines predictive accuracy and empowers data-driven decision-making for competitive pricing strategies in the real estate sector.

## Project Overview

Rental pricing in the real estate market is a dynamic challenge influenced by multiple factors. This project employs a robust linear regression model to analyze relationships between property features and rental prices, providing actionable insights for competitive pricing and investment decisions.

### Key Features:
- **Logarithmic Transformation:** Enhanced model interpretability and reduced skewness of rental price data.
- **Variable Selection:** Identified significant predictors like property size (Sq.Mt) and type (Cottage, Semidetached, Penthouse).
- **High Model Accuracy:** Achieved an R² score of 58.78% and a Mean Absolute Percentage Error (MAPE) of 4.07%.
- **Scalable Approach:** Designed to adapt with updated data, ensuring relevance to evolving market trends.

## Methodology

1. **Data Preparation:**
   - Performed data cleaning to handle null values and remove inconsistencies.
   - Applied logarithmic transformation to stabilize variance and mitigate outliers.

2. **Feature Engineering:**
   - Selected critical features: property size (Sq.Mt), Cottage, Penthouse, and Semidetached.
   - Analyzed variable significance using T-tests and p-values.

3. **Model Training:**
   - Employed an 80-20 train-test split to prevent overfitting.
   - Used the Ordinary Least Squares (OLS) method to derive coefficients.

4. **Model Validation:**
   - Evaluated the model using R², MSE, and MAPE metrics.
   - Exported predictions to Excel for error analysis and distribution inspection.

## Results and Insights

### Key Findings:
- **Size Matters:** Sq.Mt emerged as the most influential factor, with each additional square meter increasing rent by 0.2%.
- **Property Type Impact:**
  - Cottages reduce rental prices by 29%.
  - Semidetached and Penthouse properties increase rental prices by 17.8% and 9%, respectively.

### Metrics:
- **R² Score:** 58.78%
- **MAPE:** 4.07%
- **Mean Squared Error (MSE):** 0.028


## Recommendations

- **Focus on Larger Properties:** Prioritize properties with higher Sq.Mt for better rental returns.
- **Cautious Approach to Cottages:** Assess market demand carefully as these tend to lower rental value.
- **Target High-Value Types:** Invest in penthouses and semidetached properties for higher rental yields.

