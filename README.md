# World_Weather_Analysis
## Overview of the project

Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data we’ve already retrieved in this module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

## Deliverable 1: Retrieve Weather Data
In this we are generating 2000 random latitudes and longitudes then we are retrieve the nearest city and perform the API call with the OpenWeatherMap. In the intial steps we are going to fetch the folowing information:
   - Latitude and longitude
   - Maximum temperature
   - Percent humidity
   - Percent cloudiness
   - Wind speed
   - Weather description (for example, clouds, fog, light rain, clear sky)

![The summary](https://github.com/urvish7/World_Weather_Analysis/blob/main/Weather_Database/summary.png)

## Deliverable 2: Create a Customer Travel destinations map.

In this section we going to retrieve customer weather preferences then use that preferences to identify potential travel destinations and nearby hotels. 
The summary after the retrival looks like:


![summary](https://github.com/urvish7/World_Weather_Analysis/blob/main/Vacation_Search/Summary1.png)

The marker layer map and pop-up marker for the city looks similar to the folowing map:

![](https://github.com/urvish7/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

## Deliverable 3: Create a travel Itinerary map 
We are going to use the google directions API to create the travel itinerary that shows the route between four cities and that is been choosen from the customer's possible travel destinations. 
