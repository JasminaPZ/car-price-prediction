# Car Price Prediction – Regression Models (Kaggle Dataset)

This project is implemented in the notebook `car_price_prediction_JasminaPZ.ipynb` and focuses on predicting the prices of used cars using various regression models. The dataset used is from Kaggle, titled **"CAR DETAILS FROM CAR DEKHO"**, and contains **4340 records**.

## Dataset
The dataset includes various attributes of cars such as brand, model, year, fuel type, seller type, transmission, ownership history, kilometers driven, and more. The target variable is the selling price.

## Objectives
- Understand the data through EDA (Exploratory Data Analysis)
- Clean and preprocess the dataset
- Encode categorical variables and scale numerical features
- Train multiple regression models
- Evaluate models using RMSE
- Tune hyperparameters (GridSearchCV, RandomizedSearchCV, Bayesian Optimization)
- Visualize results for better model interpretability

## Models Used
- Linear Regression
- Ridge
- Lasso
- ElasticNet
- Support Vector Regressor (SVR)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

## Tuning Techniques
- **GridSearchCV**
- **RandomizedSearchCV**
- **BayesSearchCV (Bayesian Optimization)**

## Evaluation Metrics
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

## Visualizations
- Distribution and boxplots for numerical features
- Count plots for categorical features
- Barplot comparing RMSE scores across models
- Predicted vs True values (scatter plot)
- Residual plot for the best model

## Best Model
**Random Forest (Bayesian Optimized)** achieved the lowest RMSE and best generalization performance.

## File
- `car_price_prediction_JasminaPZ.ipynb` → Main notebook with all code, explanations, and visualizations.

## Author
JasminaPZ

