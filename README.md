# python-api-challenge

This activity is broken down into two deliverables, WeatherPy and VacationPy.

## WeatherPy

In this deliverable, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the Citipy Python library, the OpenWeatherMap API, and my problem-solving skills to create a representative model of weather across cities.

## VacationPy

In this deliverable, I used my weather data skills to plan future vacations. I also utilized Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 was provided to help me get started.

My main tasks were to use the Geoapify API and the geoViews Python library and employ my Python skills to create map visualizations.


**Requirements**

**Part 1: WeatherPy**

**Create Plots to Showcase the Relationship Between Weather Variables and Latitude**
  - [x] Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code
  - [x] Create a scatter plot to showcase the relationship between Latitude vs. Temperature
  - [x] Create a scatter plot to showcase the relationship between Latitude vs. Humidity
  - [x] Create a scatter plot to showcase the relationship between Latitude vs. Cloudiness
  - [x] Create a scatter plot to showcase the relationship between Latitude vs. Wind Speed

**Compute Linear Regression for Each Relationship**
  - [x] Linear regression scatter plot for Northern Hemisphere: Temperature (C) vs. Latitude
  - [x] Linear regression scatter plot for Southern Hemisphere: Temperature (C) vs. Latitude
  - [x] Linear regression scatter plot for Northern Hemisphere: Humidity (%) vs. Latitude
  - [x] Linear regression scatter plot for Southern Hemisphere: Humidity (%) vs. Latitude
  - [x] Linear regression scatter plot for Northern Hemisphere: Cloudiness (%) vs. Latitude
  - [x] Linear regression scatter plot for Southern Hemisphere: Cloudiness (%) vs. Latitude
  - [x] Linear regression scatter plot for Northern Hemisphere: Wind Speed (m/s) vs. Latitude
  - [x] Linear regression scatter plot for Southern Hemisphere: Wind Speed (m/s) vs. Latitude

**Part 2: VacationPy**

  - [x] Create a map that displays a point for every city in the city_data_df DataFrame
  - [x] Narrow down the city_data_df DataFrame to find your ideal weather condition
  - [x] For each city in the hotel_df DataFrame, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates
  - [x] Add the hotel name and the country as additional information in the hover message for each city in the map
