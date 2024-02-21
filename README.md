**Instructions**

This project is broken down into two deliverables, *WeatherPy* and *VacationPy*.

**Part 1: WeatherPy**

In this deliverable, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the *citipy* Python library, the *OpenWeatherMap* API, and my problem-solving skills to create a representative model of weather across cities.

**Requirement 1:** Created Plots to Showcase the Relationship Between Weather Variables and Latitude

To fulfill the first requirement, I used the *OpenWeatherMap* API to retrieve weather data from the cities list generated in the code. Next, I created a series of scatter plots to showcase the following relationships:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

**Requirement 2**: Computed Linear Regression for Each Relationship

To fulfill the second requirement, computed the linear regression for each relationship. Separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). I found it helpful to define a function in order to create the linear regression plots.

Next, created a series of scatter plots. Made sure to include the linear regression line, the model's formula, and the r values in the scatter plots.

Also created the following plots:
- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explained what the linear regression is modeling. Described relationships that I noticed and other findings.


**Part 2: VacationPy**

In this deliverable, I used my weather data skills to plan future vacations. Also, I used Jupyter notebooks, the geoViews Python library, and the Geoapify API.

My main tasks were to use the Geoapify API and the geoViews Python library and employ my Python skills to create map visualizations.

To succeed on this deliverable of the assignment, I did the following steps:

1. Created a map that displays a point for every city in the '*city_data_df*' DataFrame as shown in the following image. The size of the point should be the humidity in each city.
