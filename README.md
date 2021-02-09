# OpenWeatherMap-API

## Background

Created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 

## Analysis
* As expected, the weather becomes significantly warmer as one approaches the equator (0 Deg. Latitude). More interestingly, however, is the fact that the southern hemisphere tends to be warmer this time of year than the northern hemisphere. This may be due to the tilt of the earth.
* Southern Hemisphere climates tend to be slightly milder than those at similar latitudes in the Northern Hemisphere. This is because the Southern Hemisphere has significantly more ocean and much less land; water heats up and cools down more slowly than land.
There is no strong relationship between latitude and cloudiness. However, it is interesting to see that a strong band of cities sits at 0, 80, and 100% cloudiness.
* There is no strong relationship between latitude and wind speed. However, in northern hemispheres there is a flurry of cities with over 20 mph of wind.

## To run the code:
* Install citypy in your python environment (https://pypi.python.org/pypi/citipy)
* Save OpenWeatherMap API Key (https://openweathermap.org/) as 'weather_api_key'
* Google API Key (https://console.developers.google.com/getting-started) as 'g_key'
* Create API Keys and store it in the 'api_keys.py' file before running the Jupyter notebooks.
