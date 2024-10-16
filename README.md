
# Car_Price_Prediction
   CarDekho including various features such as make, model, year, fuel type, transmission type, and other relevant attributes from different cities. Your task as a data scientist is to develop a machine learning model that can accurately predict the prices of used cars based on these features. The model should be integrated into a Streamlit-based web application to allow users to input car details and receive an estimated price instantly

# Skills take away From This Project
  *  Data Cleaning and Preprocessing
  *  Exploratory Data Analysis
  *  Machine Learning Model Development
  *  Price Prediction Techniques
  *  Model Evaluation and Optimization
  *  Model Deployment
  *  Streamlit Application Development
  *  Documentation and Reporting

# Domain
   *  Automotive Industry 
   *  Data Science
   *  Machine Learning
     
# Approach:
 Data Processing
Import and concatenate:
   * Import all city’s dataset which is in unstructured format.
   * Convert it into a  structured format.
   * Add a new column named ‘City’ and assign values for all rows with the name of the respective city.
   * Concatenate all datasets and make it as a single dataset.
    
Handling Missing Values: 
   * Identify and fill or remove missing values in the dataset.
   * For numerical columns, use techniques like mean, median, or mode imputation.
   * For categorical columns, use mode imputation or create a new category for missing values.
    
Standardising Data Formats:
   * Check for all data types and do the necessary steps to keep the data in the correct format.
   * Eg. If a data point has string formats like 70 kms, then remove the unit ‘kms’ and change the data type from string to integers.
    
Encoding Categorical Variables: 
   * Convert categorical features into numerical values using encoding techniques.
   *  Use one-hot encoding for nominal categorical variables.
   * Use label encoding or ordinal encoding for ordinal categorical variables.

    
Normalizing Numerical Features:
   * Scale numerical features to a standard range, usually between 0 and 1.( For necessary algorithms)
   * Apply techniques like Min-Max Scaling or Standard Scaling.
    
Removing Outliers: 
   * Identify and remove or cap outliers in the dataset to avoid skewing the model.
   * Use IQR (Interquartile Range) method or Z-score analysis.

Exploratory Data Analysis (EDA)
Descriptive Statistics:
   *  Calculate summary statistics to understand the distribution of data.
   *  Mean, median, mode, standard deviation, etc.
    
Data Visualization: 
   * Create visualizations to identify patterns and correlations.
   * Use scatter plots, histograms, box plots, and correlation heatmaps.
    
Feature Selection:
  *  Identify important features that significantly impact the car prices.
  *  Use techniques like correlation analysis, feature importance from models, and domain knowledge.

Model Development:
Train-Test Split: 
  *  Split the dataset into training and testing sets to evaluate model performance.
   
Model Selection:
 * Choose appropriate machine learning algorithms for price prediction.
 *  Linear Regression, Decision Trees, Random Forests, Gradient Boosting Machines, etc.
   
Model Training:
  * Train the selected models on the training dataset.
  * Use cross-validation techniques to ensure robust performance.
   
Hyperparameter Tuning: 
 *  Optimize model parameters to improve performance.
 *  Use techniques like Grid Search or Random Search.

 Model Evaluation
Performance Metrics:
  * Evaluate model performance using relevant metrics.
  * Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared.
   
Model Comparison:
 *  Compare different models based on evaluation metrics to select the best performing model.
 
Optimization
Feature Engineering: 
 *  Create new features or modify existing ones to improve model performance.
 *  Use domain knowledge and exploratory data analysis insights.

Regularization:
  *  Apply regularization techniques to prevent overfitting.
  *  Lasso (L1) and Ridge (L2) regularization.

Deployment
Streamlit Application: 
  *  Deploy the final model using Streamlit to create an interactive web application.
  *  Allow users to input car features and get real-time price predictions.


# Technology Used
   1.  Machine Learning 
   2.  Python
   3.  Pandas 
   4.  Exploratory Data Analysis (EDA)
   5.  Streamlit


# PACKAGES AND LIBRARIES
*  import pandas as pd
*  import matplotlib
*  import seaborn
*  import LinearRegression
*  import MinMaxScaler
*  import joblib
*  from sklearn import preprocessing
*  import numpy as np
*  from sklearn import metrics
*  import GradientBoostingRegressor
*  import RandomForestRegressor
*  import GridSearchCV
*  import streamlit


  # Output
![Screenshot 2024-10-16 235238](https://github.com/user-attachments/assets/e3504235-2be6-49cf-98a3-8b4f750246ca)


