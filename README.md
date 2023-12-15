# Project-1-Seoul-Bike-Sharing-Demand-Prediction

This project aims to build a predictive model that could predict the number of rental bikes required for each hour using the Seoul Bike Sharing dataset. Linear regression, Lasso (L1), Ridge (L2),  Decision Tree, Random Forest,Gradient Boost, and XGBoost algorithms are used to build a model to predict the number of rental bikes required for each hour.

## **Problem Statement**:
 Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is 
 important to make the rental bike available and accessible to the public at the right time as it lessens the
 waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern.
 The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## **Dataset**:
  The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, 
 Snowfall, Rainfall, the number of bikes rented per hour and date information.

 The dataset can be found at Kaggle website:
 https://www.kaggle.com/datasets/saurabhshahane/seoul-bike-sharing-demand-prediction

 ## **Project Summary**:
 Bike Seoul is a bike sharing service in the city of Seoul, South Korea. It is part of the city's efforts to promote sustainable transportation and reduce traffic congestion. The service allows residents and visitors to rent bicycles at various stations across the city and return them to any other station, providing a convenient and eco-friendly mode of transportation. In recent years, the demand for bike rentals in Seoul has increased, leading to the need for a more efficient and effective way to manage the bike sharing operations. Accurately predicting bike demand is crucial for optimizing fleet management, ensuring the availability of bikes at high-demand locations, and reducing waste and costs.

The main objective of this project is to develop a machine learning model that can accurately predict the demand for bike rentals in Seoul, South Korea, based on historical data and various relevant factors such as weather conditions, time of day, and public holidays. In this project we have used regression analysis techniques to model the bike demand data. The model trained on a large dataset of past bike rental information, along with relevant weather and time data. The model then be tested and evaluated using metrics such as mean squared error and r-squared values. The actual data is from the Seoul city government's open data portal, and this dataset is also available on Kaggle.

So, our main goal was to achieve an accuracy of at least 85% in the bike demand predictions, which would help the city's bike sharing service providers plan their fleet operations more effectively and respond to demand changes in real-time. We have performed lots of regression algorithms like linear regression, random forest, decision tree, gradient boosting , XGB, also we tried to do hyperparameter tuning and cross validation to improve the accuracy of the model. 

This project not only provided valuable insights into bike demand patterns in Seoul but also demonstrated the practical applications of machine learning in addressing real-world problems. The findings could potentially be extended to other cities with similar bike sharing systems, leading to improved services for bike users and more sustainable transportation systems.
 
## **Conclusion**:
Customers favour rental motorcycles equally in all seasons.

When there are no holidays, customers choose to rent motorcycles. Customers hardly ever use the bikes they rent while traveling on holiday.

Nearly all consumers preferred to rent bikes during functional hours.

Bicycle rentals are popular all month long.

Renting bicycles was not very popular in 2017, but it increased by 83.02 percent in 2018.

At night, customers do not prefer to use rented bikes.

Customers do not prefer rented bikes in the mornings 4 and 5, but from 7, 8, and 9, the use of rented bikes increases, possibly due to working people going to the office, and it is the same in the evenings 5, 6, and 7, because people are travelling from the office to home. Overall, the rented bike was the most frequently used during office in and out times.

Customers mostly use rented bikes for transportation in the evening.

Customers who travel most commonly use rented bikes in the morning at 8 a.m. and in the evening at 6 p.m.

When the humidity level is between 10% and 18%, people prefer to rent bikes. wind speed is between 2 m/s and 3.5 m/s, people consistently use rented bikes, and it is at its peak when wind speed is normal, which is 3.2 m/s.

Renting a bike is the best option for customers in dew point temperatures ranging from 12°C to 18°C. The use of a rented bike increases with increasing dew point temperatures, but it still reaches normal dew point temperatures.

In the first 10 days of the month, most rented bikes ar used by customers. Customers consistently use rented bikes in the last 15 days of the month.

In June, most rented bikes are used through the year, followed by October. Customers' use of rent bikes is at its peak from April to September.

The count of rented bikes on that day is unaffected by the day's visibility, but when visibility exceeds 1750, use of rented bikes increases more than usual.

During the summer and autumn seasons, most people rent bikes. During the winter, fewer people choose to rent bikes. Even when there is no holiday other than a holiday, people rent bikes. The use of rented bikes on holidays is lower than on non-holiday days.

The use of rented bikes increased by three times in 2018 compared to 2017.


### **As a result of the model's high accuracy the XGBoost regression model and Gradient Boosting Regressor is the ideal and well-trained model for forecasting the number of rented bikes required per hour.**
​
