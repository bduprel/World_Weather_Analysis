# World_Weather_Analysis

#Creating a Travel Tool to Help Customers Select and Plan Vacations
##Overview 
This was a project to test a trip planning tool for possible customers by using OpenWeather, GoogleMas, and GoogleDirections APIs. 

##Weather Data
The factors latitude, longitude, maximum temperature, percent humidity, percent cloudiness, wind speed, and weather description were used to create a weather database for 2000 random latitude and longitude combinations 
This was then converted to a DataFrame and then a csv file 

##Customer Destination Mapping 
A cell to allow the customer to filter by maximum and minimum temperatures was created to better match preferences. 
DataFrame had hotel name added and any columns with missing information was dropped. 
A pop up map was created using gmaps to allow a more user friendly interface. 
This was then converted to a csv

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/106126621/179599788-f90b3c6e-cedf-4d5e-9d6b-960c7b7e350a.png)

##Customer Travel Itinerary Map 
A four-city trip was planned for a test
This was done by finding four latitude and longitude combinations
A map was then created with these four cities highlighted and then converted to a map to show travel paths to create the itinerary map  

![WeatherPy_travel_map](https://user-images.githubusercontent.com/106126621/179599708-75d1f8dc-32e6-4010-a93a-6b8b90363763.png)
