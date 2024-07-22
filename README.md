# Car Price Prediction using Linear and Lasso Regression
This repository contains the code and dataset required for the Car Price Prediction Machine Learning Model which predicts the selling price of used cars using Linear Regression and Lasso Regression models. It involves data pre-processing, feature selection, data splitting, model training, and model evaluation. The goal is to create a reliable tool for predicting car prices to aid in market analysis and decision-making.

## Project Workflow
- Loading and exploring the dataset
- Data preprocessing: encoding categorical variables, scaling features, etc.
- Feature analysis and visualization
- Splitting the features and target
- Train-test split
- Model training using Linear Regression and Lasso Regression
- Model evaluation using metrics such as R-squared error
- Building a predictive system

## Results
The trained models achieved the following performance metrics:

1. Linear Regression
- R-squared Error (Train): 0.89
- R-squared Error (Test): 0.85

2. Lasso Regression
- R-squared Error (Train): 0.88
- R-squared Error (Test): 0.84

## Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## About Dataset
### Context
This dataset contains information about used cars, which can be used for purposes such as price prediction to exemplify the use of linear regression in machine learning. The dataset contains several attributes describing the features of the cars.

### Content
Attribute Information:

- name: The name of the car
- year: The year the car was purchased
- Selling_Price: The price at which the owner wants to sell the car at
- Present_Price: This is the current ex-showroom price of the car.
- Kms_Driven: The distance completed by the car in kilometers
- Fuel_Type: The type of fuel used by the car (Diesel, Petrol, CNG, LPG, Electric)
- Seller_Type: The type of seller (Individual, Dealer)
- Transmission: The type of transmission (Manual, Automatic)
- Owner: The number of previous owners
For used motorcycle datasets, please visit Motorcycle Dataset on Kaggle- https://www.kaggle.com/nehalbirla/motorcycle-dataset

Feel free to dive into the code, experiment with different features, and enhance the project further. If you have any suggestions, I'd love to hear from you. Happy coding!