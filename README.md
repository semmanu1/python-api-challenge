# Python-API-Challenge

# Basic Info:

## WeatherPy

This script displays the weather for cities around the world. The script utilizes the OpenWeatherMap API to create a representative model of weather across world cities. The following relationships were plotted and analyzed:

-Temperature (F) vs. Latitude:
The plot displays a negaitve correlation between maximum temperature and city latitude. The higher the latitude, the lower the temperature. 

-Humidity (%) vs. Latitude:
From this plot, we see humidtity tends to skew higher in general. Not necessarily dependant upon latitude. Not really a strong relationship present.

-Cloudiness (%) vs. Latitude:
From this plot, the main conclusion to be drawn from this would be that cloudiness falls to the exrtemes with a solid dispersal amongst the middle. 

-Wind Speed (mph) vs. Latitude:
This plot shows that wind speeds are typically below 15 mph, apart from a few outliers.

Linear Regression was then run on each plot and divided into northern and southern hemispheres. 

-Northern Hemisphere - Temperature (F) vs. Latitude:
-Southern Hemisphere - Temperature (F) vs. Latitude 
-Northern Hemisphere - Humidity (%) vs. Latitude 
-Southern Hemisphere - Humidity (%) vs. Latitude 
-Northern Hemisphere - Cloudiness (%) vs. Latitude 
-Southern Hemisphere - Cloudiness (%) vs. Latitude 
-Northern Hemisphere - Wind Speed (mph) vs. Latitude 
-Southern Hemisphere - Wind Speed (mph) vs. Latitude

## VacationPy

This script uses the Google Places API to create a humidity heat map of the cities around the world and then identifies the closest hotels for cities with ideal weather conditions. 