# Restaurant-Order

## Project Description
The main purpose of this project is to analyze the dataset, clean and give recommendations to the insights discovered. 
Bee-eff is a classy restaurant located in the United States of America. It is the end of the first quarter of the year and the CEO employed a data analyst to help analyze the restaurant data and help give recommendations.

## Overview
The dataset has two tables called 'menu-items' and 'order-details'. 'Menu-item' table has four columns which are menu item-id, item-name, category and price. Order-details table has five columns which are order-details-id, order-id, order-date, order-time and item-id. 

## Methodology
One of the methodologies used in this project is data collection. I downloaded the dataset from Marven playground on google chrome. It was a CSV file which was imported from MS Excel to Postgres. I created tables and columns on Postgres. 
The dataset was not so dirty and disorganized and there was not so much cleaning to do. However, I used some SQL queries like joins, aggregate and CTE to clean the dataset.
In this project, the SQL queries used includes Joins, aggregate, count, common table expressions. 

## Questions
1. View the menu_items table and write a query to find the number of items on the menu
2. ///SELECT COUNT(item_name) AS number_of_items
    FROM menu_items///
