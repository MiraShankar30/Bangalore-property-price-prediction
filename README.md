# Bangalore-property-price-prediction
# Problem Statement:
In this project, we aim to predict property prices based on various features such as the area, number of bedrooms, number of bathrooms and Location. By using Hyper parameter tuning we can find a best model to estimate the property price based on these features.

# Dataset
We have a large dataset from that we need these features for extracting information for several properties:
Area (in square feet)
Number of bedrooms
Number of bathrooms
Location
Kaggle link: (https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)

# Data science concepts used:
Data load and cleaning
Outlier detection and removal 
Feature engineering
Dimensionality reduction
Gridsearchcv for hyperparameter tunning
K fold cross validation

# Technologies and tools used:
Python
Numpy and Pandas for data cleaning
Matplotlib for data visualization
Sklearn for model building
Jupyter notebook

# Implementation:
To implement property price prediction with linear regression, we can follow these steps:
Data cleaning, outlier detection and removal needs to be done.
Load the dataset and split it into input features (X) and target variable (y).
Create a linear regression model using a library like scikit-learn.
Train the model by fitting it to the training data.
Use the trained model to make predictions on new data.
Evaluate the performance of the model using suitable metrics such cross validation.
Find best model using GridSearchCV.

# Conclusion
Linear regression is a powerful algorithm for property price prediction. By leveraging the relationships between input features and property prices, we can create a model that accurately estimates the price of a property based on its characteristics.
