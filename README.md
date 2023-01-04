# SQL Queries
# SQl Queries

| example                                                                                                        | Specific SELECT | FUNCTIONS | WHERE       | GROUP BY | ORDER BY | TIME RANGE    | HAVING | JOIN   |
| -------------------------------------------------------------------------------------------------------------- | --------------- | --------- | ----------- | -------- | -------- | ------------- | ------ | ------ |
| Select the average price of all products in the store                                                          | price           | AVG       |             |          |          |               |        |        |
| Select the names and email addresses of all users who have made a purchase in the last month                   | name, email     |           |             |          |          | last month    |        |        |
| Select the total number of purchases made by each user                                                         |                 | COUNT     |             | user     |          |               |        |        |
| Select the top 5 most expensive products                                                                       |                 |           |             |          |          |               |        |        |
| Select the names of all users who have made at least 3 purchases                                               | name            |           |             |          |          |               |        |        |
| Select the average price of products in each category                                                          | price           | AVG       |             | category |          |               |        |        |
| Select the total number of purchases made by users in each country, ordered by highest to lowest               |                 | COUNT     |             | country  | COUNT    |               |        |        |
| Select the names of users who have made at least 2 purchases and spent at least $100 in the last year          | name            |           |             |          |          | last year     | 2      |        |
| Select the total sales and average price of products in each category, where the average price is at least $50 | sales, price    | SUM, AVG  | price >= 50 | category |          |               |        |        |
| Select the names of users who have made a purchase in the last 3 months, joined with their order information   | name            |           |             |          |          | last 3 months |        | orders |
