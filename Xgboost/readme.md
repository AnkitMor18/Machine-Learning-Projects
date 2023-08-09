**Project:Shipping Rate Prediction using XGBoost**

The dataset contains various features, including 'origin' and 'destination' (categorical variables that have been label encoded), month.

The main target variable is '**rate**', which represents a numerical value. 

The code builds an **XGBoost regression mode**l to predict the 'rate' based on the provided features. 

It involves preprocessing the data, shuffling it, splitting it into training and testing sets, fitting the model, making predictions, and evaluating the model's performance using the root mean squared error (RMSE) and R2 - score. 

There is also a commented-out section that I used to perform **hyperparameter tuning using grid search**.
