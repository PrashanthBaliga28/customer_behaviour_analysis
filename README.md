📊 Customer Shopping Behaviour Analysis
Overview

This project analyzes customer shopping behaviour using transactional data to uncover insights into spending patterns, customer segments, product performance, and subscription behaviour. The analysis follows a complete data analytics workflow, from data preparation and exploration in Python to SQL analysis in PostgreSQL and visualization in Power BI, with findings presented through a report and a Gamma presentation.

Dataset

Records: 3,900 customer purchases

Columns: 18

Format: CSV

Key Data Areas

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Product, Category, Amount, Season, Size, Colour

Shopping Behaviour: Discounts, Purchase Frequency, Review Rating, Shipping Type

Data Quality

37 missing values in the review_rating column

Missing ratings were imputed using the median rating by product category

Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn)

PostgreSQL

SQL

Power BI

Jupyter Notebook

Gamma (Presentation)

Project Steps
1. Data Loading & EDA (Python)

Loaded the dataset using Pandas

Explored data structure and summary statistics

Identified missing values and inconsistencies

2. Data Cleaning & Feature Engineering

Imputed missing review ratings

Standardized column names to snake_case

Created new features such as:

Age groups

Purchase frequency metrics

Removed redundant columns after validation

3. SQL Analysis (PostgreSQL)

Loaded cleaned data into PostgreSQL

Ran SQL queries to analyze:

Revenue by gender

High-spending discount users

Top-rated and best-selling products

Shipping type impact on spending

Subscribers vs. non-subscribers

Customer segmentation (New, Returning, Loyal)

Revenue contribution by age group

Power BI Dashboard

The Power BI dashboard provides:

Key performance indicators (KPIs)

Customer segmentation insights

Product and category performance

Interactive filters for deeper analysis

Results & Insights

Identified high-value customer segments and repeat buyers

Highlighted products heavily reliant on discounts

Found meaningful differences between subscriber and non-subscriber spending

Revealed age groups contributing the most to total revenue

How to Run the Project

Clone the repository:

git clone <repository-url>


Install Python dependencies:

pip install -r requirements.txt


Run the Jupyter notebooks for EDA and data cleaning.

Load the cleaned dataset into PostgreSQL.

Execute SQL scripts for analysis.

Open the Power BI file to explore the dashboard.

Review the report and Gamma presentation for final insights.

Author

Prashanth Baliga
Data Analyst | Python | SQL | Power BI
