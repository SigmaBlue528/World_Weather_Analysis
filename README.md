Trip Advisor Proto-code

Project Overview
TripAdvisor is a top travel technology company specialized in internet related services in the hotel and lodging industry.
This project will enhance the user interface and functionalities of the TripAdvisor app with the following steps:
1.	retrieve weather data including the weather description for over 500 cities across the world,
2.	create a customer travel destinations map,
3.	create a travel itinerary map.

Resources
•	Data Source: citipy, jupyter-gmaps, OpenWeatherMap API, Google Maps and Places API, Google Maps Directions API
•	Software: Python, Anaconda Navigator, Jupyter Notebook 

Results
  Retrieve weather data
  The app uses the NumPy dependency to generate 2,000 sets of coordinates (latitude and longitude).
  The Python's citipy module is then called to identify the nearest city for each coordinate combination.
  The weather data is retrieved for all identified cities through a request to the OpenWeatherMap API.

Create a customer travel destinations map
  With Jupyter's gmaps plugin, user's weather preference inputs and requests to the Google Maps and Places API, the app generates a customer travel destinations map.

Destinations map

Create a travel itinerary map

Using Google Maps Directions API the app generates a travel route between 4 cities selected by the user.
  Travel map
  Travel map with markers

