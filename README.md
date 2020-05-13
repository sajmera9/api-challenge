# Python API Challenge - What's the Weather Like?
![Equator](Images/equatorsign.png)

## Background - WeatherPy

First, I randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude. Then, performed a weather check on each of the cities using a series of successive API calls and included a print log of each city as it's being processed with the city number and city name. Finally, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. Using Matplotlib, I created scatterplots to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

I utilized a [simple Python library](https://pypi.python.org/pypi/citipy), and performed API calls from the [OpenWeatherMap API](https://openweathermap.org/api).

