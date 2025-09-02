# Financial-Report-Analysis
**Excel | Power BI | Financial Report | From Raw Data to Business Insights**

## Table of Contents
- [Project Overview](#project-overview)  
- [Dataset Description](#dataset-description)  
- [Data Preprocessing](#data-preprocessing)  
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Power Bi Dashboard](#power-bi-dashboard)
- [Conclusion / Recommendations](#conclusion--recommendations)  
- [Tools](#tools)  
  

### Project Overview
This analysis reviews company sales, discounts, profit, and manufacturing costs from Jan 2013 to Dec 2014. It highlights how discounts influenced sales volumes, identifies key products and segments, and evaluates cost patterns. it ia a review of two years of financial records using Excel and Power BI to identify sales trends, cost drivers, and discount effects. The goal is to highlight opportunities for improving profitability and guiding pricing decisions.

### Dataset Description
- **Source:** Kaggle  
- **Period:** Jan 2013 – Dec 2014  
- **Content:** Monthly data on sales, profit, manufacturing cost, discounts, products, segments, and countries.  
- **Key Features:**  
  - `Sales` — total revenue  
  - `Profit` — net profit after costs  
  - `Discount` — total discounts applied  
  - `ManufacturingCost` — production costs  
  - `Product`, `Segment`, `Country` — categories for breakdown  

### Data Preprocessing
- Converted dates to year–month format.  
- Standardized product, segment, and country labels.  
- Checked for missing or inconsistent monetary values.  
- Created metrics such as `DiscountPercent` and `Margin` for comparisons.  

### Exploratory Data Analysis (EDA)
- **By Discount Band:** Higher discount bands drove more sales but reduced overall margin.  
- **By Product:** Paseo and VTT dominated in both sales and cost contribution.  
- **By Segment:** Government was the largest segment across sales and cost.  
- **By Country:** U.S. and Germany recorded the strongest sales.  
- **Trends:** Seasonal peaks were visible in late months of each year.  

### Power Bi Dashboard  
- **KPI Cards (Top Metrics):**  
  - Total Sales: **$92.31M**  
  - Total Profit: **$13.02M**  
  - Total Manufacturing Cost: **$50.62K**  
  - Total Discounts: **$7.06M**  
  - Highest Single Discount: **$149.68K**

- **Sales Analysis:**  
  - Sales by **Discount Band** (None, Low, Medium, High)  
  - Sales by **Country** (United States, Canada, France, Germany, Mexico)  
  - Sales by **Product** (Paseo, VTT, Amarilla, Carretera, Velo, Montana)  
  - Sales by **Segment** (Government, Small Business, Enterprise, Midmarket, Channel Partners)  
  - Monthly Sales Trend (Jan 2013 – Dec 2014)

- **Manufacturing Cost Analysis:**  
  - Manufacturing Cost by **Discount Band**  
  - Manufacturing Cost by **Product**  
  - Manufacturing Cost by **Segment**  
  - Monthly Manufacturing Cost Trend

### Conclusion / Recommendations
- Discounts boosted volume but cut into margins; large discounts need closer review.  
- Focus on profitable products like Paseo while monitoring high-cost products such as VTT.  
- Limit deep discounting in segments where margin loss outweighs volume gains.  
- Add product-level margin tracking for better pricing decisions.  

### Tools
- **Power BI** — dashboards and visuals  
- **Excel** — Data Preprocessing  


