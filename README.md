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
  
<img width="1366" height="768" alt="Screenshot (127)" src="https://github.com/user-attachments/assets/53a32252-eb4c-45d2-a2a0-d4c7ada48d68" />


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
  
![Financial report_1 (1)](https://github.com/user-attachments/assets/a0b977af-26a7-441c-809b-0b0387b689e4)

![Financial report_2 (1)](https://github.com/user-attachments/assets/dd2c2201-0a3e-46a1-ac35-0a25374ee6cb)

### Conclusion / Recommendations

The analysis shows clear trade-offs between sales growth and profitability. Discounts have been effective in driving higher sales volumes, but at the cost of reduced margins. Certain products and segments are performing strongly, while others require closer monitoring to avoid eroding overall profitability.  

#### 🔎 Key Conclusions
- 📉 **Discounts vs Margins:** Discounts boosted sales volume but significantly reduced margins. The total discounts granted ($7.06M) represent more than half of total profit ($13.02M), highlighting a need for stricter discount policies.  
- 📊 **Product Performance:** Paseo stands out as a profitable product, while VTT, despite high sales, carries heavy manufacturing costs that reduce overall profitability.  
- 🌍 **Segment & Region Trends:** The Government segment contributes the most to revenue but also absorbs higher costs. Regional trends show the U.S. and Germany as strong performers, while other markets contribute less consistently.  
- 📆 **Seasonality:** Late-year peaks suggest seasonal demand patterns, which should be planned for in terms of production and promotional strategy.  

#### 💡 Recommendations
1. 🛑 **Review Large Discounts:** Deep discounts need tighter controls. Conduct a margin impact analysis before granting discounts above a set threshold.  
2. 💰 **Prioritize Profitable Products:** Focus sales efforts on Paseo and other strong-margin products, while reviewing VTT’s cost structure or pricing to improve contribution.  
3. 🎯 **Segment-Specific Discounting:** Avoid blanket discounts. Tailor discount levels by segment and country to balance competitiveness with profitability.  
4. 📈 **Margin Tracking:** Implement product-level gross margin dashboards to monitor profitability in real time. This will help sales teams make informed pricing and discounting decisions.  
5. 🔄 **Continuous Monitoring:** Reassess discount strategies quarterly, testing whether incremental sales from discounts are worth the lost margin.  
6. 🏭 **Manufacturing Efficiency:** Investigate unit manufacturing costs at high volumes to identify opportunities for cost savings and better capacity planning.  

> 🚀 **Next Step:** Integrate product-level profitability and discount analytics into the business reporting process to guide data-driven pricing and growth strategies.

### Tools
- **Excel** — Data Preprocessing 
- **Power BI** — dashboards and visuals 

*Thanks for reading through — I hope you found the insights useful!*  
