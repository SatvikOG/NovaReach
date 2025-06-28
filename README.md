# **VentureMart**
## **Overview and background :**
VentureMart, founded in 2015, is a mid-sized retail company specializing in consumer goods ranging from premium wines and gourmet foods to household and luxury items. Products are sold through multiple channels including an online store, physical outlets, and a catalog-based order system.

The company has accumulated a rich dataset covering customer demographics, purchase behavior, promotional campaign responses, and multi-channel shopping preferences. However, this data has been underutilized in generating strategic insights for marketing, product positioning, and customer targeting.

This project was designed to extract value from that data by conducting a comprehensive end-to-end marketing analytics initiative, focusing on uncovering what truly drives customer spend and how campaign strategies and shopping channels influence profitability.

 **Insights and Recommendations Are Provided Across the Following Areas:**
- **Customer Behavior Analysis :** Detailed profiling of customer segments based on age, income, household structure, and engagement level, to identify which segments are high-value and which
are cost-sensitive.

- **Marketing Campaign Impact :** Evaluation of five historic marketing campaigns to assess which ones actually led to higher revenue per customer and which did not perform effectively, using regression modeling.

- **Channel Performance :** Comparison of purchases made through online, catalog, and in-store channels to determine their individual contribution to total spend and how they differ by customer segment.

- **Revenue Driver Modeling :** Regression analysis used to quantify the impact of specific customer behaviors—such as number of web purchases or catalog orders—on overall revenue, identifying the top behavioral levers.

 - **Strategic Recommendations :** Actionable business insights for optimizing future campaigns, improving product offerings for specific customer groups (e.g., families with children), and tailoring loyalty strategies to maximize customer lifetime value.



## **Data structure Overview :**
<img width="454" alt="Screenshot 2025-06-25 at 6 16 10 AM" src="https://github.com/user-attachments/assets/4d6f9349-78de-4214-a80f-b27df0a3da1c" />


<img width="452" alt="Screenshot 2025-06-25 at 6 16 19 AM" src="https://github.com/user-attachments/assets/de9609be-08c8-4547-b9c4-d7a79572b06a" />


<img width="451" alt="Screenshot 2025-06-25 at 6 16 34 AM" src="https://github.com/user-attachments/assets/75e2afa7-2af6-433a-9086-76d84606b83c" />


<img width="453" alt="Screenshot 2025-06-25 at 6 16 42 AM" src="https://github.com/user-attachments/assets/7a6d15f1-ce89-4f1d-9ba6-6fd2d409bc57" />


## **Executive Summary :**
Inorder to increase company response, we focused on the following metrics :

**Response:** The number of people accepted the offer from the last campaign

**NumWebPurchases:** Number of purchases made through the company’s website

**NumWebVisitsMonth:** Number of visits to company’s website in the last month

Response 
- Only 14.91% of the total customer responded to the latest campaign, the reason might be it was targeted to single people which only consisted of 21.43% of total customers.

- In terms of response, campaign 4 was the most effective as it was able to bring 167 participants.

- Interestingly, Despite campaign 4 had better reach but campaign 5 was able to generate more revenue.



## **Insights deep dive:**
- There is moderae negative relationship between number of children and the total spending which could reveal a product-market misalignment. In other words, our current product portfolio might not include items that cater to households with children
  
- Campaign 2 and 3 has failed to add value in the revenue of the company as regression analysis showed the p-value of 0.72 and 0.09 respectively which is far more than 0.05. The fact has to be noted that campaign 3 was the second best campaign out of 5 which indicates despite of increased participation, company shouldnt investment more on that campaign or can work on improving the conversion rate of the campaign 3.  

## **Recommendations**




# STEP 1 : Cleaning data 

<img width="753" alt="Screenshot 2025-06-23 at 10 46 32 PM" src="https://github.com/user-attachments/assets/f9c0cd4d-1e7a-4c5a-924a-3f28bfaa26c6" />

# STEP 2 : EDA
### Company Problem statement :
LuxeMart is investing heavily in personalized marketing campaigns, but executives are unsure which customer segments respond best, and which promotional strategies deliver the most value.

We need to perform a full customer segmentation and campaign performance analysis to help marketing and finance teams make data-backed decisions.


Business relevant questions :
#### Which customer segments (by age, income, marital status) respond best to each type of campaign?
Age group 40 - 60 exceeded the shopping in almost every campaign, except for Campaign3 which was dominated by age group 30 - 40
  
#### Which campaigns had the highest conversion rates, and what channels drove those conversions (web, catalog, store)?
Campaign 4 was the most succesfull as it was targeted to right age group (40 - 60 age)

#### How does customer engagement (web visits, recency) correlate with campaign response?
There is weak correlation of 0.19 between web purchases and campaign involvement indicating the ineffectiveness of the campaigns to add new customers

#### Are customers with children more or less likely to accept promotional offers?
Customer with childrens are less likely to accept promotional offer as it has negative correlationship between children and total spending

💰 Finance Stakeholder (Head of Finance)
#### Which customer groups contribute the most revenue over 2 years (top 20% income or spending)?
More than half of the revenue is generated by 40 - 60 age group 

#### Is there a negative financial impact from customers who submitted complaints?
No, there is no negative financial impact from customer who submitted complaints 


🛍️ Product Stakeholder (Head of Product or Merchandising)
#### Which product categories are most popular across different customer segments (age, income, marital)?
- 77.7% of the sales reveune comes from the 2 categories which  are wines and meat products. This category has dominated in all of the age group especially from 40 - 60

# STEP 3 : Hypothesis testing & Regression analysis 

<img width="638" alt="Screenshot 2025-06-23 at 11 18 10 PM" src="https://github.com/user-attachments/assets/3d498e03-01bc-4956-8f5a-ddfe8eb9ab15" />








                          
## Recommendations :

## Errors 
