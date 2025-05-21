# Pizzza Pro Analysis

Pizza Pro Analysis aims to uncover insights that enhance there pizza quality and create a unique customer experience.

## Table of Content

## Project Overview
Pizza Pro is a growing pizza chain offering a variety of pizza in different sizes and flavors. Specializing in both Classic and gourmet pizzas, it caters to a broad customer base across Urban and Suburban areas in multiple United State cities. The company seeks to improve its pizza quality and ensure a top-tier customer experience through a diverse range of toppings,ingredient and sizes. The analysis explores revenue by pizza type, customer preferences by category, and sales seasonality by time of day, week, and month.

## Objectives
- Identify top-performing and underperforming pizza types by revenue.
- Analyze customer preferences across different pizza categories.
- Understand seasonal and time-based sales patterns.
- Provide actionable business recommendations based on data.

## Business Requirement
### KPIs 
  - Total Revenue: The total sales generated from the pizza orders
  - Order Quantity: The total volume of pizzas sold.
  - Total Orders: The total number of overall orders.

### Business Problems and Objectives
- Revenue by Pizza Type
  - Requirement: Analyze which pizza types contribute the most to the company's revenue.
  - Objective: Optimize menu offerings by promoting best-selling pizza types and identifying underperforming pizza to either improve or remove from the menu.
- Customer Preferences Based by Pizza Category
  - Requirement: Group pizzas by their category (e.g., Supreme, Chicken) and identify which categories are most popular among customers.
  - Objective: Target promotions towards popular pizza categories and explore cross-selling opportunities with beverages.
- Sales Seasonality:
  - Requirement: Identify trends in pizza sales across different times of the year, weekdays and times of day. 
  - Objective: Optimize inventory management and marketing strategies based on seasonal trends, ensuring adequate stock during peak demand periods to reduce waste and boost sales.
 
## Dataset
The dataset used for this analysis can be acessed in  Microsoft Excel [download here].(https://www.microsoft.com)
- Fields: Pizza Name, Category, Size, Order Time, Date, Quantity, Revenue.
- Period Covered: One year (January to December).
  
## Tool Used
- Power BI
  - For Data cleaning
  - Data transformation
  - Interactive dashboard creation.
 
## Analysis Methodology
The dataset, provided as a CSV file was loaded into Power BI and the following steps were carried out to prepare it for analysis.
1. Data Cleaning
   - Ensured data consistency by correcting misspelled words and filling missing values using the Find and Replace function.
   - Removed unnecessary columns that were not relevant for the analysis. For instance, the "Hour" column and "Pizza Type ID" were deleted since the  "Name" column already provided the necessary information.

2. Data Transformation & Integration
   - Merged the three tables into a single table for streamlined analysis.
   - Resolved inconsistencies where columns with the same names in different tables did not match.
   - Added a calculated column to categorize time into Morning, Afternoon, and Night based on the time values.
   - Created a calendar table to support time-based analysis and ensured proper data connections in the data model.

3. Loading Data into Power BI
   - After cleaning and transforming the dataset, the Close & Apply function was used to load the final table into Power BI inorder to start my analysis.

4. Dashboard Creation
   - Developed an interactive dashboard to answer the business questions, visualizing key insights to support decision-making.
- This structured approach ensured that the dataset was well-prepared for in-depth analysis, enabling accurate insights into Pizza Pro’s sales, customer preferences, and operational efficient.

### Measures Used
- All measures use in this analysis can be assessed here

### KPIs

#### Total Revenue
> Image
- Insight
- Measure Used:
  
#### Order Quantity
> Image
- Insight
- Measure Used:
  
#### Total Orders
> Image
- Insight
- Measure Used:

### Business Problem and Key Insights

### 1. Revenue by Pizza Type
> Image
- Insight:
    - Top Performers:
      
      - Thai Chicken
      - Barbecue Chicken
      - California Chicken
      - All belong to the Chicken category and generating more revenue to the company.
   - Underperformer:
     
      - Brie Carre – sells only in small size and generating the least revenue.

*Insight:* Thai Chicken, BBQ Chicken, and California Chicken pizzas dominate in revenue, accounting for over 40% of total pizza sales.
- Measure Used: 

Recommendation:

Promote Chicken pizzas across channels; offer bundle deals

Consider rebranding, resizing, or phasing out Brie Carre
*Recommendation:* Promote high-performing chicken pizzas. Consider resizing or removing Brie Carre from the menu.

### 2. Customer Preferences by Pizza Category
> Image
- Insight
  ### Pizza Category Sales

| Category | Revenue | % of Total |
|----------|---------|------------|
| Chicken  | £78,000 | 38%        |
| Supreme  | £64,000 | 31%        |
| Veggie   | £34,000 | 17%        |
| Classic  | £28,000 | 14%        |


   - Chicken pizza category is the most popular and prefered pizza by customers generating the highest revenue of 38%, nearly double of Veggie pizza.
   - The difference between the three different categories is minimal which ranges from (1–2%), showing a fairly balanced demand.
   - Chicken pizzas offer more size flexibility ( small, medium, large, X-Large and XXLarge) while the other categories offers only three (3) different sizes.
   - Small size dominates across all categories.
- Measure Used:
  
Recommendation:

Focus cross-selling efforts on Chicken pizzas with beverages and side dishes
Evaluate introducing more size options for other categories
*Recommendation:* Leverage the Chicken category for cross-selling with drinks and sides. Offer size variety in other categories for competitiveness.

### 3. Sales Seasonality
> Image 
- Insight
    - By Month and Quater:
       - Higher sales in January, March, April, May, June, July, August, November, December
       - High sales in Q1 with slight drop in Q2 and Q3 while Q4 has the lowest sale but the difference is minor or not significant

    - By Day of the Week:
       - In general sales gradually increase from Monday to Friday.
       - Friday records the highest sales likely due to -
            - Individuals rewarding themselves after a long work or school week.
            - Social activities such as parties movie night and hangout more on Fridays.
            - Most people receive there pay check on fridays. 
       - Sunday low sales can be attributed due to -
           - Families opting for home cooked meal.
           - Pro pizza which is the company that has this dataset has a reduced operating hours on Sunday which contributed to it's low sales.
     
   - By Season:
       - Spring: Highest sales
       - Autumn: Lowest

   - By Time of Day:

| Time Period | Revenue($) | Orders | Quantity
|-------------|------------|--------|----------
| Morning     | 3,406      | 202    | 209
| Afternoon   | 32,244     | 1,913  | 1,960
| Night       | 31,541     | 1,744  | 1,886

  - Afternoon and Night shows significantly higher sales, orders and quantity sold than Morning
  - Most people prefer light meal for breakfast like tea, coffee and cereal with bread while some are focused with work and not meal yet.
  - People order more in the afternoon for lunch, meetings and group gathering. 
  - Most night are for social activties and people order in regard to it and also for dinner not having to go through the stress of cooking.
    

Recommendation:

Scale down morning operations or explore breakfast-focused offerings

Promote meal deals during lunch and dinner periods

Run targeted promotions on Fridays and during 

*Recommendation:*  
- Reduce inventory and staff during low-morning hours.  
- Promote lunch/dinner deals.  
- Focus marketing on Fridays and spring season.

## Business Impact
- Improved focus on profitable items.
- Smarter inventory allocation by time of day and season.
- Data-driven promotional timing.
- Opportunity to optimize the menu and customer satisfaction.


## Next Steps
- Add customer demographic segmentation.
- Analyze customer feedback/reviews.
- A/B test modified menu offerings.
- Link this project to a live dashboard or embed visuals in GitHub README.

## Contact
If you have feedback or questions, feel free to connect with me on [LinkedIn](#) or send me a message.


## Recommendations
Recommendation:

Promote Chicken pizzas across channels; offer bundle deals

Consider rebranding, resizing, or phasing out Brie Carre
*Recommendation:* Promote high-performing chicken pizzas. Consider resizing or removing Brie Carre from the menu.
Recommendation:

Focus cross-selling efforts on Chicken pizzas with beverages and side dishes
Evaluate introducing more size options for other categories
*Recommendation:* Leverage the Chicken category for cross-selling with drinks and sides. Offer size variety in other categories for competitiveness.
Recommendation:

Scale down morning operations or explore breakfast-focused offerings

Promote meal deals during lunch and dinner periods

Run targeted promotions on Fridays and during 

*Recommendation:*  
- Reduce inventory and staff during low-morning hours.  
- Promote lunch/dinner deals.  
- Focus marketing on Fridays and spring season.
### *1. Menu Optimization*
- The top-selling pizzas (Thai Chicken, BBQ Chicken, California Chicken) are all from the *Chicken category* and available in *multiple sizes* (Small, Medium, Large).
  - *Recommendation:* Ensure that all best-selling pizzas are available in all sizes, including X-Large and XXL, to increase upsell potential.
- The *Brie Carre pizza* is underperforming and only sold in Small size.
  - *Recommendation:* Instead of removing it, revamp the recipe and introduce additional sizes. Consider bundling it with top sellers — e.g., "Buy one X-Large, get one Small Brie Carre free" — to improve visibility and trial.

### *2. Beverage Pairing Strategy*
Offer targeted beverage pairings to boost cross-selling and customer satisfaction:
- *Chicken pizzas:* Pair with Iced Tea, Lemonade
- *Supreme pizzas:* Pair with Ginger Ale or Citrus Soda
- *Classic pizzas:* Serve with Red Wine, Cola, or Root Beer
- *Veggie pizzas:* Recommend Cucumber Water, Iced Green Tea, or White Lemonade
- *General Options:* Offer Tea, Coffee, Fruit Juice, and Wine across the board

### *3. Operational Strategy by Time and Day*
- *Time of Day Insight:*  
  - Morning sales are significantly lower (£3,406, 202 orders)  
  - Afternoon sales peak (£32,244, 1,913 orders)  
  - Night sales are slightly lower than afternoon but still strong (£31,541, 1,744 orders)
  - *Recommendation:* Prioritize production and staffing in the *Afternoon and Evening*. Focus less on Morning hours.

- *Day of Week Insight:*  
  - Sales peak from *Thursday to Saturday, lowest on **Sunday*.  
  - *Recommendation:* Increase production and staffing from *Thursday to Saturday*. Reduce output on Sundays. Slightly increase Monday–Wednesday to maintain consistency.

- *Seasonality by Quarter & Month:*  
  - Q1 shows the highest sales, with a slight decline in Q2 & Q3; Q4 is the lowest.
  - Months like *January and July* perform better.
  - *Recommendation:* Increase inventory and marketing focus during *Q1 and Q2* and in high-performing months. Scale back slightly during lower-sales periods (February, September, October).

---

## Final Notes
While pizza is a year-round product with consistent demand, this dataset reveals subtle patterns worth leveraging for operational efficiency and marketing focus. These data-driven recommendations aim to increase profitability while aligning with customer behavior.

---

Excellent question — backing your recommendations with clear insights or data summaries is what transforms your work from opinion-based to evidence-based analysis, which hiring managers love to see in a GitHub portfolio.

Here’s how you can back your recommendations step-by-step:


---

1. Use Summarized Data Points

When you say something like:


4. Highlight Trends in Bullet Points

### Monthly Sales Trend (Summary)
- *Highest months:* January, July, August
- *Lowest months:* February, October
- *Quarterly Trend:* Q1 has the highest total sales; Q4 the lowest.

*Recommendation Backed by Data:* Increase production and marketing in Q1 and high-performing months (Jan, Jul, Aug).




Write a short 1–2 line "Insight" under each to connect the data to the business decision.







3. Sales by Time of Day

Insight: Afternoon and Night account for over 90% of sales revenue. Mornings contribute less than 5%.


---

4. Sales by Day of the Week

Insight: Fridays have the highest volume, likely due to weekend preparation. Sundays see a sales dip.



Recommendations

Promote Top Sellers: Focus promotions around Thai Chicken, BBQ Chicken, and California Chicken pizzas.

Revamp Underperformers: Rebrand Brie Carre and offer it in more sizes. Bundle it with large-sized pizza as a giveaway to increase exposure.

Optimize Inventory: Increase afternoon and night-time production. Cut morning supply.

Strategic Scheduling:

Scale up staffing and marketing Thursday–Saturday.

Reduce Sunday production.

Boost production in Q1, especially January and July.


Cross-Sell Beverages:

Chicken Pizzas – Lemonade, Iced Tea

Supreme – Ginger Ale, Citrus Soda

Classic – Cola, Red Wine

Veggie – Cucumber Water, Green Tea




