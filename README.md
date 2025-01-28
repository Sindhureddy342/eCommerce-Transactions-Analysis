# eCommerce-Transactions-Analysis
Analyzed eCommerce transaction data to derive business insights, build a lookalike model, and perform customer segmentation.

**README File**  

This project analyzes an eCommerce transactions dataset to extract business insights, build customer recommendation models, and perform customer segmentation. Below is a simple overview of what the project does:  

1. Objective: The goal is to understand customer behavior, identify high-value products, and group customers into meaningful segments for targeted marketing strategies.  

2. Datasets Used:  
   - Customers.csv: Contains customer details like ID, name, region, and signup date.  
   - Products.csv: Lists product information including ID, name, category, and price.  
   - Transactions.csv: Records transaction details such as transaction date, quantity purchased, and total value.  

3.  Exploratory Data Analysis (EDA):  
    Explored sales trends, customer demographics, and product performance.  
   - Found insights like "Electronics is the top-selling category" and "North American customers spend 30% more than other regions."  

4.  Lookalike Model:  
   - Built a model to recommend similar customers. For example, if Customer C0001 buys sports gear, the model finds 3 other customers with similar buying habits.  
   - Similarity scores (e.g., 0.85 out of 1) show how closely matched customers are.  

5. Customer Segmentation:  
   - Grouped customers into 5 clusters using their purchase history and demographics.  
   - Key segments include "High-Value Customers" (big spenders) and "Bargain Shoppers" (bulk buyers on a budget).  

6. Tools and Libraries:  
   - Python, Pandas (for data processing), Scikit-learn (for machine learning), and Matplotlib/Seaborn (for visualizations).  

7. Key Results:  
   - High-value customers (15% of the base) drive 45% of total revenue.  
   - Bargain shoppers prefer bulk purchases but avoid premium products.  
