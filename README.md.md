# World_Weather_Analysis

In our previous project for Jack on the PlanMyTrip app, we collected and analyzed weather data across cities worldwide. From the information gathered the PlanMyTrip app used the data to share ideal hoetels for customers based on their weather preferences. We used our expertise as data analyst and our knowledge of DataFrames to catalog weather data and providing ideal destinations accross the world. Now Jack has asked us to be part of another project which will add some changes to make the app even better for clients.

Jacks request is to add the weather description to the data we have already captured. We will allow customers to input weather prefrences and allow the app to provide destinations and nearby hotels customied to the customers weather specifications. This is a great addition and will allow the customer to choose from 4 cities and develop a travel itinerary. With help using our knowledge of Google Maps APIs we develop a route to travel between the four cities and provide markers to guide the customers journey.

_________________________________

# Results
__________________________________


### Generate a set of 2,000 random latitudes and longitudes
_____________________________________________________________________

Capture Lat_Lng 2000


### Retrieve the Cities from the API call and Create a DataFrame 
________________________________________________________________________

* City
* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Weather description (for example, clouds, fog, light rain, clear sky)





City df 


### Using the Google API Retrieve the Weather Description for Cities from Customer Preference
___________________________________________________________________

Once the customer has entered there preferred minimum and maximum temperatures we can identify cities with temperatures within the specified ranges to offer as potential travel destinations. We create a new DataFrame using the minimum and maximum temperature.This allows us to capture hotel names to offer. Using the API we can also display in our screen shot below a marker layer map with pop-up markers for the cities.

* Hotel name
* City
* Country
* Current weather description with the maximum temperature


Picture- Cities_user_pref

Additionally the customer based on their prefrences is also offered a directions layer map of the four cities to guide them along their path and assist in their selection.



The marker layer map with pop-up marker for each city allows the customers potential travel destinations, the customer is in control and able to choose between four cities for their customized travel itinerary. The Google Maps Directions API offers real time  travel route between the four cities as well as a marker layer map.





