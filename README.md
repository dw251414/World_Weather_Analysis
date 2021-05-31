# World Weather Analysis 
	- Using APIs to Visualize Weather Data, learning how to retrieve data from APIs, storing that data in a 
	DataFrame, plotting the data using Matplotlib and google maps, and performing statistical analysis. 
--- 
### Background
- Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data we’ve already retrieved in this module. Then, we have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. 

- From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, we create a travel route between the four cities as well as a marker layer map.

### Nuts and Bolts
- Consists of three technical analyses, and the following deliverables:
	- Deliverable 1: Retrieve Weather Data
		- Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city  weather data you gathered in this module, use your API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.
	- Deliverable 2: Create a Customer Travel Destinations Map
		- Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.
	- Deliverable 3: Create a Travel Itinerary Map
		- Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.
