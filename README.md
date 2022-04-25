# python-api-challenge
## What's the Weather Like?
### Background
In this challenge, we will use Python requests, APIs, and JSON traversals to answer some questions: "What's the weather like as we approach the equator?"
"Which place is for our vacation?" "Can we find the closest hotel?" There are two parts for this challenge: WeatherPy and VacationPy.
### Part 1: WeatherPy
In this section, a Python script was created to visualize the weather of 500+ cities of varying distance from the equator. A simple Python library, the OpenWeatherMap API, and our problem-solving skills were used to create a representative model of weather across cities. Some observable trends have been found in our analysis.
### Observation 1
From the scatter plot above, the city latitude is correlated with the max temperature. 
The cities that are closer to the equator line tend to have higher max temperature. 
Similarily, the cities that are farther away from the equator line tend to have lower max temperature.
### Observation 2
From the scatter plot above, there is no significant correlation between city latitude and humidity.
### Observation 3
From the scatter plot above, there is no significant correlation between city latitude and cloudiness.
### Observation 4
From the scatter plot above, there is no significant correlation between city latitude and wind speed.
### Observation 5
From the scatter plot above, there is significantly negative correlation between city latitude and max temp. 
In the northern hemispher, the latitude is farther away the equator line, and the max temp tends to be lower.
### Observation 6
From the scatter plot above, there is significantly positive correlation between city latitude and max temp. 
In the southern hemispher, the latitude is closer the equator line, and the max temp tends to be higher.
### Observation 7
From the scatter plot above, there is no significantly correlation between city latitude and humidity 
in the northern hemispher. The r-squared value indicates 
the model is not efficient to explain the relationship between latitude and humidity.
### Observation 8
From the scatter plot above, there is no significantly correlation between city latitude and humidity 
in the southern hemispher. The r-squared value indicates 
the model is not efficient to explain the relationship between latitude and humidity.
### Observation 9
From the scatter plot above, there is no significantly correlation between city latitude and cloudiness 
in the northern hemispher. The r-squared value indicates 
the model is not efficient to explain the relationship between latitude and cloudiness.
### Observation 10
From the scatter plot above, there is no significantly correlation between city latitude and cloudiness 
in the southern hemispher. The r-squared value indicates 
the model is not efficient to explain the relationship between latitude and cloudiness.
### Observation 11
From the scatter plot above, there is no significantly correlation between city latitude and wind speed in the northern hemispher. 
The r-squared value indicates the model is not efficient to explain the relationship between latitude 
and wind speed.
### Observation 12
From the scatter plot above, there is negative correlation between city latitude and wind speed 
in the southern hemispher. But the r-squared value indicates 
that latitude might not be a significant factor that causes wind speed.
### Part 2: VacationPy
Based on the previous working with weather data, we can plan future vacations by using Jupyter-gmaps and the Google Places API.
A heatmap that displays the humidity for every city was created as below:
 <img width="960" alt="screenshot_humidity3" src="https://user-images.githubusercontent.com/100816322/165152722-96a53fdd-2925-4d16-a4dd-43027c472e8b.png">
Use Google Places API to find the first hotel for each city located within 5,000 meters of your coordinates. Plot the hotels on top of the humidity heatmap, with each pin containing the Hotel Name, City, and Country, as in the following image:
<img width="960" alt="screenshot_gmap_hotels_3" src="https://user-images.githubusercontent.com/100816322/165153200-d9bb3b4b-ba44-46c8-8c55-ffc793c0bf66.png">

