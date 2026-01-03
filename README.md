# My-father-Bussiness-analysis-and-forecasting-retail-liquor-business---Data-Analysis
1. This project is based on a real business scenario inspired by my father’s retail liquor business, Teja Wines, operating multiple branches in Prakasam district, Andhra Pradesh. The goal of this project is to analyze sales patterns, customer behavior, and future trends to support data-driven business decisions.

# 🍷 Teja Wines Sales Analytics  
### End-to-End Python Data Analyst Project

---

## 1. Project Overview

This project demonstrates a complete **Python-based data analytics workflow** for a retail liquor business, starting from **raw transactional data** and ending with **actionable business insights and sales forecasting**.

The focus of this project is on **real-world data handling and analytical preparation**, not just writing code or generating charts.  
It reflects practical analytics workflows followed in data-driven retail organizations.

---

## 2. Problem Context

Retail liquor shops generate large volumes of daily transactional data such as:

- Product and brand sales  
- Customer purchasing behavior  
- Pricing and quantity variations  
- Payment mode distribution  
- Time-based sales patterns  

In real business scenarios, this data is often **raw, inconsistent, and noisy**.

The objective of this project is to transform such raw data into a **clean, reliable, analytics-ready dataset** that supports business decision-making.

---

## 3. Data Collection

- Data was taken from shops database 
- 40000 rrecords 40 records per day
- includes 5 main brands
- 6 months data from database
- 5 shops of my father syndicate
-  Dataset includes real-world issues such as:

  - Missing values  
  - Duplicate records  
  - Outliers  
  - Inconsistent data types  

This simulates **raw data collected directly from shop databases**.

---

## 4. Dataset Structure

### 4.1 Shops Covered

- Teja Wines – Ongole  
- Teja Wines – Yedugullapadu  
- Teja Wines – Kothapatnam  
- Teja Wines – Sitharampuram Koshtalu  
- Teja Wines – SN Padu  

---

### 4.2 Columns Included

| Column Name     | Description                          |
|-----------------|--------------------------------------|
| Shop_Name       | Name of the shop branch               |
| Location        | Shop location                         |
| Date            | Transaction date                     |
| Product_Type    | Liquor category                      |
| Brand           | Brand name                           |
| Quantity_Sold   | Units sold                           |
| Unit_Price      | Price per unit                       |
| Payment_Mode    | Cash / UPI / Card                   |
| Customer_Age    | Age of customer                      |
| Total_Sales     | Quantity_Sold × Unit_Price           |

---

## 5. End-to-End Workflow

Raw Sales Data  

↓  

Data Understanding & Profiling  

↓  

Data Cleaning & Validation  

↓  

Feature Engineering  

↓  

Exploratory Data Analysis  

↓  

Business Insight Generation  

↓  

Sales Forecasting  

---

## 6. Data Cleaning & Validation

Before performing analysis, the following steps were applied:

- Missing brand values filled using **most sold brand per product type**  
- Missing quantity values estimated using **price and brand sales trends**  
- Missing payment modes filled with realistic random values  
- Missing customer ages imputed using **brand-age consumption patterns**  
- Outliers detected using the **IQR method**  
- Business logic applied instead of blind data removal  

Only **cleaned and validated data** was used for analysis.

---

## 7. Data Transformation & Feature Engineering

To make the dataset analytics-ready:

- Created derived columns:
  - `Total_Sales`
  - `Month`
  - `Day_Type (Weekday / Weekend)`
  - `Age_Group`
- Standardized categorical values  
- Converted inconsistent data types  
- Prepared time-based features for trend analysis  

---

## 8. Exploratory Data Analysis (EDA)

EDA was performed from multiple business perspectives:

### Shop-Level Analysis
- Total and average sales per shop  
- Weekday vs weekend performance  

### Brand-Level Analysis
- Top-performing brands  
- Revenue contribution by brand  

### Customer Analysis
- Age group vs brand consumption  
- Shop-wise customer age distribution  

### Time-Based Analysis
- Daily sales trends  
- Monthly performance patterns  

---

## 9. Forecasting Strategy

- Daily total sales aggregated  
- Time-series forecasting performed using **Prophet**  
- Forecasted **next 6 months sales**  
- Output includes:
  - Historical trend  
  - Future prediction  
  - Confidence intervals  

---

## 10. Visualization & Reporting

The following visualizations were used:

- Line charts  
- Bar plots  
- Box plots (outlier detection)  
- Heatmaps  

All visuals focus on **clarity and business interpretability**.

---

## 11. Business Perspective

From a business owner’s viewpoint, this analysis helps to:

- Identify high-performing shops and brands  
- Understand customer demographics  
- Optimize inventory planning  
- Predict future demand and revenue  

---

## 12. Skills Demonstrated

- Python data analysis  
- Real-world data cleaning  
- Exploratory data analysis  
- Feature engineering  
- Time-series forecasting  
- Professional documentation  

---

## 13. Conclusion

This project showcases a **complete real-world analytics lifecycle**, emphasizing:

- Data quality  
- Analytical rigor  
- Business understanding  
- Structured decision-making  

It closely mirrors how **retail analytics projects** are executed in production environments.

---

## 14. Author

**Phani Inturi**  
Data Analyst | Python | Business Analytics  

GitHub: https://github.com/phani0011
