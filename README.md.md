# World_Weather_Analysis

In our previous project for Jack on the PlanMyTrip app, we collected and analyzed weather data across cities worldwide. From the information gathered the PlanMyTrip app used the data to share ideal hoetels for customers based on their weather preferences. We used our expertise as data analyst and our knowledge of DataFrames to catalog weather data and providing ideal destinations accross the world. Now Jack has asked us to be part of another project which will add some changes to make the app even better for clients.

Jacks request is to add the weather description to the data we have already captured. We will allow customers to input weather prefrences and allow the app to provide destinations and nearby hotels customied to the customers weather specifications. This is a great addition and will allow the customer to choose from 4 cities and develop a travel itinerary. With help using our knowledge of Google Maps APIs we develop a route to travel between the four cities and provide markers to guide the customers journey.

_________________________________

# Results
__________________________________


### Generate a set of 2,000 random latitudes and longitudes
_____________________________________________________________________

<img width="493" alt="Lat_Lng_2000" src="https://user-images.githubusercontent.com/88467263/136670088-ad4c6f83-751c-42f5-90d7-3aa3b69e068a.PNG">


### Retrieve the Cities from the API call and Create a DataFrame 
________________________________________________________________________

* City
* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Weather description (for example, clouds, fog, light rain, clear sky)




<img width="564" alt="City_DF" src="https://user-images.githubusercontent.com/88467263/136670090-244f310f-8e0a-42a7-8735-941c7047141b.PNG">


### Using the Google API Retrieve the Weather Description for Cities from Customer Preference
___________________________________________________________________

Once the customer has entered there preferred minimum and maximum temperatures we can identify cities with temperatures within the specified ranges to offer as potential travel destinations. We create a new DataFrame using the minimum and maximum temperature.This allows us to capture hotel names to offer. Using the API we can also display in our screen shot below a marker layer map with pop-up markers for the cities.

* Hotel name
* City
* Country
* Current weather description with the maximum temperature


<img width="493" alt="Cities_User-temp_pref" src="https://user-images.githubusercontent.com/88467263/136670096-e4a1e04d-528e-40dd-b6b1-0b479846e9ac.PNG">

Additionally the customer based on their prefrences is also offered a directions layer map of the four cities to guide them along their path and assist in their selection.

<img width="678" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/88467263/136670134-7d779996-d762-4012-ba39-42a623194bcb.PNG">


The marker layer map with pop-up marker for each city allows the customers potential travel destinations, the customer is in control and able to choose between four cities for their customized travel itinerary. The Google Maps Directions API offers real time  travel route between the four cities as well as a marker layer map.

<img width="829" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/88467263/136670144-9c72704a-b868-4c65-91ce-9836a14b9109.PNG">





