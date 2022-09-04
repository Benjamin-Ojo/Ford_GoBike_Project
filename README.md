# Ford GoBike System Data
**By Benjamin Adekunle Ojo.**



## Dataset
Ford GoBike was a bike-sharing system that covered the greater San Francisco Bay area from 2017 to 2019. This dataset has information on trips taken on 2019.

The dataset was provided by Ford Gobike System and it contains activities of customers who made use of Ford GoBike System from 2017 to 2019. The following are features contain in the Dataset:

 * `bike_id`: Unique string for every bike owed by Ford GoBike.
 
 * `duration_sec`: The duration in seconds for each trip.
 
 * `start_time`: The time a user started his or her trip.
 
 * `end_time`: The time a user ended his or her trip.
 
 * `start_station_id`: A unique string for each starting station maintained by ford GoBike.
 
 * `start_station_name`: Starting Station name.
 
 * `start_station_latitude`: Starting station latitude Location of station.
 
 * `start_station_longitude`: Starting longitude location of station.
 
 * `end_station_id`: A unique string for each ending station maintained by ford GoBike.
 
 * `end_station_name`: End station name.
 
 * `end_station_latitude`: End station latitude Location of station.
 
 * `end_station_longitude`: End station longitude location of station. 
 
 * `user_type`: Is the user a customer or subscriber. 
 
 * `member_birth_year`: Year user created or use a ford Goford account.
 
 * `member_gender`: Is the user a Male or Famale.
 
 * `bike_share_for_all_trip`: This is a discounted memberships for low-income riders. 

The main objective of the project was to exam the data using explorative and explanator visualizations. My main features i'm interest in is the trip duration feature, this provide the lenth of time a user used a gobike bike, and i would be examing features that influence the behavour or duration of this services. 



## Summary of Findings
During the course of our analysis we performed 3 tyep of visualization univariate, bivariate, and multivariate visualization. The following are insight got from this visualization. 

***Univariate Graph Findings***
 
 * We plotted the top 10 most used staring and ending station, we found out that 15 to 17 percent of trip activities are from only 3% of the stations. 
 * The trip duraion histogram showed us that most of the trip were between 5 to 15 minutes. 
 * At the begininge of our exploration we performed some feature egineering on our starting time, of this we exacted the hour a trip started and ended. from the extraction we plotted a histogram and found out that most of users use our service around 8am in morning and 5pm in the evening, 
 * Also we exacted the day of the week in which each trip was held and found out that most of our trip were on Thursdays, followed by Tuesday, with monday coming last for work days, Saturdays and Sundays had the least activities of the 7 days.
 
 
 ***Bivariate Graph Findings*** 
 
 
 * Plotting a scatter plot of age and trip duration shows a negative relationship between trip duration and age, implying that the older a user is the less time usering our service. 
 * Using a heatmap i was able to observe the relationship between age and starting hours, and this informed us that individuals within the age of 20 to 40 were use our servise in the monring around 8 and in the evening around 5. 
 * Plotting a box plot using the relationship between the trip duration and user type showed us that casual customers have higher trip duration than subscribers.
 * I use a violin plot to understand the relationship between the trip duration and gender, this showed on that on average other gender type have a more distributed duration time than the other genders. 
 
 
 ***Multivariate Graph Findings*** 
 
 
 * When comparing the relationship between age, trip duration and gender, female tend to have a higher trip duration time than others. 
 * Examing the relationship between age, trip duration, and user type used us that on avarage causal customers have a higher trip duratin than sebscribers and most of our old users like to use our subscription service more than causal customers. 
 *  I did a scatter plot of age vs. trip duration, with different markers for user type. In this chart, it was interesting to see that older people apparently prefer to be a subscriber instead of customer, but this warrants further investigation.


## Key Insights for Presentation

 For this presentation, the main feature i was trying to analysis is the how other factors influence or affect trip duration, but before we can analysis this relationship we first have to see how the trip duration is distributed. Upon plotting a histogram of trip duration we discovered that most of the trip are are between 5 to 15 minutes, however our distribution wasn't a normal distribution and we had to apply log on the feature in other for us to get a normal distribution curve. 
 
 Next, I graphed a heat map showing the relationship between the age and starting hours, this showed us that most trip occure around 8:00 in the morning and 5:00. this marches peak time when people are going to work and coming back home. 
 
 finaly, with the use of point plot and a histogram I was able to visualize a multivariate relationship between gender, user type and trip duration. from the visualization we were able to conclude that non binary genders as subscribers or causal customers have a higher trip durtion than other gender type. 
