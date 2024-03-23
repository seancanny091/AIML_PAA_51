# Practical Application Assignment 5.1 - Will the Customer Accept the Coupon?


The goal of this project was to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not. The dataset used in the analysis is available here:

[Link to Coupons Dataset](/coupons.csv)


The programming language used was Python, and the libraries used were: pandas, seaborn, matplotlib, numpy, and sweetviz.
The specifics of the analysis, including code, visualizations, comments, and observations are contained in the following Jupiter Notebook:

[Link to Jupyter Notebook](/PAA_51.jpynb)

## Exploratory Data Analysis:

The python SweetViz library was leveraged for initial data exploration. The complete SweetViz report is available here: 

[Link to SweetViz Report](/SWEETVIZ_REPORT.html)

The following potential data quality issues were identified:

#### Missing Data:
With approximately 99% of the values for 'car' being blank it isn't really adding much value to the dataset. The other columns missing values are missing so few values (i.e. less than 2%) that this will not have a significant impact overall. As a result the ‘car’ attribute was dropped from the dataset for analysis.

#### Duplicate Data: 
There are 74 duplicate rows. This is a survey and, as such, it is quite possible that there will be duplicates. The duplicates have been retained as we are interested in every response.

## General Data Visualizations
![Image](/images/CouponTypeDist.png)
<br>
<br>
![Image](/images/TempDist.png)


## Data Summary Points

#### General:
* A coupon was accepted approximately **57%** of the time.

#### Bar Coupon Specific:
* Overall acceptance rate: **41%**
* Acceptance rate for people who go to the bar 3 or fewer times a month: **37%**
* Acceptance rate for people who go to the bar more than 3 times a month: **76%**
* Acceptance rate for drivers who go to the bar more than once a month and are over 25 years old: **70%**
* Acceptance rate for drivers who go to the bar more than once a month, have passengers that are not kids, and have occupations other than farming, fishing, or forestry: **71%**
* Acceptance rate for drivers who go to the bar more than once a month, have passengers that are not kids, and are not widowed: **71%**
* Acceptance rate for drivers who go to the bar more than once a month and are under 30 years old: **72%**
* Acceptance rate for drivers who go to cheap restaurants more than 4 times a month and have an income less than 50K: **45%**

## Hypotheses

Based on the observations, we can hypothesize the following about drivers who accepted the bar coupons:

* **High Frequency of Bar Visits:** Drivers who frequently visit bars, especially more than 3 times a month, are significantly more likely to accept bar coupons. This suggests a strong correlation between the frequency of bar visits and the likelihood of accepting related coupons, possibly due to a higher value placed on such discounts by regular patrons.

* **Age Factor:** Younger drivers, particularly those under the age of 30, show a higher acceptance rate for bar coupons. This could indicate that younger demographics are more inclined towards social outings like bar visits and are more receptive to discounts associated with such activities.
  
* **Marital Status and Occupation:** Drivers who are not widowed and have occupations outside of farming, fishing, or forestry are more likely to accept bar coupons. This might reflect lifestyle or social patterns where individuals in certain occupations or marital statuses have more social engagements or value leisure activities differently.
  
* **Economic and Dining Preferences:** Drivers with specific economic and dining preferences, such as those who frequent cheap restaurants and have an income of less than 50K, have distinct acceptance rates. This could suggest that economic factors and personal dining habits influence the perceived value of bar coupons.
  
* **General Acceptance Among Other Drivers:** The relatively lower acceptance rate among "all other drivers" indicates that there are specific demographic and behavioral traits that significantly influence the likelihood of accepting bar coupons. This group likely includes drivers who do not frequently visit bars or do not fit into the specific demographic profiles outlined above.
<br>

## Independent Investigation - Carry Out & Take Away Coupon Declines

Further analysis focused on drivers who declined Carry Out & Take Away coupons.
<br>
<br>
![Image](/images/CouponsDeclineByAge.png)

**Age:** The age groups of 21 and 26 years old are the most likely to decline Carry Out & Take away coupons, each constituting approximately 20% of the declines. This suggests that younger adults in their early to mid-twenties are more inclined to decline these coupons.
<br>
<br>

![Image](/images/CouponsDeclineByMaritalStatus.png)

**Marital Status:** The majority of declines come from individuals with a married partner (approximately 40%) and singles (approximately 37%). This indicates that marital status, particularly being married or single, plays a significant role in the likelihood of declining Carry Out & Take away coupons.
<br>
<br>

![Image](/images/CouponsDeclineByEducation.png)

**Education:** Individuals with a Bachelor's degree are the most likely to decline these coupons, making up approximately 37% of the declines, followed by those with some college but no degree (approximately 30%). This suggests a higher tendency to decline among those with higher education levels.
<BR>
<BR>
## Recommended Next Steps

Based on the analyses performed and the insights gained about drivers who accept bar coupons and those who decline Carry Out & Take Away coupons, here are the recommended next steps to further understand the dataset and actions to take as a result of this increased understanding:

* **Segmentation Analysis:** Perform a deeper segmentation analysis to identify more nuanced segments within the dataset. This could involve looking at combinations of factors such as time of day, weather conditions, and location to understand how these variables influence coupon acceptance rates.

* **Predictive Modeling:** Develop predictive models to forecast coupon acceptance rates based on driver demographics, behaviors, and external factors.

*  **A/B Testing:** Conduct A/B testing with different coupon designs, offers, and messaging to see which variations lead to higher acceptance rates among different driver segments. This can help refine marketing strategies and improve coupon effectiveness.

*  **Economic Impact Analysis:** Assess the economic impact of coupon campaigns on business outcomes such as increased sales, customer retention, and brand loyalty. This analysis could help justify the investment in coupon campaigns and guide budget allocation.

*  **Competitive Analysis:** Conduct a competitive analysis to understand how competitors are using coupons and promotions. This can help identify best practices and opportunities for differentiation.

*  **Integration with Other Marketing Channels:** Explore the integration of coupon campaigns with other marketing channels such as social media, email marketing, and in-app notifications. A multi-channel approach could enhance the reach and effectiveness of coupon promotions.
