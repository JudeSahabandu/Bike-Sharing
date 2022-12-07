# Visualizing Bike Sharing Data for NYC
--
## Overview of the Analysis

The purpose of the project is to explore the possibilty of establishing a bike sharing service in Des Moines, Iowa. The data used to determine user behaviour is from New York City (Citi-Bike) user information, which can be used as indicative data to enable business decisions to be made for the execution of the Des Moines, bike share project plan.

In order to build user data and visualizations to present key insights to investors, we use the following tools for the development and execution of our visualizations;

* Pandas - Use of Jupyter Notebook and Pandas to prepare data
* Tableau - Use to access extract data and build Tableau Stories
* GitHub - Share Written Report and Link to Tableau Stories

Some of the key visualization outputs required for assessment is as follows;

* Length of time bikes are checked out for all riders and genders
* No. of bike trips for all riders and genders for each hour of each day of the week
* No. of bike trips for each type of user and gender for each day of the week.

The following report sections describe some key highlights on the outcome of the project.

The detailed Tableau stories can be found [link to dashboard](https://public.tableau.com/app/profile/jude.sahabandu/viz/NYC_CitiBike_Challenge_16704446768330/NYCCitiBikeChallenge "link to dashboard")

## Results

When considering the users of NYC Citibike, we cannot directly compare the user profiles to what we may expect at Des Moines, but the data might be indicative of what key facets of user behavior we can come to expect.

### User Profile Results

Considering the key user profile as depicted in the following image, we can determine the following insights of the typical bike share user;

![User_Profile](/Images/User_Profile.png)

* We have a total of near 2.5 million users and we can determine the proportion of users vs. population + tourists
* Ridership is predominantly Male with over 65% identifying as Male
* Tendency to be a subscriber is higher when gender is disclosed
* User traffic determined by start and end locations are limited mainly to key metro regions (The larger the bubble, the popular the start and end location)

### Trip Duration by User

![Trip_Duration_User](/Images/Trip_Duration_User.png)

When considering the length of usage of bikes, the above visualization suggests that users predominantly use each bike for a maximum of 20 minutes. Once the data peaks at around 20 minutes, we see the trip duration taper off and we hardly see usage of bikes over an hour per user.

This may be a key insight to consider how we structure our rates for bike usage to our consumers here in Des Moines. (e.g: Pay more upfront and the rates become less as time goes on)

### Trip Duration by Gender

![Trip_Duration_Gender](/Images/Trip_Duration_Gender.png)

When considering the gender breakdown, we see that again males are the main user of the bike-share services, but the usage duration between males and females are identical. Although, it is interesting to note that those who do not disclose gender identity are likely to use the bikeshare for longer. We can also determine by the user groups of those who do not reveal gender are less likely to subscribe.

It may be worthwhile exploring if users who do not subscribe tend to be local users or tourists to determine if tourists can have a visiting package to encourage further use of bikeshare.

### Weekly Bike Usage By Gender

![Weekly_Bike_Usage_By_Gender](/Images/Weekly_Bike_Usage_By_Gender.png)

When reviewing weekly bike usage by gender, we see that most of the activity is with the male subscriber audience. With a greater difference in activity between the subscribers and customers. But, when considering the differences of the female subscriber and customer, user patterns remain similar.

We could consider learning from this output and planning how to incentivize female usage of the bike sharing service in Des Moines.

### Weekly Bike Usage By Hour

![Weekly_Bike_Usage_By_Hour](/Images/Weekly_Bike_Usage_By_Hour.png)

Looking at hourly usage of bikeshare across the week, the data is typical in highlighting more user traffic across the morning and evening commute rush hours. In addition the usage of bikeshare on weekends are spread across the morning and afternoon hours.

### Weekly Bike Usage By Hour by Gender

![Weekly_Bike_Usage_By_Hour_Gender](/Images/Weekly_Bike_Usage_By_Hour_Gender.png)

The Gender breakdown of bikeshare usage by hour across the week tells a similar story, Where we see male and female users predominantly using the service across the morning and evening rush hour commutes. But, it is interesting to note that there is slightly more usage of unknown gender usage of bike share on the weekends as opposed to week day use.

### Bike Repair Requirements

![Citi_Bike_Repair](/Images/Citi_Bike_Repair.png)

In the above image, we can see a tiled representation of all the unique bike IDs used in the NYC CitiBike bikeshare. This layout will help us determine the proportion of bikes which get heavy use compared to the bikes which get light usage. This will help us understand user behavior and how much funds we may need to allocate for repairs and replacement costs for decommissioned bikes.

## Summary

Looking at the above data and visualizations, we can come to the following key conclusions;

1. Bikeshare services are most popular in densely populated areas of the city (This may be our starting point in set up in Des Moines).
2. Bikeshare services are most used in morning and evening rush our commute, which leads us to the need to incentivize rush hour commuters to buy into concept in Des Moines.
3. The male user group is a reliable market to tap into, whilst the female user may require further promotional efforts to buy into concept.
4. There is a user scenario of tourist visitors (needs to be established) who require services across weekends and for longer duration (we can consider to develop a weekend pass for tourists to encourage usage).
5. There is a proportion of heavily used bikes, which may require additional financial allocations for repairs and replacements.

In addition to the above summary, we can explore additional avenues of analysis to understand the user segments further through;

1. Determine user case scenarios by Customer and Subscriber accounts to see how we can convert customers to subscribers or develop a new pass to encourage further use amongst customers.
2. Determine bikeshare usage by age groups to develop communication and marketing efforts to attract underserved age group segments who can bolster the use of our bikeshare services in Des Moines.