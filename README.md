# customer_behavior_analysis
data analytics project showcasing customer behavoir analysis using Python,SQL and Power BI
Data Analytics Project – Python, SQL & Power BI
Overview

This project demonstrates an end-to-end data analytics workflow using Python, SQL, and Power BI. The process covers loading and exploring data in Python, cleaning and preparing it, storing it in a SQL database, creating SQL views for analysis, and finally building an interactive Power BI dashboard.

Dataset

Source: Public / provided dataset

Format: CSV

Description: The dataset contains structured records used to analyze trends, patterns, and key business metrics.

Notes: Data quality issues such as missing values and inconsistent formats were handled during data cleaning.

Tools & Technologies

Python (Pandas, NumPy, Matplotlib / Seaborn)

SQL (data storage and views)

Jupyter Notebook

Power BI

Git / GitHub

Project Workflow
1. Data Loading (Python)

Loaded the raw dataset into Python using Pandas

Inspected structure, data types, and basic statistics

2. Exploratory Data Analysis (EDA)

Analyzed distributions, trends, and relationships

Identified data quality issues and outliers

Created exploratory visualizations

3. Data Cleaning & Transformation

Handled missing values and duplicates

Standardized column names and formats

Created derived columns where needed

4. Load Data into SQL

Inserted the cleaned dataset into a SQL database from Python

Validated row counts and data integrity

5. SQL Views for Analytics

Created SQL views to:

Apply business logic

Aggregate key metrics

Prepare reporting-ready tables

Ensured views were optimized for reporting and reuse

6. Power BI Dashboard

Connected Power BI to SQL views

Built a structured and interactive dashboard

Designed visuals for clarity and business relevance

Dashboard Highlights

High-level KPIs

Trend analysis over time

Category and segment comparisons

Interactive filters and slicers

Results & Insights

Transformed raw data into analysis-ready datasets

Centralized business logic using SQL views

Delivered clear, actionable insights through Power BI

How to Run the Project
Python & SQL

Clone the repository:

git clone <repository-url>


Open the Jupyter Notebook

Install required libraries:

pip install pandas numpy matplotlib seaborn sqlalchemy


Update database connection details

Run the notebook to clean the data and load it into SQL

Power BI

Open the .pbix file in Power BI Desktop

Connect to the SQL database (or refresh the connection)

Refresh the dataset and explore the dashboard
