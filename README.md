# Python API Challenge
This repository contains the files and folders for the python-api-challenge homework. Final observations are displayed at the top of the WeatherPy notebook.  

This repository contains:
* WeatherPy folder
* Output folder (inside WeatherPy folder)
* WeatherPy jupyter notebook (inside WeatherPy folder)
* VacationPy jupyter notebook (inside WeatherPy folder)
* city_weather_data.csv (inside Output folder)
* cloudiness_lats.png (inside Output folder)
* cloudiness_lats_lr_north.png (inside Output folder)
* cloudiness_lats_lr_south.png (inside Output folder)
* gmap_heatmap_download.png (inside Output folder)
* gmap_heatmap_hotels_download.png (inside Output folder)
* gmap_heatmap_hotels_screenshot.png (inside Output folder)
* gmap_heatmap_screenshot.png (inside Output folder)
* humidity_lats.png (inside Output folder)
* humidity_lats_lr_north.png (inside Output folder)
* humidity_lats_lr_south.png (inside Output folder)
* maxtemps_latitude_lr_north.png (inside Output folder)
* maxtemps_lats.png (inside Output folder)
* maxtemps_lats_lr_south.png (inside Output folder)
* windspeed_lats.png (inside Output folder)
* windspeed_lats_lr_north.png (inside Output folder)
* windspeed_lats_lr_south.png (inside Output folder)

*Note: API keys were saved in the api_keys.py file in the WeatherPy folder in my local repository.  However, this file has been set to ignore and was not uploaded to hide my API keys.*

The WeatherPy jupyter notebook contains code to:
* Import for librarys and APIs
* Generate cities list
* Perform API call by splitting cities into lists and using a pause 
* Convert the city weather data to a dataframe and export to a csv
* Clean data by removing humidity over 100%
* Plot and export png of scatter plot of Latitude vs Temperature
* Plot and export png of scatter plot of  Latitude vs Humidity
* Plot and export png of scatter plot of  Latitude vs Cloudiness
* Plot and export png of scatter plot of  Latitude vs Wind Speed
* Plot and export png of scatter plot of  Northern Hemisphere - Max Temp vs Latitude Linear Regression
* Plot and export png of scatter plot of  Southern Hemisphere - Max Temp vs Latitude Linear Regression
* Plot and export png of scatter plot of  Northern Hemisphere - Humidity vs Latitude Linear Regression
* Plot and export png of scatter plot of  Southern Hemisphere - Humidity vs Latitude Linear Regression
* Plot and export png of scatter plot of  Northern Hemisphere - Cloudiness vs Latitude Linear Regression
* Plot and export png of scatter plot of  Southern Hemisphere - Cloudiness vs Latitude Linear Regression
* Plot and export png of scatter plot of  Northern Hemisphere - Wind Speed vs Latitude Linear Regression
* Plot and export png of scatter plot of  Southern Hemisphere - Wind Speed vs Latitude Linear Regression


The VacationPy jupyter notebook contains code to:
* Import for librarys and APIs
* Import cities exported in WeatherPy work
* Create gmaps figure that uses lat/longs of cities and humidity data 
* Convert the city weather data to a dataframe and export to a csv
* Create a new dataframe for ideal cities based on specific temperature, wind speed and cloudiness parameters
* Gather first hotel name for ideal cities
* Add hotel info marker layer to gmaps figure