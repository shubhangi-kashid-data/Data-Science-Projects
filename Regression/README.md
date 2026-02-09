# Regression Projects

This folder contains machine learning regression projects.


# Project 1: Bike Rental Demand Prediction

  Overview:
  
    Predicts hourly bike rental demand using historical data with weather conditions, time-based features, and user type information.

    Dataset Size: ~17,000+ hourly records

    Target Variable: cnt (total bike rentals per hour)

  Key Steps:
  
    Performed EDA to understand demand patterns and feature relationships
    
    Handled skewness using log transformation
    
    Treated outliers using IQR-based capping
    
    Applied One-Hot Encoding for categorical features
    
    Scaled numerical features using StandardScaler
    
    Trained and compared multiple regression models
    
    Selected and saved the best-performing model using Joblib
    

  Models Used:
  
    Linear, Ridge, Lasso, ElasticNet, Decision Tree, Random Forest, Gradient Boosting

  Outcome:

    The project successfully predicts hourly bike rental demand with strong generalization performance.
    Tree-based ensemble models (Random Forest and Gradient Boosting) outperformed linear models due to their ability to capture non-     linear relationships and feature interactions present in real-world demand patterns.



# Project 2: Diamond Price Prediction

  Overview:
  
    Built a regression model to predict diamond prices using physical measurements and quality attributes such as carat, cut, color,     clarity, and dimensions. The project focuses on understanding price drivers and handling skewed real-world data effectively.

    Dataset Size: ~53,000+ diamond records

    Target Variable: price (diamond price in USD)

  Key Steps:
  
    Explored a dataset of ~53,940 diamonds to understand feature distributions and pricing behavior
    
    Performed Exploratory Data Analysis (EDA) to analyze relationships between carat, cut, color, clarity, and price
    
    Identified strong right skewness in diamond prices and applied log transformation (log1p) on the target variable
    
    Handled outliers using IQR-based capping on numerical features
    
    Applied Ordinal Encoding for ordered categorical variables (cut, color, clarity)
    
    Scaled numerical features using StandardScaler
    
    Split data into training and testing sets
    
    Trained and evaluated multiple regression models
    
    Generated price predictions for unseen diamond samples

  Models Used:
  
    Linear Regression, Ridge, Lasso, ElasticNet, Decision Tree, Random Forest, Gradient Boosting

  Outcome:

    The project successfully predicts diamond prices with strong accuracy after handling skewness and outliers. Tree-based ensemble      models such as Random Forest and Gradient Boosting performed best due to their ability to capture non-linear relationships           between carat, quality attributes, and price.

