# Bike_Sharing_Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Problem Statement:
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

- The company wants to know:
Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands

- Goal:
Develop a model to find the variables which are significant the demand for shared bikes with the available independent variables. It will be used by the management to understand and manipulate the business strategy to meet the demand levels and meet the customer's expectations.


## Conclusions
- We can see the demand for bikes depends mainly on below variables:
'yr', 'atemp', 'windspeed', 'season_spring', 'season_winter','mnth_jan', 'mnth_jul', 'mnth_sept', 'weekday_Sunday', 'weathersit_Light_Snow_Light Rain_Thunderstorm','weathersit_Mist_Broken clouds'
    
- Demands increases in the month of September,winter season,if atemp is high and next year

- Demand decreases whenever the windspeed increases,during season_spring,mnth_jan,mnth_jul,weekday_Sunday,whenever the weather condition is weathersit_Light_Snow_Light Rain_Thunderstorm & weathersit_Mist_Broken clouds

- Final recommendations for the company:
Demand is higher in month of September.
Company should focus on expanding business during September.
Based on previous data it is expected to have a boom in number of users once situation comes back to normal, compared to 2019.
Hence when the situation comes back to normal, the company should come up with new offers during spring when the weather is pleasant and also advertise a little for September as this is when business would be at its best.


## Technologies Used
- pandas , numpy , matplotlib.pyplot , seaborn , train_test_split , MinMaxScaler , RFE , LinearRegression , statsmodels.api , variance_inflation_factor , mean_squared_error , r2_score , 


## Contact
Created by [@swetasarkar9211] - feel free to contact me!
