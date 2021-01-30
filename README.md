# python-api-challenge
We will be creating Python scripts using the weather and location API's in Jupyter Notebooks to do the following:

---

## **WeatherPy**
We will visualize the weather of 500+ cities across the world of varying distance from the equator.
To accomplish this, you'll be utilizing a simple Python library, the OpenWeatherMap API, and a little common
sense to create a representative model of weather across world cities.

### **Scatterplots**
We will create a seres of scatter plots to showcase the following relationships:
- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

### **Linear Regression**
After separating the above plots into Northern and Southern Hemisphere, run a linear regression on each relationship.

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

Our WeatherPy Jupyter notebook intends to:
- Randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude
- Perform a weather check on each of the cities using a series of successive API calls
- Include a print log of each city as it's being processed with the city number and city name
- Save a CSV of all retrieved data and a PNG image for each scatter plot

## **VacationPy**
We will use the information from the WeatherPy analysis to plan future vacations using Jupyter-gmaps and the
Google Places API for this part of the assignment.

### **Humidity Heatmap**
Create a heatmap that displays the humidity for every city from WeatherPy, including:
- stuff

### **Hotel Geoplot**
