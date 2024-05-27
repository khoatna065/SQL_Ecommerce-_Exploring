# SQL_Ecommerce_Exploring
# 1. Introduction

The eCommerce dataset is stored in a public Google BigQuery dataset. This dataset contains information about user sessions on a website collected from Google Analytics in 2017.

Based on the eCommerce dataset, the author perform queries to analyze website activity in 2017, such as calculating bounce rate, identifying days with the highest revenue, analyzing user behavior on pages, and various other types of analysis. This project aims to have an outlook on the business situation, marketing activity efficiency analyzing the products.

To query and work with this dataset, the author uses the Google BigQuery tool to write and execute SQL queries.

# 2. The goal of creating this project

- Overview of website activity
- Bounce rate analysis
- Revenue analysis
- Transactions analysis
- Products analysis

# 3. Import raw data

The eCommerce dataset is stored in a public Google BigQuery dataset. To access the dataset, follow these steps:

- Log in to your Google Cloud Platform account and create a new project.
- Navigate to the BigQuery console and select your newly created project.
- Select "Add Data" in the navigation panel and then "Search a project".
- Enter the project ID **"bigquery-public-data.google_analytics_sample.ga_sessions"** and click "Enter".
- Click on the **"ga_sessions_"** table to open it.

# 4. Business question

-  Calculate total visit, pageview, transaction for Jan, Feb and March 2017 (order by month)
-  Bounce rate per traffic source in July 2017 
-  Revenue by traffic source by week, by month in June 2017
-  Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017.
-  Average number of transactions per user that made a purchase in July 2017
-  Average amount of money spent per session. Only include purchaser data in July 2017
-  Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017. Output should show product name and the quantity was ordered.
