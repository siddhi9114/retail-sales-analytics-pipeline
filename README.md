# retail-sales-analytics-pipeline
End-to-End Retail Sales Analytics Pipeline using Python, MySQL, Machine Learning, and Power BI. The project performs data cleaning, exploratory data analysis, SQL-based business insights, and builds a sales prediction model to forecast future sales trends, with results visualized through an interactive Power BI dashboard.


**Tech Stack**

Tools  	                        Purpose

Python                  	Data Cleaning \& Analysis

Pandas / NumPy	          Data preprocessing

Matplotlib / Seaborn    	Data visualization

MySQL          	          Business data analysis

Scikit-Learn	            Machine learning model

Power BI	                Interactive dashboard

GitHub	                   Project version control


**DataSet** :

The dataset contains retail sales transaction records including:
Order ID
Customer ID
Product Category
Sales
Profit
Region
Order Date
Quantity

Total records: \~10,000+ transactions

**Project Architecture**

Raw Dataset

&#x20;    ↓
Python Data Cleaning

&#x20;    ↓
Exploratory Data Analysis

&#x20;    ↓
MySQL Business Queries

&#x20;    ↓
Machine Learning Model

&#x20;    ↓
Power BI Dashboard


###### **Data Cleaning**
Performed using Python Pandas:
• Converted date columns to datetime format
• Removed duplicate records
• Handled missing values
• Standardized column names
• Created new features such as Year and Month

###### **Exploratory Data Analysis :**
EDA was performed using Matplotlib and Seaborn to understand patterns in the dataset.

Key analyses included:
• Monthly sales trends
• Regional sales performance
• Category-wise profit distribution
• Top selling products

Example insight:
Sales show a significant increase during the November–December holiday season.

**SQL Business Analysis** :
Data was stored in MySQL to perform business queries.

Examples:
i. Top 10 Products by Revenue
ii. Region Wise Sales

**Machine Learning Models**
A Random Forest Regression model was developed to predict sales.
Features used:

Month
Region
Category
Quantity
Discount

Target variable:
Sales

Model performance was evaluated using Mean Squared Error (MSE).

**Power BI Dashboard**
An interactive dashboard was created to visualize business insights.

Key dashboard components:
• Total Revenue KPI
• Total Profit KPI
• Sales by Region
• Monthly Revenue Trend
• Top Products
• Customer Segments

**Business Insights**
• West region generates the highest revenue
• Technology category has the highest profit margin
• Sales peak during holiday seasons
• A small group of customers contributes a large portion of revenue
