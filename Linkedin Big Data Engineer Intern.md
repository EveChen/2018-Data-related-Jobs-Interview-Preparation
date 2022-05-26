# Linkedin Big Data Engineer Intern
### Date: 2018 Jan
### Question: Given that you have all data in grocery stores, what kind of data will you collect, and how will you design your schema in order to analyze selling performance?
### Source: http://www.puchinchen.com/2018/04/07/US-Interviews/
-------------------------------------

# **My Answer**
### _Basic_
* Item price: including both the original price and promotional price
* Item location: store address (including zipcode), location of item within the store (e.g. location on isle, isle number, distance from store entrance)
* Transactions: If the store has a membership program, we can anonymously identify which items are bought by the same person.
* Type of shopping behavior: in-store shopping vs order online and pick up in-store
* Point of sale (POS): Use barcode to keep track on it
* Demographic data: population, gender, age, transportation

### _Influence factors_
* Any Promotion going on: including the promotions from the grocery stores and manufacturers
* Other competitors: is there any other promotion going on from other retailers?
* Seasonality: more shoppers on weekends, holiday shopping season
* Pre-Covid vs Post-Covid: mask mandate changes, return-to-office
