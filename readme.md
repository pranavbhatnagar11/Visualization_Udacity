## Bikeshare Rental System in Washington DC
### by Pranav Bhatnagar

There are two python files. 
Project_BikeShare_Part1.ipynb goes over the exploratory data analysis. 
Project_BikeShare_Part2.ipynb goes over the explanatory data analysis. 

## Dataset

The data set can be found on https://www.kaggle.com/marklvl/bike-sharing-dataset 
The file used is day.csv
Removed columns which would not be important for providing significant visualizations: instant, year, month and atemp (feel temperature).
Rename to relevant column names. And fixing the datatypes for various attributes. Season, weather situation, weekday, holiday, working day are converted into category type, while date into datetime. Also changed from numbers to provide proper season name, weekday names and weather situations. 

## Summary of Findings (Exploratory Data Analysis)

In the exploration, I found that the total count of rental bikes have a normal distribution. Moreover, there was right skew distribution for casual rental, while normal distribution for registered rentals as well. There were around 460 days with clear skies, followed by 245 days of days with mist. Roughly 20 days, there was rain and snow. The data for humidity, windspeed and temperature were normalized in the dataset.
I explored the heatmap amd scattermatrix of all numeric attributes. There was a definite correlation of casual and registered rentals with total count (as total count is a summation of the former). There was also an initial relationship between normalized temperature and total count of bike rentals. There are is more renting from lower to mid normalized windspeed. Humidity did not show any direct relation with the total count of bike rentals. I created some plots between total count with the categorical attributed such as season, days of the week and weather conditions. There is evidence to support that the rental count goes down during winter season or rainy/snowy conditions. And marginally above spring, summer is the favorite month for bike rentals. Next I plotted graphs for total count with different seasons in different plots. Mostly the distribution was normal, except for winter with a right skew distribution. There is a slight increase in the count from April through Septmeber for both the years 2011,2012. Also there is an increase in the bike rental in the two years. For example, April 2012 has more rentals than April 2011. It can also be concluded that registered users are significantly higher than the casual users.
I created visuals of total, registered and casual count for different seasons during the different days of the week. Saturday and Sunday were preferred by the casual users. On the other hand, registered users preferred weekdays. Summer was again concluded to be the favorite season, with spring for casual users and fall for registered users as the second choice of interest. Another interesting fact revealed was that registered rentals are higher on working days while casual rentals are higher in number in holidays. 


## Key Insights for Presentation (Explanatory Data Analysis)
For the presentation, I will focus on four insights in this data set. 
I. The number of casual bike rentals doesn't have a normal distribution, and has a decreasing curve like (1/x). The casual users prefer biking based on a lot of factors like weather, day of the week and season. On the other hand, registered count has a normal distribution. This indicates that registered users are more consistent when it comes to biking. 

II. The total count of bike rentals in the Winter season is generally very low as compared to the other three seasons. There is low traffic in snowy/rainy days. The maxmimum number of rentals take place during summer with clear skies. 

III. It is indicated that regsitered bike rentals decrease in number during the weekends as compared to any weekday. While casual biking numbers go up on the weekends. Fall is preferred as the second best season for registered users, in contrast to casual bikers to prefer spring. 

IV. Finally, the casual users prefer holidays while registered user avoid holidays for bike renting. The casual bike rentals definitely takes a hit in the fall and winter due to the cold weather. While there is not much difference in numbers for registered users in terms of season except for Winters. 
