Bike Sharing
Problem Statement
A bike-sharing system is a service that provides bikes for shared use to individuals on a short-term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled, wherein the user enters payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
Background
A US bike-sharing provider, BoomBikes, has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. To address this, they have decided to come up with a mindful business plan to accelerate their revenue as soon as the ongoing lockdown comes to an end and the economy restores to a healthy state.
Objective
BoomBikes aspires to understand the demand for shared bikes among people after the ongoing quarantine situation ends across the nation due to Covid-19. They aim to prepare themselves to cater to people's needs once the situation improves and stand out from other service providers, making huge profits.
Task
The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands.
Dataset
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.
Business Goal
You are required to model the demand for shared bikes with the available independent variables. This will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet customer expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
Dataset Characteristics
The day.csv file has the following fields:
instant: record index
dteday: date
season: season (1: spring, 2: summer, 3: fall, 4: winter)
yr: year (0: 2018, 1: 2019)
mnth: month (1 to 12)
holiday: weather day is a holiday or not (extracted from )
weekday: day of the week
workingday: if day is neither weekend nor holiday is 1, otherwise is 0
weathersit:
1: Clear, Few clouds, Partly cloudy, Partly cloudy
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
temp: temperature in Celsius
atemp: feeling temperature in Celsius
hum: humidity
windspeed: wind speed
casual: count of casual users
registered: count of registered users
cnt: count of total rental bikes including both casual and registered