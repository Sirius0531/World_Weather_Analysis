# World_Weather_Analysis
## Project Overview
This project is to help the customer to design their vacation plan, which included preferred cities, hotels, and directions. We use API to request the information and use Jupyter notebook to write the script.  The project retrieves weather data, creates a custom travel destinations map, and creates a travel itinerary map.

## Resources
Data Source: https://developers.google.com/maps
Software: Jupyter Notebook, Pandas Library, CityPy, Python Request, APIs, JSON Traversals

##Summary

1. Use the random function to generate 2,000 sets of coordinates (latitude and longitude), create a date frame that included cities, countries, weather information.
With the users' preference inputs, we request the desired area and request destinations map using Google MAPs API. 
![Hotel mark](https://github.com/Sirius0531/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)
2. Use Google Map Direction APT to generates the travel route between 4 cities for user to travel by driving:
![Hotel mark](https://github.com/Sirius0531/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)
3. Pin out the hotel they will stay and shows the basic information of the hotels:
![Hotel mark](https://github.com/Sirius0531/World_Weather_Analysis/blob/main/weather_database/WeatherPy_travel_map_markers.PNG)
![Hotel mark](https://github.com/Sirius0531/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_nomarkers.PNG)