# World_Weather_Analysis project overview
### The purpose of this project is to use Api to retrieve data form word weather Api,google place Api and direction Api. Numpy random number generator is used to generate thousands coordinates. The nearest cities are found by using those coordinates by using nearest city module. After those cities are located, the weather information and city information such as hotels can be easily accessed by weather API and Google API. Those information is rendered on google map in a visualized way so users can easily obtain those information with simple mouse hover

## Cities weather data collection and analysis
### Cities location gerenated by numpy random number generator and citypy nearest city. Weather API provided the weather data such as max temperature, humdility, cloudiness wind_speed and city description, those information are formed in pandas dataframe and exported as csv files
### Max temperature vs Latitude of cities
![](https://github.com/ftjyangf/World_Weather_Analysis/blob/master/weather_data_image/Fig1.png)
### the Max Temperature is going up with the decrease of latitiude, the max temperature is also distribute in a certain 'width' globally, meaning that we can expect the range of max temperture with given latitude at this time.
###
![](https://github.com/ftjyangf/World_Weather_Analysis/blob/master/weather_data_image/Fig2.png)
### The relationship between latitude and humidity is not that clear, but we can say that at our time period most of cities have high humidity(more than 50%) 
![](https://github.com/ftjyangf/World_Weather_Analysis/blob/master/weather_data_image/Fig3_png.png)
### Cloudiness is distributed in 0%, 40%,75% and 100%. Can this caused by the reason people tend to choose those location to live?
![](https://github.com/ftjyangf/World_Weather_Analysis/blob/master/weather_data_image/Fig4.png)
### Wind speed are expected, most of cities have a wind speed under 15 and strong wind speed is also expected in some cities.

## Present cities information
![](https://github.com/ftjyangf/World_Weather_Analysis/blob/master/weather_data_image/WeatherPy_vacation_map.PNG)
### Present all the cities generated with function users just need a simple click
![](https://github.com/ftjyangf/World_Weather_Analysis/blob/master/weather_data_image/WeatherPy_travel_map_markers.PNG)
### Four cities we are planing to travel
### The travel direction
![](https://github.com/ftjyangf/World_Weather_Analysis/blob/master/weather_data_image/WeatherPy_travel_map.PNG)




