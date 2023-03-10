# Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning
In this Mini Project, I acted as a Data Scientist in a company as the core Data Science Team. I am given the responsibility to process historical marketing campaign data to improve performance and target the right customers to transact on the company's platform. Here I learned how to process data, clean data, create machine learning models, and draw conclusions and business insights that can be recommended regarding the current marketing campaign. Some of the stages carried out in this mini project are: 
- Conversion rate analysis based on income, spending and age.
- Data cleaning and preprocessing.
- Data Modeling
- Customer personality analysis for marketing retargeting.


By using RFM analysis method to determine customer segmentation, the features used to represent Recency, Frequency, and Monetary are 'Recency', 'total_transactions', 'total_spent', 'age', 'joined_in_days'. By using K-means clustering algortima, there are 3 customer clusters generated, namely: 
- Cluster 0 (637 customers or 28.44%) = high value customers, because the overall value of total spent, total transactions, but the recency value is small which means they rarely visit our platform.

- cluster 1 (1014 customers or 45.27%) = low value customers, because the recency value is quite high, they rarely shop and when shopping, the value spent is small.

- cluster 2 (589 customers or 26.29%) = high value frequent customers, having a low recency value means that they often visit our platform, often transacting in large enough amounts.

In line with the EDA conducted in the previous stage, the middle age group dominates all clusters.

Some business recommendations that can help in retargeting marketing:

1. Create a membership program that offers rewards depending on the customer's membership level. This membership level is determined from total spending, total transactions, and recency value as used in the RFM analysis method. Using a membership program will increase customer loyalty and encourage them to spend more and more to pursue the rewards offered.

2. Focus on customers who frequently shop with high value to avoid churn. If necessary, give them the highest membership level by always maintaining service quality so that they feel valued and feel comfortable shopping on our platform so that they can continue to make repeat orders.

3. For high value customers who rarely visit our platform, provide special discounts specifically for them such as periodic flash sales with special prices and provide notifications to them when flash sales are taking place to increase the value of their visits in the hope that their total transactions and total purchases will also increase.

4. For low value customers, special offers are also given in the form of discounts for items that have low selling value to increase the value of visits to our platform. It is expected that the increase in the value of visits can also increase the value of total transactions and total spent, although not as big as high value customers.
