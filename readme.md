# (Ford GoBike System Data Exploration)
## by (Gamal Samir Ali Abdalluh Shouman )


## Dataset

> There are 170839 trips in this dataset with 18 features('duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude','start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type','member_birth_year', 'member_gender', 'bike_share_for_all_trip','distance_Km', 'day_of_week') these trips happened in the period between febreuary and march in 2019. There were some missing values, trips with distances equal 0 and some illogical values in the member_birth_year like (1878, 1910, 1920,....etc) so, i removed all these values.

## Summary of Findings

> In the exploration I found a relationship between the duration and the distance with effects from the other features like 
(user_type, day_of_week, member_gender, bike_share_for_all_trip).
there is a strong positive correlation between the duration and distance variable when they were plotted in the log-scale but the correlation between the duration and distance variables and the member birth year hase a week positive correlation on thier standard scales.
most of the riders were born in 1980s or 1990s and a few of them were born 1950s to 1970s.
We find that Thursday is the most crowded day and the lowest number of trips is in Sunday
The count of bike share is very less than bikes were not shared.
The median of the duration for males is less than femals and others and this because males have a less distance median than Them.
Bike_share_for_all_trip has an opposite relation of user_type, for bike sharing, bikes not be shared have longer durations than bikes be shared for the same distance.
The median of the duration for subscribers is less than customer although the difference in distance medians is very small so, here we can say that in general subscribers have small durations than customers for the smae trip distance
days of the week don't have any effect on the trip duration even if we saw slightly weekend trips duration median is bigger than the other days.
"Saturday" has the minuimum avarage distance although "Tuesday" has the maximum avarege duration
"Tuesday" has the maximum average distance although "Sunday" has the maximum average duration
the customers have more average duration and distance than Subscribers
"other" has the highest average duration and distanc and males have the lowest

## Key Insights for Presentation

> The presentation focused on  the main features ('distance_Km', 'day_of_week', 'user_type','member_gender')by introducing the duration variable
then the distance distribution, riders birth year distribution and distribution of Trips over the weekdays. then plot the transformed scatterplot of duration and distance features.