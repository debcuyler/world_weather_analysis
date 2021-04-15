# World Weather Analysis
## Overview
- Our PlanMyTrip app needs a few changes. Weather description needs to be added to the city data. Input statements are now included to allow users to indicate min and max temperature for potential travel destinations and nearby hotels. The app will now create a travel route between four cities as well as a marker layer map
## Summary
- A weather dataframe was created by selecting 2000 random latitude and longitudes. The following information was obtained about the nearest city:
  - Latitude and Longitude
  - Maximum Temperature
  - Percent Humidity
  - Percent Cloudiness
  - Wind Speed
  - Weather Description

- A customer travel destinations map was created using inputs for preferred min and max temperature
  - The map shows hotels at given latitude and longitude based on the chosen temperature as well as the current weather and max temp.
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/80215894/114949841-e2223700-9e1f-11eb-823d-efed44e95c5b.png)

- A customer travel itinerary was created
  - Four cities were chosen and the travel intinerary is shown on the map, along with travel information from city to city
  ![WeatherPy_travel_map](https://user-images.githubusercontent.com/80215894/114950013-33cac180-9e20-11eb-98a9-f5912e5dbb35.png)
