# customer_behavior_analysis
Customer Behavior Analysis using Python, MySQL, and Power BI

# Dashboard Preview
<img width="1332" height="738" alt="Screenshot 2026-03-16 201937" src="https://github.com/user-attachments/assets/7c937555-da3f-4e86-892c-42e83fbfc94f" />

This project focuses on analyzing customer shopping behavior to generate business insights and support data-driven decision-making.

# Step 1: Data Processing (Python)
- Loaded and explored the dataset using pandas
- Performed data cleaning and preprocessing
- Handled missing values in review_rating
- Standardized column names for consistency
- Created new features such as age_group and purchase_frequency_days

# Step 2: Database Integration (MySQL)
- Created a MySQL database (shopping_project)
- Connected Python to MySQL using SQLAlchemy
- Loaded the cleaned dataset into a MySQL table (customer)

# Step 3: SQL Analysis
Performed business analysis using SQL queries:
- Revenue comparison by gender
- Identified high-spending customers using discounts
- Top 5 products based on average review rating
- Comparison of purchase amount across shipping types
- Subscriber vs non-subscriber revenue analysis
- Customer segmentation (New, Returning, Loyal)
- Top products within each category
- Repeat buyers vs subscription behavior
- Revenue contribution by age group

# Step 4: Data Visualization (Power BI)
- Built an interactive dashboard
- KPIs: Total Customers, Total Revenue, Average Purchase Amount, Average Review Rating
- Visualizations:
  • Revenue by category
  • Sales by category
  • Revenue by age group
  • Sales by age group
- Added filters for gender, category, subscription status, and shipping type

# Step 5: Key Insights
- Clothing category generated the highest revenue
- Young Adult customers contributed the most revenue
- Majority of customers were non-subscribers
- Discounts significantly influenced purchase behavior

# Step 6: Business Recommendations
- Increase subscription adoption through exclusive benefits
- Implement loyalty programs for repeat customers
- Promote high-performing product categories
- Optimize discount strategies
- Target high-value customer segments

# Tools Used:
  Python (Pandas), MySQL, Power BI
