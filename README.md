# PyBer Ride Sharing Analysis

## Overview of the analysis
The purpose of this project is to perform descriptive statistics, analyze and visualize ride-sharing data for PyBer, a ride-sharing company. Methods include using Python, Pandas, and the Matplotlib library. Given two files of ride-sharing data: "city_data.csv" comprised of city name, # of drivers, and city type, and "ride_data.csv" comprised of city name, date, fare and ride id, the two files were merged and analysis performed to determine the types of cities with the greatest amount of fares and the types of cities where the most rides occured per week. 

## Challenge Solution

[Challenge Solution](PyBer.ipynb): The solution files for the module's challenge assignment are located in this folder.

## Module Solution

[Module Solution](PyBer_Challenge.ipynb): Any module demos or solution files for the module async content are located in this folder.

## Results
Analysis of the data showed that more rides occurred in urban areas in 2019. 

A summary of the data by city type shows the large difference in numbers of total rides and total drivers in urban areas compared to suburban and rural areas. Even though fares in urban areas are on average lower than suburban and rural fares, the number of rides in urban areas results in higher revenue in total fares. However, the average fare per driver is highest in rural areas.

![Image of summary data for PyBer ride-shares in 2019](https://github.com/EBolinVA/PyBer_Analysis/blob/main/Resources/Summary_DataFrame.png)

The average number of rides in the rural cities is about 4- and 3.5-times lower per city than the urban and suburban cities, respectively. The number of rides in each city type is shown in the box plot below:

![Image of box plot showing 2019 ride data for urban, suburban and rural areas](https://github.com/EBolinVA/PyBer_Analysis/blob/main/Resources/Fig2.png "Ride Count Data (2019)")

It follows that with more demand for rides, there are more drivers in the urban areas: 

![Image of box plot showing 2019 driver data for urban, suburban and rural areas](https://github.com/EBolinVA/PyBer_Analysis/blob/main/Resources/Fig4.png "Driver Count Data (2019)")

Average fares for riders in rural areas is as much as $11 higher than urban areas, and about $5 higher than suburban areas. 

![Image of box plot showing 2019 fare data for urban, suburban and rural areas](https://github.com/EBolinVA/PyBer_Analysis/blob/main/Resources/Fig3.png "Ride Fare Data (2019)")

However, we know from the Ride Count Data (2019) chart above that there is simply more demand for rides in urban areas. Even with lower average fares than suburban and rural city types, urban areas bring in more revenue for Pyber.

![Image of pie chart showing percentage of Total Fares data for urban, suburban and rural areas](https://github.com/EBolinVA/PyBer_Analysis/blob/main/Resources/Fig5.png "% of Total Fares by City Type (2019)")

![Image of pie chart showing percentage of Total Rides data for urban, suburban and rural areas](https://github.com/EBolinVA/PyBer_Analysis/blob/main/Resources/Fig6.png "% of Total Rides by City Type (2019)")

![Image of pie chart showing percentage of Total Drivers data for urban, suburban and rural areas](https://github.com/EBolinVA/PyBer_Analysis/blob/main/Resources/Fig7.png "% of Total Drivers by City Type (2019)")

Merged together, the line chart below illustrates the Total Fare by City Type for the first quarter of 2019. Urban cities consistently earned higher fares than suburban and rural cities. Every city type experienced a spike in total fares between February and March, perhaps the colder, rainier time of the year. 

![image of a line chart showing Total Fare by City Type for Quarter 1 of 2019](https://github.com/EBolinVA/PyBer_Analysis/blob/main/Resources/Challenge_fare_summary.png)

## Summary and Recommendations

Based on the results of 2019 PyBer rideshare analysis showing overall higher revenue in urban areas, and lower ride count but higher average fares in rural areas, here are three recommendations for PyBer:

- Increase fare for rides in urban areas. 
    - Demand for rides in urban areas is evident with % Total Rides by City Type. 
    - Average Fares per driver is lowest in urban areas, so increasing the fare will encourage drivers to make more trips, earning them more pay.

- Decrease the fares for rides in rural areas to incentivize riders to use the service
    - Average fare per ride, and average fare per driver in rural areas is higher than both urban and suburban areas. Offering special fares to riders will increase ridership and revenue in the rural areas.

- Consider analyzing pay per mile in each area. 
    - A close look at pay structure might lead to equalizing pay per mile across city types.