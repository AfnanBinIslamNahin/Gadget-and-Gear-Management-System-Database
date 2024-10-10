# -Gadget-and-Gear-Management-System-Database

# Introduction

Welcome to the Gadget and Gear Management System (GGMS) 
database project. GGMS is crafted to address the contemporary 
challenges in managing electronic devices within organizations. This 
project aims to develop a centralized platform for efficient inventory 
tracking, maintenance scheduling, and allocation of gadgets and gears. 
By providing real-time visibility and optimization of resources, GGMS 
intends to enhance productivity and reduce operational costs. Through 
this project, we endeavor to design a user-friendly interface with robust 
functionality, revolutionizing the management of gadgets and gears 
within organizations.

# Case Study / Scenario

Gadget and Gear Management System (GGMS) is enhancing operational 
efficiency with a design that allows customers to order a variety of tech products 
based on their preferences. It’s an online-based company.
The company offers a wide range of electronics, including Apple mobile phones 
(iPhone 13 Pro to iPhone 15 Pro), Apple laptops (Macbook), headphones, shooting 
drones, power banks, speakers, camaras, and smart watches. Additionally, TVs 
from Sony are available. Customers can order products and must provide their 
name, phone number, and email. 
This order details the product name, model, quantity, price, and order date. Orders 
are managed centrally, streamlining the purchasing process for efficiency and 
customer satisfaction. This company sells products at lower prices than others. So 
the sales of every product from this company have increased. Struggling to handle 
customers. Many customers buy more than one product due to lower prices. Due to 
this, there are many customers who are not able to buy any products.
For this reason, the company made a policy which is each customer can purchase 
any one product. These policy are made so that the products of this company can 
reach every customer.

# Table
1)C.Id, C.Name, Phone No., Email, P.Id — Customer Details

2)P.Id, P.Name, Model, Price, Category — Product Information

3)C.Id, C.Name, Phone No., Email, O.Id — Customer Information

4)O.Id,Date — Order Details

5)Po.Id,P.Id,O.Id — Order Details 1

6)P.Id,P.Name,Model,Price,Category,Od.Id — Product Details

7)Od.Id, Quantity, Product — Product Details 1

8)Ood.Id, O.Id, Od.Id — Delivery


# Query Question
### CONDITIONAL STATEMENT :
```bash
*Display the customer name from Customer Details where the name starting letter ‘A’ 
and end letter ‘s’

*Display customer name,model and price from product information where price is less than 
30000

*Display Order id and Order date from order details where order id is 230

*Display Order_details_id ,quantity, product from product_details_1 where quantity is equal to 3

*Display product id,product name,price ,category and model from product details where 
order_details_id is between 43 to 47
```
### SINGLE ROW FUNCTION:
```bash
*Change the product name from product information in capital letter

*Find the length of customer name from customer details

*Show the concat between customer name and product id from customer details

*Print the first 4 letter of product name from product details

*Search the category from product information where product name is TV and find the location of ‘H’
```
### MULTIPLE ROW FUNCTION :
```bash
*Display the max and min price from product information

*Display the sum price from product information

*Display the avg price from product details
```
### SUBQUERY:
```bash
*Display the customer name,phone number from customer details where product id is greater than 
Leo Messi product id

*Display the product name,model from product details where price is greater than AirpodsMax price
```
#### Download the pdf file to see the answer. 

# TABLE OF CONTENTS 
```bash
TOPICS                 Page no.
Title Page                 1
Table of Content           2
1. Introduction            3
2. Case Study              4
3. ER Diagram              5
4. Normalization          6-8
5. Finalization            9
6. Table Creation        10-13
7. Data Insertion        14-17
8. Query Test            18-27
9. Relational Algebra      28
10. Conclusion             29 
```
###  Please Download the pdf file to see all of this. 


## Installation

1. Install Oracle 10g .

## Contact

For more information, reach out to:

- **Email:** [nahin.islam.bd4@gmail.com](mailto:nahin.islam.bd4@gmail.com)
