---
title: "Weather App GUI in java"
summary: Using Java, data provided by OpenMeteo API
description: Learn the steps taken to build my weather app gui in Java
date: 2024-03-27 
---

# What is this?
I built an app that shows the user the temperature, humidity, weather condition and wind speed when the user inputs a city. 

This is a very simple project that I have worked on to brush up on my java skills, as well as learn more about handling json, and making http requests in java. 

# High level summary
The user inputs the name of the city/area that they want to know the weather condition of. I use the [Open Meteo](https://open-meteo.com/) api to obtain data about the geocode of this area, then use it again to obtain current weather data. Then I used JSON Simple library to parse through the json, and obtain necessary data. Then this data is displayed back to the user via the GUI. Better summary at [weather_app repository](https://github.com/ricebiceps/weather_app). ![weather_app](/images/weather_app.png)

# Going forwards
Once again, this is a very easy and simple project to brush up on java skills. I aim to create a real time analytics app using java in the future, using concepets from this project as the base.
