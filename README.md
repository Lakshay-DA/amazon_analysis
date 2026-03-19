Amazon E-commerce Sales Analysis

This project focuses on analyzing Amazon product data to uncover insights related to pricing, discounts, customer ratings, and product demand. The goal is to understand customer behavior and identify patterns that can help in business decision-making.
 
Project Overview

In this project, we performed:

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Visualization of key business metrics

Insight generation from product data

The analysis highlights how pricing, discounts, and product categories influence customer engagement and satisfaction.

Tech Stack

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Dataset

Source: Amazon product dataset (CSV file)

Contains information such as:

Product name

Price

Discount percentage

Ratings

Rating count

Category

Data Cleaning

Key preprocessing steps included:

Handling missing values in rating_count

Extracting numeric values from text-based columns

Converting data types for analysis

Removing inconsistencies in dataset

 Analysis & Insights
 Rating Distribution

Most products have ratings between 4.0 and 4.5

 Price Distribution

Majority of products fall in the ₹200 – ₹1000 range

 Discount vs Rating

No strong relationship between discounts and ratings

Discounts do not significantly impact customer satisfaction

 Top Reviewed Products

Highly reviewed products are mostly from:

Electronics

Accessories

Indicates high demand in these categories

 Correlation Analysis

Weak correlation between discount and rating

Pricing and ratings are not strongly dependent

 Category Analysis

Certain categories dominate in both reviews and sales activity

 Key Takeaways

High discounts ≠ High ratings

Customer satisfaction is driven more by product quality than price cuts

Electronics category has the highest engagement

Mid-range pricing (₹200–₹1000) is the most popular

 Visualizations Included

Rating Distribution Plot

Price Distribution Plot

Discount vs Rating Scatter Plot

Top Reviewed Products Chart

Correlation Heatmap

Category Analysis

 How to Run
# Clone the repository
git clone https://github.com/your-username/amazon-sales-analysis.git

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run the notebook
jupyter notebook
🙌 Author

Lakshay
Aspiring Data Analyst | Learning SQL, Python & Power BI
