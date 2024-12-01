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
   - [Page 5: Improvements](#page-5-improvements)  
   - [Page 6: Cost of Improvements & Budgeting](#page-6-cost-of-improvements--budgeting)  
   - [Page 7: Cost and Budgeting Evaluation](#page-7-cost-and-budgeting-evaluation)  
   - [Page 8: Vendor Performance Analysis](#page-8-vendor-performance-analysis)  
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
![Water Sources Breakdown & Population Distribution](dashboard/Data%20Schema.jpg)
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
![Page 1 Water Sources Breakdown & Population Distribution](dashboard/Page%201%20Water%20Sources%20Breakdown%20&%20Population%20Distribution.jpg)  
**Overview:**  
This page provides a comprehensive overview of the population distribution and water source types, highlighting access disparities between rural and urban areas.  

**Key Insights:**  
- **64%** of the population resides in rural areas, with limited access to clean water.  
- **43.84%** rely on shared taps, and **17.38%** use contaminated wells.  
- Unsafe sources like rivers are still used by **14.54%** of the population.  
- **33.55%** of the population has basic access to water services.  

**Recommendations:**  
- Increase shared tap infrastructure in rural areas.  
- Repair and maintain broken water sources to enhance access.  

---

### **Page 2: Queue Time Analysis** ⏳ 
![Page 2 Queue Time Analysis](dashboard/Page%202%20Queue%20Time%20Analysis.jpg)  
**Overview:**  
This page analyzes queue times at shared taps, the most common water source in the region.  

**Key Insights:**  
- **Saturdays** have the longest queue times, averaging **246 minutes**.  
- **Weekday queue times** peak between 12 PM and 6 PM, with the highest average of **282 minutes** on Saturdays.  
- **66%** of those queuing are women, indicating a significant gender burden.  

**Recommendations:**  
- Install additional shared taps in high-demand areas to reduce wait times.  
- Implement scheduling systems to spread out peak usage.  

---

### **Page 3: Crime Rate Analysis** 🚨  
![Page 3 Crime Rate Analysis](dashboard/Page%203%20Crime%20Rate%20Analysis.jpg) 
**Overview:**  
This page examines the relationship between crime rates and water access points.  

**Key Insights:**  
- Over **77,000 crimes** were reported near water sources, with **64%** of victims being women.  
- Theft and harassment are the most common crimes, often occurring during long queues.  

**Recommendations:**  
- Enhance security at high-traffic shared taps.  
- Reduce waiting times to minimize crime opportunities.  

---

### **Page 4: Well Contamination Analysis** 🧪  
![Page 4 Well Contamination Analysis](dashboard/Page%204%20Well%20Contamination%20Analysis.jpg)  
**Overview:**  
This page focuses on the contamination levels of wells, a vital water source for rural areas.  

**Key Insights:**  
- **Average Pollution Level**: **2.28** (on a scale of 0 to 5).  
- **Total Number of Tests**: **17,380**.  
- About **71.5%** of wells are contaminated, with **40.8%** being chemically polluted and **30.92%** biologically contaminated.  

**Recommendations:**  
- Deploy RO and UV filters to treat wells.  
- Conduct regular water quality monitoring and educate communities on contamination prevention.  

---

### **Page 5: Improvements** 
![Page 5 Improvements](dashboard/Page%205%20Improvements%20.jpg)
**Overview:**  
This page assesses the infrastructure improvements needed to address water access issues.  

**Key Insights:**  
- Key improvements include the installation of **RO filters** and the drilling of new wells.  
- Rural areas account for a substantial share of improvements needed.  

**Recommendations:**  
- Prioritize high-impact improvements such as the installation of RO filters and drilling new wells.  
- Use performance dashboards to ensure the efficient allocation of resources for these improvements.  

---

### **Page 6: Cost of Improvements & Budgeting** 💰  
![Page 6 Cost and Budgeting](dashboard/Page%206%20Cost%20and%20Budgeting.jpg)  
**Overview:**  
This page provides an analysis of the costs associated with water infrastructure improvements.  

**Key Insights:**  
- **RO filters**: **7,093** required, costing **$39.96M**.  
- **New wells**: **3,379** required, costing **$38.86M**.  
- The total improvement cost is estimated to be **$146.74M**, with **80%** allocated to rural areas.  

**Recommendations:**  
- Allocate resources efficiently, prioritizing areas with the highest need.  
- Ensure that funds are used transparently, as shown through performance dashboards.  

---

### **Page 7: Cost and Budgeting Evaluation** 📊  
![Page 7 Cost and Budgeting Evaluation](dashboard/Page%207%20Cost%20and%20Budgeting%20Evaluation.jpg)  
**Overview:**  
This page evaluates the budget allocation and provides insights into the overall financial planning for the water access improvements.  

**Key Insights:**  
- The total budget required for the infrastructure improvements is **$146.74M**.  
- Most of the resources need to be directed toward rural communities, which face the highest challenges in water access.  

**Recommendations:**  
- Ensure the appropriate allocation of funds based on priority areas.  
- Use dashboards to track spending, ensuring maximum impact and resource optimization.  

---

### **Page 8: Vendor Performance Analysis** 🔧  
![Page 8 Vendor Performance Analysis](dashboard/Page%208%20Vendor%20Performance%20Analysis%20.jpg) 
**Overview:**  
This page assesses the performance of vendors responsible for implementing water infrastructure improvements.  

**Key Insights:**  
- **25,398 projects** were completed, focusing mostly on rural areas.  
- Vendor performance varied, with some vendors exceeding budget and delivery time.  

**Recommendations:**  
- Monitor vendor performance using defined metrics to ensure timely, cost-effective delivery of infrastructure.  
- Set benchmarks for vendor efficiency to improve project timelines and cost management.  



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
