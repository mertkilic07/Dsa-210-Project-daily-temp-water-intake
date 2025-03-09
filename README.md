# 🌡️ Daily Temperature vs. Water Intake 💧

### 📌 Project Overview
Hydration is a fundamental aspect of human health, playing a crucial role in bodily functions such as temperature regulation, metabolic processes, and overall well-being. This study aims to investigate whether **daily temperature influences water intake habits**, exploring the correlation between **average temperature data from Meteostat which belongs to Istanbul Kurtköy** and **personal water consumption data from WaterMinder**.  

Given my active lifestyle and engagement in sports, maintaining an adequate water intake is essential. However, I have often perceived drinking water as a task rather than a natural habit. Over time, I observed that on **warmer days, drinking water felt less burdensome**, prompting me to question whether external environmental conditions, such as temperature, influence hydration behavior. By systematically collecting and analyzing data, this project seeks to provide empirical evidence supporting the hypothesis that **higher temperatures lead to increased water consumption**.  

To achieve this objective, the study will integrate **daily temperature records retrieved from the Meteostat API** and **water intake logs exported from WaterMinder**. Statistical techniques  will be applied to assess the strength of the relationship between the two variables. Additionally, visualization techniques such as **scatter plots or time-series graphs** will be utilized to represent the data effectively. If a significant correlation is found, the study will explore potential applications, including **predictive modeling** to estimate individual water consumption based on temperature variations.  

This project contributes to the broader field of behavioral and environmental analytics by examining how **climatic factors influence daily hydration habits**. The findings may provide insights that can be utilized in **personalized hydration recommendations**, particularly for individuals engaged in physical activities or those residing in extreme temperature conditions.  


---

## 🏆 Motivation
Drinking water is important for everyone’s health. However, for me, it always felt like a task. Since I do sports, I need to pay extra attention to my water intake. But I realized that on hot days, drinking water felt easier. This made me curious about the relationship between temperature and water consumption, so I decided to analyze it.  

As a result, I developed the following hypothesis:  
**"Individuals are more likely to consume greater amounts of water on hotter days."**  

---

## 🔍 Data Sources  
This study utilizes two primary data sources: **daily temperature records from Meteostat** and **personal hydration records from WaterMinder**. Below are the details of how each dataset is obtained and why they were chosen.  

### **🌡️ Temperature Data – Meteostat API**  
📌 **Source:** [Meteostat API](https://dev.meteostat.net/)  
📌 **Location:** Istanbul Kurtköy (Closest available region to my university)  
📌 **Data Format:** Excel (Daily average temperature)  
📌 **Date Range:** Customizable based on study period  

- The **Meteostat API** provides reliable historical weather data.  
- To ensure **relevance to my personal environment**, I selected **Istanbul Kurtköy** as the location, as it is the nearest weather station to Sabancı Universty.
- The dataset consists of **daily average temperature values**, allowing for analysis.  
- The data is exported in **Excel format**. 

### **💧 Water Intake Data – WaterMinder CSV/PDF Export**  
📌 **Source:** [WaterMinder](https://apps.apple.com/)  
📌 **Access Method:** Subscription-based CSV/PDF export  
📌 **Data Format:** CSV / PDF (Daily water intake in milliliters)  
📌 **Date Range:** Full historical records available upon subscription  

- While searching for a suitable application to track my daily water intake, I found **WaterMinder**, which offers **structured hydration data logging**.  
- The application provides **CSV and PDF export options**, allowing me to access and analyze my past hydration records.  
- The dataset includes **daily water consumption (ml)**, which will be used to observe trends and correlations with temperature changes.  

By combining **Meteostat’s weather data** with **WaterMinder’s hydration logs**, this study aims to analyze whether **higher temperatures lead to increased water intake**, contributing to a broader understanding of personal hydration behavior.  

---

## 📊 Analysis Plan
1. **Data Collection**:  
   - Fetching daily temperature data from Meteostat API (**Kurtköy location**).  
   - Exporting daily water intake logs from WaterMinder (CSV/PDF).  
2. **Data Cleaning**:  
   - Formatting dates, handling missing values, ensuring consistency.   
3. **Correlation Analysis**:  
   - Pearson correlation to determine statistical relationships.  
---


## 📅 Project Timeline
| Milestone | Date |
|-----------|------|
| 🔹 Proposal Submission (README) | **March 10** |
| 🔹 Data Collection & EDA | **April 18** |
| 🔹 Machine Learning Implementation | **May 23** |
| 🔹 Final Report Submission | **May 30** |

---

