# Bike Lending Prediction
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
A startup has recently suffered considerable dips in their revenues due to Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
In such an attempt, the startup aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
Here we attempt to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the market. Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)


## General Information
- An attempt to understand the meterological factors on which demand of bike depends
- This is a multiple linear regression project
- Trying to understand which variables and by how much do they impact the demand for bike sharing.
- day.csv


## Conclusions
- The bike sharing demand depends on 6 variables in the day.csv file: temperature on that day, weather situation (snowy or misty), year (2018 and 2019 data), season , month(september) and if it is a working day.
- It depends the most on temperature on that day: if the temperature increases by 1 unit(normalised based on training dataset), the bike demand increases by 0.42 units(normalized based on training dataset)
- The adjusted R^2 value for training data set is 0.8005 and that of test data set is 0.8091


## Technologies Used
- pandas 
- seaborn 
- sklearn 
- statsmodel


## Acknowledgements
Give credit here.
- UpGrad


## Contact
Created by [@ishitatr] - feel free to contact me!


