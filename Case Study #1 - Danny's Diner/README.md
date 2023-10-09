# Case Study #1: Danny's Diner 
<img src="https://user-images.githubusercontent.com/81607668/127727503-9d9e7a25-93cb-4f95-8bd0-20b87cb4b459.png" alt="Image" width="500" height="520">

## Table of Contents
- [Problem Statement](#problem-statement)
- [Entity Relationship Diagram](#entity-relationship-diagram)
- [Datasets](#datasets)
- [Question and Solution](#question-and-solution)

## Problem Statement
Danny wants to use the data to answer a few simple questions about his customers, especially about their visiting patterns, how much money they’ve spent and also which menu items are their favourite. 

***
## Entity Relationship Diagram
![image](https://user-images.githubusercontent.com/81607668/127271130-dca9aedd-4ca9-4ed8-b6ec-1e1920dca4a8.png)

***
## Datasets

### Sales Table ###

| customer_id | order_date               | product_id |
| ----------- | ------------------------ | ---------- |
| A           | 2021-01-01T00:00:00.000Z | 1          |
| A           | 2021-01-01T00:00:00.000Z | 2          |
| A           | 2021-01-07T00:00:00.000Z | 2          |
| A           | 2021-01-10T00:00:00.000Z | 3          |
| A           | 2021-01-11T00:00:00.000Z | 3          |
| A           | 2021-01-11T00:00:00.000Z | 3          |
| B           | 2021-01-01T00:00:00.000Z | 2          |
| B           | 2021-01-02T00:00:00.000Z | 2          |
| B           | 2021-01-04T00:00:00.000Z | 1          |
| B           | 2021-01-11T00:00:00.000Z | 1          |
| B           | 2021-01-16T00:00:00.000Z | 3          |
| B           | 2021-02-01T00:00:00.000Z | 3          |
| C           | 2021-01-01T00:00:00.000Z | 3          |
| C           | 2021-01-01T00:00:00.000Z | 3          |
| C           | 2021-01-07T00:00:00.000Z | 3          |

### Menu Table ###

| product_id | product_name | price |
| ---------- | ------------ | ----- |
| 1          | sushi        | 10    |
| 2          | curry        | 15    |
| 3          | ramen        | 12    |

### Members Table ###

| customer_id | join_date                |
| ----------- | ------------------------ |
| A           | 2021-01-07T00:00:00.000Z |
| B           | 2021-01-09T00:00:00.000Z |

---
