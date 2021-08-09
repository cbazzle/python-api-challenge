# Python API Weather Analysis

![Equator](Images/equatorsign.png)

## Part I - WeatherPy

I created a Python script to visualize the weather of more than 500 cities across the world using the citipy Python library and OpenWatherMap API. Each city was plotted on a scatter plot to show:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Then I ran linear ran a linear regression on each relationship in the Norther and Souther Hemispheres.

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

Your final notebook must:

### Part II - VacationPy

To plan a fictional vacation to a city I used jupyter-gmaps and the Google Places API.

I created a heat map that displays the humidity for every city from Part I.

  ![heatmap](Images/heatmap.png)

To find a destination that I preferred I filtered the following results and dropped those that didn't meet the parameter(s):

 - Temperature greater than 39 and less than 76 degrees Farenheit
 
 - Humidity less than 76%
 
 - Wind speed less than 9 miles per hour  

  * A max temperature lower than 80 degrees but higher than 70.

I used Google Place API to find the first hotel for each city located within 5,000 meters of the city's coordinates and plotted them on top of the humidity heatmap.

  ![hotel map](Images/hotel_map.png)

