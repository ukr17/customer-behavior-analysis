Customer Shopping Behavior Analysis
Project Overview
This project provides an end-to-end data analysis of 3,900 customer transactions. The goal was to uncover spending patterns, customer segments, and product preferences to guide strategic business decisions. The project covers the full data lifecycle: from cleaning and feature engineering to database management and interactive visualization.

Key Insights
Total Revenue: $233K.

Customer Loyalty: 3,116 loyal customers out of 3,900.

Subscription Behavior: 27% of customers are subscribers.

Key Demographic: Young Adults drive the highest revenue across all age groups.

Technical Stack
Language: Python (Pandas for EDA and data manipulation).

Database: SQL Server (for data storage and querying).

Visualization: Power BI (interactive dashboard for business reporting).

Pipeline Steps
Data Loading: Ingested raw transaction data using Python/Pandas.

Exploratory Data Analysis (EDA): Performed initial exploration using df.info() and df.describe() to understand data structure and distribution.

Data Cleaning: Handled 37 missing values in the "Review Rating" column through median imputation.

Feature Engineering: Created new features such as age_group and purchase_frequency_days to provide deeper insights.

Database Integration: Loaded the cleaned and transformed dataset into SQL Server for efficient storage and querying.

Visualization: Built an interactive dashboard in Power BI to track sales, tender types, and customer segments.

Project Presentation
For a detailed breakdown of the methodology and business recommendations, you can view the full project presentation here: Customer-Shopping-Behavior-Analysis.pdf
