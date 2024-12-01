# 🌍 **Maji Ndogo Water Crisis Analysis** 💧

## **Table of Contents**  
1. [Introduction](#introduction)  
2. [Project Goals and Questions](#project-goals-and-questions)  
3. [Data Overview and Schema](#data-overview-and-schema)  
4. [Tools and Techniques](#tools-and-techniques)  
5. [Dashboard Pages and Analysis](#dashboard-pages-and-analysis)  
   - [Page 1: Water Sources Breakdown & Population Distribution](#page-1-water-sources-breakdown--population-distribution)  
   - [Page 2: Queue Time Analysis](#page-2-queue-time-analysis)  
   - [Page 3: Crime Rate Analysis](#page-3-crime-rate-analysis)  
   - [Page 4: Well Contamination Analysis](#page-4-well-contamination-analysis)  
   - [Page 5: Improvements and Budgeting](#page-5-improvements-and-budgeting)  
   - [Page 6: Vendor Performance Analysis](#page-6-vendor-performance-analysis)  
6. [Proposed Solutions](#proposed-solutions)  
7. [Impact of Proposed Changes](#impact-of-proposed-changes)  
8. [Conclusion](#conclusion)  


## **Introduction**  
Access to clean water is a basic human right, but for millions in African communities, it remains a daily struggle. Hours spent queuing for water at shared taps, reliance on contaminated wells, and a lack of safe infrastructure have created a significant public health and social crisis.  

The **Maji Ndogo Project** was designed to analyze these challenges through data-driven approaches. Using simulated real-world data, this project aimed to understand the root causes of water access issues and propose practical, data-backed solutions to improve lives in underserved communities.  

This report documents the tools, methods, and insights from this project, initially developed during the **ALX Data Science Program** and recently enhanced with additional analysis and storytelling elements.  



## 🎯 **Project Goals and Questions**  

This project was guided by key objectives to address critical water access challenges:  
1. Who are the most underserved populations in terms of water access?  
2. What are the primary factors contributing to long queue times and overcrowding?  
3. How does contamination of wells exacerbate water access issues?  
4. What is the relationship between water access points and crime rates?  
5. How can resources be optimally allocated to maximize the impact of improvements?  



## 📊 **Data Overview and Schema**  

### **Dataset Schema Overview**  
The dataset simulated real-world challenges, covering:  

1. **Visits Table**  
   - Tracks inspections of water sources, including queue times and daily usage statistics.  
2. **Water Sources Table**  
   - Details water source types, status, and geographic locations.  
3. **Queue Composition Table**  
   - Provides demographic information, such as percentages of males, females, and children in queues.  
4. **Crime Data Table**  
   - Records crimes near water sources, detailing crime types, victim demographics, and incident times.  
5. **Well Pollution Data**  
   - Tracks contamination levels (chemical and biological) in wells.  
6. **Project Progress Table**  
   - Monitors infrastructure improvements, including costs, vendor performance, and completion status.  



## 🛠 **Tools and Techniques**  

### **1. Spreadsheets**  
- Used for initial exploration and organization of raw data.  
- Calculated basic metrics and spotted inconsistencies before deeper analysis.  

### **2. SQL**  
- Cleaned, transformed, and aggregated data.  
- Identified patterns, fixed inconsistencies, and prepared data for analysis.  

### **3. Power BI**  
- Built dynamic dashboards for interactive analysis.  
- Visualized data to uncover insights and tell impactful stories.  
ETL Tool : Power Query

## 📋 **Dashboard Pages and Analysis**  

### **Page 1: Water Sources Breakdown & Population Distribution** 🌍  
**Overview:**  
This page provides a comprehensive overview of the population distribution and water source types, highlighting disparities.  

**Key Insights:**  
- **64%** of the population resides in rural areas with limited water access.  
- **43.84%** rely on shared taps, while **17.38%** use contaminated wells.  
- Only **33.55%** have basic access to water services.  

**Recommendations:**  
- Expand shared tap infrastructure in rural areas.  
- Repair and maintain broken water sources.  



### **Page 2: Queue Time Analysis** ⏳  
**Overview:**  
Analyzes queue times at shared taps, the most common water source.  

**Key Insights:**  
- Saturdays have the longest queue times, averaging **246 minutes**.  
- Women make up **66%** of those queuing, reflecting a significant gender burden.  

**Recommendations:**  
- Install additional shared taps in high-demand areas.  
- Implement scheduling systems to spread out peak usage.  



### **Page 3: Crime Rate Analysis** 🚨  
**Overview:**  
Examines the relationship between crime rates and water access points.  

**Key Insights:**  
- Over **77,000 crimes** were reported near water sources, with women accounting for **64%** of victims.  
- Theft and harassment are the most common crimes, often occurring during long queues.  

**Recommendations:**  
- Enhance security at high-traffic shared taps.  
- Reduce waiting times to minimize crime opportunities.  



### **Page 4: Well Contamination Analysis** 🧪  
**Overview:**  
Focuses on contamination levels in wells, a critical water source for rural areas.  

**Key Insights:**  
- **56%** of wells are chemically polluted.  
- **44%** are biologically contaminated, causing widespread health risks.  

**Recommendations:**  
- Deploy RO and UV filters to treat wells.  
- Conduct regular water quality monitoring and educate communities.  



### **Page 5: Improvements and Budgeting** 💰  
**Overview:**  
Evaluates infrastructure improvements and their associated costs.  

**Key Insights:**  
- **7,093 RO filters** and **3,379 new wells** are needed, costing **$146.74M**.  
- **80%** of the budget is allocated to rural areas.  

**Recommendations:**  
- Prioritize impactful improvements like RO filters and new wells.  
- Use dashboards for transparent resource allocation.  



### **Page 6: Vendor Performance Analysis** 🔧  
**Overview:**  
Assesses vendor efficiency in completing infrastructure projects.  

**Key Insights:**  
- **25,398 projects** were completed, with most focused on rural areas.  
- Variability in vendor performance underscores the need for strict monitoring.  

**Recommendations:**  
- Hold vendors accountable with performance metrics.  
- Establish benchmarks to ensure timely and cost-effective delivery.  


## 💡 **Proposed Solutions**  

1. **Infrastructure Expansion**: Add shared taps and drill wells in underserved areas.  
2. **Water Treatment**: Treat polluted wells with RO and UV systems.  
3. **Crime Mitigation**: Install lighting and security near high-crime water sources.  
4. **Community Education**: Train locals to maintain water sources and prevent contamination.  
5. **Vendor Management**: Use dashboards to track progress and ensure accountability.  



## 🌟 **Impact of Proposed Changes**  

- **Queue Time Reduction**: Average queue times projected to drop by **40%**, saving families hours weekly.  
- **Improved Health**: Treated wells provide clean water to millions, reducing disease outbreaks.  
- **Crime Reduction**: Enhanced security and reduced congestion lower crime rates by **25%**.  
- **Optimized Budgeting**: Transparent allocation ensures maximum impact from the **$147M budget**.  



## 📜 **Conclusion**  

The Maji Ndogo Project demonstrates how data can address pressing real-world challenges. By combining **spreadsheets**, **SQL**, and **Power BI**, this project identified critical issues and proposed actionable solutions to improve water access and safety.  

This project is a testament to the power of data to inspire impactful change. Let’s continue leveraging data for meaningful solutions.  

---

Feel free to reach out with feedback or suggestions! 💬  
