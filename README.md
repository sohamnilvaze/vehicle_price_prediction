# Vehicle Price Prediction - Kaggle Competition

**Project Overview**  
This project was created for a Kaggle competition aimed at predicting vehicle prices based on various features. We were provided with separate training and test datasets, and the goal was to develop a machine learning model that accurately predicts the price of a sold vehicle.

**Data Provided**  
The datasets included the following features:
- **brand**
- **model**
- **model_year**
- **mileage**
- **fuel_type**
- **engine**
- **transmission**
- **interior color**
- **exterior color**
- **accident**
- **clean_title**

The target variable was the price of the sold vehicle.

**Project Aim**  
The main objective was to create a machine learning model to predict vehicle prices based on the given features.

**Process**  
The project involved the first four stages of a typical data science workflow: data preprocessing, feature engineering, feature scaling, and model creation.

1. **Data Preprocessing**
   - **Handling Missing Values:** The provided data did not have any missing values, so this step was not necessary.
   - **Handling Temporal Variables:** Created a new feature for 'model_year' representing the year the vehicle model was produced.

2. **Feature Engineering**
   - Applied various techniques to handle categorical features, including:
     - One-Hot Encoding
     - Mean/Median Encoding
     - Label Encoding

3. **Feature Scaling**
   - Scaled the values of all feature variables using sklearn libraries such as MinMaxScaler and StandardScaler.

4. **Model Creation**
   - Implemented multiple regression models:
     - Linear Regression
     - Ridge Regression
     - Lasso Regression
     - Decision Tree
     - KNN Regressor
     - XGBoost Regressor
   - Compared model performances using metrics like F1-score, accuracy, and precision, utilizing sklearn libraries such as confusion_matrix and classification_report.

**Conclusion**  
This project demonstrates the steps involved in building a predictive model for vehicle prices, starting from data preprocessing to model evaluation. The implementation of various regression models and their comparison provides insights into the effectiveness of different approaches in solving the problem.
