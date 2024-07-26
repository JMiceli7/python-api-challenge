# python-api-challenge

This is a repo containing files for the module 6 python api challenge. 

In the WeatherPy folder, you will first see an output_data folder. In this folder you will find a set of created figures. Each figure is a scatter plot with day-of-collected city data.

Fig1: City Latitude vs. Max Temp
Fig2: City Latitude vs. Humidity
Fig3: City Latitude vs. Cloudiness
Fig4: City Latitude vs. Wind Speed

Cities.csv is a file created from the api call as well. It is a collection of cities and city info such as the above mentioned max temperature, humidity %, cloudiness %, and wind speed data.

Outside of the output_data folder is a set of ipynb files, VacationPy and WeatherPy. The WeatherPy file contains code for an API call to OpenWeatherMap and pulls the aforementioned city data and creates the output cities.csv file previously mentioned as well. 

VacationPy file contains code that reads the city.csv file. With the read file, it is then possible to map the cities and identify closest hotels as well for easily scheduled accomodations.
