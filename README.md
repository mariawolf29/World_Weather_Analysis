# World_Weather_Analysis
## Part 1 Instructions

Get the Weather Description and Amount of Precipitation for Each City for customers so that they know what the weather is as they are traveling

Create a new Jupyter Notebook file and name it Weather_Database.ipynb.
Generate a new set of 1,500 random latitudes and longitudes.
Get the nearest city using the citipy module.
Perform an API call with the OpenWeatherMap.
Retrieve the following information from the API call:
Latitude and longitude
Maximum temperature
Percent humidity
Percent cloudiness
Wind speed
Weather description (e.g., clouds, fog, light rain, clear sky)
The amount of rainfall over the last hour (1 hr).
The amount of snowfall over the last hour (1 hr)

## Part 2 Instructions
Have Customers Narrow Their Travel Searches Based on Temperature and Precipitation
A notation in the search criteria to indicate if it is raining or snowing for customers who are making travel decisions in real-time

Filter the DataFrame for minimum and maximum temperature preferences, and if the rain or snow accumulation is 0 inches or not using conditional statements.
Prompt the customer for the minimum temperature preference.
Prompt the customer for the maximum temperature preference.
Prompt the customer to answer if he or she would like it to be raining or not, using input("Do you want it to be raining? (yes/no) ").
Prompt the customer to answer if he or she would like it to be snowing or not, using input("Do you want it to be snowing? (yes/no) ").
Add the cities to a marker layer map with a pop-up marker for each city that includes:
  Hotel name
  City
  Country
  Current weather description with the maximum temperature
  
  ## Part 3 Instructions
Create a Travel Itinerary with a Corresponding Map. a map (travel itinerary) that shows the route between four cities from the customer’s possible travel destinations, and then create a map with pop-up markers for the four cities.
  
