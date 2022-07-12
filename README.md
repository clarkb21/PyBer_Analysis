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

### Was District Summary Affected?
- Original District Summary
![image](https://user-images.githubusercontent.com/104038813/177370423-c22614f5-0789-4a12-9d05-acaa8293c4ae.png)
- Updated District Summary

![image](https://user-images.githubusercontent.com/104038813/177370862-4ba4c646-53ad-4eb7-9682-1d47cc996313.png)

- Changing the data from Thomas High School did not affect the total number of schools, students, or the budget. 
- Based on the images above, the data for average math score changed slightly, and average reading score did not change.
- Since the changes to the averages was so small, the % Passing Categories did not reflect much change, either.

### Was School Summary Affected? 
- Original School Summary 
![image](https://user-images.githubusercontent.com/104038813/177373506-12db1a92-0982-4af5-8e1d-da92855284c6.png)
- Updated School Summary 
![image](https://user-images.githubusercontent.com/104038813/177373810-8bfb2270-a421-4e8c-8709-6006c7767c96.png)
- Because of the way I updated the data, only data from Thomas High School would be affected. 
- All other schools data remained untouched, so the data would not change. 

- Replacing scores for 9th graders at Thomas High School with "Not a Number" removes those scores from future calculations. Those scores are ignored rather than placing zeros, which would greatly impact the average scores. 

### Impact of Replacing 9th Grade Scores
![image](https://user-images.githubusercontent.com/104038813/177378725-dccbd4f4-fe93-41a1-b383-c9b268f9a459.png)

![image](https://user-images.githubusercontent.com/104038813/177378793-ef713dcb-a2a9-46d5-8571-903ac3b9bd21.png)


- From the above images, 9th grade Math scores from Thomas High School were replaced with NaN 
- The same was done to reading scores for 9th graders at Thomas High School.

- Scores based on School Spending 

![image](https://user-images.githubusercontent.com/104038813/177379240-f3222570-2c7f-4a85-ad9b-37a0cd0a70f2.png)


- Scores by School Size 

![image](https://user-images.githubusercontent.com/104038813/177379337-bbd3dc50-37de-49ee-bd1a-da7e8ddbb3ae.png)

- Scores by School Type

![image](https://user-images.githubusercontent.com/104038813/177379426-d04a82eb-cc4d-47eb-a7d6-58ab1d4c19b1.png)


## Challenge Summary

Four changes to the original district summary after replacing 9th grade scores from Thomas High School with "NaN"
1. Averages for math and reading changed slightly 
2. 9th Grade scores were removed, not affecting all other data
3. Total students was not affected in the summary page, but total students was changed to affect not using 9th grade scores in the percentage calculations. 
4. Scores by school type changed slightly since Thomas High School was a charter school. 

- Data didn't appear to change significantly after replacing scores because there were less than 500 9th grade students in a data set of over 39,000 students. 
