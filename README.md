# Bikesharing Analysis

This project contains the resulting visualizations from the NYC Citibike data analysis using Tableau Public to upload the resulting story which can be seen [here](https://public.tableau.com/app/profile/daniel1314/viz/NYCCitibikeanalysis_16650890507940/NYCCitibikeanalysis)

## Overview

The visualizations that resulted from the analysis are the following: 

1. 'Checkout Times for Users'
2. 'Checkout Times for Users by Gender'
3. 'Trips by Weekday per Hour'
4. 'Trips by Weekday per Hour per Gender'
5. 'Usertrips by Gender by Weekday'
6. 'Bikes due for Repair'
7. 'Customer Types'

## Results

An overview for each of the visualizations will be shown in this section.

### Checkout Times for Users

[!Checkout_Times_for_Users](/Images/Checkout%20Times%20for%20Users.png)

The information from the dataset is filtered by the hours the trip lasted (which can be toggled using the filter at the right hand side). The Y axis information belongs to the number of bikes that were used on the trips that lasted the selected amount of hours. The X axis belongs to the minutes the trip lasted. 

In this image, the trips that lasted from 0 hours to less than 3 hours are shown.

### Checkout Times for Users by Gender

[!Checkout_Times_for_Users_by_Gender](/Images/Checkout%20Times%20for%20Users%20by%20Gender.png)

This visualization breaks down the previous chart into the gender behaviour for the users of citibike. In this chart it's possible to filter by gender and trip duration. 

Most of the users are male clients. The trip duration for the 3 shown genders shows that most trips do not go above 59 minutes.

### Trips by Weekday per Hour

[!Trips_by_Weekday_per_Hour](/Images/Trips%20by%20Weekday%20per%20Hour.png)

This heatmap visualization displays the hours and days where the service is most used. During working days (monday to friday) the heatmap shows most activity around 8am and then around 5pm, this could be related to both working hours for employees as well as school hours for students, which means the citibike service is mostly used for work/school transportation during these days.

On weekends, the activity is more evenly distributed compared to working days

### Trips by Weekday per Hour per Gender

[!Trips_by_Weekday_per_Hour_per_Gender](/Images/Trips%20by%20Weekday%20per%20Hour%20per%20Gender.png)

By breaking up the heatmap per gender we can spot the hours with the highest demand per group. As mentioned before, male users make up the majority of the clients, which is why their heatmap has the most activity.

### Usertrips by Gender by Weekday

The data is split between customer and subscribers for the citibike service. The heatmap shows that the majority of the users are subscribers, among these, the majority is male.  

### Bikes due for Repair

[!Bikes_due_for_Repair](/Images/Bikes%20due%20for%20Repair.png)

In this visualization, each square represents a bike ID; the darker the shade of its coloring means the bike has been used more and has a higher priority to receive repairs than the others.

### Customer Types

[!Customer_Types](/Images/Customer%20Types.png)

This simple pie chart gives a better overview aoubt the distribution between customer and subscribers for the citibike program.

## Summary

The visualizations created by Tableau help better understand the relationship between the different entries in the dataset and assisst with a better decision making. Visualizing data is a fast way to answer questions and provide those answers to both technical and non-technical audiences.

Other visualizations that could be included to get a clearer image of the citibike users are the following:

* Birth year to user type pie chart
* Trip duration for each bike ID
* Start time and Start Station
* End time and End Station