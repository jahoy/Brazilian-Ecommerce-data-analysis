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
 - Try to extract value from customer reviews
 
### Summary: 
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

This shows that the delivery is something that the seller have to pay extra attention, always looking for a transporter that has low rate of delay and in most cases delivery early than the estimated.
