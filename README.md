# PyBer_Analysis

## Analysis Overview

The purpose of this analysis is to identify how the ride-sharing data differs by city type and how those differences can help the decision-makers at Pyber.


# Analysis
The analysis was performed by creating pie charts, a summary DataFrame of the ride-sharing data by city type and a multiple-line graph that represents the total weekly fares for each city type using Python, Pandas and Matplolib.


## Results

### Total Rides by City Type

- As seen on the image below, the Urban City Rides with 1625 rides takes the biggest portion of the pie chart representing 68.4% of the total rides.
- Suburban Cities take the second place with 625 rides being 26.3% of the total rides.
- Rural cities take the third place with only 125 rides being 5.3% of the total rides.

![% of Total Rides by City Type](./Analysis/Fig6.png)



### Total Drivers by City Type

- The following pie chart represents the total drivers by city type.
- Urban city type, had 2,405 drivers taking 80.9% of the pie chart. 
- Suburban cities had 490 drivers representing 16.5% of the total drivers.
- Rural cities had only 68 drivers representing 5.3% of the total drivers.


![% of Total Drivers by City Type](./Analysis/Fig7.png)


### Total Fares by City Type

- As seen on the image below:
- Urban cities had $39,854.38 in transactions which represents 62.7% of the total fares.
- Suburban cities had $19,356.33 in transactions representing 30.5% of the total fares.
- Rural cities had only $4,327.93 of the transactions representing 6.8% of the total fares.


![% of Total Fares by City Type](./Analysis/Fig5.png)


The image below displays the Pyber Summary DataFrame, where we can see the ride-share data differences between Urban, Suburban and Rural cities.

- Urban cities have the highest number of Total Rides Total Drivers, and the biggest amount of Total Fares, while at the same time having the lowest Average Fare per Ride and Average Fare per Driver.

- Suburban cities were the ones in the middle for all the results.

- On the other extreme, Rural cities were the ones with the lowest amount of Total Rides, Total Drivers, and Total Fares. While the Average Fare per Ride and Average Fare per Driver were the highest among all three different types of cities.


![pyber_summary_df](./Analysis/pyber_summary_df.png) 



The following chart represents the Pyber Fare Summary where the lines show the Total Fare by City Type and each peak or drop is a different week between the dates of Jan/01/2019 to April/28/2019.

 - The yellow line represents the Urban cities trend over the 5 months period, starting at a Total Fare of $1,661.68 and ending at $2,238.29. 

 - The red line shows the Suburban cities trend where the Total Fare starts at $7,21.60 and ends at $1,357.75.

 - The blue line displays the Rural cities trend starting at $187.92 and having a increasing to $191.85.

 - Something else worth mentioning is that all three city types had a pick in the total fare at the 3rd week of February.



![Pyber_fare_summary](./Analysis/Pyber_fare_summary.png)


## Conclusion 

Urban cities have the highest amount of ride-share trips and consequently more drivers, which results in the largest amount of transactions happening there compared to Suburban and Rural cities. This also has a big impact on the price per ride on the rural cities.

This can be interpreted by: the more dense and concentrated a city is, the highest demand and lower price it has.
Where the more disparsed a city is, the demand is lower and price is high.


## Summary

Business Recommendations:

- In order to increase the overall outcomes for suburban and rural cities perhaps the company could decrease the price per fare for these cities, until is becomes more accessible which would increase the demand for drivers and consequently more rides would be taken.

- Another recommendation is to promote the ride-share service on social media, local radio stations, and local shops in order to being noticed and get more clients. Where they could also share the benefits of using this service.

- Promoting campaigns to hire more drivers.

- Specify main points where drivers could be located in the suburban and rural cities, like near grocery stores, shopping centers, terminals, etc in order to target the the clients on the places they may need the most. 


