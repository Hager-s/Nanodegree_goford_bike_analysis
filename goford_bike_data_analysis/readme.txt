# Ford GoBike Data Visualization
## by Hager Sayed


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in fabuary 2018. 
The dataset includes:
* an ID number for each bicycle
* how long it was rented for, in seconds
* the beginning and end staton ID, latitude, longitude and station name
* the start and end time
* the year the user was born
* the gender of the user
* bike_share_for_all_trip

* whether the user has a subscription to the service or not
There are 183412 rows and 16 columns.

There was some cleaning done to the dataset. This included: 
* Deleting the rows without gender or birth year
* Only use ages that are reasonable. Check for abnormally old or young values and remove them,and ages older than 90 were removed from the data
* Change data types, including times to datetimes, and user_type and member_gender to categories
* Extract days of the week from start_time

## Summary of Findings

-the percentage of male users is the hieghest as 75% of users are males,23% are females and 2% are others.
-the majority of the users are subscribers (91% of users are subscribers and 9% customers)
-the mean age of the members is 33 years old and number of members decreases as age goes higher.

- the majority of the ride are less than 20 minutes.
- the majority of rides are on thursday then tuesday followed by wednesday,friday,monday,saturday and sunday have the least rides for both types of users(but when analyzing the daily usage for both types of users seperatly customers ride more on the weekends and subscribers ride more on the weekdays than the weekends and this sound reasonable as subscribers tend to ride as a daily thing but riding for customers is ocassional like on the weekends )
-a larger percentage of customers are taking longer rides duration compared to subscripers 

## Key Insights for Presentation

For my presentation, I will focus on the difference in usage for customers and subscribers(which is my main feature of interest). I will first show the univariate results, such as the distribution of different variables like (gender,user type,duaration,age) and usage on days of the week. then we will continue by adding more variables in bivariate and multivariate visuals to see the relationship between different variables. My conclusion is that whether a user is a customer or a subscriber has the biggest influence on results also age is an important  factor, compared to gender it rarly affects any other variables in the data. 

