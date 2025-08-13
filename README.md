# Maven Cycles: Global Sales & Profitability Analysis Dashboard

**Executive Summary:** This project provides a comprehensive dashboard and analysis to identify and improve sales performance and profitability for a global company.

## Project Overview

This project is a comprehensive sales and profitability analysis for a fictional company, Maven Cycles. The analysis was built as a self-driven extension of my foundational Power BI learning. The primary objective was to move beyond basic reporting and demonstrate my ability to generate deeper, actionable business insights using advanced features and a logical narrative flow.

The final dashboard and analysis were created to answer critical business questions and identify key trends in sales, profitability, and customer behavior.

## Key Business Questions Answered

1.  What is our overall revenue performance against set targets?
2.  How do we identify our most and least profitable product categories and their impact on total revenue?
3.  Which customer demographics are our primary revenue drivers?
4.  How do sales and profitability compare across different global regions?
5.  Which were the top 10 products by quantity sold and total revenue?
6.  What are the key influencers behind an increase in product quantity sold?

## Project Methodology

### **1. Data Cleaning & Preparation**

The raw data was provided in multiple CSV files. I used Power Query Editor to perform the following steps, ensuring data was clean and fit for analysis:
* Renamed columns for clarity and consistency.
* Changed data types for proper formatting of dates, numbers, and text.
* Removed duplicate rows to maintain data integrity.
* Used **data profiling, grouping, and aggregation** to consolidate and validate the dataset.
* Created a custom **'Calendar' table** using DAX for proper time intelligence functions.

### **2. Data Modeling**

I built a robust data model to create logical relationships between the different tables. The model was structured connecting a central `Sales` fact table to multiple dimension tables including `Products`, `Customers`, `Age Group`, `Region`, `Categories`, `Sub Categories`, `Gender`, and the `Calendar` table. This advanced structure ensured efficient and accurate cross-filtering across all visuals. 

### **3. Advanced DAX Functions**

I developed several custom DAX measures to create key insights in the dashboard, demonstrating proficiency with complex functions:
* **KPIs:** Created measures for `Total Revenue`, `Profit Margin %`, and `Total Profit` to track core business performance.
* **Time Intelligence:** Utilized functions like `CALCULATE` and `SAMEPERIODLASTYEAR` to calculate `Year-over-Year Revenue % Change`.
* **Dynamic Messages:** An `IF` statement with variables was used to create a dynamic text box that informs stakeholders if sales are "On track" or "Falling behind" a specific revenue target.
* **Ranking:** Used ranking functions to identify the **top 10 products by both quantity sold and revenue**, allowing for granular analysis.

### **4. Data Visualization & Insights**

The dashboard was designed with a clear narrative flow to answer the business questions. Key visualizations include:
* **Decomposition Tree & Key Influencers:** These advanced visuals were used to perform root cause analysis and identify what factors influence an increase in product quantity sold, which I found to be primarily the 'Accessories' product category.
* **Q&A for Natural Language Analysis:** Enabled the Q&A feature to allow end-users to ask natural language questions and receive quick, data-driven answers, demonstrating an understanding of self-service BI.
* **Treemap Chart:** Visualized `Revenue by Region` to show the geographical distribution of sales, highlighting the dominance of the USA market.
* **Combo Chart:** A dual-axis combo chart was built to analyze `Profit Margin` and `Total Revenue`, revealing that high-revenue products like 'Road Bikes' have a disproportionately low profit margin, a critical area for business review.
* **Time-Series Analysis:** A line chart with a dual-axis was used to track `Revenue` and `Profit` over time, revealing seasonal trends and historical performance.

## Key Insights & Business Answers
- The **combo chart is the centerpiece** of this analysis, revealing that high-revenue products like **'Road Bikes' and 'Jerseys' have the lowest profit margins**, which suggests a need for further investigation into our pricing strategy or cost of goods for these categories.
- The **Key Influencers visual identified 'Accessories' as the top factor** influencing an increase in quantity sold, which can inform inventory and marketing strategies to capitalize on this trend.
- The **Treemap shows the USA is our most dominant market**, while the **Pie Chart identifies 'Adults (35-64)' as our most valuable customer segment**, providing a clear picture of our primary business drivers that can inform targeted marketing efforts.
- The **Q&A feature empowers stakeholders** to perform their own ad-hoc analysis, increasing the self-service capability of the report.

## The Final Dashboard
_The 'Executive View' tab of this dashboard was a guided project. However, the 'Global Sales' tab and the advanced analysis tabs were built by me from scratch to extend the project and demonstrate my independent skills._


## Conclusion & What I Learned
This project was a journey from guided learning to independent analysis. It helped me solidify my foundational skills while challenging me to think critically about how to translate data into a compelling business narrative using both core and advanced Power BI features.

---
_Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/arman262/)/) to discuss this project further._
