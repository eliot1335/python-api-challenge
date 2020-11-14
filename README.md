# Python API Homework - What's the Weather Like?

## WeatherPy

In this activity, I will be practicing how to utilize what I have learned so far, including API calls, to organize, analyze, and visualize the data extracted from OpenWeather API. My tasks are:

### Generate Cities List
Import citipy and randomly create a list of cities around the world based on latitudes and longitudes.

### Perform API Calls
Request response from OpenWeather API, query about the cities generated and keep the ones that match. Put together a Pandas DataFrame with the values extracted.

### Create a series of scatter plots to show case following relationships
- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

### Run linear regression on each relationship
- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

Plot the charts and provide insights

------------------------------
## VacationPy

In this activity, I will not only be practicing how to utilize the codes in WeatherPy, I will also include requesting from Google Places API, plotting heatmaps, and add markers. My tasks are:

### Store Part I results into DataFrame
 Use the exported csv file from WeatherPy and put it into a DataFrame for VacationPy.

### Create Humidity Heatmap
Incorporate gmap and add heatmap layers using values from "Humidity" column. Play with the arguments to make the heatmap more readable.

### Create new DataFrame fitting weather criteria
In order to filter and get the best vacation travel spots, we are asked to set up some criteria:
- A max temperature lower than 80 degrees but higher than 70.
- Wind speed less than 10 mph.
- Zero cloudiness.
Use the DataFrame created from WeatherPy, and find the cities that quarlify all 3 criteria. Will need to do some cleaning  
, dropping NaN and etc.

### Hotel Map
Finally, with the newly created DataFrame including only cities that meet the criteria. We will use Google Places API to id  
one hotel in each city that is within 5000 meters of the city's coordinate. Then insert markers of these coordinates to the  
heatmap we built earlier.
 
