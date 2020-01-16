Created a Python script to visualize the weather of 500+ random cities across the world of varying distance from the equator. Utilizes the citipy library and the OpenWeatherMap API. 

Built a series of scatter plots with Matplotlib to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

* Randomly selects 500 unique (non-repeat) cities based on latitude and longitude.
* Performs a weather check on each of the cities using a series of successive API calls.
* Includes a print log of each city as it's being processed with the city number and city name.
