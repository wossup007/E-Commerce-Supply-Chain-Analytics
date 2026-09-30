```markdown
# E-Commerce Supply Chain & Operations Analytics

End-to-end Supply Chain Analytics project using **Python** and **Power BI** on the Brazilian E-Commerce (Olist) dataset.

## Project Overview

This project analyzes 100K+ real e-commerce orders to evaluate delivery performance, inventory implications, and operational efficiency. Beyond basic reporting, the project includes safety stock estimation, scenario analysis, and commercial recommendations aimed at improving service levels and reducing fulfillment risk.

### Key Objectives
- Clean and transform raw e-commerce data using Python
- Calculate core supply chain KPIs (Lead Time, On-Time Delivery, Delay Rate)
- Perform inventory & safety stock analysis by product category
- Run scenario analysis to measure the impact of operational improvements
- Build an interactive 3-page Power BI dashboard
- Deliver actionable business recommendations

## Tools & Technologies

- **Python** (Pandas, NumPy) – Data Cleaning, Feature Engineering, Inventory & Scenario Analysis
- **Power BI** – Interactive Dashboard & Visualization
- **DAX** – KPI Measures

## Dataset

- Source: [Brazilian E-Commerce Public Dataset by Olist (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Period: 2016 – 2018
- Size: 100,000+ delivered orders

## Project Workflow

1. **Data Cleaning & Feature Engineering (Python)**
   - Merged Orders, Order Items, Products, Customers, and Sellers tables
   - Created key features: Lead Time, Delivery Delay, On-Time/Delayed flag, Total Order Value
   - Filtered only delivered orders

2. **Inventory & Safety Stock Analysis**
   - Calculated average daily demand and demand variability by product category
   - Estimated safety stock using 95% service level (z = 1.65)
   - Identified categories requiring higher inventory buffers

3. **Scenario Analysis**
   - Scenario A: Impact of removing/improving the worst-performing sellers
   - Scenario B: Impact of reducing lead time for high-delay categories by 20%
   - Measured changes in On-Time Delivery rate and Average Lead Time

4. **Power BI Dashboard**
   - Designed a 3-page interactive report
   - Created DAX measures for key operational KPIs
   - Added business recommendations based on analysis

## Dashboard Pages
<img width="1340" height="755" alt="Page 1" src="https://github.com/user-attachments/assets/af06e321-b8ca-48f5-bfb4-121cbcb25a36" />
<img width="1486" height="831" alt="image" src="https://github.com/user-attachments/assets/b3ed7e33-2a6b-4781-86e1-9e3d3ca338f8" />
<img width="1490" height="834" alt="image" src="https://github.com/user-attachments/assets/002cda28-9f4f-4936-94a3-d3c1ed2842ba" />

### 1. Executive Overview
- Total Revenue, Total Orders, Average Lead Time
- On-Time Delivery % and Delayed %
- Monthly Revenue Trend
- Top Product Categories by Revenue

### 2. Delivery Performance
- Average Lead Time by Customer State
- Average Lead Time by Product Category
- Delayed Orders by Seller State
- Delivery Delay Distribution

### 3. Insights & Forecast
- Monthly Revenue Forecast
- Revenue by Customer State
- Key Insights
- Business Recommendations

## Key Insights

- Overall On-Time Delivery Rate: **≈ 93%**
- Average Lead Time: **≈ 12 days**
- Top category by revenue: **Health & Beauty**
- Office Furniture shows the longest lead time (20+ days) and elevated delay rate
- Several high-volume categories (Baby, Electronics, Health & Beauty) have above-average delay rates

## Business Recommendations

- Prioritise **Office Furniture** category due to long lead time and higher delay rate
- Focus seller performance improvement on **Baby, Electronics, and Health & Beauty**
- Increase safety stock for high demand-variability categories to protect service levels
- Introduce seller tiering (A/B/C) based on delay rate and lead time performance
- Target lead time reduction in underperforming seller states

## Skills Demonstrated

- Data Cleaning & Feature Engineering
- Supply Chain KPI Development
- Inventory & Safety Stock Analysis
- Scenario / What-if Analysis
- Dashboard Design in Power BI
- Translating data into commercial recommendations

## How to Use

1. Clone this repository
2. Open the `.pbix` file in Power BI Desktop
3. (Optional) Run the Python script to reproduce the cleaned dataset and analysis


If you find this project useful, feel free to star the repository!
```

---

Just paste this and commit.  
After you update it, tell me and I can also give you the stronger **CV bullet points**.
