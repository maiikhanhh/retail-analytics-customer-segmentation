# Quantium Retail Analytics Virtual Experience Program

## Overview
This repository contains my work for the Quantium Retail Strategy and Analytics Virtual Experience Program on Forage, an online platform offering self-paced virtual job stimulations designed by global top companies.
The project focuses on data preparation, exploratory data analysis (EDA), customer segmentation and purchasing behaviour analysis using real-world retail transaction data.
The purpose was to uncover insights into customer behaviour and support data-driven commercial decisions.

## Key Work
- Clean transaction and customer datasets
- Identify and handle outliers and missing values
- Explore key features like brand and pack size
- Examine customer patterns across segments
- Perform statistical testing to validate insights
- Use affinity analysis on product preferences

## Tools and Technologies
### Programming and Core Packages
- R
- R Markdown
- dplyr
- ggplot2
- tidyr
- data.table
- readr / readxl
### Analytical Techniques
- Data cleaning
- Feature engineering
- Exploratory data analysis (EDA)
- Customer segmentation
- Hypothesis testing
- Affinity analysis

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

### 3. Customer Segmentation Analysis
Performed segmentation to identify behavioural differences across groups
- Total sales by customer segment
- Number of customers per segment
- Average units purchased per customer by segment
- Average price per unit by segment
Outcome: Identified high-value customer groups driving sales

### 4. Statistical Testing
- Conducted independent t-tests
- Evaluated whether price differences between groups were statistically significant

### 5. Affinity Analysis
- Compared the purchasing behaviour between the target and non-target customer base
- Identified the preference patterns:
  Preferred pack sizes
  Preferred brands

## Key Insights
1. Clear seasonal sales trend observed:
- Increased demand leading up to Christmas
- No transactions on Christmas Day due to store closures

2. Mainstream young singles/couples were the highest value segment in terms of revenue contribution:
- Higher willingness to pay per unit
- Strong preference for branded/premium products
- Higher likelihood of purchasing larger pack sizes

3. Business implication:
- Adjust staffing and stock planning
- Increase inventory and run promotions before the holiday season
- Focus marketing campaigns, promotions specialised for this segment to maximise revenue
- Prioritise preferred-brand shelf visibility
- Promote and display bundle or family/party-size larger packs

## Business Impact
This analysis replicates real-world retail analytics workflows used in commercial teams to:
- Optimise inventory planning by understanding seasonal sales patterns and demand fluctuations
- Improve customer targeting strategies
- Develop targeted promotions aligned with customer preferences
- Support product positioning and pricing strategy
- Improve product assortment and shelf placement decisions
- Enable strategic decision-making with evidence-based recommendations

## Limitations
- The data only covers a one-year period, which can not determine long-term trends, and patterns can differ across years
- Lack of demographic customer information for more detailed targeted recommendations and financial (e.g. cost) data for profitability insights, as high revenue is not always profitable 



