WeatherPy contains code that will retrieve data from the OpenWeatherMap API for a randomly selected sample of over 500 cities across the globe.


It will then output scatter plots tht showcase the following relationships:


      Temperature (F) vs. Latitude
      
      Humidity (%) vs. Latitude

      Cloudiness (%) vs. Latitude

      Wind Speed (mph) vs. Latitude
      
      
It will then split the data by Northern and Southern hemisphere, and examine the same relationships for each hemisphere.




VacationPy utilizes the same data pulled from our sample in WeatherPy and plots each datapoint onto a heatmap weigted by humidity.


It then filters out the data to only include cities that meet my ideal weather conditions and uses the google place API to find a hotel within a 5000 meter radius of each ideal location.


The hotels are then pinned to the heatmap, and each pin contains the hotel name, city, and country.
