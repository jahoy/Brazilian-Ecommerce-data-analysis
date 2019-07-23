# Brazilian-Ecommerce-data-analysis




## Abstract

<img width="683" alt="Screen Shot 2019-07-19 at 10 48 50 AM" src="https://user-images.githubusercontent.com/50973416/61503477-d9b28780-aa12-11e9-81ee-9ac5419ce226.png">

This is a Brazilian ecommerce public dataset of orders made at Olist Store. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners. See more on website: www.olist.com

<img width="905" alt="olistdata" src="https://user-images.githubusercontent.com/50973416/61434473-044c0400-a971-11e9-91e4-9698be4277fc.png">


## Basic Analysis
 - Focus on  `orders`, `customers`, `payments`, `products` and `reviews` datasets.  
    * Analysis by Purchase Period
    * Analysis by Customer State
    * Analysis by Payment Type
    * Analysis by Product Categories
    * Analysis by Review Score

## Customer Review Analysis  
**Try to extract value from customer reviews Using NLP(Natural Language Processing) Technique**
 
**Summary**:   
Olist's customers(review score=5) enjoy about their experience:  
* Fast delivery ('chegou antes prazo', 'entrega rapida', 'entregue antes prazo', 'super rapida')
* High quality goods ('produto otima qualidade', 'otimo produto', 'produto excelente', 'produto boa qualidade')
* Good packaging ('bem embalado', 'produto chegou bem')

Olist's customers(review score=1)were dissatisfied with their experience:  
* They received the wrong goods ('recebi produto errado', 'produto veio errado', 'produto totalmente diferente')
* Some customers received fake items('produto nao original')
* People rate seller's customer service badly, which seems to be unresponsive in some cases
* Some people didn't receive their invoices

From Clusting Techinque:  
We can see that the delivery time is very important for the customers. Good reviews that shows compliments and contentment mainly related to the early delivery of the products. On the other hand, Bad reviews shows discontentment about delays in delivery and in some cases the wrong product beeing delivered but the delays still are majority.

## Modeling Customer Churn Risk and Future Purchases
**The primary goal of this work is to build a probabilistic model(`BG/NBD model`) for forecasting customer lifetime value(Future Purchases) and customer churn risk in non-contractual setting on an individual level.**

1. Distinguish active customers from inactive customers.
2. Generate transaction forecasts for individual customers.
3. Predict the purchase volume of the entire customer base.
4. Predict customer churn risk

**Summary:**  
I have these churn groupings, we can move forward and apply special treatments to these groups.  
`churned`: 1928(number of churned)  
`high risk`: 84(number of high risk)  
`not churned`: 73(number of not churned)  
**1) Reach out to churned customers to figure out why they left.**  
**2) Send different types of targeted emails and special offers to the high risk group.**  
**3) Determine the the highest value customers in the non-churn group, and serve them additional benefits to ensure that they remain loyal customers(VIP).**


## Seller Side Data Analysis
From the seller side, Olist’s marketing team want to increase the number of merchants using Olist platform.
**The scope of this analysis focuses more on the seller side (B2B) of Olist that can bring some helpful insights into Olist’s B2B marketing team.**

<img width="680" alt="Screen Shot 2019-07-22 at 9 04 03 PM" src="https://user-images.githubusercontent.com/50973416/61720470-ccdebc80-ada1-11e9-864f-4aafbdc5b697.png">

**Summary:**  
**1) Marketing Channel Effectiveness**   
+ The majority of MQLs come from organic_search channel. Continue to work on SEO/Events to increase organic traffic
+ If the marginal cost of paid search increases, it would be possible to examine effectiveness of 'social' as an alternative. 

**2) Sales Performance**     
+ Both conversion rate and sales length were improved in 2018 against 2017.
+ Leads are steadiness type. Olist can build customer persona around these type of people and crafting messaging/content to target these people.  

**3) Closed Deal Performance Overview**  
+ The biggest segment was 'watches', which generated 17.4% of total revenues.
+ Sport leisure and watches segment can be developed more because Olist can capture high revenue from them


