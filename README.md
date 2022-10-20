# Fordgo bike system data analysis project
## by Beryl Chebet


## Dataset overview Introduction

This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis.

In this part (1/2) I will use Python visualization libraries to systematically wrangle and explore a 2019-fordgobike-tripdata datafile, starting from plots of single variables and building up to plots of multiple variables.

In the following second part of the project (2/2), I will produce a short presentation that illustrates interesting properties, trends, and relationships that I discovered in the selected (cleaned) dataset. (based on another file 2019-fordgobike-tripdata_clean which is output of this project part 1.

The dataset used for this exploratory analysis consists of Bay Wheels's trip data for individual rides made in a bike-sharing system covering the greater San Francisco Bay area in February 2019.

The Dataset consists of the following information regarding trips:

- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- Bike ID
- User Type (Subscriber or Customer)
- End Station Longitude
- End Station Latitude
 

## Summary of Findings

I performed some cleaning operations on the dataset which are outlined further in the exploration report. The  following are key variables used in the data analysis:
 
 - Start Hour
 - Start Day
 - Gender
 - User type
 - Duration
 
 Univariate analysis performed on the dataset, revealed that:
 
 - Thursdays and Tuesdays had the highest bikerides, while Saturdays and Sundays had the least bike rides.
 - Majority of the riders are in their 20s and 30s years of age
 - Males use the bikeriding service than females.
 - Majority of the bikeriders are subscribers  with a very small percentage being the customers.
 - The highest start rides occur at 8 and 9 am in the morning,5pm and 6pm in the evening, this is mostly the time when people are going to work and leaving their workstations respectively.This trend is also observed in the end rides.
 - Duration is highly skewed to the right, with fewer rides taking more than 50 minutes.
 
 Bivariate analysis on the dataset,strengthened some of the findings on the univariate analysis and also presnted new information, the following are the findings:
 
 - Customers take fewer trip compared to subscribers and Subscribers generally take shorter trips, which majority of the rides lasting for 4 minutes and 6 minutes,
 - Subscribers ride mostly during the weekdays with the lowest rides being during the weekends.
 - Majority of female and male genders are subscribers and the Number of male customers is higher than that of female customers.
 - There are more male bike riders than female riders across all ages,There are significantly fewer females than males as we get to the ages of 50s and above
 - Start rides for customers is relatively steady between 8 to 5pm, unlike subscribers who have major peaks at 8 ,9 am and 5 and 6pm
 
 The following are key findings from the multivariate analysis:
 
 - Duration of Trips on Weekends take longer than those during weekdays for Customers,with the highest duration being on a Sunday 27.78 minutes.
 - Subscribers take  shorter trips compared to Customers
 - Customer Trips starting at 3am have longer durations than all other start hours,
 - Customers have greater numbe rides on Thursdays, at 5pm,6pm and on Fridays, Thursday and Tuesday at 8am
 - Over the weekends on Saturday and Sunday most of the rides start between 1 pm and 4pm for the customer,


## Key Insights for Presentation
The key insights from the exploration are:
     1. Subscribers take shorter trips than customer, despite subscribers making a larger percentage of those who use the bike riding               service.
     2. Subscribers take trips during the weekdays as opposed to during the weekends.
     3. Majority of the riders are in their 20s and 30s
     4. Subscribers have 4 major hours to start rides 8am, 9am , 5pm and 6pm
 
For the presentation I'll focus on telling a story using the usertype,duration,start hour and days of the week. I will first display a barchart for the user type, then a histogram showing the relationship between duration and user type, and also a clustered barchart showing the relationship between user type and days of the week. The final plot will be a heatmap between usertype,duration,starthour and days of the week.
