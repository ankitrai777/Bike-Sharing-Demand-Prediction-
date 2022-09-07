# Bike-Sharing-Demand-Prediction-
Predicting demand for Bike Sharing - Supervised ML (Regression)
![image](https://user-images.githubusercontent.com/94640875/188790064-4ccbfcb3-c454-4b52-beb4-3ef3f34a53f8.png)
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
Our job is to develop a regression model based on the important variables which can help in predicting the demand for shared bikes.This will help the management to strategise their buisness plan and to meet their user's Bike Sharing Demand.

After loading our data, we performed feature engineering on it by removing irrelevant variables and deriving the new ones. Further, we performed EDA and tried drawing insights from the data, like :

Rented biked sharing demand goes highest in "summer" while it falls to least in "winter".
The bike sharing demand shoots up to peak between 5pm to 7pm and 7 am to 9 am. The demand is lowest between 4am to 5 am
The bike counts starts increasing the afternoon (from 3pm to 8pm) where temperature is the highest, with the most visibility, windspeed, and least humidity
Then we hot encoded categorical variables and rescaled the Numerical Variables.

After splitting our data into 1:4 ratio for testing and training, we applied five regression models. We also used metrics to find the performance of all the applied models.

From the metrics result we found that the “Random Forest” model gave the best result , with 0.79 R2 score. Finally, We did hyperparameter tuning (Randomized Grid Search) and optimized our model which gave final R2 score of 0.81.

At the end we have a model to predict rented bike demand efficiently in the coming times.
