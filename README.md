# Real-Estate-Price-Prediction
A machine learning model based on Linear Regression to estimate house prices in Bengaluru using area, BHK, bathrooms, and location as input features.

<h2> Bengaluru House Price Prediction Model </h2> <br>

This ML model aims to predict house prices in Bengaluru based on key parameters such as area (in square feet), number of bedrooms (BHK), number of bathrooms, and location. The dataset used for training and testing the model is sourced from Bengaluru real estate data.<br>


<h2> Data Cleaning and Feature Engineering<br>

The initial dataset is cleaned by dropping unnecessary features and handling missing values. A new feature 'bhk' is created by extracting the BHK information from the 'size' column. Additionally, the 'total_sqft' column is normalized by converting range values to average. Outliers are removed based on square feet per bedroom, and properties with unrealistic bathroom counts are filtered out.<br>


<h2> One Hot Encoding<br>

To handle categorical data for the 'location' feature, one hot encoding is applied, which creates binary columns for each unique location. This process helps in reducing dimensionality and improves the model's accuracy.<br>


<h2> Linear Regression Model<br>

The ML model employs a Linear Regression algorithm, which is a supervised learning technique for regression tasks. It learns the relationships between the input features (area, BHK, bathrooms, and location) and the target variable (house prices) from the training data. The trained model can then make predictions on new data.<br>


<h2> Model Evaluation and Prediction<br>

The model's performance is evaluated using cross-validation and grid search techniques to find the best hyperparameters. The Linear Regression model achieves an accuracy of over 80%. It is then used to predict house prices for given inputs (area, BHK, bathrooms, and location).<br>


<h2> Use Case<br>

The Bengaluru House Price Prediction Model can be utilized by real estate professionals, property developers, and individuals looking to buy or sell houses in Bengaluru. By providing the necessary inputs, users can obtain estimated house prices, which can aid in making informed decisions in the competitive real estate market of Bengaluru.<br>
