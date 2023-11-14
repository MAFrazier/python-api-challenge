# python-api-challenge

In this challenge we use Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?" 

Activity is broken down into two deliverables, WeatherPy and VacationPy.

Part 1: WeatherPy
In this deliverable, a Python script to visualize the weather of over 500 cities of varying distances from the equator using the citipy Python libraryLinks to an external site. and the OpenWeatherMap APILinks to an external site.

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship

create a series of scatter plots. 

Sample scatter plot with the linear regression line.
You should create the following plots:

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

Finally, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

Part 2: VacationPy
In this deliverable, the main tasks will be to use the Geoapify API and the geoViews Python library to create map visualizations.

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:

Create a map that displays a point for every city in the city_data_df DataFrame


Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

Add the hotel name and the country as additional information in the hover message for each city on the map.