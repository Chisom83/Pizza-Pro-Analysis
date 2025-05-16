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
The dataset, provided as a CSV file, was loaded into Power BI, and the following steps were carried out to prepare it for analysis.
- Data Cleaning
   - Ensured data consistency by correcting misspelled words and filling missing values using the Find and Replace function.
   - Removed unnecessary columns that were not relevant to the analysis. For instance, the "Hour" column and "Pizza Type ID" were deleted since the  "Name" column already provided the necessary information.



2. Data Transformation & Integration

Merged the three tables into a single table for streamlined analysis.

Resolved inconsistencies where columns with the same names in different tables did not match.

Added a calculated column to categorize time into Morning, Afternoon, and Night based on the time values.

Created a calendar table to support time-based analysis and ensured proper data connections in the data model.



3. Loading Data into Power BI

After cleaning and transforming the dataset, the Close & Apply function was used to load the final table into Power BI.



4. Dashboard Creation

Developed an interactive dashboard to answer the business questions, visualizing key insights to support decision-making.




This structured approach ensured that the dataset was well-prepared for in-depth analysis, enabling accurate insights into Pizza Pro’s sales, customer preferences, and operational efficient.

### Key Insights

#### Revenue by Pizza Type

- Insight: Top Performers:
      - Thai Chicken
      - Barbecue Chicken
      - California Chicken
      - All belong to the Chicken category
- Underperformer:
      - Brie Carre – only sells in small size, contributing the least revenue

Recommendation:

Promote Chicken pizzas across channels; offer bundle deals

Consider rebranding, resizing, or phasing out Brie Carre



#### Customer Preferences by Pizza Category

- Insight
   - Chicken category is the most popular and profitable
   - Category Size Variety: Chicken has 5 size variants; others only 3
   - Difference in preference between categories is small (1–2%), showing a fairly balanced demand


Recommendation:

Focus cross-selling efforts on Chicken pizzas with beverages and side dishes

Evaluate introducing more size options for other categories

#### Sales Seasonality
- Insight
    - By Month:
       - Higher sales in: January, March, April, May, June, July, August, November, December
       - Slight drop in Q2 and Q3; Q4 is lowest but difference is not significant

    - By Day of the Week:
       - Friday: Highest sales – end-of-week relaxation and group hangouts
       - Sunday: Lowest sales
       - Steady increase from Monday to Friday

   - By Season:
       - Spring: Highest sales
       - Autumn: Lowest


By Time of Day:
| Time Period | Revenue (£) | Orders | Quantity | |-------------|--------------|--------|----------| | Morning     | 3,406        | 202    | 209      | | Afternoon   | 32,244       | 1,913  | 1,960    | | Night       | 31,541       | 1,744  | 1,886    |

Afternoon and Night see significantly higher sales than Morning

Afternoon peak driven by lunch breaks and group orders

Night orders often relate to dinner and family meals


Recommendation:

Scale down morning operations or explore breakfast-focused offerings

Promote meal deals during lunch and dinner periods

Run targeted promotions on Fridays and during spring



---

Business Impact

Optimized product offerings (e.g., reduce Brie Carre, expand Chicken category)

More effective marketing through targeted timing and days

Informed inventory planning by season and time of day

Increased revenue through strategic cross-selling and bundling



---

Visuals (Power BI / Excel Dashboard Suggestions)

Bar Chart: Revenue by Pizza Type

Pie Chart: Customer Preferences by Category

Line Chart: Monthly Sales Trend

Heatmap: Sales by Day and Time of Day

Stacked Column Chart: Sales by Season

Table or KPI Cards: Sales Metrics (Total Revenue, Top Pizza, Best Day/Time)



---

Next Steps

Segment customers by demographics or location for deeper personalization

Add customer feedback/review analysis

Run A/B testing on revamped menu options



---

Let me know if you’d like me to generate a sample README.md for GitHub or create dashboard visuals as mockups!
