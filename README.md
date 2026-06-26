# House-price-prediction
Using Machine Learning to Predict the Future prices of House based on available data

House Price Prediction Model
Project Objective
The primary objective of this project is to develop a machine learning model capable of predicting house prices based on various property features. This involves data preprocessing, model training, performance evaluation, and visualization of predictions.

Dataset Used
The dataset utilized for this project is the 'House Price' dataset from Kagglehub, provided by juhibhojani/house-price. It contains comprehensive information about various properties, including details such as 'Amount(in rupees)', 'Carpet Area', 'Super Area', 'Bathroom', 'Balcony', 'Floor', 'location', and other descriptive features.

Models Applied
Two different regression models were applied and compared for this prediction task:

Linear Regression: A foundational linear model that assumes a linear relationship between features and the target variable.
Gradient Boosting Regressor: A powerful ensemble learning method that builds a strong predictive model from a combination of weaker models, often capturing complex non-linear relationships in data.
Key Results and Findings
Both models were evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) on a test set. The preprocessing steps involved handling missing values, converting object-type numerical columns, and one-hot encoding categorical features.

Here is a comparison of the model performances:

Metric	Linear Regression	Gradient Boosting
MAE	2895.96	1098.14
RMSE	30071.37	29902.13
