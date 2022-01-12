# BoomBikes Case Study
> A US bike-sharing provider BoomBikes is a bike-sharing system in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- They want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

    * Which variables are significant in predicting the demand for shared bikes.
    * How well those variables describe the bike demands


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We have done Data cleaning, Exploratory data analysis and build Linear Regression Model to get better insights of data. We found following driving variable which will give us inference about the count of rented bike. 

Following are the predictor variable which effect the counts - 
   - `yr` - As the year increases, the counts also increases. This might be due to increase in popularity among people.
   - `Workingday` - We can say that on working days people usually prefer renting the bike. This might be because they are using it to commute to workplace.
   - `windspeed` - As we all know that if the windspeed is high then it is difficult to ride a bike. We can see that in this data, windspeed is having a negative coefficient which means when windspeed is high the count will decrease.
   - `Summer`, `winter`, `fall` -  During Summer, winter and fall season the sum of count is more compared to spring. We have observed that spring season has more holidays compared to other season. Hence, people might have rented less bikes during spring.
   - `Sat` - We can see that the coefficient of Saturday is positive, which means on saturday there is more chance of bike rents than other weekdays.
   - `Mist+Cloudy`,`Light Rain / Light Snow` - We can say that whenever the weather is clear or few clouds, most of the people consider to ride bikes which can be explained by the coefficients of both variables which is negative.
    


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.1.5
- Numpy - version 1.18.5
- Matplotlib - version 3.1.3
- Seaborn - version 0.10.1
- Scikit-learn - version 1.0.2
- Statsmodels - 0.11.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by Upgrad.


## Contact
Created by [@Ray0705](https://github.com/Ray0705) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
