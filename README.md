Practical Application Assignment 5.1 - Will the Customer Accept the Coupon?


The goal of this project was to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.


## Findings:

Exploratory Data Analysis:

The python SweetViz library was leveraged for initial data exploration. The complete SweetViz report is available here:

https://github.com/seancanny091/AIML_PAA_51/blob/main/assignment_5_1_starter/SWEETVIZ_REPORT.html

The following potential data quality issues were identified:

Missing Data - With approximately 99% of the values for 'car' being blank it isn't really adding much value to the dataset. The other columns missing values are missing so few values (i.e. less than 2%) that this will not have a significant impact overall. As a result the ‘car’ attribute was dropped from the dataset for analysis.

Duplicate Data - There are 74 duplicate rows. This is a survey and, as such, it is quite possible that there will be duplicates. The duplicates have been retained as we are interested in every response.

Assigned Investigation - General Data Visualizations

Assigned Investigation - Data Summary Points

General
A coupon was accepted approximately 57% of the time.


Bar Coupon Specific:
The bar coupon was accepted approximately 41% of the time.
The bar coupon was accepted approximately 37% of the time by people who went to the bar 3 or fewer times a month. 
The bar coupon was accepted approximately 76% of the time by people who went to the bar more than 3 times a month.
The bar coupon was accepted approximately 70% of the time by drivers who go to the bar more than once a month and are over the age of 25. The bar coupon was accepted approximately 34% of the time by all other drivers.
Drivers who go to the bar more than once a month and are over 21 are more likely to accept the bar coupon.
The bar coupon was accepted approximately 71% of the time by drivers who go to the bar more than once a month, had passengers that were not a kid, and had occupations other than farming, fishing, or forestry. The bar coupon was accepted approximately 56% of the time by all other drivers.
The bar coupon acceptance rate was approximately 71% for drivers who go to bars more than once a month, had passengers that were not a kid, and were not widowed.
The bar coupon acceptance rate was approximately 72% for drivers who go to bars more than once a month and are under the age of 30.
The bar coupon acceptance rate was approximately 45% for drivers who go to cheap restaurants more than 4 times a month and income is less than 50K

Assigned Investigation - Hypotheses

Based on the observations, we can hypothesize the following about drivers who accepted the bar coupons:
High Frequency of Bar Visits: Drivers who frequently visit bars, especially more than 3 times a month, are significantly more likely to accept bar coupons. This suggests a strong correlation between the frequency of bar visits and the likelihood of accepting related coupons, possibly due to a higher value placed on such discounts by regular patrons.
Age Factor: Younger drivers, particularly those under the age of 30, show a higher acceptance rate for bar coupons. This could indicate that younger demographics are more inclined towards social outings like bar visits and are more receptive to discounts associated with such activities.
Marital Status and Occupation: Drivers who are not widowed and have occupations outside of farming, fishing, or forestry are more likely to accept bar coupons. This might reflect lifestyle or social patterns where individuals in certain occupations or marital statuses have more social engagements or value leisure activities differently.
Economic and Dining Preferences: Drivers with specific economic and dining preferences, such as those who frequent cheap restaurants and have an income of less than 50K, have distinct acceptance rates. This could suggest that economic factors and personal dining habits influence the perceived value of bar coupons.
General Acceptance Among Other Drivers: The relatively lower acceptance rate among "all other drivers" indicates that there are specific demographic and behavioral traits that significantly influence the likelihood of accepting bar coupons. This group likely includes drivers who do not frequently visit bars or do not fit into the specific demographic profiles outlined above.



