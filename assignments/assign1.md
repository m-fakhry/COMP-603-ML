# Assignment 1

Due 10-04 before lecture. 

1. **Paper-based** 
   - Derive the closed-form solution of linear regression using 
     - matrix notations 
     - element-wise notation 

2. **Implementation**: 
   The objective of this task is to gain skills required to develop machine learning models for the Housing prediction task. The target is to predict the median house value or California districts. Use Jupyter notebook for this exercise. 
   - Download the data using scikit library `sklearn.datasets.fetch_california_housing`
   - Process the data and plot distribution of each feature, target variable, and show the correlation between each feature and target
   - Is there any missing values? Is there any outliers (abnormal values)? 
   - Report the coefficients $\theta$ using the closed-form solution  
   - Report the coefficients learned using the function `LinearRegression().fit(X, y)`
   - What is the difference between closed-form solution and numerical solution? 
