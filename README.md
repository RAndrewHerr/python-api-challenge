# python-api-challenge

## Background

#### Data's true power is its ability to definitively answer questions. Taking what I've learned about Python requests, APIs, and JSON traversals I attempt to answer a fundamental question: "What is the weather like as we approach the equator?"

#### Of course one may think: “That’s obvious. It gets hotter.” This challenge attempts to prove this relationship visually.

## Challenge

#### This challenge was broken down into two deliverables, WeatherPy and VacationPy.

### Part 1: WeatherPy

#### In this deliverable, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python library, the OpenWeatherMap API, and my problem-solving skills to create a representative model of weather across cities.

### Part 2: VacationPy

#### In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

#### The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

#### Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

## Requirements

### The requirements for "Part 1: WeatherPy" are the following

### Create Plots to Showcase the Relationship Between Weather Variables and Latitude

#### Using the OpenWeatherMap API to retrieve weather data from the cities list:
* Create a scatter plot to showcase the relationship between Latitude vs. Temperature
* Create a scatter plot to showcase the relationship between Latitude vs. Humidity
* Create a scatter plot to showcase the relationship between Latitude vs. Cloudiness
* Create a scatter plot to showcase the relationship between Latitude vs. Wind Speed

#### Compute Linear Regression for Each Relationship:
* Linear regression scatter plot for Northern Hemisphere: Temperature (C) vs. Latitude
* Linear regression scatter plot for Southern Hemisphere: Temperature (C) vs. Latitude
* Linear regression scatter plot for Northern Hemisphere: Humidity (%) vs. Latitude
* Linear regression scatter plot for Southern Hemisphere: Humidity (%) vs. Latitude
* Linear regression scatter plot for Northern Hemisphere: Cloudiness (%) vs. Latitude
* Linear regression scatter plot for Southern Hemisphere: Cloudiness (%) vs. Latitude
* Linear regression scatter plot for Northern Hemisphere: Wind Speed (m/s) vs. Latitude
* Linear regression scatter plot for Southern Hemisphere: Wind Speed (m/s) vs. Latitude

### The requirements for "Part 2: VacationPy" are the following

* Create a map that displays a point for every city in the city_data_df from Part 1
* Narrow down the city_data_df DataFrame to find your ideal weather condition
* Create a new Dataframe (hotel_df) to hold the ideal weather data
* For each city in the hotel_df DataFrame, use the Geoapify API to find the first hotel located within 10,000 metres of each city
* Add the hotel name and the country as additional information in the hover message for each city in the map