# World Weather Analysis

## Main Objective

1. Perform tasks using Python libraries and modules including: Pandas, gmaps, requests, numpy, citipy
2. Retrieve and use weather data from an API "get" request.
3. Create a Customer Travel Destination Map
4. Create heatmaps, and add markers using the Google Maps API.

## Overview

After working on an app, beta testers requested a new feature be added to the markers that pop up after clicking on a pin and present a description of the weather.  The beta testers also wanted to be able to select potential travel destinations based on their desired minimum and maximum temperatures for a trip.   
From there, four cities were chosen to create an itinerary map with pins and markers for the cities and nearby hotels.

# Results

## Retrieve the Weather Data

An API was established with OpenWeatherMap and a DataFrame was created to get the initial list of potential cities.  The list of potential destinations are included the spreadsheet linked below:

Potential travel destinations fro beta testers:
(https://github.com/jbowman86/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv)

## Create a Customer Travel Destinations Map

After prompting the beta testers for their minimum and maximum temperature preferences, the data frame was cleaned for null hotel entries and empty rows.  Markers and pins were created for the remainder of the hotels.  The resulting travel destination mao is included below:

![Pic 2](https://github.com/jbowman86/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

## Create an Itinerary Map

The list was narrowed down to four cities in the same country.  It was determined that the beta testers wanted to visit four cities in England (Liverpool, Newport, Reading, and Clacton-On-Sea).  The travel map that was created in depicted below:

![Pic 3](https://github.com/jbowman86/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

Makers with weather information were added to the map of the four English cities.  The updated map in icluded below:

![Pic 4](https://github.com/jbowman86/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
