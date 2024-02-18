# Anticipating building performance
The goal of the project is to predict energy consumption and carbon emissions of the non-residential buildings of Seattle and to evaluate the influence of the 'ENERGY STAR Score' metric.

## Data origin
The data comes from Seattle Open Data (https://data.seattle.gov/), contains 3376 entries (1 entry = 1 building), 46 features.

## Notebooks
- [00_EDA](00_EDA.ipynb): presents exploratory analysis
- [01_Model_TotalGHGEmissions](01_Model_TotalGHGEmissions.ipynb): data preprocessing, training, predicting the carbon emissions target, feature importance analysis.

## Models
The following models were tested:

    - Linear Regression
    - Ridge and Lasso Regressions
    - Elastic Net
    - Support Vector Regression
    - Random Forest Regression
    - Gradient Boosting