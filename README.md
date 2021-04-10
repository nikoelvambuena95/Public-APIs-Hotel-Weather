# python-api-challenge

This challenge focuses on API calls and organizing the data using Pandas and visualiztions methods.
<br>
<br>
500+ cities were randomly generated using the CityPy Python library (https://pypi.python.org/pypi/citipy). Using this list of cities and the OpenWeatherMap API, I generated a Pandas data frame of each cities' weather. Following this was an analysis of the weather data.
<br>
<br>
The analysis focused on:
- Temperature (Farenheit)
- Humidity
- Cloudiness
- Wind Speed (mph)
Separating the weather data by Northern Hemisphere cities and Southern Hemisphere cities allowed for potential, observable trends unique to each.
<br>
<br>
In the <b>WeatherPy</b> notebook, this analysis takes the form scatterplots and linear regression models generated using the Matplotlib Python Library. Trends and observations for each analysis included in the notebook.
<br>
<br>
The <b>VacationPy</b> notebook uses the previous weather data to generate aGoogle heat map as a visualization.
<br>
<br>
Conditions were passed through the weather data to create a data frame of cities suitable for vacations. These cities were passed through the Google Places API to find suitable hotels. Markers were placed on the heatmap to display hotel locations.
