# Python-API_Challenge

## Part 1: WeatherPy

The goal is to create visualization for the weather of 500+ cities of varying distance from the equator. Utilize problem-solving skills to create a representative model of weather across cities. Primary tools - Python 

The first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude

![image](https://user-images.githubusercontent.com/99145651/165107717-844eea85-f1ab-430c-9bbf-32f32512beb2.png)


* Humidity (%) vs. Latitude

![image](https://user-images.githubusercontent.com/99145651/165107891-8c3f1eb3-8c2f-48e5-ad28-d619a9c9b6f1.png)


* Cloudiness (%) vs. Latitude

![image](https://user-images.githubusercontent.com/99145651/165108053-5c1c93b0-5e5f-4374-99be-b4b732037e8a.png)

* Wind Speed (mph) vs. Latitude

![image](https://user-images.githubusercontent.com/99145651/165108243-4af2474c-2ea2-44c7-8e44-419ff71a40fe.png)

Include a sentence of analytical explanation.

Compute the linear regression for each relationship separating the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
![image](https://user-images.githubusercontent.com/99145651/165151755-fffe48a1-f458-495c-805d-57fc05224719.png)
![image](https://user-images.githubusercontent.com/99145651/165151827-0ec0837a-27af-488a-bb25-b753f03fbb4a.png)

* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
![image](https://user-images.githubusercontent.com/99145651/165151951-cf41d5ce-d35a-4380-9568-89b77ddabec1.png)
![image](https://user-images.githubusercontent.com/99145651/165152035-83be149d-71e3-4ebf-a7e4-d64342cc87c0.png)

* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
![image](https://user-images.githubusercontent.com/99145651/165152124-0ba9a9bf-e7be-446f-8003-dd3802f2f66a.png)
![image](https://user-images.githubusercontent.com/99145651/165152199-693ccb88-b2e6-46f1-934f-4226a509d179.png)

* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude
![image](https://user-images.githubusercontent.com/99145651/165152301-8e4ca5e8-7f30-43c4-9949-4a1bad3e2a34.png)
![image](https://user-images.githubusercontent.com/99145651/165152629-8486e860-d92a-49e0-967a-3d50bd80f0fe.png)

Inclusion of what the linear regression is modeling by describing relationships.

The analysis provides:

* 500 unique (non-repeated) cities based on latitude and longitude.
* Weather check on each of the cities using a series of successive API calls.
* Print log of each city as it's being processed, with the city number and city name.
* Save a CSV of all retrieved data and a PNG image for each scatter plot.

### Part 2: VacationPy

In addition, using Jupyter-gmaps and the Google Places, create a heat map that displays the humidity for every city from Part 1.
Using the following parameters:

  * A max temperature lower than 80 degrees but higher than 70.
  * Wind speed less than 10 mph.
  * Zero cloudiness.
  * Drop any rows that don't satisfy all three conditions. You want to be sure the weather is ideal.

![image](https://user-images.githubusercontent.com/99145651/165129012-6834b634-bb8b-4bf1-9518-2111d5caf5eb.png)


* Use Google Places API to find the first hotel for each city located within 5,000 meters of your coordinates.

* Plot the hotels on top of the humidity heatmap, with each pin containing the **Hotel Name**, **City**, and **Country**, as in the following image:
![image](https://user-images.githubusercontent.com/99145651/165152751-75a24c7d-89c8-4828-984f-ee1f708c0a63.png)


