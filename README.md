# Danny's_Diner_SQL_Challenge



## 1. Background

Danny, a passionate lover of Japanese cuisine, decided to follow his dream and open a small restaurant named **Danny’s Diner** at the start of 2021. The diner serves his three favorite dishes: sushi, curry, and ramen. However, as the business grows, Danny finds himself in need of data-driven insights to help his restaurant thrive.

He has collected some basic customer data but needs assistance in analyzing it to understand his customers' behaviors, spending patterns, and preferences. By doing so, Danny hopes to create a more personalized experience for his diners and improve his customer loyalty program.

To achieve these goals, Danny has provided key datasets related to customer orders, menu items, and loyalty program members. Using this data, the aim is to answer several important business questions that will help Danny make strategic decisions for his restaurant.




## 2. Overview

This project is a part of the **8-Week SQL Challenge** and focuses on using **SQL** to analyze customer behavior and purchasing patterns at Danny's Diner. The challenge involves using three datasets provided by Danny, which include **sales**, **menu**, and **members**.

Through the use of SQL queries, this project answers key questions such as:

1. **Total customer spending** at the diner.
   
2. **Frequency of customer visits**.
   
3. **First purchased item** for each customer.

4. **Most purchased menu item** overall and for each customer.

5. Customer behavior **before and after** joining the loyalty program.
   
6. **Points calculation** based on their spending, with multipliers for specific items and loyalty bonuses.

The data analysis will help Danny optimize his restaurant's loyalty program, understand customer preferences, and improve overall customer satisfaction.



## 3. Datasets Used:
**Sales**: Records of customer orders, including order date and menu items purchased.

**Menu**: Information about each menu item and its corresponding price.

**Members**: Data on when customers joined the restaurant's loyalty program.

![Danny's Diner](https://github.com/user-attachments/assets/3cd4266f-162b-461b-a833-1c5f59ca4066)


## Tools and Skills:

SQL for querying relational databases.

Basic data manipulation and aggregation techniques.

Understanding of business metrics and customer behavior analysis.

Through this project, I used SQL queries to answer business-related questions and provide actionable insights for Danny's Diner. You can find the detailed analysis and queries in the files linked in this repository.




## 4. Executive Summary
This analysis aims to uncover key insights about customer behavior, popular menu items, and the effectiveness of the loyalty program. The study focuses on customer spending patterns, visit frequency, first purchased items, and the performance of the restaurant's membership program. By understanding these metrics, the restaurant can better tailor its offerings and reward loyal customers, ultimately boosting customer retention and profitability.




## 5. Insights Deep Dive

### 5.1 Total Spending by Each Customer

We calculated the total amount spent by each customer:

**Customer A** spent $228.

**Customer B** spent $222.

**Customer C** spent $108.

### 5.2 Customer Visit Frequency

The number of days each customer visited the restaurant was:

**Customer A** visited 4 times.

**Customer B** visited 6 times.

**Customer C** visited 2 times.

### 5.3 First Purchased Item

The first item each customer purchased:

**Customer A**: Sushi.

**Customer B**: Curry.

**Customer C**: Ramen.

### 5.4 Most Purchased Menu Item

**Ramen** was the most purchased item across all customers, with a total of 24 orders.

### 5.5 Most Popular Item per Customer

**Customer A's** favorite item was Ramen.

**Customer B** had multiple favorites: Ramen, Sushi, and Curry.

**Customer C's** favorite item was Ramen.

### 5.6 First Purchase After Joining Membership

The first item purchased after becoming a member:

**Customer A**: Ramen.

**Customer B**: Sushi.

### 5.7 Last Purchase Before Membership

The last item purchased before joining the membership program:

**Customer A**: Sushi and Curry.

**Customer B**: Sushi.

### 5.8 Total Items and Amount Spent Before Membership

**Customer A** ordered 6 items, spending a total of $75.

**Customer B** ordered 9 items, spending a total of $120.

### 5.9 Customer Loyalty Points

Points are awarded based on the following criteria:

Each $1 spent earns 10 points.
Sushi has a 2x multiplier for points.

Total points for each customer:

**Customer A**: 2,580 points.

**Customer B**: 2,820 points.

**Customer C**: 1,080 points.

### 5.10 Double Points in the First Week of Membership

In the first week after joining the loyalty program, customers earn double points for all items. Points accumulated by the end of January:

**Customer A**: 4,110 points.

**Customer B**: 2,820 points.

### 5.11 Product and Membership Status for Each Order

For each customer, we detailed every order date, the product purchased, its price, and whether the customer was a member at the time of the purchase.

### 5.12 Order Ranking Based on Membership Status

Orders were ranked based on the order date and membership status. If a customer was not a member when they made the order, their ranking was displayed as NULL. This ranking allows for the identification of purchase patterns before and after joining the loyalty program.



## 6. Recommendations

Based on the insights from the analysis, the following recommendations can help the restaurant improve customer experience and boost revenue:

**1. Enhance the Loyalty Program**: *Customers who joined the membership program significantly increased their spending. Promoting the loyalty program to all customers could lead to higher retention and spending*.

**2. Focus on Popular Items**: *Ramen is the most purchased item overall. The restaurant could capitalize on this by offering Ramen-based promotions or bundling it with other items to increase average order value*.

**3. Offer Personalized Promotions**: *By identifying the most popular items per customer, the restaurant can create targeted offers, encouraging customers to return and try new items*.

**4. Leverage Point Multipliers**: *Sushi’s 2x points multiplier led to increased purchases by loyal customers. Expanding the multiplier to other popular items, like Ramen, during promotional periods could further drive sales*.

**5. Optimize Menu Based on Preferences**: *Customer A and B have different preferences, with Customer A favoring Ramen and Customer B enjoying a wider variety. Adjusting the menu or offering combo deals catered to these preferences could enhance customer satisfaction*.











