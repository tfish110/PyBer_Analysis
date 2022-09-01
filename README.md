# PyBer_Analysis
## Overview
### Purpose

The CEO of PyBer, a ride-sharing company, has assigned us to create a summary comparing and contrasting ride-sharing data among three city types: rural, suburban, and urban. We have been asked to specifically include a graph detailling the total weekly fares for each type of city. Our goal is to provide insights on how differences in these data can drive decision-making at PyBer.

### Resources
- Data Sources: city_data.csv, ride_data.csv
- Software: Python 3.7.13, Anaconda command line client 1.9.0, Conda 4.13.0, Jupyter Notebook 6.4.8, Pandas 1.3.5, NumPy 1.21.5, Matplotlib 3.5.1

## Results
### Summary DataFrame
![Summary DataFrame](https://github.com/tfish110/PyBer_Analysis/blob/main/analysis/Summary_DataFrame.png)

The summary DataFrame that was extrapolated from the raw data is shown above. Here, we can see that the fewest number of rides and drivers are in the rural cities. The greatest number of rides and drivers are in urban cities, with suburban cities falling between rural and urban. However, this pattern is reversed with respect to the average fares per ride and per driver, with the highest being in rural cities and the lowest in urban cities.

### Total Fare by City Type
![Total Fare by City Type](https://github.com/tfish110/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

This figure shows the total fares for each city type over the first four months of 2019. Each peak and valley in the lines represents the total fare for one week. This illustrates the differences in fares between cities that was described in the DataFrame. It should be noted that for each city type, the weekly fare totals remain relatively consistent over time.

## Summary

The data above regarding the numbers of rides and drivers fall into place with expected numbers based on the operational definition differentiating the three city types by population numbers; in other words, by definition, the population of a given city would dictate how many PyBer drivers there would be, and how many rides would be sought through PyBer's ride-sharing services.

As was pointed out above in the description of the Total Fare by City Type graph, the fare level for each city seems to be internally consistent over time. There seems to be a slight upward tren in the first for months across all three city types. This seems likely due to weather, as winter months in colder climates would be likely to deter people from traveling anywhere as much, even within their own cities. This would indicate that seasonal incentives to increase ridership may be an appropriate route to drive decision-making, as those trends seem universal across city types. 

The urban cities seem to be most set apart from the other two categories on one parameter in particular: the number of PyBer drivers. In rural and suburban cities, there were more rides than drivers, meaning that there were more opportunities for each given driver in those areas to earn money. However, in urban cities there were more drivers than there were rides given. This would indicate that many drivers are not getting the opportunites to charge fares that their rural and suburban counterparts are getting. This would indicate that it might be beneficial to scale back the number of drivers in urban cities.

Alternatively, rather than scaling back drivers in urban cities, it may also indicate that there is an opportunity to increase fares in urban cities. As can be seen in the average fares per ride and per driver, rural and suburban cities' average fare per ride is less than their average fare per driver. However, in urban cities, this trend is reversed, and the average fare per driver is lower than the average fare per drive. This indicates that the market may tolerate an increase in fares in urban areas, as scarcity of drivers is clearly not a problem there. The major caveat for this point is that urban areas likely have more competition in the market from traditional taxi servies that their rural and suburban counterparts do not have to contend with. So, it's recommended that market research be done to determine the viability of a fare increase in order to maximize profits.
