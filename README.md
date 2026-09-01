# E-Commerce Cohort Analysis

A cohort analysis of one year of online orders (October 2020 - September 2021), 
looking at how customers behave over time: how much revenue each cohort brings in, 
how many customers come back, and how fast retention drops off.

## What's inside

- **Monthly cohort analysis** - new customers, orders, and revenue per cohort, 
  plus ARPU (Average Revenue Per User) across each cohort's lifetime.
- **Weekly retention & churn analysis** - how many customers from each weekly 
  cohort are still buying, week by week.
- **Deeper analysis** - whether the big December sale attracts less loyal customers, 
  and which product categories drive repeat purchases.

## Key findings

- Only about **6.5% of first-time customers** come back to buy again the following week.
- New customer growth is driven by big promotional spikes (like December 2020), 
  not steady organic growth.
- High ARPU in later cohort months is mostly a survivorship effect - the customers 
  who stick around tend to be the highest spenders, which pulls the average up.
- Around 39% of all orders in the raw data are canceled - a separate issue worth 
  investigating on its own.

Full write-up, charts, and business recommendations are in the notebook.

## Data

The dataset (`sales.csv`) is an e-commerce order log with order, product, and 
customer information. Only business-relevant columns (order id, date, status, 
price, quantity, discount, category, payment method, customer id) are used in 
the analysis — no personal information is processed or displayed.

## Tools

- Python
- pandas / numpy
- matplotlib / seaborn
