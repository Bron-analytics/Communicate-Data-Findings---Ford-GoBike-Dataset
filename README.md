# Communicate-Data-Findings---Ford-GoBike-Dataset
Udacity Data Analyst Nanodegree Project 6
Project Ford GoBike System Data Exploration
by Oyebade James
Dataset
GoBike System Data provides 175,194 bike trip records for the month of February, 2019. It includes features like Trip Duration (seconds), Start Station Name, End Station Name, User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual), Member Gender, Bike Share For All Trip, Age Group, Trip Duration (minutes), Start Time (hours), Start Time Day of the WeekEnd Time (hours), End Time Day of the Week, and Distance (miles).

After a first exploratory view, I chose to simplify the dataset according to my targets. So, I dropped columns of the stations (coordinates), and I created Age Group, Trip Duration (minutes), Start Time (hours), Start Time Day of the Week, End Time (hours), End Time Day of the Week, Distance (miles). I noticed that the following variables Duration, Distance and most especially, Age have some outliers. In order to allow the plots to show the trends clearly, member years above 1900 were only selected from the dataset.

In the exploratory analysis, I explored different types of visualizations for my variables and found interesting features.

Summary of Findings
In my exploration, I found that bike trips on average were between 4 and 10 minute range, with 75% of trips being under 14 minutes. This suggests that users are taking the bikes on short distances. Users most common start time hour is 8AM and most common end time hour is 5PM. This revealed that users are more of working class that leave for work in the morning and come back home in the evening. Another interesting fact is that users in this category ride less than an hour and that is why both start time and end time peak at the same hour mark.

Market St is the most popular start station followed by San Francisco Caltrain Station 2. San Francisco Caltrain Station 2 is observed to overtake Market St as the most popular end station.

Another interesting fact is that many users fall within the age group called MIllennials (25-40) which is also the age bracket for young adults and working class. Hence work days (Monday-Friday) have higher demand for bike trips, while the demand is significantly low on weekends (Saturday and Sunday).

Customers tend to go on a long distance and long duration trip while Subcribers use bike for both short distance and short duration trip. This reveals that Subcribers are looking for a consistent experience as they use bike for their daily commute.

Interestingly, there is a steep jump or increase in both customers duration and subcribers duration on weekends (Saturday and Sunday).

There were more short time trips on working days (Mon-Fri). The duration of trip of age range Gen Z, Millennials and Gen X is more stable than the older range.

Key Insights for Presentation
For the presentation, I focus on just the influence of start time, member age and user type on duration and distance of bike trip. I start by introducing the duration variable, followed by the pattern in start time distribution, then in distance.

Afterwards, I introduce each of the categorical variables one by one. To start, I use the count plots of start time weekday across user type, gender, bike share for all trip and age group, and gender across age group, age group across gender, gender across user type and user type across gender.

And finally, I plot the variables with other set of two variables that validates the insights from the bivariate section. I have made changes to my presentation, including suggestions based on feedback from an ex Udacity student.

References
Create a boolean series https://knowledge.udacity.com/questions/525039

Converting to numeric https://stackoverflow.com/questions/56391169/pandas-astypeint-applied-to-float-column-returns-negative-numbers

Extracting month as month name https://stackoverflow.com/questions/37625334/python-pandas-convert-month-int-to-month-name

Extracting weekday as day name https://stackoverflow.com/questions/30222533/create-a-day-of-week-column-in-a-pandas-dataframe-using-python

Calculating distance with Haversine formular https://knowledge.udacity.com/questions/282090

Knowing the right plot https://www.datapine.com/blog/how-to-choose-the-right-data-visualization-types/

How to create slideshow https://knowledge.udacity.com/questions/386810

Refer good READMEs on web: https://github.com/matiassingers/awesome-readme

https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project

https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-
