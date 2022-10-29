# Communicate Data Findings (FordGobike)
## by Oloruntoba James Moritiwon


## Dataset

Ford GoBike System now rebranded as Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. The dataset under review contains an initial 183412 observations and 16 variables covering ride share for February 2019. This changed to 174760 observations and 21 variables after wrangling. Customers may choose from a number of options ranging from a single ride to an annual membership. The dataset can be found on udacity server- https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv


## Summary of Findings

The fordgobike csv file was imported into df_bike dataframe and assessed to discover cleanliness issues and some detcted one include missing values found in 'start_station_name', 'end_station_name', 'start_station_id', 'end_station_id', 'member_birth_year ' and 'member_gender' columns. These issues were resolved and new columns derived from existing ones an example is the riders_age derived from birth_year and duration_minutes from seconds.

From the analysis done, all age brackets compared favourably to each other however, tennagers tend to start more trips at the 15th hour (3pm) than any other age group. Notably, the highest duration for trips undertaken in February 2019 happened on weekends and both user types have the same preference for start hour of the day for rides. Gobike riders are vocal about not sharing bike for all trip regardless of the hour of the day of trip commencement and the average number of unwilling riders ranged from almost 13 times more on Tuesday to almost 5 times more than willing riders on Satudays and Sundays.The average trip duration for customers is almost thrice compared to subscriber trips on Sundays but a little less than double on Tuesdays. This compares the widest and closest gap between the two user types trip durations by days of the week. Also, the average duration of trip is highest for people of other gender and lowest for males on all days of the week. No customer is willing to share bike for all rides and interestingly, they have the highest averages for trip duration!

This implies that ride sharing habit tilts toward youthfulness compared to full adulthood and adverts and premiums should be designed to attract more young adults and be flexible to accomodate and encourage other age brackets. Also, frequent trips are easier to undertake with a subscription compared to casual booking as a customer. Therefore, bike sharing subscribtions should be made accessible and robust.The most preferred start hour is the 17th hour however, its only slightly preferred than the 8th hour of the day. Infrequent ride-starts on weekends may be attributed to the need to cummute to work on workdays, and not on weekends.This may be because of sight-seeing, excursions, travels and religious activities which may require longer trips. In addition, it can be inferred that subscription to ride share service encourages ride start all hours of the day with the seventeenth hour having most of ride starts. In like manner, the prominent 'No' to bike share for all trips may be due to personal preference for bikes or personalised experience and that casual approach as acustomer may be flexible for longer rides. It may also indicate that riders prefer subscriptions for shorter rides and would rather book long rides casually outside their subscription cards. Finally, Weekends are prefered for longer trip start for all genders. Customers may undertake a one time lenthy trip without sharing a bike probably because they are not oblidged to undertake another trip like a subcriber would!



## Key Insights for Presentation

For the presentatation, I gave priority to riders age and how it affect patronage. Afterwards, I discussed When most trips started at times of the day, days of the week and how long trips are on the average for all ages and genders under study.  

I started with the countplot of bike sharing service patronage by age brackets, and went further to show the counplot of willingness to share bike for all trip by start hour of the day. Finally, I showed how average duration of trips undertaken by user types and by gender may start on days of the week with pointplots. I have made sure to pass the right messages with colous for each variable clearly.
