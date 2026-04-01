# Customer-Behavior-Data-Analysis-Python-SQL-PowerBI-

🛍️ Customer Shopping Behavior Analysis
📌 Project Overview
This project focuses on analyzing customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The main goal is to uncover meaningful insights into:
* Customer spending patterns
* Product preferences
* Customer segmentation
* Subscription behavior

These insights help businesses make better data-driven decisions.

📊 Dataset Summary
Total Rows: 3,900
Total Columns: 18

Key Features:
Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Behavioral Data:
Discount Applied
Promo Code Used
Previous Purchases
Purchase Frequency
Review Rating
Shipping Type

Missing Values:
37 missing values in the Review Rating column
🧹 Data Cleaning & EDA (Python)

Performed using Python (Pandas, NumPy):
Loaded dataset using pandas

Explored data using:
df.info()
df.describe()

Handled missing values:
Imputed Review Rating using median per category
Standardized column names (snake_case)

Feature Engineering:
Created age_group
Created purchase_frequency_days

Removed redundant column:
Dropped promo_code_used

Connected to PostgreSQL and stored cleaned data for further analysis
🗄️ Data Analysis (SQL - PostgreSQL)

Key business questions answered:
Revenue comparison by gender
High-spending customers using discounts
Top 5 highest-rated products
Impact of shipping type on purchase amount
Subscribers vs non-subscribers comparison
Products heavily dependent on discounts

Customer segmentation:
New
Returning
Loyal
Top 3 products in each category
Relationship between repeat buyers and subscriptions
Revenue contribution by age group

📈 Power BI Dashboard
An interactive dashboard was created to visualize:
Revenue trends
Customer segmentation
Product performance
Subscription insights

This makes it easy for stakeholders to understand and explore the data.

💡 Business Recommendations
* Boost Subscriptions
* Offer exclusive deals and benefits
* Customer Loyalty Programs
* Reward repeat customers
* Optimize Discount Strategy
* Balance between sales growth and profit margins
* Product Positioning
* Promote top-rated and best-selling items
* Targeted Marketing
* Focus on high-value age groups and express-shipping users

🛠️ Tools & Technologies Used
* Python (Pandas, NumPy)
* PostgreSQL (SQL)
* Power BI
* Jupyter Notebook
