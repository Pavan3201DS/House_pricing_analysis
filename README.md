# House Pricing Prediction with Machine Learning

This repository contains a machine learning algorithm to predict house prices based on various features. The algorithm is implemented using Python and popular machine learning libraries such as scikit-learn.

## Dataset

The dataset used for training and testing the machine learning model is the [House Prices: Advanced Regression Techniques](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data) dataset from Kaggle. It consists of various features such as the size of the house, number of bedrooms, location, etc., along with their corresponding sale prices.

## Files

- `House Pricing predictor`: Google collab Notebook containing the machine learning algorithm implementation, including data preprocessing, model training, evaluation, and prediction.
- `Bengaluru_House_Data.csv`: Directory containing the dataset used for training and testing the model.



Below data science concepts are used in this project

* Data loading and cleaning
* Outlier detection and removal
* Feature engineering
* Dimensionality reduction
* K fold cross validation

Technology and tools used in this project

* Python
* Numpy and Pandas for data cleaning
* Matplotlib for data visualization
* Sklearn for model building

## Steps ##

- Step#1: Import the required libraries

- Step#2: Load the data

- Step#3: Understand the data

        - drop unnecessary columns

- Step#4: Data Cleaning

        - Check for na values
        - Verify unique values of each column
        - Make sure values are correct (eg. 23 BHK home with 2000 Sqrft size is worng)        
        - Feature Engineering        
        - Dimesionality Reduction
        - Outlier removal using domain knowledge (2bhk price < 3bhk price, size per bhk >= 300 sqft)
        - Outlier removal using standard eviation and mean
        - One Hot encoding

- Step#5: Build Machine Learning Model

- Step#6: Testing The model

## Dataset Reference##

* [Bengaluru House price data](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)
* I have also uploaed the csv file in this repository [Bengaluru_House_Data.csv](https://github.com/Pavan3201DS/House_pricing_analysis/blob/main/Bengaluru_House_Data.csv)

Reference [codebasics](https://www.youtube.com/watch?v=rdfbcdP75KI)
