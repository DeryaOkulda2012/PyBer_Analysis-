# PyBer City-Type Analysis

## Overview of the analysis:

The company president has given us a new assignment. Using Python and Pandas, create a summary DataFrame of the ride-sharing data by city type (Urban, Suburban, or Rural). Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. Finally, summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Results:
Using images from the summary DataFrame and a multiple-line chart, the differences in ride-sharing data among the different city types will be analyzed and described.

### Total Rides:
Not surprisingly, the number of rides in urban areas is significantly higher than suburban rides, which is subsequently higher than rural rides. The total number of rides in each city type is as follows:

![image](https://github.com/DeryaOkulda2012/PyBer_Analysis-/blob/09fa7ba9b176efa1e06233790109d70d927f590e/Analysis/Fig1_Total_rides_for_each_city_type.png)

### Total Drivers:
In line with populations and demand density in urban areas as opposed to suburban and rural areas, the number of drivers serving these three areas is also aligned, with the number of drivers working in urban areas being significantly higher than suburban, which is significantly larger than the number of rural drivers. The total number of drivers working in each city type is as follows:

![image](https://github.com/DeryaOkulda2012/PyBer_Analysis-/blob/1b686509601436786debf4efd1565d28f22a4984/Analysis/Fig2_Total_drivers_for_each_city_type.png)

### Fares for Each City Types:
In line with the number of rides and the number of drivers in each city type, the total amount of fares collected in each city type also reflects these totals, with total fares in urban areas being significanly larger than suburban, and suburban subsequently being significantly larger than the rural fares total. The total amount of fares collected for each city type is as follows:

![image](https://github.com/DeryaOkulda2012/PyBer_Analysis-/blob/625bd50f1666f36803cc5c1da2ca65b561e697ff/Analysis/Fig3_Total_fares_for_each_city_type.png)

### Average Fare:
When we look at the average fare per ride, the totals are flipped, most likely due to the distances travelled in each city type and the mileage-based fares charged per ride. The average urban ride generates the lowest fare, then the suburban ride, then the rural ride, as the long distances involved in rural rides generates the highest average fare per ride. The average fare per ride for each city type is as follows:

![image](https://github.com/DeryaOkulda2012/PyBer_Analysis-/blob/625bd50f1666f36803cc5c1da2ca65b561e697ff/Analysis/Fig4_Average_fare_per_ride_for_each_city_type.png)

### Average Fare per Driver:
Subsequently, rural drivers earn the highest average fare of all drivers as the long rides in rural areas generate the highest average fare per driver, then suburban, and finally urban drivers earning the lowest average fare per driver. The average fare per driver for each city type is as follows:

![image](https://github.com/DeryaOkulda2012/PyBer_Analysis-/blob/625bd50f1666f36803cc5c1da2ca65b561e697ff/Analysis/Fig5_Average_fare_per_driver_for_each_city_type.png)

### Data Summary:
Once we clean up the dataframe, the result looks as follows:

![image](https://github.com/DeryaOkulda2012/PyBer_Analysis-/blob/625bd50f1666f36803cc5c1da2ca65b561e697ff/Analysis/Fig6_PyBer_Summary_DataFrame_Formatted.png)

### Weekly Summary:
When we analyze the weekly summary of PyBer fares, we can clearly see the significant differences between Urban, suburban, and rural fares.

![image](https://github.com/DeryaOkulda2012/PyBer_Analysis-/blob/c2dba5066746e913b9bfef67987bf8cfe5e92d8f/Analysis/Fig7_PyBer_FareSummary_Pivot.png)

The weekly total fares for each city type for the first four months of 2019 clearly ilustrates the consistent differences in totals between the urban, suburban, and rural city types. The urban type consistently generates around twice the suburban city type, and the suburban types consistently generates around four times (!) the rural city type over a four (4) month period. This significant disparity between the three city types is illustrated below:

![image](https://user-images.githubusercontent.com/93683791/145460599-a7b3831b-ed36-4555-ba3d-f09d4d6e5ead.png)

## Summary:
The three city types clearly result in different total number of rides, total number of drivers, and total fares for each city type. Although these results are not surprising, some adjustments could be possible to improve these results:

* Mileage fares in urban areas could be increased to take advantage of short distances travelled by those rides as opposed to suburban or rural rides which are incrementally longer.
* Time-of-day price variation could be introduced in busier urban and suburban city types to take advantage of different demand periods, such as higher fares during rush hour.
* 
