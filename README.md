# PyBer_Analysis

## Overview of the analysis
### **Purpose**
<br> In this project, we would like to run following two types of analyses, so as to understand the disparities in the ride-sharing data among the city types.
- what's the total number of the rides,drivers per each city type(Rural/Suburban/Urban), as well as the average fares per ride and per driver.
- What's the fare distribution per city type(Rural/Suburban/Urban) during a range of dates: from 2019-01-01 to 2019-04-29

## Results
### Summary of Overall Ride-Sharing per City Type
![Pyber_summary](./challenge/Pyber_summary.png)  
<br>From what is shown in the dataframe above, from the perspectives of total rides, total drivers, and total fares, we can see there're 10 times more fares, rides, and drivers in Urban than Rural area. Even comparing with Urban and Suburban area, the total fares of Urban cities are 2 times more than that in Suburban cities.
<br>However, even though the total fares, rides are way less in Rural area than that in Urban cities. As we have less drivers working in the Rural area, the average fare per ride and per driver is almost 40% higher than that in Urban cities.

### Fares distribution from Jan.2019 to Apr.2019 per City Type
![PyBer_fare_summary](./challenge/PyBer_fare_summary.png)
<br>The line chart above also reflects the same point as the overall summary - Urban cities have the most total fares, followed by Suburban cities and Rural areas.  
<br> On the other hand, we can also see the variance of fares from Jan.2019 to Apr.2019 is very minimum, as all 3 lines tend to be flat during that period of time, which means not too much difference in the level of fares during Jan.2019 to Apr.2019.

## Summary
Based on the analysis of rides, driver numbers, and fares, we have following suggestion:
- Do a further research in the Suburban and Rural area to break down the actual demand of the rides in those 2 areas, as well as the average wage of the drivers in Suburban and Rural areas.
- Maintain the drivers in Urban cities to accommodate the high level of ride demands in Urban cities. 
- Based on the break down analysis of the ride demands and wage level in Suburban and Rural areas, we can further decide whether to encourage part of the drivers in Urban cities to accommodate the rides in Suburban cities and Rural area, or recruit more drivers based in Suburban and Rural area to absort the local business. 