# Bike Sharing Assignment
### Overview
To forecast the demand for shared bikes, we must create a multilinear regression model.

### Statement of the Problem
A bike-sharing system is a service that allows people to rent bikes from each other for a fee or for free for a brief period of time. In many bike share programs, users can check out a bike from a "dock," which is typically computer-controlled. After entering their payment details, the system unlocks the bike. After that, this bike can be brought back to another dock that is part of the same system.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Using the aforementioned independent variables, we must construct a model for the demand for shared bikes. The management will utilize it to determine the precise differences in needs across various aspects. As a result, they can adjust their company plan to satisfy customer expectations and demand levels. Additionally, the model will help management comprehend the patterns of demand in a new market.

## Conclusions
  ### Observations of EDA ###
  - cnt has increased from 2018 to 2019
  - cnt is higher from May to October
  - No outliers present
  - Fall season having high no of count
  - Count is higher in 2019 as compared to 2018 for all seasons
  - Count is higher when it is clear weather
  - Count is higher in 2019 as compared to 2018 for all weathersit
  - Count is higher on Non holidays
  - Count increased in 2019 as compared to 2018 for both holidays and non hoidays
  - Less no of counts on Sunday
  - Count increased on 2019 as compared to 2018 for all weekdays
  - We can infer from heat map that casual and registered are highly correlated wth cnt. Count is sum of Registered and Casual
  - Holiday, Hum, Windspeed are negatively correlated with cnt
  - Independant variable temp and atemp are highly correlated. One of them can be removed

### Conclusion ###
 - R2 score for Test data is 0.78
 - R2 score for Train data is 0.83  
The model seems to be very good


## Technologies Used
- numpy
- pandas
- seaborn
- matplotlib
- sklearn
- statsmodels


## Acknowledgements
- This project was inspired by live session of upGrad on Linear Regression by Upgrad tutors and live session of UpGrad on PreAssignment session by Akashdeep Makkar
UpGrad tutorials on Linear Regression on the learning platform



