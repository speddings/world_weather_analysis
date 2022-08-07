# world_weather_analysis
## World Weather Analysis Overview
The purpose of this analysis is to update the PlanMyTrip app in three areas.

1. Retreive weather data, adding the weather description to the file.
2. Create a destination map based on the customer's preferences.
3. Create a travel itinerary, that shows the route between four cities, with a marker layer map.

## Resources
1. Python
2. Jupyter notebook
3. OpenWeather API
4. Google Places API
5. Google Directions API

## World Weather Analysis Results
### Weather Database
- Generate 2000 random pairs of latitudes and longitudes. 
- Identified 759 cities from the coordinates using the Python `citypy` library.
- Create and export a dataframe by retreiving city data using OpenWeather API. data points included: temp, humidity, cloudiness, wind, and weather description.
  
![dataframe](/weather_database/weather_database_df.png)

### Vacation Search
- Create input statments to ask the customer for temperature preferences using the weather database 
- Create a google map that shows the locations that match the customer's preferences, using Google Places API.

![dataframe](/vacation_search/WeatherPy_vacation_map.png)

### Vacation Itinerary
- Create a travel itinerary map that shows the route between four cities
- Include pop-up markers for each city

![dataframe](/vacation_itinerary/WeatherPy_travel_map.png)
![dataframe](/vacation_itinerary/WeatherPy_travel_map_markers.png)
