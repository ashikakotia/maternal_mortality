# Maternal Mortality

This Project is a comprehensive study aimed at understanding the causes and contributing factors to maternal mortality. The primary objective of this project is to identify key areas where interventions can significantly reduce the rate of maternal deaths.

# Analysis

  * Overall trends in maternal mortality globally and by region
  * Countries with the highest/lowest maternal mortality ratios
  * Correlations between maternal mortality and factors like nutrition, substance abuse, pre-pregnancy weight, and healthcare policies.
  * Changes in maternal mortality over time for specific countries
  
  Visualizations are generated to illustrate the key findings (https://public.tableau.com/app/profile/neha.rana1750/vizzes).

# Models

Two machine learning models are trained to predict maternal deaths on factors like nutrition, substance abuse, and health policy:

 * __Gradient Boosting Machine (GBM): A gradient boosting model using XGBoost is trained to predict the target variable. Hyperparameter tuning is performed using  
   randomized search.

 * Linear Regression: A regularized linear regression model is trained with L1 and L2 regularization to prevent overfitting. The regularization strength is tuned 
   using cross-validation.
