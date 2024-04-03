# Python-api-challenge

## WeatherPy

### Purpose:

- The purpose of WeatherPy is to analyze the relationship between various weather variables and latitude. This is achieved by utilizing the OpenWeatherMap API to retrieve weather data for a list of cities. Subsequently, scatter plots are generated to visualize the relationships between latitude and different weather parameters such as temperature, humidity, cloudiness, and wind speed.

### Contents:

- `weatherpy.py`: This Python script serves as the main implementation for WeatherPy. It includes functions to interact with the OpenWeatherMap API, retrieve weather data, and create scatter plots.

- `output/`: This directory contains the output of WeatherPy, which includes scatter plots depicting the relationships between weather variables and latitude. Each plot is accompanied by a linear regression line and related statistical information.

### Explanation:

- WeatherPy starts by fetching weather data for cities using the OpenWeatherMap API. Then, scatter plots are generated to visualize the relationship between latitude and various weather variables. Linear regression analysis is performed on each plot to identify trends and correlations. 

## VacationPy

### Purpose:

- VacationPy aims to assist in planning future vacations by identifying cities with ideal weather conditions. It utilizes the weather data obtained from WeatherPy to narrow down the list of cities based on specified criteria such as temperature, wind speed, and cloudiness. Using the geoViews Python library and the Geoapify API, it creates interactive map visualizations showing city locations and weather information. Furthermore, it identifies nearby hotels for each selected city to facilitate travel planning.

### Contents:

- `vacationpy.ipynb`: This Jupyter notebook contains the code for VacationPy. It guides users through the process of filtering cities based on weather conditions, creating map visualizations, and finding nearby hotels using the Geoapify API.


### Explanation:

- VacationPy begins by filtering the list of cities obtained from WeatherPy based on user-defined weather criteria. It then utilizes geoViews and the Geoapify API to create visually appealing map visualizations. These maps provide a clear overview of city locations, along with information such as temperature, humidity, and nearby hotels. 
