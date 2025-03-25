# Pizzza Pro Analysis

Pizza Pro Analysis aims to uncover insights that enhance there pizza quality and create a unique customer experience.

## Project Overview
Pizza Pro is a growing pizza chain offering a variety of pizza in different sizes and flavors. Specializing in both Classic and gourmet pizzas, it caters to a broad customer base across Urban and Suburban areas in multiple United State cities. The company seeks to improve its pizza quality and ensure a top-tier customer experience through a diverse range of toppings,ingredient and sizes.

## Business Requirement
- KPIs 
  - Total Revenue: The total sales generated from the pizza orders
  - Order Quantity: The total volume of pizzas sold.
  - Total Orders: The total number of overall orders.
    
### Business Problems and Objectives
- Revenue by Pizza Type
  - Requirement: Analyze which pizza types contribute the most to the company's revenue.
  - Objective: Optimize menu offerings by promoting best-selling pizza types. Also, identifying underperforming pizza to either improve or remove from the menu.
- Customer Preferences Based on Pizza Category
  - Requirement: Group pizzas by their category (e.g., Supreme, Chicken) and identify which categories are most popular among customers.
  - Objective: Target promotions towards popular pizza categories and explore cross-selling opportunities with side dishes or beverages.
- Sales Seasonality:
  - Requirement: Identify trends in pizza sales across different times of the year, correlating with holidays, weather changes, and regional events.
  - Objective: Optimize inventory management and marketing strategies based on seasonal trends, ensuring adequate stock during peak demand periods while minimizing waste during slower months.
 
## Data Source
The dataset used for this analysis can be acessed in  Microsoft Excel [download here].(https://www.microsoft.com)
## Tool Used
- Power BI
  - For Data cleaning
  - Data transformation
  - Interactive dashboard creation.
 
## Analysis Methodology
To derive meaningful analysis the following steps were taken
- Data Cleaning

- Analysis Methodology

The dataset, provided as a CSV file, was loaded into Power BI, and the following steps were carried out to prepare it for analysis:

1. Data Cleaning & Preprocessing

Ensured data consistency by correcting misspelled words and filling missing values using the Find and Replace function.

Removed unnecessary columns that were not relevant to the analysis. For instance, the "Hour" column and "Pizza Type ID" were deleted since the "Name" column already provided the necessary information.



2. Data Transformation & Integration

Merged the three tables into a single table for streamlined analysis.

Resolved inconsistencies where columns with the same names in different tables did not match.

Added a calculated column to categorize time into Morning, Afternoon, and Night based on the time values.

Created a calendar table to support time-based analysis and ensured proper data connections in the data model.



3. Loading Data into Power BI

After cleaning and transforming the dataset, the Close & Apply function was used to load the final table into Power BI.



4. Dashboard Creation

Developed an interactive dashboard to answer the business questions, visualizing key insights to support decision-making.




This structured approach ensured that the dataset was well-prepared for in-depth analysis, enabling accurate insights into Pizza Pro’s sales, customer preferences, and operational efficiency.
