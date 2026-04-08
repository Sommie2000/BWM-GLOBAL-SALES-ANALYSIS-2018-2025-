# 🚗 BWM-GLOBAL-SALES-ANALYSIS (2018-2025)
This project analyses global sales performance for BMW from 2018-2025 and the insights goes beyond just revenue numbers but focus on growth, product strategy and macroeconomic impact. This analysis reinforced an important lesson: sales performance does not exist in isolation, it is influenced by product strategy and economic conditions.

### TABLE OF CONTENT
* [Project Overview](#project-overview)
* [Dataset Overview](#dataset-overview)
* [Data Cleaning](#data-cleaning)
* [Excel Dashboard](#excel-dashboard)
* [Dashboard](#dashboard)
* [Key Insights](#key-insights)
* [Interactive Analysis](#interactive-analysis)
* [Recommendation](#recommendation)
* [Data Source](#data-source)

### PROJECT OVERVIEW
This Project analyzes BMW globl sales performance from 2018-2025, focusing on growth, product strategy, revenue, models performance, market strength, economic indicators, regional sales and macroeconomic impact revealing a strategic shift. I used power query editor for data cleaning and excel for data transformation and visualization.

### DATASET OVERVIEW

COLUMNS:
- Year
- Month	
- Days	
- Region	
- Model	
- Units_Sold	
- Avg_Price_EUR	
- Revenue_EUR
- BEV_Share
- Premium_Share
- GDP_Growth
- Fuel_Price_Index

DATASET SAMPLE PREVIEW:
|Year|	Month| Days| Region|	Model| Units_Sold| Avg_Price_EUR| Revenue_EUR| BEV_Share| Premium_Share| GDP_Growth| Fuel_Price_Index|
|----|--------|-----|-------|------|-----------|--------------|------------|----------|--------------|-----------|-----------------|
|2019|	1/4/1900|	Wed|	Europe|	MINI|	$2.6K|	$40K|	$105M|	0.06|	17.63|	3.98|	1.04|
|2020|	1/4/1900|	Wed|	USA|	MINI|	$2.5K|	$43K|	$110M|	0.061|	19.81|	3.52|	1.16|
|2018|	1/1/1900|	Sun|	Europe|	MINI|	$2.6K|	$43K|	$110M|	0.013|	19.12|	3.5|	1|
|2021|	1/2/1900|	Mon|	Europe|	MINI|	$2.8K|	$40K|	$113M|	0.084|	15.12|	4.2|	1.14|
|2018|	1/10/1900|	Tue|	China|	MINI|	$2.7K|	$42K|	$114M|	0.025|	19.19|	5.28|	0.92|


[Dataset file showing the pivot tables][bmw_global_sales_2018_2025.xlsx](https://github.com/user-attachments/files/26570700/bmw_global_sales_2018_2025.xlsx)


### DATA CLEANING
- Changed date and amount datatype to date and currency format 
- Removed, duplicate, missing or invalid values using 
  
### EXCEL DASHBOARD 
KPI Cards
1. 💹 Total Revenue: $1571B
2. 🚙 Total Units Sold: $25M
3. 🚗 BEV Share:
   > Percentage of battery electric vehicles (EV adoption trends) (+14%YoY)
4. 🚗 Premium Share:
   > Proportion of premium vehicles sold (-2%YoY)
5.   Growth Metrics:
   * YoY Revenue Growth (+2%YoY)
   * YoY Units Growth (+2%YoY)
6.  Slicers: Year and Region are the slicers i used for filtering for further analysis 

DASHBOARD CHARTS

- 💹 Top model that generated the highest revenue is X7-best selling BMW model (Revenue by Model)
- 🚗 Top model that generated the highest unit sold is IX-best selling unit (Unit sold by Model)
  > But here is what is surprising: IX Series model is the most sold unit yet X7 series generated the highest revenue ($286B)
  > Which proves an important business lesson, high sales volume does not always mean high revenue
- 🗺️ Top selling region is China (Revenue by Region)
- 📊 Regional sales breakdown - Total Revenue by Model and by Region (This shows all models sold in each region and X7 model top in all the regions
- BEV_Share vs Premium Share: This revealed an interesting strategic shift while premium share declined slightly by 2% (-2%YoY), overall revenue increased, supported by a strong 14% YoY growth in BEV_Share
- GDP Growth vs Fuel Price Index: The chart compares the trend of fuel price index and GDP growth from 2018 to 2025

### DASHBOARD

<img width="811" height="459" alt="BMW sales Dashboard" src="https://github.com/user-attachments/assets/59a21d37-aa23-4089-baf2-ba121821fdd6" />


### KEY INSIGHTS 
1. Australia emerged as the highest revenue generating country with 18%, indicating strong market demand and effective regional sales performance while New Zealand generated the lowest revenuewith 15%
2. Revenue peaked in June and July, revealing a possible seasonal buying pattern, this insight could be;
   > Seasonal inventoy planning, Targeted marketing campaigns and Promotional timing strategies
3. Smooth silky salty chocolate product contributed the highest revenue, suggesting strong product-market fit, customer preference and demand while the product with the lowest revenue is the 70% dark bites
4. The top sales person is Ches Bonnell, Ches Bonnell generated the highest sales revenue, demostrating strong sales effectiveness
5. The top selling product with the highest boxes shipped is the 50% dark bites chocolate even if it didnt drive the highest sales revenue

### INTERACTIVE ANALYSIS 
To enhance usability, I integrated a Year Slicer, allowing dynamic filtering of the performance metrics across different years. 
This helps uncover;
- Year-over-year performance change
- Shifts in product demand
- Trend Analysis
- Performance tracking by period
- Market growth patterns

### RECOMMENDATION   
* Expand distribution of smooth silky salty chocolate and review pricing strategies for low margin products such as 70% dark bites and caramel stuffed bars chocolates
* Analyze underperforming products and months for improvement opportunities
* Stregthening top markets in Australia and also support underperforming countries
* The company can optimize revenue growth and sales strategy
* Leverage peak months (june and july) with promotions

### DATA SOURCE
This data was gotten from Kaggle
[Download here](https://www.kaggle.com/datasets?search=chocolate+sales)






