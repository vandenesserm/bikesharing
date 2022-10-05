# NYC Bike Sharing Analysis


## Overview of the analysis: 
The purpose of this analysis is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, an in-depth analysis of a similar program in New York City was analyzed. The results for the month of August are presented below and also published on this [Tableau Stories](https://public.tableau.com/app/profile/raquel.vandenesse/viz/NYC_CitiBike_16646762858380/Story1?publish=yes "Link to dashboard") .

#

## List of requested deliverables:
- Deliverable 1: Change Trip Duration to a Datetime Format
- Deliverable 2: Create Visualizations for the Trip Analysis
- Deliverable 3: Create a Story and Report for the Final Presentation

#
## Tools:
- GitBash
- Jupyter Notebook
- Pandas
- Virtual Studio Code
- Live Server
- Tableau

#
## Results: 
![Overview](/PNGs/Overview.png)
The dashboard above shows the breakdown of relevant data at a glance. For analysis purposes, there were a total of 2,344,224 rides for the month of August. 

### Types of users: 
There are two types of users: subscribers and customers. Subscribers refer to annual subscribers of the bike-sharing service, while "customers" are short-term riders. Subscribers make up the vast majority of users with 1,900,359 while there are 443,865 customers.

### Gender breakdown:
There were three identified genders: male, female and unknown. Males represent the majority of the users with 1,530,272 followed by females with 588,431. Unknown accounted for 225,521.

### Top Starting and Ending Locations:
As shown in both graphs, the top starting and ending locations are both within the central manhattan area ( Midtown), with a significant decrease in use in areas further away such as Brooklyn and Queens.

### Peak Hours:
A.M. peak hours are between 8:00 and 10:00 in the morning with a combined total of 313,410 trips. P.M peak hours are between 4:00 and 8:00 in the afternoon, with a total of 767,121 trips.

![Average Trip Duration](/PNGs/Average_trip_duration.png)
This graph analyses trip duration. It is important to note that most trips last 5 minutes (146,752 total trips)and almost all trips are within the 5 to 40 minutes range with very few trips lasting longer than 40 minutes. This aligns with the geographical distances between the popular starting and ending points.


![Average Trip Duration by Gender](/PNGs/Average_trip_duration_gender.png)
When the average trip duration is divided by gender, we can see that female and male users follow a similar pattern with peak usage around the 5-6 minute mark. In contrast, unknown users usage is nearly the same between 8 and 25 minutes.

![Trips by Weekday per Hour](/PNGs/Trips_by_day_by_hour.png)
As the graph indicates, during weekdays, the peak hours are between 7:00 and 10:00 A.M. and 4:00 and 8:00 P.M., which coincides with commuting hours. Considering that the majority of users are subscribers, it is possible that bike sharing is widely used as a commuting method. Saturday and Sundays show a steady usage starting around 10:00 A.M. until about 8:00 P.M..

![Trips by Gender (Weekday per Hour)](/PNGs/Trips_by_gender.png)
When usage is broken down by gender and customer type, we can see that males and females hold similar usage patterns with weekdays commuting hours and weekends afternoons being steadily busy.

![Trips by Gender (Weekday per Hour)](/PNGs/Trips_by_gender_by_weekday.png)
When usage is further broken down by gender and customer type, we can see that males and females hold similar usage patterns when it comes to weekday usage amongst the same types of users.


#
## Summary:
The data shows that the NYC Bikeshare system is used largely by male subscribers. The patterns seem to indicate that it is also often used for commuting purposes. In order to gain a more insightful picture of the program usage, it would be important to further analyze data from different seasons. Weather is likely to have an impact on usage and it would be important to measure that impact in order to have an accurate analysis. Based on that, it is suggested that a visualization showing the average trips in correlation to temperature and another one in correlation to precipitation be added to the stories. Furthermore, all graphs and analyses should be reproduced using data from one month in each season in order to define the impact weather may have on ridership.


