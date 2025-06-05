# Sakila DVD Rental Business Analysis (MySQL Project)

## Project Overview

This project explores the Sakila DVD Rental Database using MySQL to uncover actionable insights that can help improve business performance. We analyze customer behavior, film performance, staff efficiency, and store-level trends.

The dataset includes details about:

- Customers, rentals, and payments  
- Film categories, inventory, and pricing  
- Store locations and staff members

Using SQL joins, window functions, CTEs, aggregates, and case logic, we answer 20 data-driven business questions and form conclusions that drive strategic recommendations.

## Problem Statement

Sakila Inc. wants to scale its DVD rental business by:

- Retaining high-value customers  
- Optimizing its film catalog  
- Improving operational efficiency across stores  

Through structured SQL analysis, we aim to help Sakila make informed decisions about customer loyalty, inventory management, pricing strategy, and employee performance.

## Summary of Findings

- 584 active customers drive the core business, with 543 of them renting more than 20 times.
- Total rental revenue amounts to 67,406.56 — mostly from loyal repeat customers.
- The film ‘Telegraph Voyage’ earned 231.73, topping the revenue charts.
- Genres like Action and Animation average 3.9+ per rental, while Games has the highest rate at 3.25.
- 43 films were never rented — indicating content that may need to be removed or re-promoted.
- Out of all rentals, 8,592 were returned on time, while 7,269 were late, suggesting a nearly 46% delay rate.
- Staff Mike and Jon generate nearly equal revenue (33,482.50 vs. 33,924.06).
- Store 2 earns more revenue, but Store 1 processes more rentals, pointing to volume vs. value tradeoffs.
- Rentals peak in February, suggesting seasonal marketing opportunities.
- A churn analysis revealed 158 customers were active in Q1 but dropped off by Q3/Q4.
- Karl Seal paid the most in late fees (157.75) — perhaps a candidate for retention incentives.

## Recommendations for Stakeholders

1. **Nurture Loyal Customers**  
   Launch a VIP or loyalty program for the 543 high-frequency renters to increase engagement and lifetime value.

2. **Prune Dead Inventory**  
   Remove or repackage the 43 unrented films. Reinvest in genres like Action, Animation, and Games, which are proven revenue drivers.

3. **Fix the Late Return Problem**  
   Introduce SMS/email return reminders or offer grace periods to address the high late-return rate (~46%).

4. **Maximize Store Performance**  
   Analyze why Store 2 earns more per rental and why Store 1 drives higher volume. Use findings to improve both locations.

5. **Target Churned Customers**  
   Re-engage the 158 churned users with offers, emails, or exit surveys to bring them back.

6. **Capitalize on Peak Periods**  
   Since rentals peak in February, align campaigns and promotions with this trend to increase impact.
