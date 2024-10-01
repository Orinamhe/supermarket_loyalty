# SUPERMARKET LOYALTY
The project contains python-driven data exploratory analysis of a supermarket loyalty program

**Introduction**

Supermarket loyalty program is a strategic initiative to stimulate customer engagement and reward shopping loyalty, encouraging repeat visits and increased spending. By leveraging data analytics, supermarkets can tailor their offerings to meet the unique preferences of their shoppers, ultimately driving both sales and customer satisfaction.


**Dataset**

The dataset consisted of 8 columns:

 customer_id 
 
spend :The total spend of the customer in their last full year

 first_month :The amount spent by the customer in their first month of the year
 
items_in_first_month :The number of items purchased in the first month

 region
 
 loyalty_years :The number of years the customer has been a part of the loyalty program
 
joining_month :The month the customer joined the loyalty program

promotion: Did the customer join the loyalty program as part of a promotion? 


**Tools**

Python (Pandas & Matplotlib) for data manipulation and visualization
Jupyter Notebook for code development and documentation


**Analysis Performed**

-Annual total spending of customers who are members of the program

-Explore how their subscription timing correlates with the amount spent at sign-up, and the total amount spent at the end of the year.

-Investigate spending patterns across various geographical regions

-Determine the length of time that customers have been part of the loyalty program, and how it affects their spending.

-Investigate the monthly patterns in overall spending and its relationship with spending based on loyalty group categories


**Insights and Summary**

_Customer spending_

Identifying top spenders can help foster long-term loyalty through targeted rewards. There was no significant correlation between the number of items purchased and the amount spent by customers during their first month in the loyalty program compared to their total spending over the past year.

_Loyalty group_

Customers subscribed to the loyalty program for less than a year contributed the most total spending but had the lowest average spend per person, while those in the 5-10 year range spent the most on average. Shoppers in the 1-5 year group showed no significant differences in spending patterns, and long-term customers (over 10 years) contributed the least overall.

_Regional Analysis_

Customers in the Middle East/Africa region recorded the highest spending, while those in Asia/Pacific had the lowest, possibly due to the number of supermarkets. Most loyal customers (over 5 years in the program) were in the Middle East/Africa, contributing 31% of total spending, whereas Europe had fewer long-term customers but ranked second in regional spending.

_Monthly Analysis_

Despite missing 10% of monthly records, customers who joined the loyalty program in January had the highest total spending, while November and December had the lowest, likely due to fewer months available for spending. Shoppers subscribed for less than 3 years spent more in early months, whereas those in the program for over 5 years concentrated their spending later in the year.

_Existing Promotion_

According to the database, 49% of the shoppers joined the loyalty program as part of a promotion offered by International Essentials. The average spending and the number of items purchased by shoppers who joined due to a promotion were similar to those who joined without one.
