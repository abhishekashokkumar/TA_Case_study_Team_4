Data Set Information:

Data is of a manufacturer who sells their product to distributor. Distributor sells the products to retailers, who in turn sells to end customer.

There are below datasets:
sales.csv - the primary business by month data and distributor
net_value.csv - the secondary business by month data and distributor
retail_outlet.csv  - contains data about some programs organized by the client. It has data on the amount the distributor sold on wholesale 
orders.csv - contains the details of retailer's orders to distributor
orders_extended.csv- if the distributor was not able to sell something to retailer, then the reason about the problem is mentioned here
order_with_app.csv: the distributor uses some app to order from sales manager. this file contains the info if the order is made with app
order_without_app.csv: contains info about if the distributor is ordering without app
date_of_joining.csv- containing the exact date on which the distributor joined
returns.csv - contains details of the distributor profits/ returns
monthly_coverage.csv - contains details about how much the distributor is covering the retailers
invoice.csv - contains details about how many unique retailers are there for each distributor and how many times the retailer bought from distributor
no_objection.csv - It contains the policy related information for the distributor
business.csv - This file contains the information on number of retailers for each distributors. 

Attribute Information:

customer_code column in these data files is the distributor.

Usecase:
Churn analysis: Here the client is worried about the churning of distributor due to various voluntary or involuntary reasons and since distributor is the mediator, there is a possibility of retailer also being lost as a consequence.