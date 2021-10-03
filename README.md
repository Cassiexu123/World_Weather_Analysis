# World_Weather_Analysis
## Overview
PlanMyTrip is a top travel technology company that specializes in internet related services in the hotel and lodging industry. I will collect and present data for the customers via the search page, which they will then filter based on their preferred travel criteria in order to find their ideal hotel anywhere. Jupyter notebook and Citipy module will be used to get the cities from more than 500 random latitudes and longitudes then I will preform requests on the open weather map API and retrieve the Jason weather data from the cities. The weather data will be added to a Pandas's data frame, where I will use matplotlib to create a series of scatter plots to show the relationship between the latitude and a variety of weather parameters for over 500 cities around the world. As part of my analysis, I will need to perform statistical calculations on the data, using linear regression on the weather parameters in the Northern and Southern hemispheres. This data will help my team predict the best time of year for people to plan their vacation.
Finally, I will export the data, clean it and use the weather data to choose the best cities for a vacation based on certain weather criteria and then map there cities using Jupyter G maps and the Google places API.

### Task
Collect and analyze weather data across cities worldwide.
### Purpose
PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
### Method
Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.
### Analysis process
-Collect the data
-Exploratory analysis with visualization
-Visualize travel data




- Adding the weather description to the weather data that retrieved this module.
- Have the beta testers use input statements to filter the data for their weather preference, which will be used to identify potential travel destinations and nearby hotels.
- From the list of potential travel destinations, the beta tester will choose 4 cities to create a travel itineary.
- A travel route between 4 cities and marker layer map using the Google map API.
