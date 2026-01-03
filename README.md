# Spice Odyssey & Co. Sales Analysis
 ---
## 🎯 Objective
Analyze and interpret Spice Odyssey Restaurant & Co. Sales data to uncover actionable insights that drive customer engagement, menu & product optimization, targeted marketing, inventory & operational planning.
### **Project Purpose:**
  * To analyze restaurant sales data and uncover ordering patterns, customer preferences, and revenue drivers.
  * To support data-driven decisions for menu optimization, pricing strategy, and operational planning.
### **Key KPIs:**
  * Total Orders: 5K
  * Total Sales:  ~160K
  * Average Price: ~13.16
  * Average Order Value (AOV): ~29.27
### **Deliverables:**
  * Interactive Power BI dashboard
  * Actionable business insights
  * Strategic recommendations for menu & operations
---

## 📘 Project Overview 
### **Context Highlights:**
  * Kevaro Athletics, a global sports organization, maintains a diverse selection pool of 50 athletes representing 11 countries and multiple sporting disciplines.
  * This project evaluates the balance and fairness of gender participation and salary distribution, reflecting organizational commitment toward inclusivity and performance-based equity.


### **Context Highlights:**
  * This project analyzes sales data for Spice Odyssey Restaurant & Co., a multi-cuisine restaurant brand, to provide a holistic view of business performance and customer behavior.
  * The analysis helps Spice Odyssey’s marketing and product teams understand:
    * The restaurant operates across multiple cuisine categories — Asian, Mexican, Italian, and American.
    * Sales performance varies by weekday, meal type, and time of day.
    * Stakeholders lacked a centralized analytics solution to:
        * Monitor overall performance.
        * Identify demand patterns.
        * Uncover revenue and growth opportunities.
  * This analysis consolidates raw transactional data into a single, interactive Power BI dashboard, enabling faster insights and more informed strategic decisions.
---
 
## 🗂️ Data Overview & Schema     
### **Data Source:**  
  * **Source:** Internal restaurant transactional sales dataset (simulated business data for analytics use case)
  * **Data Type:** Structured, row-level order transaction data
  * **Time Period:** January 2023 – December 2023

### **Data Structure & Metrics:** 
  * **Key Index Types:** Order ID, Order Date, Order Hour, Weekday Order Number, Item Name
  * **Total Rows:** ~5,000 order-level records
  * **Categories:**
    * Cuisine Category: Asian, Mexican, Italian, American
    * Meal Type: Breakfast, Lunch, Dinner, Late Night
    * Time Dimensions: Month, Weekday, Hour
  * **Calculated Metrics:**
    * Total Orders
    * Total Sales
    * Average Price
    * Average Order Value (AOV)
---
 
## 💻 Tech Stack    
### **Tools:**
  * **Excel**
      * Data validation & exploratory analysis
  * **PowerQuery**
      * ETL transformations
  * **PowerBI**
      * Visualization, DAX measures & dashboard design
      * DAX – Calculated measures and time intelligence
  * **PowerPoint**
      * Presentation and final dashboard snapshots
---
        
## 📈 Methodology & Analysis  
### **Prepare, Process & Analytical Approach:** 
  * **Data Preparation & Cleaning:**
    * Imported raw restaurant sales data & verified column consistency (Order Date, Order Time, Category, Item Name, Price).
    * Performed data quality checks: Missing values, Duplicate Order_Details_ID, Invalid or inconsistent price entries.
    * Standardized date and time formats & ensured category and item naming consistency for downstream BI usage.
  * **Data Modeling & Integration:**
    * Imported the cleaned Excel dataset into Power BI.
    * Used a single-table, flat data model for performance and simplicity.
    * Created logical analytical groupings: Order Date → Month, Weekday, Order Time → Order Hour, Category → Item hierarchy.
    * Enabled dynamic slicing by: Item Category, Meal Type, Weekday Order Number.
  * **Feature Engineering:**
    * Created derived columns using Excel + Power BI: Order Month, Weekday Order Number (for correct weekday sorting), Meal Type classification based on order time.
    * Developed key DAX measures: Total Orders, Total Sales, Average Price, Average Order Value (AOV).
  * **Visualization Design:**
    * Designed KPI cards for quick executive-level insights.
    * Optimized visual hierarchy for business storytelling and decision-making.
  * **Validation & Formatting:**
    * Validated slicer interactions across all visuals.
    * Finalized dashboard for presentation and stakeholder consumption.
---
 
## ❓ Problem Statement     

### **Key Questions:**
  * What is the overall gender representation in Kevaro’s global selection pool?
  * Which sports offer the highest total and average salaries?
  * Is there a significant gender pay gap across specific sports?
  * Which countries contribute the most athletes and salary volume?

---

## 💡 Key Insights      
### **Top Findings:** 
  * **Balanced Gender Participation:** 25 Male & 25 Female athletes selected globally.
  * **High-Salary Sports:** Cycling Road, Volleyball, Alpine Skiing, and Triathlon show top salary aggregates.
  * **Pay Disparity Exists:** Males dominate higher-paying sports like Biathlon, Cycling Road, and Triathlon.
  * **Female Salary Dominance:** Notable in Volleyball, Equestrian, and Shooting, indicating strong female representation.
  * **Country Representation:** France, Australia, and USA lead in total candidates and salary share.
### **Supporting Metrics:**
  * **Highest Male Salary Sport:** Cycling Road – $9.6M
  * **Highest Female Salary Sport:** Volleyball – $8.6M
  * **Countries with maximum athletes:** France (9), Australia (8), USA (7)
---
 
## 📍 Conclusion
### **Summary:** 
  * Kevaro Athletics demonstrates an encouraging gender balance in athlete participation but shows uneven salary distribution across disciplines.
  * While certain sports reflect female leadership in earnings, others maintain a significant male bias.
  * The data highlights the need for targeted parity initiatives, performance-linked pay reviews, and inclusive sponsorship strategies.

---
 
## 🖥️ Dashboard Overview
![image alt](https://github.com/Cnik1710/Kevaro-Athletics-Co.-Membership-Systemization-Analysis/blob/aa2996caef41d9fc465f8d0cd5d171d6d83ccc6a/Kevaro%20Athletics%20%26%20Co.%20Membership%20Systemization%20Analytics%20Dashboard.png)

---

## ✅ Business Impact & Use Cases   
  * Supports gender equity reporting and compliance with global sports standards.
  * Enables salary budgeting and sponsorship alignment per sport and gender.
  * Empowers HR and management to identify underrepresented sports for development.
  * Forms basis for Kevaro’s Diversity & Inclusion dashboard in future athlete selection cycles.
---
 
 ## 🙏 Acknowledgements & Contact 
 ### Project Analyst: Anik Chakraborty	
   📧 Email: anikc1710@gmail.com  
 ### Special Thanks To: 
   * Coding Ninjas – for project framework and guidance  
   
