# Ford-GoBike-Data-Exploration-and-Visualization
## by Abhudeep Kaur

This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process which is a project part of the Udacity Data Analytics Nanodegree course.

In the first part (1/2) I used Python visualization libraries to systematically wrangle and explore the 2019-fordgobike-tripdata datafile, starting from plots of single variables and building up to plots of multiple variables.

In this second part of the project (2/2), I present slides with visualizations the interesting relationships, patterns and insights that I discovered in the (in part 1) selected and cleaned dataset.


## Dataset

> There are 183412 bikes in the dataset with 16 features. Most variables are numeric in nature, but the variables like user type, gender, bike share should be ordered factor variables with the following levels.

user type: Customer, Subscriber
gender: Male, Female, Other
bike_share_for_all_trip: Yes, No


## Summary of Findings

> The maximum duration of bike trip has extremely high value: 1409.1333333333334 minutes.
> The median of the distribution is 8.5 mins
> We have dropped 9346 rows of bike rides with a duration longer than 24.8 minutes, calculated by outlier detection through Q1-1.5(IQR) and Q3+1.5(IQR)
> The distribution of starting a bike trip has mode on Thursday
> The most busy hour is 1700 hrs and 0800 hrs.
> Market St at 10th St is most popular start station
> San Francisco Caltrain (Townsend St at 4th St) is most popular end station
> Subscribers typically have shorter bike trips (with quite high mode in the bin 6-8 minutes)
> The use of this service for Subscribers is high on weekdays and decreases on weekends
> The average bike trip duration of Customers is almost the double of Subscribers
> The that third quartile of Subscribers is even below the median of the Customers distribution.
> Customers have as busy hours for starting their bike trip after 1100 hrs and before 1800 hrs.Subscribers have as busy hours for starting their bike trip 0800-0900 hrs.
> The trip duration has a dip between 0600 hrs and 2100 for both user_types.


## Key Insights for Presentation

> In the presentation I focus on the relationship between bikes ride count and trip duration and user_types (Customers, Subscribers).
> There is also focus on outlier removal impact
> There is a barchart visual with the distribution of trip count between the 2 user_types. This is followed by the distribution of biketrip duration for each user_type (2 histograms side-by-side).
> There is also a clustered barplot of trip duration by both end_station_name (limited to the top 10 end stations). This illustrates that also the location of the end destination station matters as variable for explaining bike usage and trip duration.


