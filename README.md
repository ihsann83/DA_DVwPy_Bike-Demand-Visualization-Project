# DA_DVwPy_Bike-Demand-Visualization-Project

Free or affordable access to bicycles has been provided for short-distance trips in an urban area as an alternative to motorized public transport or private vehicles. Thus, it is aimed to reduce traffic congestion, noise and air pollution. The aim of this project is to reveal the current patterns in the data by showing the historical data of London bike shares with visualization tools. This will allow us to X-ray the data as part of the EDA process before setting up a machine learning model.

# Determines



#Features

- timestamp - timestamp field for grouping the data
- cnt - the count of a new bike shares
- t1 - real temperature in C
- t2 - temperature in C “feels like”
- hum - humidity in percentage
- wind_speed - wind speed in km/h
- weather_code - category of the weather
- is_holiday - boolean field - 1 holiday / 0 non holiday
- is_weekend - boolean field - 1 if the day is weekend
- season - category field meteorological seasons: 0-spring ; 1-summer; 2-fall; 3-winter.

**"weather_code" category description:**
* 1 = Clear ; mostly clear but have some values with haze/fog/patches of fog/ fog in vicinity 
* 2 = scattered clouds / few clouds 
* 3 = Broken clouds 
* 4 = Cloudy 
* 7 = Rain/ light Rain shower/ Light rain 
* 10 = rain with thunderstorm 
* 26 = snowfall 
* 94 = Freezing Fog
---

Initially, the task of discovering data will be waiting for you as always. Recognize features, detect missing values, outliers etc.  Review the data from various angles in different time breakdowns. For example, visualize the distribution of bike shares by day of the week. With this graph, you will be able to easily observe and make inferences how people's behavior changes daily. Likewise, you can make hourly, monthly, seasonally etc. analyzes. In addition, you can analyze correlation of variables with a heatmap. 

# Discovering The Data

I checked missing values and if there are any dublicate rows or not. I plotted the distribution of various discrete features on (Season, haliday, weekend and weathercode). Then, I looked at the data type of each variable, transformed timestamp in type, and set it as index. After that, I made feature engineering and extracted new columns (day of the week, day of the month, hour, month, season, year etc.).

# Reviewing The Data from various angles in different time breakdowns

Firstly, I visualized the correlation with a heatmap. Secondly, I visualized the correlation of the target variable and the other features with barplot. Then I plotted bike shares over time use lineplot. Lastly, I plotted bike shares by months and year_of_month (use lineplot, pointplot, barplot). 

# Anaysing How People's Behavior Changes Daily, Hourly, Monthly, Seasonally etc.

Firstly, I plotted bike shares by hours on (holidays, weekend, season). Secondly, I plotted bike shares by day of week. Thirdly, I plotted bike shares by day of month and plotted bike shares on holidays by seasons. After that, I visualized the distribution of bike shares by weekday/weekend with piechart and barplot. Lastly, I plotted the distribution of weather code by seasons and visulaized all the continuous variables with histogram and scatterplot. 


