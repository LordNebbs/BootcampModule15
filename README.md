# NYC Citibike Analysis
MODULE 14 - Citibike analysis

## OVERVIEW
### Purpose:  The aim of the current analysis is to provide potential investors with visual representations that illustrate the success of the NYC Citibike bike-sharing program, with the intention of demonstrating that a bike-sharing program in Des Moines is a sound business proposition. Our visualizations include information such as: 1) The duration of bike rentals for riders of all genders, 2) The quantity of bike trips for riders of all genders during each hour of every day of the week, and 3) The number of bike trips made by each type of user and gender for each day of the week.


## RESOURCES
  - Source Files: 201908-citibike-tripdata.csv, 201908-citibike-revised_tripdata.csv



## RESULTS
#### Analysis

  - [POINT #1](Images/Pt1.png) - Comparing visualizations for the **'Top Starting Locations'** and **'Top Ending Locations'**, we can see that the most active starting locations are also among the most active ending locations.  This is important, because we need to know whether there might be an excess or shortage of bikes at particularly stations over time.

  - [POINT #2](Images/Pt2.png) - Looking at visualizations for **'Checkout Times for Users'** and **'Checkout Times by Gender'**, we see that most rides are for 20 minutes or less, and that the vast majority of rides are less than one hour.  We also see that this pattern is the same regardless of gender.

  - [POINT #3](Images/Pt3.png) - The **'Gender Breakdown'** pie chart shows that males in NYC utilize the bikesharing program almost 3 times as often as females.  Further analysis is needed to understand why this is the case.

  - [POINT #4](Images/Pt4b.png) - The heatmap of **'Trips by Weekday per Hour'** shows a clear pattern of bicycle useage 1) during the morning weekday commute (7-9 a.m.), 2) during the evening weekday commute (4-7 p.m.) except on Wednesday evenings, and 3) all day long on weekends.

  - [POINT #5](Images/Pt5.png) - The **'Trips by Gender (Weekday per Hour)'** heatmap shows that the useage pattern is true regardless of gender, although the total numbers for males is considerably higher.

  - [POINT #6](Images/Pt6.png) - The **'User Trips by Gender by Weekday'** heatmap demonstrates the following points:  subscribers are mostly male and account for most of the weekday activity,  customers' gender are often unknown,  and useage on the weekend is more evenly split between subscribers and customers.

  - [POINT #7](Images/Pt7.png) - Our **'Bike Utilization'** and **'Bike Repairs'** charts show that some bikes are used for many trips and many total hours, while other bikes are hardly used at all.  More analysis is called for to assess whether there are predictable patterns of use for high- or low-use bikes. 



## SUMMARY
### Insights into the usage of bicycles in the NYC Citibike bike-sharing program have been gained through this analysis, revealing patterns of usage by gender and time. Predictions regarding utilization rates can now be made based on location and time of day. The weekdays show a high concentration of usage during the morning and afternoon commute, while weekend usage is more evenly distributed throughout the day. To further understand these trends, we suggest conducting additional analysis on the comparison of weekday and weekend trip durations and examining usage patterns for the most frequently used bicycles by creating maps displaying their starting and ending locations/routes. Additionally, a visualization should be created to identify any completely unused locations.
