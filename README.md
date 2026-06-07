# Quantium Retail Analytics Virtual Experience Program
- **Tools**: R, dplyr, ggplot2, tidyr, data.table, readr / readxl
- **Techniques**: Data cleaning, Feature engineering, Exploratory data analysis (EDA), Customer segmentation, Hypothesis testing, Affinity analysis

## Key Insights
<img width="500" height="362" alt="No  of transactions overtime" src="https://github.com/user-attachments/assets/4c5ab0dd-95c9-4afc-9bf3-fbba56a0439b" />

### **1. Clear seasonal sales trend observed**
- Increased demand as transaction volume rises significantly leading up to Christmas
- No transactions on Christmas Day due to store closures
- **Business implication**: Stock, staffing planning, and promotional activities should be focused on before the holiday seasons

### **2. Mainstream young singles/couples were the highest-value segment in terms of revenue contribution**
- Statistically significantly higher willingness to pay per unit than budget and premium counterparts
- Stronger preference for branded/premium products
- Higher likelihood of purchasing larger pack sizes
- High in both customer count and sales contribution, making them a volume and value driver
- **Business implication**: Targeted marketing campaigns and promotions, premium brand shelf visibility, and bundle/party-pack/family-size displays specialised on this segment offer potential revenue uplift

## Overview
- This repository contains my work for the Quantium Retail Strategy and Analytics Virtual Experience Program on Forage.
The project replicates a real-world analytics workflow, including two datasets: transaction records and customer purchase behaviour, to uncover commercial insights, support evidence-based decisions, and deliver recommendations to a Category Manager.
- **Business question**: Which customer segments drive chip sales, and how can their purchasing behaviour inform commercial strategy?

## Project Workflow
### 1. Data Preparation
- Converted Excel serial dates into proper date formats
- Removed non-chip products from the dataset
- Identified and excluded bulk-buying outliers
- Cleaned and standardised chip brand names
- Generated new variables: PACK_SIZE, BRAND

### 2. Exploratory Data Analysis (EDA)
- Analysed transaction trends over time
- Investigated missing transaction dates
- Examined sales distribution by: Customer lifestage and segments (Budget/Mainstream/Premium), Pack size, Brand
- Merged transaction and customer datasets

### 3. Customer Segmentation Analysis
Performed segmentation to identify behavioural differences across groups
- Total sales by customer segment
- Number of customers per segment
- Average units purchased per customer by segment
- Average price per unit by segment
- Outcome: Identified high-value customer groups driving sales

### 4. Statistical Testing
- Conducted independent t-tests comparing unit price between Mainstream vs Premium and Mainstream vs Budget young and mid-age singles/couples
- Evaluated whether price differences between groups were statistically significant, indicating that Mainstream customers pay a higher unit price
- The result suggests that greater willingness to pay, not just higher volume, drives their revenue contribution

### 5. Affinity Analysis
- Compared the purchasing behaviour between the target (Mainstream young singles/couples) and the non-target customer base
- Identified the target segment's preference patterns:
  - More likely to buy bigger packs
  - Stronger brand-driven purchasing behaviour

## Recommendations
This analysis replicates real-world retail analytics workflows used in commercial teams to:
- **Inventory:** Optimise planning and increase stock by understanding seasonal sales patterns and demand fluctuations
- **Staffing:** Align staffing plans and allocation with the holiday demand spike 
- **Promotions:** Develop targeted promotions aligned with customer preferences, like designing bundle deals and party-pack promotions targeted for mainstream young singles/couples; volume-based deals for older families
- **Shelf placement:** Prioritise  increasing visibility for preferred brands in high-frequency areas by the target demographic

## Limitations
- The data only covers a one-year period, which can not determine long-term trends, and patterns can differ across years
- Lack of demographic customer information available for deeper customer profiling
- Lack of cost data for profitability insights, as high revenue does not necessarily mean high profitability

## Repository contents
- Quantium Retail Strategy Analytics.Rmd | Full R Markdown analysis script
- Quantium Retail Strategy Analytics Report.pdf | Written report with findings and recommendations
- Quantium Retail Strategy Analytics - Slide.pdf | Slide deck summary for stakeholder presentation
- QVI_transaction_data.xlsx | Transaction dataset
- QVI_purchase_behaviour.csv | Customer purchase behaviour dataset


