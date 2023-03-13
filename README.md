# Bike-Sharing-Assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

This assignment is a programming assignment wherein we have to build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* General Info
* Technologies Used
* Dataset
* Conclusions
* Acknowledgements



## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 



## Technologies Used
- Python Libraries for visualising, training & Testing model. Such as - numpy, pandas , statsmodel, sklearn, seaborn & matplotlib.
- Jupyter Notebook 
- Github


## Dataset
day.csv have the following fields:
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	- weathersit : 
		  1: Clear, Few clouds, Partly cloudy, Partly cloudy
		  2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		  3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		  4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered


## Conclusions
- The top three predictor variables are -
  1. Tempreture(temp) - with the coefficient value 0.479457 indicates that the increase in temp variable increases the bike booking by 0.479457.
  2. Light Snow(Light_snowrain) - with the coefficient value -0.285587 indicates that the increase in yr variable decreases the bike booking by 0.285587.
  3. Year(yr) - with the coefficient value 0.234391 indicates that the increase in yr variable increases the bike booking by 0.234391.
- Results -
  1. r2 for test data - 0.8031908103816627
  2. Adjusted R2 for test data - 0.7938



## Acknowledgements
- Upgrade Learning
- Upgrade Faculty
- Aditya Bhosle


## Contact
Created by [Aditya Bhosle](https://github.com/adibhosle) - feel free to contact me!
