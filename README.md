# World Weather Analysis
## 1 Overview of The Project
PlanMyTrip is an application that specializes in internet related services in the hotel and lodging industry. The application retrieves information of the weather data from API. Next, user can input of the minimum temperature and maximum temperature to filter potential travel destinations and nearby hotels based on their weather preference. Subsequently, user can choose four cities to create a travel itinerary and make a travel route between the four cities as well as a marker layer map.

The following tasks will be performed in this analysis:

1.	Retrieve all of the following information from the API call: 

    a.	Latitude and longitude
    
    b.	Maximum temperature
    
    c.	Percent humidity
    
    d.	Percent cloudiness
    
    e.	Wind speed
    
    f.	Weather description (for example, clouds, fog, light rain, clear sky)
    
2.	Create a DataFrame from the information that has been retrieved from the API call
3.	Export DataFrame to CSV
4.	Make an input statement to to prompt the customer for their minimum and maximum temperature preferences.
5.	Create a new DataFrame based on the minimum and maximum temperature.
6.	Retrieve hotel name and update it to DataFrame.
7.	Export DataFrame to CSV
8.	Create a marker layer map with pop-up markers for the cities in the vacation
9.	Create four DataFrame for each city  on the itinerary.
10.	Retrieve latitude and longitude pairs for each of the four cities.
11.	Create a directions layer map between the cities and the travel map 
12.	Create a DataFrame that contains the four cities on the itinerary
13.	Create a marker layer map with a pop-up marker for the cities on the itinerary 

## 2 Resources
Software: Python 3.7.6 , Jupyter notebook, Pandas library, Google API

## 3 Results

![image](https://user-images.githubusercontent.com/88597187/135385435-58bbfb59-78d0-45a0-b63a-707d8c4fc3de.png)

<sub>Figure 1 Weather Data DataFrame</sub>

Figure 1 showcases weather data from cities that has been retrieved by API using random generated latitude and longitude. It has 9 columns and 692 rows data. This DataFrame will be saved to csv and used as data source for the vacation search.

In the vacation search, user can input the minimum and maximum temperature to search vacation spot they want to go. Next, the hotel data will be updated on the DataFrame. Figure 2 illustrates the Dataframe after the input temperature is applied as filter and the hotel name has been retrieved. While Figure 3 shows the marker layer map with pop-up markers for all the cities in the DataFrame.

![image](https://user-images.githubusercontent.com/88597187/135385538-c0abaa4d-d9f5-447c-b427-c40305f7bf9a.png)

<sub>Figure 2 Vacation Spot DataFrame</sub>

![image](https://user-images.githubusercontent.com/88597187/135385606-6cdc5536-8276-44e0-8618-c2f16db96da9.png)

<sub>Figure 3 Marker Map with Hotel Pop-up Markers for All Cities </sub>

The vacation spot DataFrame will be used in the Vacation itinerary to make a travel itinerary in 4 cities that has been selected by user. In this example all of the cities located in Srilanka. Figure 4 shows the directions map between the cities. While Figure 5 shows marker layer map with pop-up markers for the cities in the itinerary.

![image](https://user-images.githubusercontent.com/88597187/135385654-2745c0a9-b861-4ea0-a21c-3a81e19e067b.png)

<sub>Figure 4 Directions Map for the Cities in Itinerary </sub>

![image](https://user-images.githubusercontent.com/88597187/135385692-772c5308-fd39-4caf-86b9-1ed0f0423b7b.png)

<sub>Figure 5 Marker Map with Hotel Pop-up Markers for Cities in Itinerary  </sub>


