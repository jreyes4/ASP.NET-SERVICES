# Assignment 3: Services Development and Deployment

There are 6 services included in this solution.

WeatherService: Takes a ZIP as a parameter and returns a 5 day forecast for the given ZIP code.
StoreLocator: Takes 2 parameters, a ZIP code and a store name. The service returns the address of the closest store to the given ZIP.
HotelLocator: Takes a city name and a desired baseline rating for a hotel. The service will return a list of hotels in the target city and with a rating at or above the one given.
AirportCode: Assists the SearchFlights service, it takes 2 parameters, the origin and destination cities and returns a list with with the city codes required to query the sky picker API.
SearchFlights: Requires the AirportCode service. Takes 3 parameters, an origin, a destination, and a date (in the form MM/DD/YYYY). The service finds direct flights between the two cities and returns a short list containing the most afordable flights. 
TemperatureConversion: RESTFUL service. Require 2 parameters a bool variable indicating whether the temperature is celsius or not and the temperature. Returns the temperature.

The services are deployed @ http://webstrar56.fulton.asu.edu/page5/default.aspx

The web page default.aspx is the TryIt page for each service listed above, however it can be unstable. As such, the project contained here can be run entirely locally. 

Additional information on services can be found on index.html

For questions contact jonreyes4@gmail.com