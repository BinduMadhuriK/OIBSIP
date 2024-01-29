# TASK 3 - CAR PRICE PREDICTION WITH MACHINE LEARNING

## Task Description
- The price of a car depends on a lot of factors like the goodwill of the brand of the car, features of the car, horsepower and the mileage it gives and many more. 
- Car price prediction is one of the major research areas in machine learning. So if you want to learn how to train a car price prediction model then this project is for you.

## About the Dataset
The provided dataset **```car data.csv```** is used here to train a car price prediction model which was downloaded from Kaggle. It contains data about all the main features that contribute to the price of a car. These features are as below:

- Car_Name: Name of the car model
- Year: Year of the car sold
- Selling_Price: Selling price of the car
- Present_Price: Present Price of the car
- Driven_kms: kms driven
- Fuel_Type: Fuel type of the car
- Selling_type: Selling type of the car
- Transmission: Transmission of the car
- Owner: Number of owners for the car

Dataset Link:
```
https://www.kaggle.com/datasets/vijayaadithyanvg/car-price-predictionused-cars/data
```

## Problem Statement
Predicting the price of cars is based on a wide range of attributes and features. It is based on finance and the marketing domain. Using a dataset containing car details such as Name of the car model, Selling price of the car, Present price of the car, and more, we aim to develop a machine learning model that accurately estimates the price of different car models. Car price prediction is a crucial application of machine learning. This project is designed to help you learn how to build a model for car price prediction.

## Objective
- Explore the factors affecting car prices.
- Create a machine learning model to predict car prices based on various influencing factors including brand reputation, features, horsepower, and fuel efficiency.
- Gain valuable experience in the field of machine learning and automotive pricing.

## Key Tasks

1. Data Collection: Gather data on various car attributes and their corresponding prices.
2. Data Preprocessing: Clean, transform, and prepare the data for modeling.
3. Feature Engineering: Identify the most important features for price prediction.
4. Model Building: Create a machine learning model capable of predicting car prices.
5. Model Evaluation: Assess the model's accuracy and performance using appropriate metrics.
6. Model Comparison: Compare the model's accuracy and choose the robust model for accurate price prediction.
7. Training with Best Model: To Make the trained model available for car price predictions.

## Benefits
By completing this project, we'll gain valuable insights into machine learning, data analysis, and the automotive industry. We'll also have a functional car price prediction model that can be useful for future car pricing decisions.

## Results
The following table represents the performance metrics for all the models trained. Performance metrics such as R2 Score, MAE, MSE and RMSE are evaluated to compare the model's accuracy and choose the robust model for accurate price prediction. I have selected R2 score as the primary evaluation metric for the Car Price Prediction model. 

|          Models           | R2 score | Mean Absolute Error (MAE) | Mean Squared Error (MSE)	| Root Mean Square Error (RMSE) |
| :------------------------ |:-------- |:------------------------- | :----------------------- | :---------------------------- |
| GradientBoostingRegressor | 0.967601 |          0.421077         |        0.384427          |            0.620021           |
| RandomForestRegressor     | 0.951357 |          0.476054         |        0.577170          |            0.759717           |
| DecisionTreeRegressor     | 0.946469 |          0.488879         |        0.635162          |            0.796971           |
| XGBRegressor              | 0.927664 |          0.535207         |        0.858288          |            0.926438           |
| LinearRegression          | 0.872995 |          0.937785         |        1.506962          |            1.227584           |

All the Models performed well but the high R2 score is achieved by Gradient Boosting Regressor model with the least MSE. By using Gradient Boosting Regressor model we can improve Selling Price of the cars prediction more accurately.

## Conclusion
This project explores the automotive industry's intricate dynamics, aiming to predict car prices with machine learning. By analyzing various factors such as fuel type, selling type, and transmission, we uncover valuable insights and select a robust model for accurate price prediction.

**Key Insights:**
- Data seems to contain a lot of outliers and need to be scaled as well.
- 'Automatic' transmission cars typically have higher prices than their 'Manual' counterparts, reflecting consumer preferences.
- 'Automatic' Transmission Cars seem to have higher Driven_kms than 'Manual' Transmission Cars.
- 'Owner' count plays a role in car pricing, with 'First Owner' cars being more expensive than 'Second' or 'Third Owner' cars.
- 'Dealers' sell the cars at higher prices than 'Individual' sellers, revealing the impact of seller type on prices.
- Latest cars seem to have higher selling price.
- The relationship between driven kilometers and 'Selling_Price' is negative, suggesting that cars with fewer kilometers tend to have higher selling prices.
- 'Diesel' cars tend to have higher 'Selling_Price' compared to 'Petrol' or 'CNG' vehicles, emphasizing the influence of fuel type on car pricing.
- Present price of a car plays an important role in predicting Selling Price, One increases the other gradually increases.
- Car age is effecting negatively. As older the car, lesser the Selling Price.
- The 'CITY' model is the top-selling car, followed by 'corolla altis,' 'verna,' 'fortuner,' and 'brio,' providing a snapshot of popular car models in the market.
- The year 2015 saw the highest number of car purchases, making it the most favored year for buying cars, followed by 2016 and 2014.
- 'Petrol' is the predominant fuel type for cars in the dataset, surpassing 'Diesel' and 'CNG,' indicating fuel preference among buyers.
- The majority of cars are sold through dealers, underscoring the role of dealerships in the automotive market.
- 'Manual' transmission cars significantly outnumber 'Automatic' transmission cars, showcasing consumer transmission preferences.
- 'First Owner' cars generally command higher 'Selling_Price,' while 'Second' or 'Third Owner' cars often have lower prices.
- Various machine learning models were assessed, out of which the Gradient Boosting Regressor model being chosen for car price prediction due to its robust performance.
- The project used the R2 score as the primary evaluation metric to assess model accuracy.
- The Gradient Boosting Regressor model achieved impressive accuracy with 96% R2 score with the least MSE of 0.38, making it a suitable choice for car price prediction.

The insights provide a holistic understanding of the factors influencing car prices, both from Exploratory Data Analysis(EDA) and Machine Learning model perspectives. The Gradient Boosting Regressor model's accuracy underscores its potential for practical applications in the automotive market.

This project has not only equipped us with valuable data science skills but has also deepened our understanding of car pricing, making it a significant step in the field of data science and machine learning.

## Appendix
In this project, I have developed a machine learning model to predict car prices based on various influencing factors using Python as part of the Data Science Internship at [Oasis Infobyte](https://www.linkedin.com/company/oasis-infobyte/mycompany/). I explored various visualizations to understand the trends and patterns in Car prices Data. In this project various machine learning models were assessed, with the Gradient Boosting Regressor model model being chosen for car price prediction due to its robust performance. Also evaluated the models with various performance metrices in which R2 score is used as the primary evaluation metric to assess model accuracy.

Please refer to the Jupyter Notebook file ```Car Price Prediction With Machine Learning.ipynb``` for a detailed step-by-step analysis with various visualizations and Car price prediction code.

> If you have any questions or suggestions, feel free to reach out to my LinkedIn profile [here](https://www.linkedin.com/in/bindu-madhuri-kadiyala-79a55718a/)

