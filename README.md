# Inventory-management
The analysis aims to help businesses optimize their inventory, reduce costs, and improve overall supply chain efficiency

# Inventory Management Analysis Dashboard
1. Project Overview
Description: This project involves the development of an interactive dashboard to analyze and visualize key aspects of inventory management. The dashboard provides insights into stock levels, valuation, reordering needs, and supplier performance. The analysis aims to help businesses optimize their inventory, reduce costs, and improve overall supply chain efficiency.

Purpose: The primary purposes of this project are to:
- Provide a comprehensive overview of inventory status.
- Identify areas for improvement in inventory management practices.
- Enable stakeholders to make data-driven decisions related to stock levels, reordering, and supplier relationships.
- Visualize key inventory metrics and trends.

Target Audience: This dashboard is designed for a broad audience, including:
- Inventory managers
- Supply chain analysts
- Operations managers
- Procurement teams
- Business stakeholders

2. Skills Demonstrated
This project showcases the following data analyst skills:
- Data Visualization: Designing and creating effective visualizations using Power BI to communicate complex inventory data.
- Data Analysis: Analyzing inventory data to identify trends, patterns, and areas for optimization.
- KPI Development: Defining and calculating key performance indicators (KPIs) relevant to inventory management.
- Dashboard Design: Creating a user-friendly and interactive dashboard that facilitates data exploration.
- Data Interpretation: Interpreting visualizations and KPIs to provide actionable insights and recommendations.
- Data Transformation: Preparing the data for analysis, including cleaning, transforming, and loading it into Power BI.

3. Project Details
Tools Used:
- Power BI Desktop: For data connection, modeling, DAX calculations, and dashboard creation.
- Data Sources: 
Sample inventory management data, including product information (product ID, product name, category), stock levels, pricing, supplier details, and date information.

Key Metrics Analyzed:
- Total Products
- Inventory Value($)
- Stock Quantity
- Average Lead Time
- Month with the Highest Stock
- Turnover Rate by Category
- Products Category in Urgent Need of Reorder
- Count of Stock Age Category by Stock

Visualizations Created: 
- KPI cards: Displaying key metrics such as total products, inventory value, stock quantity, and average lead time.
- Line chart: Visualizing the month with the highest stock, March has the highest restock with 450 items while February has the lowest 384 for the product
- Bar chart: Showing the top 5 most expensive products, product 3413 is the most expensive product and also has the highest quantity of product in stock as well.
- Bar chart: Displaying the turnover rate by category, the turnover which was based on stock quantity and lead time, sports and office supplies have the highest and lowest turnover rate respectively.
- Table and bar chart: Listing product categories in urgent need of reorder.
- Donut chart: Showing the count of stock age category, how long the products have been in store since last restock date.

 4. Data Preparation 
Data Cleaning: (Describe cleaning steps. Example below)
- Ensured data consistency in category names.
Data Transformation:
- Calculated inventory value by multiplying stock quantity by unit price.
- Categorized stock age based on the last restock date.
- Created a calculated column for stock age and quantity below reorder point(1,0) using the IF statement, goods less than 3 months are "Fresh goods" while goods between 3 - 7 months are termed "Aging goods" etc
Data Loading: 
The cleaned and transformed data was loaded into Power BI Desktop using the "Get Data" functionality.

5. Dashboard Highlights
- Inventory Overview: Provides a high-level summary of the inventory with key metrics.
- Stock Analysis: Offers insights into stock levels, product value, and turnover rates.
- Reorder Management: Highlights categories that need urgent reordering.
- Stock Aging: Visualizes the distribution of stock across different age categories.
- Actionable Insights: Delivers insights to inform decisions related to inventory optimization, reordering, and supplier management.

6. Challenges and Solutions
- Challenge: Determining the appropriate timeframes for stock age categorization (e.g., fresh, old, aging).
  Solution: Researched industry best practices and consulted with stakeholders to define relevant timeframes.
- Challenge: Calculating accurate turnover rates without detailed sales history.
  Solution:Used available data to estimate turnover and clearly communicated the limitations of this approach.

7. Recommendation
- Aging Stock Management: A significant portion of the inventory is aging, indicating a potential need for targeted sales or markdown strategies to minimize losses.
- Reorder Prioritization: Focusing on the "Books," "Office Supplies" and "Clothing" categories, which are in urgent need of reorder, will ensure timely replenishment and prevent stockouts.
- Lead Time Optimization: Analyzing lead times can help in negotiating better terms with suppliers or exploring alternative sourcing options to reduce delays.
