# "Predicting Feed Grain Prices Using Machine Learning: A Data-Driven Approach for Agriculture and Market Analysis"

Source : :https://data.world/cdc2019/agriculture Click here
Domain name: Agriculture data

# Overview:

This project aims to predict feed grain prices, a crucial factor for the agriculture and farming industries. Accurate price predictions are essential for farmers, suppliers, and market analysts to make informed decisions regarding production, inventory management, and pricing strategies. Given the fluctuating nature of market demand, seasonal trends, and economic factors, this project leverages machine learning models to forecast feed grain prices accurately.

# Objective
The primary objective of this project is to develop a machine learning model that predicts feed grain prices based on historical data, geographical information, and temporal factors.

# Table of Contents:

Introduction
Data Description
Data Collection
Data Preprocessing
Exploratory Data Analysis (EDA)
Feature Selection
Model Training
Hyperparameter Tuning and saving the model
Predictions
Conclusion
Future Work

# Introduction:
The goal of this project is to build a machine learning model that can accurately predict rfeed grain prices based on historical data, geographical information, and temporal factors.
 
# Data Description:

Here's a detailed description of the features 

•	Source: Feed Grain dataset

•	Features:

o	SC_Group_Desc: Describes the group, such as "Prices."

o	SC_GroupCommod_Desc: Describes the commodity (e.g., "Oats").

o	SC_GeographyIndented_Desc: Geographic location.

o	SC_Attribute_Desc: Attribute description, such as "Prices received by farmers."

o	SC_Unit_Desc: Unit of the amount (e.g., "Dollars per bushel").

o	Year_ID: Year of the record.

o	Timeperiod_Desc: Time period (monthly).

o	Amount: Target variable, representing the price.

# Data Collection:
   
•	The dataset is preloaded from the file "FeedGrains.csv."

•	Preliminary analysis shows various commodities and their prices over time.

#  Data Preprocessing :
   
•	Handle missing values in the dataset.

•	Removing outliers .

•Label Encoding: Categorical features were encoded using label encoding.

Data Splitting: The dataset was split into training and testing sets.

# Exploratory Data Analysis (EDA):

•	Gain insights into data distribution and patterns:

1)Barplot

2)Countplot

3)Boxplot

4)Heatmap

# Feature Selection:
RandomForestRegressor: Used to identify important features.

# Model Training :
Here various type regression models were trained:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor

By using these models the Random Forest Regressor is considered as the best performing model

# Hyperparameter Tuning and saving the model:

Use GridSearchCV to tune hyperparameters and optimize model performance.
Best Parameters: Identified and applied to improve model performance
Model Saving: Here we save the best performing model.

# Predictions:
After the saving abd evaluation then we will make the predictions on unseen data and then the results will be displayed.


# Conclusion:

In conclusion, The machine learning model developed in this project has successfully demonstrated its ability to predict feed grain prices with a high degree of accuracy. By leveraging historical data, geographical information, and temporal factors, the model provides valuable insights that can aid farmers, suppliers, and market analysts in making informed decisions regarding production, inventory management, and pricing strategies. The predictive power of this model can help mitigate the challenges posed by market demand fluctuations, seasonal trends, and economic factors.

# Future work:

Future work could focus on integrating additional variables such as weather patterns, global economic indicators, and more granular geographical data to further enhance the model’s accuracy and robustness. Additionally, exploring advanced machine learning techniques and models could provide even more precise predictions, thereby offering greater support to stakeholders in the agricultural sector

