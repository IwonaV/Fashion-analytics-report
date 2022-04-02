# Fashion-analytics-report-for-a-fast-fashion-retailer

Building the fashion analytics report for a fast fashion retailer. Based on what the company will able to improve its performance (the revenue growth). 
The report will consist of three sheets:
1.	It will feature the company metrics compered on the year to year basics 
2.	It will provide the customer driven metrics which we examine across three different customer segments 
3.	It will feature customer life cycle which will feature two charts: first number of orders that customers made on the website and the second one showing how long usually it takes for the consumer to make a repeat purchase. Both are integrated to understanding the behaviour of the clients and more importantly the are the key metrics that need to be optimized to improve margins.

The story in Tableau

## 1.	Building company’s KPI 
It will include year to year comparison 
-	The first KPI is the volume of sales 
-	The next is total order value or gross sales 
-	Then discount amount
-	Net sales – total order value – discounts 
-	Line SKU Production cost 
-	Gross profit = net sales - production cost in other words is actual revenue from the sales
-	(%GP) Gross Profit margin= Gross profit/ net sales 
-	fashion retailers requite to look at consumer’s metrics, along with financials metrics as leading KPIs
considering how the average value of the consumer evolves over time for instance is a key metrics to access the value of the company from a consumer equity stand point. So we will add
-	Consumer LTV
-	AOV-average order value = sum (total order value/ count (order id)

image

Sales by country – targeting the country where the sales is the lowest or the highest

image 

Insights:
And we can compare this metrics on the year to year basis whether there is growth or decline in the KPIs. As we can see in our analysis there is a 1% increase in the %GP in 2020 compares to 2019.  
In 2020 we have made more sales compering to previous year more than double the sales. Naturally this show increase in total order value, discounts and gross sales.
GP% determines the growth and it is why this is the most important metric for any business.


## 2. building consumer's KPI
KYC - to Know Your Costumers is vital across industries - Knowing how the base of the consumers are distributed will help the organisation identify the consumer and the consumer cluster that matter. this intern will allow to target the right customer base and attract future consumers with the same profile. so we look at the different types of consumers or customer Tiers. so we divided the customers by the life time value.

The main consumer KPIs are:
- customer LTV - Total order value – cost of goods sold
So we divide costumers according to their LTV into tears or percentiles so we have:
	- Tear 3 –(0 – 0.33)
	- Tear 2 – (0,33 – 0,66)
	- Tear 1 – (0.66 -1) – top paying customers. 
Once we have 3 tiers we can see number of customers we have in each of them so we need to add
- distinct count of customer ids  
-  we also want to see customer percentage by tear which is same number of customers but display in percent (% of total % customers)
- distinct count of customer
- average order value by tear
- purchase frequency across customers tear = sum of number of orders/ distinct number of order id
- and the last we need to include average LTV of the customers  

Insights:
we have Consumers engagements.
Here we have consumer driven metrics driven by consumer tiers. As we can see that the highest paying consumers make up for smallest consumer’s clusters. So Tier 1 is is the most valuable consumer cluster and it is where the companies should invest to keep consumers on their website and could be where the marketing focuses its campaign on the new users with the same profile


## 3. To analyse the purchase behaviour of the clients we can create 
-	The frequency curve will display the number of orders made by consumers on our website ( I’ll show the number of orders by count as a bar chart) a dual y-axis will display the cumulative frequency of orders in percentages as a line chart

image
-	Repurchase curve – average time of repurchases based on the consumer’s information so the x-axis for both charts will show the average months between repurchases and on the y-axis for the bar chart will display the number of customers who have repurchased in a specified period. 

image 

Insights:
in the last dashboard we have the consumer’s lifecycle. Looking at the frequency curve we can see that the majority of our consumers made a single purchase on the website. So the companies should concentrate their effort to keep customers on the website. So the goal is to convince customers to stay active on the website and make repeat purchases, this can be trace back to any part of the customer’s journey from the first click on the website to the variety of irrelevance they show while they are there. Customers journey should be flawless and engaging.
Repurchasing curve – the average time it takes of the majority of the customers to repurchase is the crucial element of fashion analytics. It determines when we must target our consumer base before they’ve become inactive and we’ll loose them. We can see that about 70 % of our customers repurchase within 4 months or less. This also indicates that this data comes from a fast fashion brand rather than a luxury one. So we should focus on those newly active consumers within the first few months of their first purchase and we should target them. Later than that we could potentially loosing almost two third of the customers into repeaters.
So the frequency and repurchase frequency are the key metrics to measure the consumer base and they are the key metrics for our business. Focusing on maximising all these metrics would lead to healthy consumer base that drive high margins.

