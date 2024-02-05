# TASK 5 - SALES PREDICTION USING PYTHON

## Task Description
- Sales prediction means predicting how much of a product people will buy based on factors such as the amount you spend to advertise your product, the segment of people you advertise for, or the platform you are advertising on about your product.
- Typically, a product and service-based business always need their Data Scientist to predict their future sales with every step they take to manipulate the cost of advertising their product. So let’s start the task of sales prediction with machine learning using Python.

## About the Dataset
The advertising dataset consists of sales of the products in 200 different markets. It also includes advertising budgets for the product in each of those markets for three different media: TV, radio, and newspapers. The dataframe with 200 rows and 5 variables are as follows:

- Unnamed: 0 - contains index
- TV: a numeric vector indicating the advertising budget on TV.
- Radio: a numeric vector indicating the advertising budget on radio.
- Newspaper: a numeric vector indicating the advertising budget on newspaper.
- Sales: a numeric vector indicating the sales of the interest product.

Dataset Link:
```
https://www.kaggle.com/datasets/bumba5341/advertisingcsv
```

## Problem Statement
The problem at hand involves predicting future sales for product and service-based businesses. With the dynamic nature of the market, businesses need to anticipate sales figures based on various factors, including advertising expenses, audience targeting, and the choice of advertising platforms.

## Objective
The dataset has advertising data sales (in thousands of units) for a particular product advertising budgets (in thousands of dollars) for TV, radio, and newspaper media. On the basis of this data, we need to suggest a marketing plan for future sales that will result in high product sales. We have to create various regression models with a focus on robust performance. And the identify the optimal model based on to its balanced accuracy and generalization. So, we have to use this advertising dataset given in the task and analyse the predicted sales based on the given advertising expenditures using the best regression model. The model should provide actionable insights into the relationships between advertising investments, audience segments, and advertising platforms with sales figures.

## Implementation
Python will be the primary tool for implementing machine learning models. Techniques such as regression analysis and predictive modeling will be employed.

## Outcome:
The project aims to deliver a robust sales prediction model, enabling businesses to make data-driven decisions, optimize advertising strategies, and enhance operational efficiency.

## Results
The following table represents the performance metrics for all the models trained. Performance metrics such as R2 Score, MAE, MSE, MAPE and RMSE are evaluated to compare the model's accuracy and choose the robust model for accurate sales prediction. I have selected R2 score as the primary evaluation metric for the Sales Prediction model. 

|          Models           | R2 score | Mean Squared Error (MSE) |
| :------------------------ |:-------- |:-------------------------|
| Linear Regression         | 0.899438 |           3.174          |       
| Ridge Regression          | 0.899438 |        3.174             |       
| ElasticNet Regression	    | 0.899474 |       3.173              |
| Lasso Regression          | 0.899551 |       3.171              |  
| KNN Regression            | 0.910620 |       2.821              | 
| Decision Tree Regression	| 0.923106 |       2.427              |    
| XGBoost Regression        | 0.980344 |      0.620               |  
| Random Forest Regression	| 0.980398 |      0.619               | 
| Gradient Boosting         | 0.983424 |       0.523              | 

Among the models evaluated, Gradient Boosting Regression model performed the best with around 98.3% accuracy and lowest Mean Squared Error (MSE) of 0.523, followed by Random Forest Regression model with 98% accuracy and Mean Squared Error (MSE) of 0.619 and XGBoost Regression model with 98% accuracy and Mean Squared Error (MSE) of 0.620.

## Conclusion
In the dynamic landscape of product and service-based businesses, the ability to forecast sales is paramount. This project, undertaken during the data science internship at Oasis Infobyte, delved into the realm of sales prediction using machine learning with Python. Let's encapsulate the key findings:

**Key Insights:**
- In analyzing the Sales Prediction Dataset, I navigated through data visualization, preprocessing, and machine learning model selection.
- The characteristics of the dataset, including the nature of relationships and noise, influence model performance. Simple models like Linear Regression and Regularization methods like Lasso,Ridge are best when dealing with linear relationships.
- We have observed that there is a small amount of outliers in the Newspapers category, while the other categories have no outliers. And since Newspaper category have less correlation with target, no outliers treatment is required.
- Sales exhibit a positive correlation with both TV and Radio advertising expenses, signifying the effectiveness of these channels.
- Notably, there's a strong correlation between TV advertising expenses and sales, emphasizing the impact of TV advertising on driving sales.
- The R2 score, chosen as the evaluation metric, showcased the accuracy of the model in predicting sales.
- The Gradient Boosting model emerged as the preferred choice, achieving an impressive 98.3% accuracy and lowest Mean Squared Error (MSE) of 0.523, followed by Random Forest Regression model with 98% accuracy and Mean Squared Error (MSE) of 0.619 and XGBoost Regression model with 98% accuracy and Mean Squared Error (MSE) of 0.620..
- Hence, Gradient Boosting Regression is identified as the optimal model based on to its balanced accuracy and generalization with accurate sales predictions.

The insights provide a holistic understanding of the factors influencing sales, both from Exploratory Data Analysis(EDA) and Machine Learning model perspectives. The Gradient Boosting Regressor model's accuracy underscores its potential for practical applications in the Finance and go-to-market strategies.

This project not only addresses the nuances of sales prediction but also highlights the pivotal role of data science in optimizing business strategies. The findings contribute to informed decision-making, offering valuable insights for future sales initiatives.

## Appendix
In this project, I have developed a machine learning model using Python to predict future sales as part of the Data Science Internship at [Oasis Infobyte](https://www.linkedin.com/company/oasis-infobyte/mycompany/). I explored various visualizations to understand the trends and patterns in Advertising Data. In this project various machine learning models were assessed, with the Gradient Boosting Regressor model being chosen for sales prediction due to its robust performance. Also evaluated the models with various performance metrices in which R2 score is used as the primary evaluation metric to assess model accuracy.

Please refer to the Jupyter Notebook file ```Sales Prediction Using Python.ipynb``` for a detailed step-by-step analysis with various visualizations and Sales prediction code.  Also refer to ```Sales_Prediction``` file which contains the predicted sales after predicting with Gradient Boosting Regression model.

> If you have any questions or suggestions, feel free to reach out to my LinkedIn profile [here](https://www.linkedin.com/in/bindu-madhuri-kadiyala-79a55718a/)


