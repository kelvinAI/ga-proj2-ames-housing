# ga-proj2-ames-housing

In this notebook we will explore the AMES housing dataset and attempt to build a machine learning model that will predict the price of a house given the set of features. As the provided features a large, we will attempt to simplify the model without sacrificing the performance of the machine learning model.

The general steps performed for this experiment outlined below:

1  Importing and perform Exploratory Data Analysis
  - 1.1  Import necessary libraries and data into environment
  - 1.2  Data Cleaning : Exploring missing values by columns
  - 1.3  Data Cleaning : Exploring predictive power of columns with high missing values on sale price
  - 1.4  Data Cleaning : Dropping columns with high percentage of missing values
  - 1.5  Checking for outliers in data
  - 1.6  Exploring Missing data by rows
  - 1.7  Handling Missing Data
2  Imputation & Feature engineering
  - 2.1  Data Dictionary
  - 2.2  Notes for Feature engineering:
  - 2.3  Investigate features that are highly correlated with each other
  - 2.4  Generate the final dataframe for the model
3  EDA: Exploring the ms_subclass category
  - 3.1  Investigating the relationsip between MS Zoning Feature and Sale Price
  - 3.2  Investigating the impact of other categorical columns on saleprice
  - 3.3  Investigation Notes:
4  Model Prep: Creating feature matrix X and target vector y
  - 4.1  Split Training and testing sets
  - 4.2  Scale the training and test dataset
  - 4.3  Creating the baseline model (Linear Regression model)
  - 4.5  Instantiate the first model (Linear Regression with Lasso Regularization)
  - 4.7  Second Model : Lasso CV on reduced features
  - 4.7.2  Correlation Check
  - 4.7.3  Investigating features that have top correlations with saleprice VS features with top coefficients from lasso
  - 4.8  Third Model : Ridge Regression Model
  - 4.10  Final Model : Consider only the top 25 features selected by lasso CV
  - 4.11  Baseline LR model with 25 features
5  Conclusion

6  Generate predictions on final test set
