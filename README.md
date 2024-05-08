# Python-Api-Challenge

Have you ever wondered how the weather changes as you travel the globe? Or dreamed of the perfect vacation getaway with ideal weather conditions?This repository contains Python code to analyze weather data and plan a vacation based on weather preferences.

Part 1: "WeatherPy"

The WeatherPy.ipynb Jupyter notebook explores the relationships between weather variables and latitude across over 500 cities. It utilizes the following:

citipy library: Generates random geographic coordinates and finds nearby cities.
OpenWeatherMap API: Retrieves weather data for the identified cities.
The script performs the following tasks:

Generates random coordinates and finds nearby cities.
Fetches weather data using the OpenWeatherMap API.
Creates scatter plots to visualize:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed
Computes linear regression for each relationship, separated by hemispheres (Northern and Southern).
Analyzes the results and explains the findings for each plot, including the relationship modeled and any observed trends.



Part 2: "VacationPy"

The VacationPy.ipynb Jupyter notebook focuses on using weather data to plan a vacation. It leverages the following:

geoViews library: Creates map visualizations.
Geoapify API: Locates hotels near chosen cities.
The script performs the following actions:

Imports libraries and loads weather data from Part 1.
Creates a map displaying points for each city, sized based on humidity.
Defines user-specified criteria for ideal vacation weather conditions (e.g., temperature range, wind speed, cloudiness).
Filters the data to find cities matching the vacation criteria.
Utilizes the Geoapify API to locate hotels near shortlisted cities (limited to 10,000 meters).
Creates a new DataFrame containing city, country, coordinates, humidity, and hotel information.
Displays a map with city points and hover messages showcasing hotel details.
Note:

Starter code for both parts is provided in the respective Jupyter notebooks.
Refer to the README.md files within each notebook for detailed instructions.
