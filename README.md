### Superstore Sales Dashboard | Power BI

An interactive business intelligence dashboard analyzing sales, profit, and customer trends across the United States from 2014 to 2017.

# Overview

This project presents a comprehensive Sales Analytics Dashboard built using Power BI on the popular Superstore dataset. The dashboard enables stakeholders to quickly identify top-performing product categories, monitor profit trends over time, track monthly revenue fluctuations, and pinpoint high-value customers — all through dynamic, filterable visuals.

# Problem Statement

Retail businesses often struggle to extract actionable insights from raw transactional data. The goal of this project is to:

Identify which product categories and sub-categories drive the most revenue
Understand profit trends across years and categories
Pinpoint geographic regions with the highest sales concentration
Discover the top customers contributing to profitability
Analyze monthly sales patterns to support inventory and staffing decisions


# Dataset

|     Property      |     Details         |
|-------------------|---------------------|
|    NameSample     |  Superstore Dataset |
|    Key Columns    |  Order ID, Order Date, Ship Mode, Customer Name, Segment, State, Category, Sub-Category, Sales, Quantity, Discount, Profit |

# Tools & Technologies

|        Tool         |         Purpose                                           |
|---------------------|-----------------------------------------------------------|
|  Microsoft Excel    |   Dashboard design, data cleaning, and all visualizations |
|  Excel Pivot Tables | Data aggregation by category, region, customer, and time  |
|  Excel Charts       | Bar charts, line charts, pie charts, and area charts      | 
|  Excel Slicers      | Interactive filters for Category and Year                 |

# Methods

|     Methods         |                         Purpose                                     |
|---------------------|---------------------------------------------------------------------|
|    Data Import      | Loaded the raw CSV into Excel and formatted it as a structured Table|
|    Data Cleaning    | Removed duplicates, fixed date formats, filled missing values, and standardized category names|
|    Pivot Tables     | Created multiple pivot tables to summarize Sales, Profit, and Count by Category, Sub-Category, State, Customer, and Month|
|    Charts           | Built linked charts from pivot tables (bar, line, pie, area) directly on the dashboard sheet|
|    Slicers          | Added Category and Year slicers connected to all pivot tables for cross-filtering |

# Key Insights

1. Phones are the highest revenue-generating sub-category at $330,007, closely followed by Chairs ($328,167).  
2. Technology consistently shows the steepest profit growth year-over-year from 2014 to 2017.  
3. California dominates sales by state, reaching up to $457,687 in total sales.  
4. The Top 5 customers collectively contribute a significant share of total profit, highlighting the importance of key account management.  
5. Monthly sales peak sharply toward Q4 (November–December), suggesting strong seasonal demand.  
6. Furniture shows relatively flat profit growth despite high sales volume, indicating margin compression.  

# Dashboard / Output

 ![Sales Dashboard Preview](./dashboard_preview.png)  

The Excel dashboard includes the following panels:

|             PanelChart           |         Type           |                    Description                       |
|----------------------------------|------------------------|------------------------------------------------------|
|   Sales By Category              | Horizontal Bar Chart   |  Ranks all sub-categories by total sales             |
|   Profit Gained Over Time        | Line Chart             |  Tracks profit trends for each category (2014–2017)  |
|   Sales By State                 | Filled Map Chart       |  Shows sales intensity across US states              |
|   Top 5 Customers Making Profit  | Pie Chart              |  Highlights the highest-profit customers             |
|   Monthly Sales                  | Area Chart             |  Reveals seasonal sales patterns across the year     |


# Results & Conclusion

The Superstore Sales Dashboard successfully surfaces key business trends hidden within raw transactional data. The analysis confirms that Technology is the most profitable category, Q4 seasonality is a significant revenue driver, and geographic concentration in California, New York, and Texas presents both opportunity and risk. The dashboard empowers decision-makers to act on data rather than intuition.

# Author & Contact
KRISHNA

LinkedIn: https://www.linkedin.com/in/krishna-krishna-26a106231/

