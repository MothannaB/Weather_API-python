Plot the relationship between latitude and weather parameters for more than 500 cities around the world using Python, Pandas, and the OpenWeatherMap and Google APIs.


## Vacation_Search: Retrieve Weather Data

In this part, I will create a new set of 2,000 random latitudes and longitudes and get the nearest city using the `citypy` module. Using  OpenWeatherMap API key, I'll retrieve all the weather data + the weather description. I'll then add all the data to a DataFrame and export the DataFrame into the "Weather_Database" folder as `WeatherPy_Database.csv`.


## Vacation_Search: Create a Customer Travel Destinations Map

In this part, I will filter the `WeatherPy_Database.csv` on the minimum and maximum temperature preferences to identify potential travel destinations. Then I'll find nearby hotels using the Google Maps and Places API. After adding the hotel to the DataFrame I'll export the DataFrame into the "Vacation_Search" folder as `WeatherPy_vacation.csv`, and then show those destinations on a marker layer map with pop-up markers.



## Vacation_Itinerary: Create a Travel Itinerary Map

In this part, I will create a travel route itinerary using the Google "Directions API". From the filtered cities in `WeatherPy_vacation.csv` I will select four cities to travel to and then create a directions layer map. Then I'll to create a marker layer map with a pop-up marker for each city on the itinerary.