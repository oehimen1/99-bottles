# Database Systems Project: 99 Bottles

## Project Description
Online shopping is very popular, as it allows people to get many choices on a single platform compared to traditional shopping. Because of this, the preference for online shopping is large scale. The primary purpose of this project is to create a database for an alcoholic beverage e-commerce website. The database will store information about the site's products, product categories, customer orders, customers, the website's stock, and brands sold. Some of the entities in our database include "Product," "Order," and "Customer." 


## Table of Contents
- [Example Usage](#example-usage)
- [Requirement Analysis](#requirement-analysis)
- [Database Schema](#database-schema)
- [Technologies Used](#technologies-used)
- [Project Report](#project-report)

## Example Usage
Requirement: When the customer enters the website, they can see the list of products along with the image, the price, the rating, and the seller's brandname.
![Requiremnt 1](http://g.recordit.co/o5Lp1mus9T.gif)


## Requirement Analysis
- A new upcoming e-commerce company wants us to create a database for a website they will launch soon. They want their website to be like Amazon but for alcohol, where there is a seller (one who sells the alcohol) and a customer (one who buys alcohol from the seller).
- A customer’s information must be stored to create an account to purchase products. The most critical information the customer needs is their name, address, unique username, and date of birth. It would also be helpful if their payment information were stored, so they could easily place orders. 
- The seller wants to be able to sell different alcoholic products to its customers. This means the seller’s information, such as their email,  phone number, and brand name. It would be helpful for the customers to view the name of the products and the price, a short description, a picture of what the product looks like, and who sells it. In addition, it may be helpful for the customer to choose which product to buy by seeing the rating. 
- Products can be listed under several different categories for more straightforward customer navigation. Each category will have a name and brief description. The website allows customers to add products to an online cart before ordering. The customer must use the cart to make a purchase. The items in the cart would also be saved on their browser until either an order is placed or the cart is cleared. Once an order is placed, the details should be stored and provided to the customer. -- The order details would include an order ID, the date the order was placed, the total price, and the shipping address for the delivery. 
- The seller wants to verify each payment before shipping the order; they want to see the type of payment used, the status, and the date the payment was made for each customer’s payment. When an item is shipped, customers should be provided with delivery details to track when their order arrives. The essential information related to delivery is the order ID, the seller ID, the customer username, and the delivery status. The seller would like to see the past orders and the products purchased through them; this refers to the seller's history. Customers should be able to see their past order history. This information would include any details related to the order they have placed. 


## Database Schema

ER Model:
![Updated ER Model (327)](https://github.com/oehimen1/db-project/assets/65789610/8244f818-31a5-4ab7-9f30-6735882dd415)



## Technologies Used
- PostgreSQL
- Visual Studio Code



Requirement: Some info (particularly an address and payment method) can be retrieved when a user places an order.
![Requirement 2](http://g.recordit.co/VrH165lyzi.gif)


## Project Report
[Project Report](https://docs.google.com/document/d/1W5k3AW97v1SvNLqHRQX_ThOoXlu1DVTpxF4e_MXM9ow/edit?usp=sharing)
