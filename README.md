# Car Price Predictor

## Aim

This project aims to predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.


Some packages are:
 - numpy 
 - pandas 
 - scikit-learn

3. Run the "application.py" file
And you are good to go. 

# Description

## What this project does?

1. This project takes the parameters of an used car like: Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.
2. It then predicts the possible price of the car.

## How this project does?

1. First of all the data was scraped from Quikr.com (https://quikr.com) 

2. The data was cleaned (it was super unclean :( ) and analysed.

4. Then a Linear Regression model was built on top of it which had 0.89 R2_score.

5. This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.

   <img src="https://github.com/Vaibhavpasalkar12/Car_Price_Prediction/blob/main/Demo.png">


