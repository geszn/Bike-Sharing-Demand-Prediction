<h1 align="center">
  Bike Sharing Demand Prediction
</h1>
</br>
<h1 align="center">
  <img src="https://img.icons8.com/officel/80/000000/cycling-track.png"><img src="https://img.icons8.com/officel/80/000000/cycling-track.png"><img src="https://img.icons8.com/officel/80/000000/cycling-track.png">
</h1>

### Context 
Bike sharing systems are a new generation of traditional bike rentals where the whole process from membership, rental and return back has become automatic. It’s becoming popular due to their important role in traffic, environmental and health issues. Even the government promote bike ridership to reduces traffic. In this analysis we will analyze the dataset based on the environment factors such as temperature, wind, time and weather and then create a predictive model to forecast future ridership.

### Content 
The datasets retrieved from UCI Machine Learning Repository of the University of California, Irvine (<a href="https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset">https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset</a>).</p>
The datasets hour.csv and day.csv have the following fields, except hr which is not available in day.csv. we’ll be using only one of the data set which is the hour.csv.</p>

-	instant: record index
-	dteday : date
-	season : season (1:springer, 2:summer, 3:fall, 4:winter)
-	yr : year (0: 2011, 1:2012)
-	mnth : month ( 1 to 12)
-	hr : hour (0 to 23)
-	holiday : weather day is holiday or not (extracted from [Web Link])
-	weekday : day of the week
-	workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
-	weathersit :
1. Clear, Few clouds, Partly cloudy, Partly cloudy
2. Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
3. Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
4. Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
-	temp : Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
-	atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
-	hum: Normalized humidity. The values are divided to 100 (max)
-	windspeed: Normalized wind speed. The values are divided to 67 (max)
-	casual: count of casual users
-	registered: count of registered users
-	cnt: count of total rental bikes including both casual and registered
