# 🌡️ Daily Temperature vs. Water Intake 💧

### 📌 Project Overview  
Hydration is a fundamental aspect of human health, playing a crucial role in bodily functions such as temperature regulation, metabolic processes, and overall well-being. This study aims to investigate whether **daily temperature and atmospheric humidity influence water intake habits**, exploring the correlation between **average temperature data from Meteostat (Istanbul Kurtköy)**, **humidity levels**, and **personal water consumption data from WaterMinder**.  

By systematically collecting and analyzing data, this project seeks to provide empirical evidence supporting the hypothesis that **higher temperatures and lower humidity levels lead to increased water consumption**.  

To achieve this objective, the study will integrate **daily temperature and humidity records retrieved from the Meteostat API** and **water intake logs exported from WaterMinder**. Additionally, **hydration level recommendations**, as suggested by WaterMinder for a healthy individual, will be included as a benchmark for comparison. Statistical techniques will be applied to assess the strength of the relationship between these variables. Furthermore, visualization techniques such as **scatter plots and time-series graphs** will be utilized to represent the data effectively. If significant correlations are found, the study will explore potential applications, including **predictive modeling** to estimate individual water consumption based on temperature, humidity, and hydration level recommendations.  

This project contributes to the broader field of behavioral and environmental analytics by examining how **climatic factors influence daily hydration habits**. The findings may provide insights that can be utilized in **personalized hydration recommendations**, particularly for individuals engaged in physical activities or those residing in extreme temperature conditions.  

---

## 🏆 Motivation  
Drinking water is important for everyone’s health. However, for me, it always felt like a task. Since I do sports, I need to pay extra attention to my water intake. But I realized that on hot days, drinking water felt easier. Additionally, I wondered whether humidity levels also play a role in hydration behavior. This made me curious about the relationship between temperature, humidity, and water consumption, so I decided to analyze it.  

As a result, I developed the following hypothesis:  
**"Individuals are more likely to consume greater amounts of water on hotter days and in drier conditions."**  

---

## 🔍 Data Sources  
This study utilizes three primary data sources: **daily temperature and humidity records from Meteostat**, **hydration level recommendations from WaterMinder**, and **personal water consumption records from WaterMinder**. Below are the details of how each dataset is obtained and why they were chosen.  

### **🌡️ Temperature & Humidity Data – Meteostat API**  
📌 **Source:** [Meteostat API](https://meteostat.net/en/)  
📌 **Location:** Istanbul Kurtköy (Closest available region to my university)  
📌 **Data Format:** Excel (Daily average temperature & humidity)  
📌 **Date Range:** Customizable based on study period  

- The **Meteostat API** provides reliable historical weather data, including both **temperature and humidity levels**.  
- To ensure **relevance to my personal environment**, I selected **Istanbul Kurtköy**, the nearest weather station to Sabancı University.  
- The dataset consists of **daily average temperature and humidity values**, allowing for comprehensive analysis.  
- The data is exported in **Excel format**, making it easy to integrate into statistical analysis and visualization processes.  

### **💧 Hydration Level – WaterMinder Recommendation**  
📌 **Source:** [WaterMinder](https://apps.apple.com/)  
📌 **Data Type:** Recommended hydration level for a healthy individual)  
📌 **Measurement Unit:** Milliliters per day  

- WaterMinder provides **recommended hydration levels** as a goal based on general health guidelines.
- If a person reach the goal it becames %100.  
- Including this recommendation in the analysis allows for a deeper understanding of **how closely actual consumption aligns with ideal hydration levels under different weather conditions**.  

### **💧 Water Intake Data – WaterMinder CSV/PDF Export**  
📌 **Source:** [WaterMinder](https://apps.apple.com/)  
📌 **Access Method:** Subscription-based CSV/PDF export  
📌 **Data Format:** CSV / PDF (Daily water intake in milliliters)  
📌 **Date Range:** Full historical records available upon subscription  

- **WaterMinder** offers **structured hydration data logging**, making it an ideal source for personal water intake records.  
- The application provides **CSV and PDF export options**, enabling systematic data collection.  
- The dataset includes **daily water consumption (ml)**, which will be used to observe trends and correlations with temperature and humidity changes.  

By combining **Meteostat’s weather data**, **WaterMinder’s hydration logs**, and **hydration recommendations**, this study aims to analyze whether **higher temperatures and lower humidity levels lead to increased water intake**, contributing to a broader understanding of personal hydration behavior.  

---

## 📊 Analysis Plan  
1. **Data Collection:**  
   - Fetching daily temperature and humidity data from **Meteostat API (Kurtköy location)**.  
   - Retrieving **recommended hydration levels** from WaterMinder.  
   - Exporting **daily water intake logs from WaterMinder (CSV/PDF format)**.  

2. **Data Cleaning:**  
   - Formatting dates, handling missing values, ensuring consistency.  

3. **Correlation Analysis:**  
   - Pearson correlation to determine statistical relationships between **temperature, humidity, hydration recommendations, and actual water intake**.  

---

## 📅 Project Timeline  
| Milestone | Date |
|-----------|------|
| 🔹 Proposal Submission (README) | **March 10** |
| 🔹 Data Collection & EDA | **April 18** |
| 🔹 Machine Learning Implementation | **May 23** |
| 🔹 Final Report Submission | **May 30** |

---
