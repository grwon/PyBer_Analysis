# PyBer_Analysis

## Project Overview
V. Isualize has given myself and Omar a brand-new assignment. We created a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you created a multiple-line graph that shows the total weekly fares for each city type.

### Purpose
Purpose of this report is to summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer. 


## Resources
- Data Source: city_data.csv and ride_data.csv
- Software: Python 3.8, Visual Studio Code, 1.46.1

## Results: Pyber by City Type Summary

![Pyber Summary](https://github.com/grwon/PyBer_Analysis/blob/master/Resources/pyber_summary_df.png)   

### Average Fare per ride
From the above Pyber Summary, we noticed that the average fare per ride in the rural cities is about $10 and $4 more per ride than the urban and suburban cities, respectively. The variance in fare may be due to the distance traveled per ride. Destination are farther apart in rural cities than urban cities, you may have to go 20km to get to the closest grocery store compared to 2km in urban cities and 5km in suburban cities. 

### Average Fare per Driver
If we compare the average fare per driver between each city type, we will notice that the average fare per driver in the rural cities is about 3.3 and 1.4 times higher than urban and suburban cities, respectively. 

### Total number of ride, drivers and total fare
The number of total rides for rural cities is about 13 and 5 times less than urban and suburban cities, repsectively. The total number of drivers in rural cities is about 31 and 6 times less than urban and suburban cities, respectively. The total fare in rural cities is about 9 and 4 times lower than urban and suburban cities.

## Recommendation
When we look at the total fare by city type line graph below, we can see that total fare for urban cities is consistently high than suburban and rural cities. This can be explained by the density of population living in urban cities compared to suburban and rural cities. We can increase total fare in rural cities by lowering fare per ride, as this will give riders in rural cities incentive to take more rides and therefore increase number of rides and increase overall revenue in rural cities. We should further analyze the number of riders and purpose of their rides such as commuting to work, to do groceries, or to go out for restaurants. We can then roll out marketing campaign targeting riders in suburban city type to increase their ridership, such as reminding them of convenience to be picked up outside the groceries stores instead of walking to the bus stops and ability to drink freely on a night out instead of having to worry about driving home. This will increase total fare in suburban cities. We can also further investigate the location of each ride, there could be hot spots in each city type where drivers can find more riders. This will help increase total revenue for all city types, especially rural cities where it could be costly for drivers to get from one fare to the next.

![Pyber_Fare_Summary](https://github.com/grwon/PyBer_Analysis/blob/master/analysis/PyBer_fare_summary.png)

