# Ford Go Bike Data Exploration
## by by Eng. Al-Moataz bellah Mohamed Essam eldin


## Dataset

This data set is taken from https://www.fordgobike.com/system-data and represents trips taken by members of
the bike sharing service by FORD for month of February of 2019.
Data consists of info about trips taken by service's members, their types, their birth year, their gender,
stations of starting and ending trips, duration of trips etc.

##Data Wrangling

> drop null values.

> convert start_time and end_time to datetime type format.

> convert member_birth_year , start_station_id & end_station_id to integer data type.

> add columns for the member age according to year of birth, the day of week the trip started

> order the category of weekdays.


## Summary of Findings

> The distribution of the trip duration and age of members was a little confusing at first.
I found that 99% of users younger than 65 years, And found that 99% of trips' duration is less than 3176 seconds.
By plotting out the cleaned data, Used .describe(percentiles=[0.99]) and xticks() to zoom in to a smaller range
where most trip records fell, which made the distribution much clearer.

> I found that the age of most of users who uses this service is between 24 years & 40 years

> The Trip's durations of most of the trips is between 120 seconds & 840 seconds

> Notice that there is days that have high number of trips count than other days, by more investigation appears that
the trips is mostly used during working days(monday to friday) and its rate gets low during weekends(saturday & sunday)

> plot shows the peak hours of using this service is between 7 & 9 AM and 4 & 6 PM

> It is obvious that 90% of users are subscribers for the service

> It shows that the 74% are males while females are 23.4%

> We found that 90.2% of trips don't share the bike

> It appears that the subscribers have shorter trip duration than customers

> we found that males tend to have slightly shorter trips compared to females

> it shows that during working days the trips is shorter than weekends days

> younger users is having trips during weekends while older users uses it in working days

> There is overall more trips for subscribers than customers, while it shows the subscribers mainly uses this service for work

> both subscribers and customers tend to use the bikes during rush hours of going to work(7 to 9 AM) or leaving from work(4 to 6 PM)

> Most of customers age is between 27 & 35 years, while most of subscribers age is between 24 & 33

> The females users are slightly younger than males users

> Sharing the bike is occure in younger users

> Most of Trips are at working days at 8 AM and 5 PM for both males and females

> Sharing bikes happens more from (8 AM to 8 PM) during all week while its peak happens in working days at 5 PM (leaving from work)

> Users who most share bike at age 24 & 26 years all weekdays,
while most trips taken by users of age 31 years at working days

> The average duration of trip when sharing bike is smaller than not sharing the bike in both males and females


## Key Insights for Presentation

> The main goal here is trying to find the users who use the bike sharing and when.# visualization-project
# visualization-project
# visualization-project
