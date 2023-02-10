# python-api-challenge
Module 6 Challenge

This repository is composed of a "WeatherPy" folder that contains two notebooks (WeatherPy and VacationPy), as well as an "output_data" folder with the list of cities CSV and four figures from the WeatherPy notebook.

The WeatherPy notebook focuses on showcasing relationships between city latitude and its other corresponding variables (temperature, humidity, cloudiness, and wind speed). The city data was gathered using the OpenWeatherMap API and stored in "cities.csv". Each of the corresponding four variables were graphed alongside the city's latitude and a linear regression plot was created for all for both the Northern and Southern Hemispheres. Most relationships offered weak to moderate correlations, but the linear regression plot between latitude and temperature in the Northern Hemisphere gave us a strong negative correlation with an r-value of 0.72.

The VacationPy notebook focuses on using Geoapify and hvplots for mapping out cities from the CSV gathered in WeatherPy. Next, I narrowed down the list of cities according to my ideal weather specifications and found the nearest hotel for each city that met those specifications. The final map shows those cities and includes their relevant information in each hover message.

This resource was used to help me figure out how to add information to hover messages on a map:
https://hvplot.holoviz.org/user_guide/Customization.html

MR