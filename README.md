## Fashion Analytics Report

Building a fashion analytics report for a fast fashion retailer. On its basis the company will able to improve its performance - the revenue growth. 
The report (story) consist of three sheets:
1.	Contain the company metrics compered on the year to year basics.
2.	Provide the customer - based metrics that will be examined across three different customer segments 
3.	Feature customer life cycle which will include two charts: 
- Representing umber of orders that customers have placed on the website. 
- Showing how long it usually takes for the consumer to make a repeat purchase. 
Both charts are integrated to understand customer behaviour and more importantly, are key metrics that need to be optimized to improve margins.

Tableau [story](https://public.tableau.com/app/profile/iwona8604/viz/FashionAnalyticsStory_16416831242580/Story1)

### 1.	Building Company’s KPI 

The report will include year to year comparison of the key metrics.
-	The volume of sales 
-	Total order value (gross sales)
-	Discount amount
-	Net sales 
-	Line SKU Production cost 
-	Gross profit 
-	(%GP) Gross Profit margin 
Fashion retailers need to look at consumer metrics, along with financials metrics as leading KPIs
Considering how the average value of the consumer changed over time is a key metrics to assess the value of the company from a consumer equity standpoint. Therefore, is necessary to add:
-	Consumer LTV
-	AOV-average order value 

![image](https://user-images.githubusercontent.com/85560182/161405182-846a0c3a-6214-4628-aede-cb01d4df6c8a.png)

Sales by country targets the country with the lowest or the highest sales. 

![image](https://user-images.githubusercontent.com/85560182/161405178-640992f3-b97e-40c0-8739-099f28c84725.png)

#### Insights:
We can compare this metrics on the year to year basis whether there is growth or decline in the KPIs. As we can see in our analysis, GP% (gross profit margin) in 2020 increased by 1% compared to 2019.  
Also in 2020 the number of sales more than doubled compared to the previous year.  This shows an increase in the total order value, discounts and gross sales.
GP % determines growth and therefore it is the most important metric for any business.


### 2. Building Consumer's KPI

KYC - Knowing Your Costumers is vital across all industries. Knowing how the base of the consumers are distributed will help the organisation identify the consumer and the consumer cluster that matter. This information will allow to target the right customer base and attract future consumers with the same profile. 
Therefore, we look at the different types of consumers or customer tiers. The customers will be divided by the life time value.
Dividing costumers according to their LTV into tears or percentiles and obtaining:
- Tear 1 – (0.66 -1) – Top paying customers.	
- Tear 2 – (0,33 – 0,66)
- Tear 3 – (0 – 0.33)
	 
Having these 3 tiers we can see number of customers in each of the tier. 
Also including:
- Distinct count of customer IDs  
-  Customer percentage by tear which is the number of customers but display in percent (% of total % customers)
- Average order value by tear
- Purchase frequency across customers’ tear (sum of number of orders/ distinct number of order ID)
- Average LTV of the customers  

![image](https://user-images.githubusercontent.com/85560182/161405240-44764219-49ec-4b2f-90a8-916440882226.png)

![image](https://user-images.githubusercontent.com/85560182/161405257-6cbc2652-cfc5-469f-a24b-4332eb5e48f4.png)

#### Insights:
We can see that the highest paying consumers make up for smallest consumer’s clusters. Therefore, tier 1 is the most valuable consumer cluster and it is where the companies should invest to keep consumers on their website and can be a place where the marketing focuses its campaign on new users with the same profile.

### 3. Purchase Behaviour of the Clients

To Analyse the purchase behaviour of the customers we can create:
- The frequency curve that displays the number of orders placed by consumers on our website (showing the number of orders by count as a bar chart). A dual y-axis displays the cumulative frequency of orders in percentages as a line chart.
	
![image](https://user-images.githubusercontent.com/85560182/161405273-44f83964-1076-4153-8c2a-61da93ccfcdb.png)

- The repurchase curve display the average time of repurchases based on the consumer information. The x-axis for both charts shows the average months between repurchases and the y-axis for the bar chart shows the number of customers who have repurchased over the specified period. 
	
![image](https://user-images.githubusercontent.com/85560182/161405282-bf9b4e58-7e76-4403-8e44-5657517e443c.png)

#### Insights:
Looking at the frequency curve, we can see that the majority of our consumers made a one -time purchase on the website. Therefore, the companies should concentrate their effort to keep customers on the website. So the goal is to persuade customers to stay active on the website and make repeat purchases.
A key part of fashion analysis is looking at the repurchasing curve which is the average time it takes most customers to repurchase.  It determines when we must target our consumer base before they become inactive and we lose them. We can see that approximately 70 % of our customers repurchase within 4 months or less. So we should focus on those newly active consumers within the first few months of their first purchase and we should target them. After that period, we could potentially lose nearly two - third of the customers into repeaters. 
Focusing on maximising all these metrics would lead to healthy consumer base that drive high margins.

### Data reference:
[retail_dataset.xlsx](https://github.com/IwonaV/Fashion-analytics-report/blob/main/retail_dataset.xlsx) by [365datascience](https://learn.365datascience.com/)

