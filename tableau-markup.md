# Citi Bank Tableau Homework

## 1. Bike potentially due for maintenace (Bike Usage Dashboard)
In an effort to identify bikes that may be approaching their need for maintenace before malfunctions or breakdowns due to ware occure, we've put together a list of bike IDs with some usage metrics for 2019:<br>

    - Ride Count: Simply counts of the number of rides groubed by each bike id.<br>
    - Estimated Usage Hours: Due to errors in triggering stop time of a ride when the bike is returned to the dock, there are some greatly inflated ride times, making it difficult to do aggregate calculations and summary. To get around this, we took the median ride duration for each bike and multiplied it by the ride count for each bike id.  This gave us what we call the "estmated usage hours.<br>

We decided to look at two different time scales to see which bikes might be due for maintenance.  First, we looked at overall usage across all of 2019 (Jan through September). Second, we looked at bikes that had highest usage over the winter and early spring months when road and weather conditions would accelerate wear. Looking at the box diagram on the Dashboard, the darker shaded boxes represent bikes with higher estimated usage hours.  Additionally, they are sized and sorted based on the number of rides.  This should give a quick illustration of which bikes are used most through the year. <br>

**Bike IDs most likely in need of repiar soon:**<br> 

    - Top 5 bikes based on ride count and estimated usage hours for the year to date [35316, 35029, 34181, 33897, 33938]
    - Top 5 bikes based on ride count and estimated usage hours for January-March 2019 [35779, 35641, 35619, 34707, 35544]

Note: If there was more time, it would be prudent to calculate the distances the bikes are traveling as another metric of bike usage and ware. 

## 2. Weekday ride habits and pass sales
We looked at the average number of rides by weekday (2013-2018) compared to 2019 year to date. Overall, ridership is up across all days of the week.  Wednesday has the most number of rides during the week on average. The distribution of rides on average are lighter on weekends then during the middle of the week. As the weather improves and the city hits peak summer season, this skews slightly more towards Wednesday, Thursday, Friday and Saturday having the greatest concentration of rides on average.<br>

However, when looking at the number of passes sold (1-day pass and 3-day passes), The middle of the week sees the lowest number of passes sold on average.  Pass sales peak on Saturday and Sunday.  This could be attributed to heavy bike usage by locals with anual subscriptions, utilizing the bikes for commuting and daily errands.  When the weekend comes, those individuals may not have needs for bike utilization. Tourists and visitors come into the city, and decide to purchase short term passes to tour the city.  

## 3. Station map
Plotting the stations on a map show the most popular stations tend to be south of Midtown where more of concentration of offices and points of interest are located. Also, we varied the size of the station marker based on the average trip duration taken from that station. What we found is that bike stations along the border of central park and the river walks had bikes who tended to go on trips of longer duration. 


