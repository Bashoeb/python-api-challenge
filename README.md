**WeatherPy**

In this project, we visualized the weather of over 500 cities from different distances from the equator. We utilized citipy, OpenWeatherMap API and Python coding skills to create a model of weather across cities.

Requirements

- Python 3.10.09
- Matplotlib.pyplot
- Pandas
- Numpy
- Requests
- Time
- Scipy.stats
- Pprint
  
**Part 1**

In WeatherPy, we completed two requirements:

1. Created scatter plots to showcase the relationships between weather variables and latitude.
2. Compute Linear Regression for Each Relationship

**Part 2: VacationPy**

In VacationPy, we used the weather data from Part 1 to plan future vacations. We utilized geoViews Python library and Geoapify API to create visualizations.

Steps

Created a map that displays a point for every city in the city_data_df DataFrame, where the size of the point is the humidity in each city.
Narrowed down the city_data_df DataFrame to find the ideal weather conditions based on the user's specifications.
Created a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
Used the Geoapify API to find the first hotel located within 10,000 meters of each coordinate.
Added the hotel name and country as additional information in the hover message for each city in the map.
