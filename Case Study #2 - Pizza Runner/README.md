
# Case Study #2: Pizza Runner

<img src="https://user-images.githubusercontent.com/81607668/127271856-3c0d5b4a-baab-472c-9e24-3c1e3c3359b2.png" alt="Image" width="500" height="520">

## 📚 Table of Contents
- [Business Task](#business-task)
- [Entity Relationship Diagram](#entity-relationship-diagram)
- Solution
  - [Data Cleaning and Transformation](#-data-cleaning--transformation)
  - [A. Pizza Metrics](#a-pizza-metrics)
  - [B. Runner and Customer Experience](#b-runner-and-customer-experience)
  - [C. Ingredient Optimisation](#c-ingredient-optimisation)
  - [D. Pricing and Ratings](#d-pricing-and-ratings)

## Business Task
Danny wants to expand his new Pizza Empire so he had one genius idea to combine with it, he was going to Uberize it and, so Pizza Runner was launched!

Danny started by recruiting “runners” to deliver fresh pizza from Pizza Runner Headquarters (otherwise known as Danny’s house) and also maxed out his credit card to pay freelance developers to build a mobile app to accept orders from customers.
## Entity Relationship Diagram

![Pizza Runner](https://github-production-user-asset-6210df.s3.amazonaws.com/81607668/242152356-78099a4e-4d0e-421f-a560-b72e4321f530.png)

## Data Cleaning and Transformation
### Table: customer_orders

The below `customer_orders` given, we can see that there are
- In the exclusions column, there are blank spaces ' ' and null values.
- In the extras column, there are blank spaces ' ' and null values.
  
We need to clean the table:
- Create a temporary table with all the columns
- Remove null values in `exlusions` and `extras` columns and replace with blank space ' '.
<img width="1063" alt="image" src="https://user-images.githubusercontent.com/81607668/129472388-86e60221-7107-4751-983f-4ab9d9ce75f0.png">
