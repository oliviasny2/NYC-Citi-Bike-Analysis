# NYC-Citi-Bike-Analysis

## Overview of the Statistical Analysis

The purpose of this analysis is to determine trip durations across user type and gender and across different days of the week. There is an additional analysis of the stations that bikes are returned to versus the stations they were rented from.

## Results

### Checkout Times for Users

<img width="601" alt="Checkout Times for Users" src="https://user-images.githubusercontent.com/101011641/173210226-0817ee5c-b046-4fb1-8fba-e1902e71da8e.png">

This line graph shows a high level view of how long most users trip duration is. This graph peaks at about 10 minutes with an almost exponential decay the longer the trip duration is.

### Checkout Times for Gender

<img width="553" alt="Checkout Times by Gender" src="https://user-images.githubusercontent.com/101011641/173210233-2f8e5a79-72e2-4824-bafa-a071c708b3fd.png">

This line graph expands on the previous graph and distributes the length of a trip duration across genders. The male and female genders follow the overall pattern, while the unknown gender has a similar count of users using the service between 10 and 30 minutes.

### Trips by Weekday per Hour

<img width="277" alt="Trips by Weekday per Hour" src="https://user-images.githubusercontent.com/101011641/173210239-caf1c2a8-d0cb-460b-a1b6-12b6d401615c.png">

This heatmap shows the distribution of the use of bikes at different times of the day for each day of the week. Monday through Friday, the use is higher between 7 and 9am and again between 5 and 7pm, as characterized by the darker color. Saturdays and Sundays have an even distribution of riders between 10am and 7pm for each of the hours in between.

### Trips by Weekday by Gender

<img width="560" alt="Trips by Gender (weekday per hour)" src="https://user-images.githubusercontent.com/101011641/173210248-c1fc7b00-6ebb-452d-ad46-aa7cd1f102d2.png">

This heatmap expands on the previous heatmap by separating the users into genders. Because there are more male users than other users, that map is the darkest, but the distributions across all genders reflects the previous graph.

### Trips by Gender by Weekday by Usertype

<img width="230" alt="User trips by gender by weekday" src="https://user-images.githubusercontent.com/101011641/173210280-c3528546-3fcf-438c-a9ea-c1db735c8375.png">

This heatmap shows the distribution of male, female, and unknown genders across the days of the week separated into user types (customer and subscriber). The largest categories, as represented by the darker colors, are the male and female subscribers. The subscribers tend to have higher bike use during the weekdays while customers use it slightly more on the weekends. Also notable, the likelihood that the gender is unknown, the more likely it is to be a customer and not a subscriber.

### User Types by Birth Year

<img width="669" alt="User Types by Birth Year" src="https://user-images.githubusercontent.com/101011641/173210300-6291d3c6-291a-44b1-97da-1cf3cce7a26d.png">

This bar graph shows the distribution of user type across birth year. Generally speaking, it appears that more people are subscribers across all birth dates. The notable exeption is 1969.

### Latitude and Longitude Changes among Users with Different Start and End Stations

<img width="560" alt="Latitude and longitude change of users with different start and end stations" src="https://user-images.githubusercontent.com/101011641/173210316-2008b2e6-33af-44dc-9604-04bb4f7d1d0c.png">

This bar graph shows the change in latitude and longitude (End - Start) across start and end stations for each trip that the bike was not returned to the original station. These graphs are approximately normally distributed.

## Summary

According to the graphs above, our target demographic is male subscribers that use the bike for short durations (between 5 and 15 minutes. The final two graphs in the analysis section (User type by birth year and Latitude and Longitude Changes among Users with Different Start and End Stations) are my personal contributions to this project. I think birth years could be further analyzed to understand trends in customers and subscribers and across other dimensions like gender as well. I also believe that understanding the distribution of bikes across the different stations is important as to adequately supply each station to meet demands for each day and each hour.

## Link to Dashboard
[https://public.tableau.com/views/Mod14Challenge_16549650290700/Story1?:language=en-US&:display_count=n&:origin=viz_share_link]
