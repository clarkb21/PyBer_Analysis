# PyBer Ride Sharing Analysis

## Project Overview
- Data analyst for Pyber, a ride sharing company 
- Create visualizations to tell a story about the data
- Showcase the relationship between the type of city, the number of drivers, number of rides, and percentage of total fares, riders, and drivers by type of city
- Goal is to improve access to ride sharing services and determine affordability


### Challenge Overview
- Create a summary data frame of the ride sharing data by city type
- Create a multiple-line graph that shows the weekly fares for each city type

## Resources
- Data Source: city_data.csv; ride_data.csv
- Software: Python 3.7.6, Conda 4.13.0, Jupyter Notebook 6.4.8, Pandas 1.4.3
- MSU Bootcamp Spot Module 5: https://courses.bootcampspot.com/courses/2508/pages/5-dot-0-1-visualizing-ride-sharing-data?module_item_id=634904

## Results

![image](https://user-images.githubusercontent.com/104038813/178526674-751619aa-415f-400b-a2b6-654b63fd086c.png)


### Rides by City Type
![Fig2](https://user-images.githubusercontent.com/104038813/178518395-8f56e4e4-d136-4c6f-86ab-41d8c8a20fd3.png)

- Based on the above chart, urban cities have an median number of rides of 24, where suburban median is 17 and rural median is 6. Urban cities have a median number of rides 4 times larger than rural cities. 
- Urban city data did have one outlier city; suburban and rural cities had no outliers in the data
- Urban cities accounted for over 68 percent of all rides

![Fig6](https://user-images.githubusercontent.com/104038813/178520752-7ed1a678-b88b-433c-b110-977adfc3dad5.png)

### Drivers by City Type

![Fig4](https://user-images.githubusercontent.com/104038813/178519522-e0dfe0a6-6e43-45d7-891f-468fcee7b251.png)

- The average driver count for city type was 37 for urban, 14 for suburban, and 4 for rural cities. 
- Based on the plot, urban cities had a larger disparity between higher and lower number of drivers. 
- The most number of drivers in urban cities was 39 drivers, which occurred 86 times. The most number of drivers in rural cities was  1 driver, which occurred 32 times. 
- Drivers in urban cities accounted for over 80 percent of all drivers

![Fig8](https://user-images.githubusercontent.com/104038813/178521235-81ab10c7-1931-49d4-b55c-751dbe2663d5.png)


### Fares by City Type

![Fig3](https://user-images.githubusercontent.com/104038813/178522174-4eb994e3-eca0-4bb0-9570-d0f6480c9de7.png)

- The average fare price for urban trips was $24.53, suburban trips was $30.97, and rural trips was $34.62
- Some factors that could cause the fare price to increase in rural trips can include total distance traveled and the lack of drivers available. 
- Urban cities accounted for about 63 percent of all fares.

![Fig5](https://user-images.githubusercontent.com/104038813/178522802-3136d3c6-9c70-440d-beed-ef960a2df126.png)

### Total Fare by City Type
![Pyber_fare_summary](https://user-images.githubusercontent.com/104038813/178523279-c12c8b87-1a67-452b-ab55-714a60eca948.png)

- In a snippet of 4 months worth of rides, the line chart shows urban cities having a much higher total fare count than the other two types of cities. 
- All types increase total fares near the end of February and dip down near the beginning of March.

![Fig1](https://user-images.githubusercontent.com/104038813/178523300-ed1c3331-54be-42aa-9b69-3f7b8e65e05c.png)

- From the bubble chart above, urban cities had more rides than suburban and rural cities, but the average fare was usually higher for rural trips.
- The size of the bubbles indicates the driver count.


## Summary
Three business recommendations based on the data: 
1. Since urban drivers make up almost 87 % of all drivers, but only make up 63 % of all fares, I recommend adding more drivers in rural and suburban areas. 
2. Adding more drivers during "peak" times and seasons would allow for an increase in total rides which results in an increase in total fares. 
3. By identifying urban cities with a high driver count but lower number of rides and average fare, we can reduce number of drivers in those cities and save on payroll. 
