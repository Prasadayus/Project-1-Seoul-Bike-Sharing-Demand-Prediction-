# Project-1-Seoul-Bike-Sharing-Demand-Prediction

The goal of this project is to use the Seoul Bike Sharing dataset to create a prediction model that can estimate how many rental bikes will be needed for each hour. A model to forecast how many rental bikes will be needed for each hour is constructed using the following algorithms: Linear Regression, Lasso (L1), Ridge (L2), Decision Tree, Random Forest, Gradient Boost, and XGBoost algorithms.


## **Problem Statement**:
 Right now In several large cities, rental bikes have been implemented to improve mobility comfort. In order to reduce waiting times, it is crucial that the public have access to the rental bikes at the appropriate times. Eventually, maintaining a steady supply of rental bikes for the city becomes a big priority. Predicting the number of bikes needed each hour to maintain a steady supply of rental bikes is an essential component.


## **Dataset**:
  The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall, the number of bikes rented per hour and date information.

 The dataset can be found at Kaggle website:
 https://www.kaggle.com/datasets/saurabhshahane/seoul-bike-sharing-demand-prediction

 ## **Project Summary**:
 In Seoul, South Korea, there is a bike rental program called Bike Seoul. It is a component of the city's initiatives to encourage environmentally friendly transportation and lessen gridlock. Bicycle rentals are available to both locals and visitors at many locations across the city, and they may be returned to any other station, making this a convenient and environmentally responsible form of transportation. Bicycle sharing operations in Seoul have to be managed more effectively and efficiently due to the rise in demand for bike rentals in the city in recent years. Reducing waste and expenses, guaranteeing the availability of bikes at high-demand locations, and streamlining fleet management all depend on accurate demand predictions for bicycles.


The primary goal of this project is to create a machine learning model that, using historical data and other pertinent variables like the weather, time of day, and public holidays, can reliably forecast the demand for bike rentals in Seoul, South Korea. Regression analysis techniques have been employed in this study to model the data on bike demand. The model was trained using a sizable dataset of historical bike rental data in addition to pertinent time and weather variables. Metrics like mean squared error and r-squared values are then used to test and assess the model. The real dataset comes from the open data portal of the Seoul municipal administration and can also be found on Kaggle.


Our primary objective was to anticipate bike demand with a minimum accuracy of 85% so that the city's bike sharing service providers could better manage their fleet operations and react to variations in demand instantly. In an effort to increase the model's accuracy, we have tested a variety of regression techniques, including gradient boosting, XGB, random forest, gradient regression, and hyperparameter tuning.
 

This study not only offered insightful information about Seoul's bike demand trends, but it also showed how machine learning can be used to solve real-world issues. The results may be applied to other cities with comparable bike sharing programs, resulting in better services for cyclists and more environmentally friendly transit options.
 

## **Conclusion**:
In all seasons, customers have equal preference for rental motorcycles.

Customers opt to rent motorcycles when there are no vacations. When on vacation, customers hardly ever use the bikes they rent.

Almost all customers said they would rather rent bikes during business hours.

All month long, renting bicycles is a popular option.

Bicycle rentals rose by 83.02 percent in 2018 despite being relatively unpopular in 2017.

Renting bikes at night is not something consumers want to do.


Customers don't like renting bikes in the mornings (4 and 5), but from 7 to 9 (perhaps because of people going to work), they are more popular. This also applies in the evenings (5, 6, and 7), when people are returning home from the office. All things considered, during business hours, the rental bike was the one that was used the most.

Renting bikes is how most customers get around in the evenings.

Rentable bikes are most frequently used by customers who travel between 8 a.m. and 6 p.m.


People tend to rent bikes when the humidity is between 10% and 18%. People regularly ride rental bikes, and the wind speed ranges from 2 to 3.5 m/s. It peaks at 3.2 m/s when the wind speed is normal.

For clients, renting a bike is the ideal choice when dew point temperatures are between 12°C and 18°C. While it still reaches normal dew point temperatures, the utilization of a rental bike grows with rising dew point temperatures.

The majority of renters utilize their bikes within the first ten days of the month. The final fifteen days of the month are usually when customers use their rental bikes.


The majority of motorcycles that are rented out are used from June to October. Rent-a-bike usage is at its highest from April to September.

The number of bikes hired on that particular day is independent of visibility; nonetheless, rental bike usage rises above average when visibility is greater than 1750.

Most people rent bikes in the summer and fall. Fewer individuals opt to rent bikes in the cold. People rent bikes even on days when there isn't a holiday at all. Compared to non-holiday days, fewer people rent bikes on holidays.

Compared to 2017, the number of rental bikes used tripled in 2018.



### **As a result of the model's high accuracy the XGBoost regression model and Gradient Boosting Regressor is the ideal and well-trained model for forecasting the number of rented bikes required per hour.**
​
