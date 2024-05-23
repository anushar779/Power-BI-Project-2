# Comparison of Region Based on Sales

### Dashboard Link : 

## Description:
The director of a leading organization wants to compare the sales between two regions. He has asked each region operators to record the sales data to compare by region. The upper management wants to visualize the sales data using a dashboard to understand the performance between them and suggest the necessary improvements. 

Objective: Help the organization by creating a dashboard to visualize the sales comparison between two selected regions.


### Steps followed:

1.	Select Sample Superstore as Dataset  
•	Use Sample Superstore Dataset

•	Select Data

•	Use Group by from Data Source Table on a Folder to create a folder to segregate the required data for Customer Name and Order ID in order to organize the data thoroughly.
2.	Create a hierarchy called Location for the variable Country. 

3.	Create two parameters: Primary Region and Secondary Region with all regions listed in them. Here, primary and secondary region are the two regions where the sales are being compared.

•	Create Parameters for Primary Region and Secondary Region

•	Create a Calculated Field for both Primary Region and Secondary Region

4.	Create a First Order Date

•	Create a Calculated Field and name it as the First Order Date

5.	Create a dashboard
•	Align all sheets in the dashboard

6.	Partition the dashboard to display the below details of Primary Region and Secondary Region.

•	First Order Date

•	Total Sales

•	No. of Customers

•	No. of Orders

•	No. of Products in Sale

Formulas used to Create New Calculated Fields:

•	First Order Date: MIN ([Order Date])

•	Total Sales: SUM([Sales])

•	No. of Customers: COUNTD ([Customer ID])

•	No. of Orders: COUNTD ([Order ID])

•	No. of Products in Sale: COUNTD ([Product ID])
 
 # Report Snapshot (Power BI DESKTOP)

 
![Sales Comparison by Region](https://github.com/anushar779/Dashboards/assets/170659132/f2b299e1-4cbb-4809-b29d-23c48faf5699)

# Interpretation:
 
1. Regional Performance Metrics – 

East Region leads in total sales, No. of Customers, No. of Orders, and No. of Products in Sale.
Central Region has its first order date earlier than East Region indicating that business activities or efforts to establish a presence in Central Region began earlier.

2.  Overall Performance – 

Map Visualization: The map in the secondary region that East Region in the teal blue, indicating the highest total sales ($679K), while the map in the primary region shows that Central Region in the teal blue, indicating the lower sales ($501K). 

4. Comparative Analysis – 

Bar Chart: East Region significantly outperforms the Central Region in total sales of Phones, Chairs and Storage, indicating a strong market presence.

Total Sales Analysis:

-	High sales sub categories:
•	East Region generally outperforms Central Region in most sub categories, especially in Phones, Chairs and Storage sub categories.

•	Phones: East Region ($100,615) > Central Region ($72,403)

•	Chairs: East Region ($96,216) > Central Region ($85,231)

•	Storage: East Region ($71,613) > Central Region ($45,930)

•	Central Region seems to have a larger or more effective market in these categories.


-	Low sales sub categories:

•	Fasteners: East Region ($819) > Central Region ($778)

•	Labels: East Region ($2,602) > Central Region ($2,451)

•	Fasteners and Labels perform slightly better in East Region, but the overall difference is not significant.

The table chart of two regions provides a clear snapshot of sales performance across different Sub Categories, highlighting areas of strength and opportunities for growth. By analyzing total sales alongside min and max sales, stakeholders can make informed decisions about product strategy, marketing efforts, and resource allocation to maximize revenue and market share.

Minimum Sales Analysis:

•	Lowest Min Sales:

East Region: Binders ($0.85), Art ($1.50)

Central Region: Binders ($0.56), Art (1,34)

Both regions have the low-cost items in the Binders & Art sub categories, indicating lower price points or smaller sales transactions.

•	Highest Min Sales:

East Region: Copiers ($497)

Central Region: Copiers ($318)

Both regions show high minimum sales for Copiers, indicating premium pricing.

Maximum Sales Analysis:

•	Highest Max Sales:

Copiers: Central Region ($17,499) > East Region ($11,199)

Machines: East Region ($9,099) > Central Region ($8,159)

Supplies: Central Region ($4,164) > East Region ($4,633)

Central Region’s higher max sales for Copiers & Supplies, suggest it has more high-value customers or larger purchases. East Region generally has higher max sales for Machines, indicating the presence of more high-value transactions.

•	Lowest Max Sales:

Fasteners: Central Region ($58) > East Region ($40)

Labels: Central Region ($491) > East Region ($122)

Art: Central Region ($209) > East Region ($289)

Central Region’s higher max sales suggest it has more high-value customers or larger purchases.


Category Performance Insights:

•	High Variation Categories:

Phones, Chairs, Binders and Storage in both regions show significant differences between min and max sales, indicating a broad range of products from low-cost to high-value items.
These sub categories benefit from a diverse product offering appealing to various customer segments.

•	Low Variation Categories:

Fasteners, Labels & Envelopes show less variation, suggesting more consistent and lower-priced products. 
These sub categories likely focus on high volume, low-margin sales. Implies focus on consistency, simplicity, and affordability in product offerings.

Strategic Recommendations:

•	For East Region:

Enhance High-Performing Categories: Focus on increasing sales in Phones, Chairs, Storage, Machines & Binders through targeted marketing and product diversification.

Improve Lower-Performing Categories: Investigate ways to boost sales in Fasteners, Labels, Envelopes possibly through promotional campaigns or bundling strategies.

•	For Central Region:

Leverage High-Value Transactions: Continue to capitalize on high-value transactions in Phones, Chairs, Binders, Storage & Tables by offering premium products and personalized services.

Expand Moderate Categories: Explore opportunities to further increase sales in categories like Fasteners, Labels & Envelopes by enhancing product offerings and promotional efforts.

Conclusion:

By comparing the two regions, stakeholders can identify strengths and weaknesses in each market. East Region generally performs better, with higher total sales and maximum sales values across many categories, indicating a more affluent or larger market. Central Region, while performing well, especially in categories like Phones and Chairs, can benefit from strategic initiatives to boost sales and capture higher-value transactions. This comparative analysis provides a clear direction for optimizing sales strategies and resource allocation in each region.

