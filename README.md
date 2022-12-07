# Module 5 | Assignment - PyBer

## Overview of the analysis
Analyze and visualize ride-sharing data using Python, Pandas, and the Matplotlib library. Given two files of ride-sharing data: city_data comprised of city name, # of drivers, and city type, and ride_data comprised of city name, date, fare and ride id, the two files were merged and analysis performed to determine the types of cities with the greatest amount of fares and the types of cities where the most rides occured per week. 

## Challenge Solution

[Challenge Solution](Challenge_Solution): The solution files for the module's challenge assignment are located in this folder.

## Module Solution

[Module Solution](Module_Solution): Any module demos or solution files for the module async content are located in this folder.

## Results
Analysis of the data showed that more rides occurred in urban areas in 2019. The average number of rides in the rural cities is about 4- and 3.5-times lower per city than the urban and suburban cities, respectively. The number of rides in each city type is shown in the box plot below:

![Image of box plot showing 2019 ride data for urban, suburban and rural areas](/Resources/fig2.png "Ride Count Data (2019)")

It follows that with more demand for rides, there are more drivers in the urban areas: 

![Image of box plot showing 2019 driver data for urban, suburban and rural areas](/Resources/fig4.png "Driver Count Data (2019)")

Average fares for riders in rural areas is as much as $11 higher than urban areas, and about $5 higher than suburban areas. 

![Image of box plot showing 2019 fare data for urban, suburban and rural areas](/Resources/fig3.png "Ride Fare Data (2019)")

However, we know from the Ride Count Data (2019) chart above that there is simply more demand for rides in urban areas. Even with lower average fares than suburban and rural city types, urban areas bring in more revenue for Pyber.

![Image of pie chart showing percentage of Total Fares data for urban, suburban and rural areas](/Resources/fig5.png "% of Total Fares by City Type (2019)")

![Image of pie chart showing percentage of Total Rides data for urban, suburban and rural areas](/Resources/fig6.png "% of Total Rides by City Type (2019)")

![Image of pie chart showing percentage of Total Drivers data for urban, suburban and rural areas](/Resources/fig7.png "% of Total Drivers by City Type (2019)")

Merged together, the line chart below illustrates the Total Fare by City Type for the first quarter of 2019. Urban cities consistently earned higher fares than suburban and rural cities. Every city type experienced a spike in total fares between February and March, perhaps the colder, rainier time of the year. 

![image of a line chart showing Total Fare by City Type for Quarter 1 of 2019](/Resources/Challenge_fare_summary.png)


