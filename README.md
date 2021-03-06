## WeatherPy

Here, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a [simple Python library](https://pypi.python.org/pypi/citipy) and the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities.

I first build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

I then ran a linear regression on each relationship, and separated them into Northern Hemisphere and Southern Hemisphere:

* Northern Hemisphere - Temperature (F) vs. Latitude

![](WeatherPy/Images/nmt.png)

* Southern Hemisphere - Temperature (F) vs. Latitude
![](WeatherPy/Images/smt.png)
* Northern Hemisphere - Humidity (%) vs. Latitude
![](WeatherPy/Images/nh.png)
* Southern Hemisphere - Humidity (%) vs. Latitude
![](WeatherPy/Images/sh.png)
* Northern Hemisphere - Cloudiness (%) vs. Latitude
![](WeatherPy/Images/nc.png)
* Southern Hemisphere - Cloudiness (%) vs. Latitude
![](WeatherPy/Images/sc.png)
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
![](WeatherPy/Images/nws.png)
* Southern Hemisphere - Wind Speed (mph) vs. Latitude
![](WeatherPy/Images/sws.png)
