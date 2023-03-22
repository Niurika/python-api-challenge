# Weather API Visualizations

## Background:
A python script to visualize the weather of 500+ cities of varying distance from the equator. 

## Prerequisites:
* Simple Python Library: https://pypi.python.org/pypi/citipy
* OpenWeatherMap API: https://openweathermap.org/api

## Pt. 1 - WeatherPy:
A series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Linear regression for each relationship

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

## Pt. 2 - VacationPy:
A heat map that displays the humidity for every city from Part 1. DataFrame is narrowed down to ideal weather conditions. 
* Use Google Places API to find the first hotel for each city located within 5,000 meters of your coordinates.

* Plot the hotels on top of the humidity heatmap, with each pin containing the **Hotel Name**, **City**, and **Country**

## Built With: 
* Jupyter notebook
* Matplotlib
