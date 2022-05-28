# PyBer Analysis

## Overview of the Analysis

The purpose of this project was to use Python, Pandas, and Matplotlib to create a summary DataFrame of ride-sharing data by city type, as well as a create a multiple line graph to show the weekly fares for each city type for the ride-sharing app company PyBer.

## Results
#### PyBer City Type Summary DataFrame

A city type summary data frame was created by merging the city data and ride data using the groupby function. The summary data frame contains total rides, total drivers, total fares, average per ride, and average per driver for each city type of rural, suburban, urban.

![image](https://user-images.githubusercontent.com/103764279/170830308-ea6c9431-64a1-4c23-9861-3f4abca67473.png)

This summary data frame shows that urban cities had more total rides and total drivers compared to suburban and rural city types. However, when looking at the average fare per ride and the average fare per driver, urban cities had a lower average compared to suburban and rural city types. The data shows that there is a correlation between the number of total drivers and the average fare per driver. The more drivers there are, the less each driver makes per ride. When there are less drivers, the more each driver makes per ride.

#### Total Fare by City Type

From the City Type Summary DataFrame, the pivot and resample functions were used to create a new data frame with the total fares by city type for the weeks between 2019-01-01 and 2019-04-28. Using Matplotlib, a multiple line graph was created to display the total fares by city type.

![image](https://user-images.githubusercontent.com/103764279/170831664-06037cbf-a3f6-429c-87f8-ab5c8e806bfa.png)

This line graph is an impactful visualization of the data because it can be immediately seen the differences in total fares for each city type. The line graph shows urban city types having the highest total fares and rural city types having the lowest. This was an interesting finding due to the fact that when looking at the average fare per ride, ubran was the lowest while rural was the highest.

Another interesting finding is that in the weeks leading up to March, the line graph shows a spike in increasing fares for all city types, as well as an immediate decline in the first week of March.

## Summary

With a completed analysis, here are three business recommendations:

1. In Urban city types where there are more drivers than there are rides, the goal would be to produce more rides which can be done through marketing and adverising. With more rides being produced, the average fare per ride and average fare per driver would also increase. 
2. In Suburban and Rural city types, the overall goal is to get more people to use ride share. Lowering the fare per ride would encourage more people use ride share. The average fare per ride in rural city types is about $10 more than in Urban city types. If there was a way to lower the fare for a certain time period in order to get more people in that area to use ride share, then that would lead to more rides. Increasing the total number of rides would eventaully lead to drop in fare, hopefully giving drivers more rides so they could also make more money.
3. In Rural city types, the total numbers of drivers is also very low. If there was an increase in drivers in rural city types, then there would be more availability for ride share. More availability leads to more people using ride share, which is still helping achieve the overall goal of getting more people to use ride share. This can also be applied for suburban city types.
