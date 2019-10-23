# bamazonCustomer.io

## Overview

What I have created is an Amazon-like storefront with MySQL and Node skills. The app will take in orders from customers and deplete stock from the store's inventory. As a bonus, you can run your program as a manager to track what inventory is low, add more stock, or add totally new items!

## Challenge 1: Customer View

Create a MySQL Database called bamazon.

Then create a Table inside of that database called products.

The products table should have each of the following columns:

item_id (unique id for each product)

product_name (Name of product)

department_name

price (cost to customer)

stock_quantity (how much of the product is available in stores)

The app should then prompt users with two messages.

The first should ask them the ID of the product they would like to buy.

![Alternate text](stockdispay.png)

![Alternate text](/stockdispay.png)

![Procuct ID](https://aamoesi.github.com/bamazonCustomer.io/stockdispay.png)



The second message should ask how many units of the product they would like to buy.
Once the customer has placed the order, your application should check if your store has enough of the product to meet the customer's request.

If not, the app should log a phrase like Insufficient quantity!, and then prevent the order from going through.
However, if your store does have enough of the product, you should fulfill the customer's order.

This means updating the SQL database to reflect the remaining quantity.
Once the update goes through, show the customer the total cost of their purchase.
