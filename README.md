# customer-behavior-analysis
Data Analysis showing customer behavior using Power BI, SQL and Python 

 Customer Shopping Behavior Analysis
Project Overview
This project analyzes customer shopping behavior using Python, SQL Server, and Power BI.
Objectives
The main goal is to extract insights such as:

Customer spending patterns
Product performance
Impact of discounts
Subscription behavior


Step-by-Step Workflow
 Step 1: Load Data in Python

Imported dataset using Pandas for initial exploration and processing.


 Step 2: Data Cleaning & Preprocessing
Performed multiple data cleaning and feature engineering steps:


Handle Missing Values

Filled missing review ratings using the median value by category



Standardize Column Names

Converted all column names to lowercase
Replaced spaces with underscores



Rename Columns

Renamed columns for better clarity and consistency



Create Age Groups

Segmented customers into groups like:

Young Adults
Adults
Middle-aged
Seniors





Convert Purchase Frequency

Transformed categorical frequency values into numeric days



Remove Redundant Columns

Dropped unnecessary columns to simplify the dataset




 Step 3: Load Data into SQL Server


Create Connection

Connected Python to SQL Server (SQL Express) using SQLAlchemy



Upload Table

Exported cleaned dataset into SQL Server as a table (customer)




 Step 4: SQL Analysis
Performed key business queries to extract insights:

Revenue by gender
High-value customers
Product ratings
Shipping comparison (Standard vs Express)
Subscription impact on spending
Discount trends
Customer segmentation (New, Returning, Loyal)
Top products per category


 Step 5: Power BI Dashboard

Connected Power BI directly to SQL Server
Built an interactive dashboard for visualization

 Dashboard Includes:

Revenue KPIs
Customer segmentation charts
Product performance visuals
Discount analysis
Subscription insights





