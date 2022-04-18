# PyBer_Analysis
Module 5
## Overview

The purpose of our analysis is to create a summary dataframe that will show ride sharing data by city type(Rural,Urban & Suburban). Once we find our data we are going to create a multiple line graph that shows total weekly fares by each city type. How we first pulled our data is by using the pandas Groupby() function with the count() and sum () to get the total number of drivers,rides and fares by city type. Once we pulled this information and assigned it to functions we were able to calculate our average fare per ride and driver. Once we had all of that information together we were able to format into a newdata frame and re-format the columns. In the second part of this excercise we used the pivot() and resample function to create a multiple line graph that shows the total fares for each week by city type between the months of January & April of 2019.

## Results
The dataframe summary for ridesharing tells us a number of things. There are significantly more rides in Urban cities than Suburban or Rural. The number of drivers also follows that same pattern with more drivers being in Urban cities. The average fare per ride and average fare per driver are actally most expensive in the rural areas and cheaper in the Urban cities. This tells us that as a ride share service has more drivers available the ride expenses or fares become cheaper on average. However, it is interesting to note that a missing piece of crucial data is the length of the ride. Its possible that since rural areas might require longer rides, that the data is skewed by the duration of the ride causing an increase in fares.

- Rural cities has the least amount of drivers, rides and total fares.
- Urban cities have the most amount of drivers, rides and total fares.
- Suburban cities are in the middle having the 2nd most drivers, rides and total fares.
- Although Rural cities see the least amount of drivers,rides & fares the have the highest average of fare per ride and fare per driver.
- Although the Urban cities command the most drivers, rides and fares they have the lowest average of fare per ride and fare per driver.

There are more rides in Urban cities vs. Suburban or Rural.
![Urban Cities rides](https://user-images.githubusercontent.com/99842026/163745514-292831b6-ab62-4c05-96fb-1e6db458334b.png)

The percent of total drivers by city shows the same pattern having more drivers being in Urban cities. 
![Urban city drivers](https://user-images.githubusercontent.com/99842026/163745528-e72986bd-5fd1-400b-8024-c8a7e5a1197a.png)

The average fare per ride with the average fare per driver are most expensive in the rural city type and less expensive in the urban city type. Yes, rural city type rides are higher; however, more fare dollars are made from urban city type fares.
![Urban city fares](https://user-images.githubusercontent.com/99842026/163745536-9fd1a542-4720-49b5-939c-13eaa138c290.png)

## Summary

The multiline graph gives a nice visualiation of the ride share data. It clearly shows that all city types (Urban, Suburban, and Rural) are fairly consistent in total fares over time. There are a few spikes in the data here and there but overall quite consistent. It also shows that the majority of the money comes from Urban cities followed by Suburban and Rural last... It is clear from both of the summary dataframe and graph that even though the average fair of a Rural ride is higher, more money is made from Urban rides in total.
Based on the results of our analysis, we offer the following business recommendations to the PyBer CEO for addressing the disparities in rides, fares and driver opportunities among the different city types.

- Have your drivers assigned to different city types based off of what type of cities they typically work in.
- Charge more per mile in urban cities because trips most likely are shorter and drivers dont earn as much per trip.
- Make small charge increases or descreases based off of how many riders there are in the city during certain months.
