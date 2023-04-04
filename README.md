# DU Data Analyis Bootcamp Unit 5 Homework: Python APIs 

## Part 1: WeatherPy

This jupyter notebook  visualizes the weather of over 500 cities of varying distances from the equator. The citipy Python library (https://pypi.org/project/citipy/) is used to generate a random list of cites. The OpenWeatherMap API (https://openweathermap.org/api) is used to collect current weather information for these cities.

The code then creates a scatter plot of latitude verses each of the following:
* max temperature 

* humidity 

* cloudiness 

* wind speed 

Next, the code then calculates the linear regression, pearson correlation coefficient and r-values for each of the above relationships in the southern and northern hemispheres. It then creates a scatter plots for each of the following relationships  including the linear regression line, the model's formula, and prints the r values.

* Latitude vs max temperature in the northern  hemisphere 

* Latitude vs max temperature in the southern hemisphere 

* Latitude vs humidity  in the northern  hemisphere 

* Latitude vs humidity  in the southern hemisphere 

* Latitude vs cloudiness in the northern  hemisphere 

* Latitude vs cloudiness in the southern hemisphere 

* Latitude vs wind speed in the northern  hemisphere 

* Latitude vs wind speed in the southern hemisphere 

See the jupyter notebook for analysis of these relationships.

## VacationPy 

This jupyter notebook reads in the city data from the WeatherPy output file, cities.csv. It then does the following:

* Creates a map with a point for each city. The point size reflects the humidity of the city.

* Narrows down the city list to those cities with a:
  + Max temperature lower than 27 degrees but higher than 21.
  + Wind speed of less than 4.5 m/s
  + Zero cloudiness

* Creates a map of the narrowed down city list. The hover message for each point (city) contains longitude, latitude, city name, country name, humidity and the name of the nearest hotel with 10 kilometers to the latitude/longitude.

## Locations
* Output for WeatherPy is located in WeatherPy/output
* The csv output file from WeatherPy, cities.csv, is used as input to VacationPy
* VacationPy and WeatherPy each contain their own jupyter notebook and api_keys.py
