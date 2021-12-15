# Google Weather Api

![weather gif](https://user-images.githubusercontent.com/77027814/146243731-e9fed73a-a23e-4d9b-a655-b09be4a42b10.gif)

## Part I:
**Shown in the _weathepy_ folder** 

![little-rain-tornado-rainstorm](https://user-images.githubusercontent.com/77027814/146244624-2f8cd922-ae75-45ba-b68b-71717888ddb2.gif)

A representative model of weather across world (500+) cities is created. The Python script utilizes python library, citypy, makes API calls to **Open Weather Map** to retrieve weather data. The first objective is to build a series of scatter plots to showcase the following relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude
- The next objective is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees - latitude) and Southern Hemisphere (less than 0 degrees latitude).

## Part II:
**Shown in the _vacationpy_ folder**

![fun weather gif](https://user-images.githubusercontent.com/77027814/146244506-83b2f85a-b4e1-41e9-923e-33400732a77c.gif)

This part of the project involves working with weather data to plan a future vacation. Jupyter, gmaps and the Google Places API have been used for this part of the assignment.A heat map is generated displaying the humidity for every city from part I.

This helped to further narrow down data to find ideal weather condition. **Google Places API** is used to find the first hotel for each city located within 5000 meters of selected coordinates. Finally, the hotels are plotted on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.

