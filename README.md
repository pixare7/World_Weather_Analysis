# World Weather Analysis

## Table of Contents
- [Project Description](#project-description)
- [Results](#results)

## Project Description

### Overview
This project undertakes a comprehensive analysis of the relationship between weather variables and latitude. It utilizes sample data from OpenWeatherMap and GeoWeather APIs to derive insights about how weather variables behave at different latitudes.

### Analysis Highlights

### Scatterplots

##### Latitude vs. Max Temperature
![City Latitude vs. Max Temperature on 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig01.png)

**Figure 1:**  
The scatter plot above shows the relationship between latitude and maximum temperatures of cities in our sample on 7/21/24. We see that the further a city is from the equator, the lower the temperature, as expected. Although maximum temperatures increase as the latitude approaches the equator (latitude 0), our sample data did not show that the highest maximum temperatures are at the equator. Instead, we observe peak temperatures between 20-30 degrees latitude.

##### Latitude vs. Humidity
![City Latitude vs. Humidity on 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig02.png)

**Figure 2:**  
The scatter plot above shows the relationship between latitude and humidity of cities in our sample on 7/21/24. Overall, the scatter plot does not show a strong relationship between latitude and humidity.

##### Latitude vs. Cloudiness
![City Latitude vs. Cloudiness on 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig03.png)

**Figure 3:**  
The scatter plot above shows the relationship between latitude and cloudiness of cities in our sample on 7/21/24. Overall, the scatter plot does not show a strong relationship between latitude and cloudiness.

##### Latitude vs. Wind Speed
![City Latitude vs. Wind Speed on 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig04.png)

**Figure 4:**  
The scatter plot above shows the relationship between latitude and wind speed of cities in our sample on 7/21/24. Overall, the scatter plot does not show a strong relationship between latitude and wind speed.

##### Linear Regressions

##### Latitude vs. Maximum Temperature: Northern Hemisphere
![City Latitude vs. Maximum Temperature in the Northern Hemisphere on 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig05.png)

**Figure 5:**  
The linear regression plot shows the relationship between latitude and maximum temperature of cities in the Northern Hemisphere in our sample on 7/21/24. The plot shows a negative relationship, indicating that as latitude increases, maximum temperature decreases, as expected. The R-squared value is approximately 0.33812, confirming a linear correlation between latitude and maximum temperature.

##### Latitude vs. Max Temperature: Southern Hemisphere
![City Latitude vs. Maximum Temperature in the Southern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig06.png)

**Figure 6:**  
The linear regression plot shows the relationship between latitude and maximum temperature of cities in the Southern Hemisphere in our sample on 7/21/24. The plot shows a positive relationship, indicating that as latitude increases, maximum temperature also increases, as expected. The R-squared value is approximately 0.55184, confirming a linear correlation between latitude and maximum temperature.

##### Latitude vs. Humidity: Northern Hemisphere
![City Latitude vs. Humidity in the Northern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig07.png)

**Figure 7:**  
The linear regression plot shows the relationship between latitude and humidity of cities in the Northern Hemisphere in our sample on 7/21/24. The plot does not show a strong relationship between latitude and humidity. The R-squared value is approximately 0.03243, confirming that there is no linear correlation between latitude and humidity. Thus, we cannot predict humidity based on the latitude of a city.

##### Latitude vs. Humidity: Southern Hemisphere
![City Latitude vs. Humidity in the Southern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig08.png)

**Figure 8:**  
The linear regression plot shows the relationship between latitude and humidity of cities in the Southern Hemisphere in our sample on 7/21/24. The plot does not show a strong relationship between latitude and humidity. The R-squared value is approximately 0.00033, confirming that there is no linear correlation between latitude and humidity. Thus, we cannot predict humidity based on the latitude of a city.

##### Latitude vs. Cloudiness: Northern Hemisphere
![City Latitude vs. Cloudiness in the Northern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig09.png)

**Figure 9:**  
The linear regression plot shows the relationship between latitude and cloudiness of cities in the Northern Hemisphere in our sample on 7/21/24. The plot does not show a strong relationship between latitude and cloudiness. The R-squared value is approximately 0.02833, confirming that there is no linear correlation between latitude and cloudiness. Thus, we cannot predict cloudiness based on the latitude of a city.

##### Latitude vs. Cloudiness: Southern Hemisphere
![City Latitude vs. Cloudiness in the Southern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig10.png)

**Figure 10:**  
The linear regression plot shows the relationship between latitude and cloudiness of cities in the Southern Hemisphere in our sample on 7/21/24. The plot does not show a strong relationship between latitude and cloudiness. The R-squared value is approximately 0.00418, confirming that there is no linear correlation between latitude and cloudiness. Thus, we cannot predict cloudiness based on the latitude of a city.

##### Latitude vs. Wind Speed: Northern Hemisphere
![City Latitude vs. Wind Speed in the Northern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig11.png)

**Figure 11:**  
The linear regression plot shows the relationship between latitude and wind speed of cities in the Northern Hemisphere in our sample on 7/21/24. The plot does not show a strong relationship between latitude and wind speed. The R-squared value is approximately 0.00968, confirming that there is no linear correlation between latitude and wind speed. Thus, we cannot predict wind speed based on the latitude of a city.

##### Latitude vs. Wind Speed: Southern Hemisphere
![City Latitude vs. Wind Speed in the Southern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig12.png)

**Figure 12:**  
The linear regression plot shows the relationship between latitude and wind speed of cities in the Southern Hemisphere in our sample on 7/21/24. The plot does not show a strong relationship between latitude and wind speed. The R-squared value is approximately 0.00968, confirming that there is no linear correlation between latitude and wind speed. Thus, we cannot predict wind speed based on the latitude of a city.

##### Map Plots

##### Map Plot Cities by Humidity
![Map Plot of Cities](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig13.png)

**Figure 13:**  
The map plot above shows the cities from our data. The size of the circles indicates the relative humidity. Hovering over a city with the mouse will display the latitude, longitude, city name, and humidity.

##### Map Plot Cities with Ideal Weather Conditions
![Map Plot of Cities](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig14.png)

**Figure 14:**  
The map plot above shows the cities from our data with ideal weather conditions. The data is filtered to include cities with maximum temperatures between 19-28 degrees Celsius, wind speeds less than 4.5 kilometers per hour, and no cloudiness. The size of the circles indicates the relative humidity. Hovering over a city with the mouse will display the latitude, longitude, city name, humidity, nearest hotel, and country.

## Conclusions

1. **Latitude and Maximum Temperature**:
   - There is a clear relationship between latitude and maximum temperature. Cities further from the equator tend to have lower temperatures.
   - Peak temperatures were observed between 20-30 degrees latitude rather than exactly at the equator.

2. **Latitude and Humidity**:
   - There is no strong correlation between latitude and humidity. The scatter plots and linear regression analyses indicate that latitude is not a reliable predictor of humidity.

3. **Latitude and Cloudiness**:
   - Similar to humidity, there is no significant correlation between latitude and cloudiness. The data shows that cloudiness cannot be predicted based on latitude.

4. **Latitude and Wind Speed**:
   - There is no strong relationship between latitude and wind speed. The scatter plots and linear regression analyses confirm that latitude does not reliably predict wind speed.

5. **Hemispheric Differences**:
   - In the Northern Hemisphere, maximum temperature decreases as latitude increases.
   - In the Southern Hemisphere, maximum temperature increases as latitude increases.

6. **Predictive Limitations**:
   - While latitude is a useful predictor for maximum temperature, it is not effective for predicting humidity, cloudiness, or wind speed.

7. **Ideal Weather Conditions**:
   - Cities with ideal weather conditions (moderate temperatures, low wind speeds, and no cloudiness) can be identified, but these conditions are not dependent on latitude alone.

These conclusions highlight the complexities of weather patterns and the varying influences of latitude on different weather variables.

## Results

#### Scatterplots

##### Latitude vs. Max Temperature
![City Latitude vs. Max Temperature on 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig01.png)

**Figure 1:**  

##### Latitude vs. Humidity
![City Latitude vs. Humidity on 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig02.png)

**Figure 2**  

##### Latitude vs. Cloudiness
![City Latitude vs. Cloudiness on 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig03.png)

**Figure 3**  

##### Latitude vs. Wind Speed
![City Latitude vs. Wind Speed on 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig04.png)

**Figure 4** 

#### Linear Regressions

##### Latitude vs. Maximum Temperature: Northern Hemisphere
![City Latitude vs. Maximum Temperature in the Northern Hemisphere on 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig05.png)

**Figure 5**  

##### Latitude vs. Max Temperature: Southern Hemisphere
![City Latitude vs. Maximum Temperature in the Southern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig06.png)

**Figure 6**  

##### Latitude vs. Humidity: Northern Hemisphere
![City Latitude vs. Humidity in the Northern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig07.png)

**Figure 7**  

##### Latitude vs. Humidity: Southern Hemisphere
![City Latitude vs. Humidity in the Southern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig08.png)

**Figure 8**  

##### Latitude vs. Cloudiness: Northern Hemisphere
![City Latitude vs. Cloudiness in the Northern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig09.png)

**Figure 9**  

##### Latitude vs. Cloudiness: Southern Hemisphere
![City Latitude vs. Cloudiness in the Southern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig10.png)

**Figure 10**  

##### Latitude vs. Wind Speed: Northern Hemisphere
![City Latitude vs. Wind Speed in the Northern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig11.png)

**Figure 11**  

##### Latitude vs. Wind Speed: Southern Hemisphere
![City Latitude vs. Wind Speed in the Southern Hemisphere 7/21/24](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig12.png)

**Figure 12**  

#### Map Plots

##### Map Plot Cities by Humidity
![Map Plot of Cities](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig13.png)

**Figure 13**  

##### Map Plot Cities with Ideal Weather Conditions
![Map Plot of Cities](https://github.com/pixare7/World_Weather_Analysis/blob/main/output_data/Fig14.png)

**Figure 14** 
