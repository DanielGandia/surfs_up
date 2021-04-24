# Surfs Up
## Overview of the Analysis:
Analyze the temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.
## Resources:
- Data Sources: hawaii.sqlite
- Software: Python 3.8.3, Jupyter Notebook 6.1.4, Visual Studio Code 1.54

## Results:
As shown on the below tables, we notice the following:
 - There is a only 2 degree difference in the max temparature between June and December. 
 - The average temperature is 3 degrees warmer in June, which would be expected since it is the beginning of Summer.
 - The biggest difference can be found on the minimum temperature between the two months with 8 degrees of variance. 
### June Results:

Stat | Temperature
---------- | -----------
Avg | 74.944118
Min | 64.000000
Max | 85.000000
### December Results:

Stat | Temperature
---------- | -----------
Avg | 71.041529
Min	| 56.000000
Max	| 83.000000

## Summary

Due to the very minimal change in temperature in these months, it can be concluded the the surf and ice cream shop business can be sustainable throughout the year. According to the additional analysis done, the main difference between the months is not so much in the temperature but rater in the precipitation.  

Below are the queries to provide additional information to the analysis.
### June Rainfall:

![june_rain_query.png](https://github.com/DanielGandia/surfs_up/blob/main/analysis/june_rain_query.png)

![June_Rain.png](https://github.com/DanielGandia/surfs_up/blob/main/analysis/June_Rain.png)

### December Rainfall:

![december_rain_query.png](https://github.com/DanielGandia/surfs_up/blob/main/analysis/december_rain_query.png)

![Dec_Rain.png](https://github.com/DanielGandia/surfs_up/blob/main/analysis/Dec_Rain.png)