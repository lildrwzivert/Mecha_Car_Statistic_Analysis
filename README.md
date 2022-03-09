# Mecha_Car_Statistic_Analysis

## Linear Regression to Predict MPG
![Screen Shot 2022-03-09 at 12 35 07 PM](https://user-images.githubusercontent.com/93094482/157498988-032c2bea-a8b8-429b-9640-84eb27dc972c.png)

1. Vehicle length and ground clearance gave non-random variance to mpg.
2. The slope is not zero Since p is less than .05, the null hypothesis is rejected.
3. Yes, based on the high r-squared value this is accurate model of mpg for MechaCars.

## Summary Statistics on Suspension Coils
![Screen Shot 2022-03-09 at 12 36 01 PM](https://user-images.githubusercontent.com/93094482/157498932-0616a90f-72bf-4ba5-8d83-1814a7fc7ce9.png)
![Screen Shot 2022-03-09 at 12 36 11 PM](https://user-images.githubusercontent.com/93094482/157498956-5a989c08-cca3-4ae4-a77c-7e4613c8c67b.png)

The current manufacturing data only meets the design specification for all manufacturing lots in total, but not for lot 3 individually. Lot 3's variance is 170, while the total variance is 62 and lot 1 and 2 are approximately 1 and 7 respectiviely.

## T-Tests on Suspension Coils
![Screen Shot 2022-03-09 at 12 35 50 PM](https://user-images.githubusercontent.com/93094482/157499017-63697120-0133-41e9-a905-6174da7f8617.png)

![Screen Shot 2022-03-09 at 12 35 33 PM](https://user-images.githubusercontent.com/93094482/157499000-5b5c27f4-50b0-43df-9e56-88b83fe01e7e.png)

For all manufacturing lots total, the p-value is above .05, meaning we can't reject the null hypothesis. This is the case for lots 1 and 2 as well. We can reject the null hypothesis for lot 3 as its p-value is .04168, less than .05, making it significant.

## Study Design: MechaCar vs Competition
The study will evaluate city and highway fuel efficiency between MechaCars and the competition.

What metric or metrics are you going to test? City and highway fuel efficiency.
What is the null hypothesis or alternative hypothesis? The null is that there is no statistically significant difference in the fuel efficiency of MechaCars and its competitors. The alternative is that there is a difference in fuel efficiency.
What statistical test would you use to test the hypothesis? And why? A two-sample T-test to compare city and highway fuel efficiency between MechaCars and competitors. 
What data is needed to run the statistical test? The mpg yielded from driving in the city versus on the highway.
