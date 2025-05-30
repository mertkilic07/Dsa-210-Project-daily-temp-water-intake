# 🌡️ Daily Temperature vs. Water Intake 💧

### 📌 Project Overview  
Hydration is a fundamental aspect of human health, playing a crucial role in bodily functions such as temperature regulation, metabolic processes, and overall well-being. This study aims to investigate whether **daily temperature and atmospheric humidity influence water intake habits**, exploring the correlation between **average temperature data from Meteostat (Istanbul Kurtköy)**, **humidity levels**, and **personal water consumption logs**.  

Initially, I manually tracked my daily **step count** to analyze physical activity alongside hydration behavior. However, step count is **not allowed as a variable in this project**. Therefore, I decided to use **"calories burned by step"** instead—this derived metric retains physical activity context while adhering to the project constraints.

By systematically collecting and analyzing data, this project seeks to provide empirical evidence supporting the hypothesis that **higher temperatures lead to increased water consumption**.  

The study integrates **daily temperature and humidity records retrieved from the Meteostat API**, **personal water consumption logs exported from WaterMinder**, and **step-based calorie expenditure** tracked manually. Statistical techniques are applied to assess the strength of the relationship between these variables. Visualization techniques such as **scatter plots and time-series graphs** are utilized to effectively represent patterns in the data. If significant correlations are found, the results may serve as a foundation for future predictive models estimating hydration needs under varying weather conditions.  

This project contributes to the broader field of behavioral and environmental analytics by examining how **climatic factors influence daily hydration behavior**. The findings may provide insights for **personalized hydration tracking**, especially for individuals exposed to heat or those with varying activity levels.  

---

## 🏆 Motivation  
Drinking water is essential for health, yet it often feels like a chore. As someone who is physically active, I realized that **drinking water feels easier on hot days**, and I became curious whether **humidity levels also affect this pattern**.  

Therefore, I decided to analyze my own behavior to explore this question further.  
My hypothesis is:  
**"Individuals are more likely to consume greater amounts of water on hotter days and in drier conditions."**  

---

## 🔍 Data Sources  

This study uses three primary data sources:  

### 🌡️ Temperature & Humidity Data – Meteostat API  
- **Source:** [Meteostat API](https://meteostat.net/en/)  
- **Location:** Istanbul Kurtköy (closest to Sabancı University)  
- **Format:** Excel (daily average temperature & humidity)  
- **Date Range:** Customizable based on study period  

### 🔥 Calories Burned by Step – Manually Tracked  
- **Source:** Manually calculated using health app metrics  
- **Metric Used:** Calories burned through step count  
- **Format:** Excel  

> Step count was manually tracked using a mobile fitness tracker.  
> Due to project restrictions on using step count directly, **calories burned by step** was calculated and used instead.  

### 💧 Water Intake – WaterMinder CSV Export  
- **Source:** [WaterMinder App](https://apps.apple.com/)  
- **Access Method:** CSV export  
- **Format:** CSV (daily water intake in milliliters)  
- **Date Range:** Full historical logs  

---

## 📊 Analysis Plan  

1. **Data Collection:**  
   - Export **daily temperature and humidity data** from Meteostat  
   - Collect **calories burned by step** data manually  
   - Export **daily water intake logs** from WaterMinder  

2. **Data Cleaning:**  
   - Format date columns  
   - Group water logs by day  
   - Merge all datasets on common date  
   - Remove missing values  

3. **Exploratory Data Analysis (EDA):**  
   - Generate **time-series plots** for each variable  
   - Analyze **trend consistency and variability**  

4. **Correlation Analysis & Hypothesis Test:**  
   - Run **Pearson correlation tests**  
   - Test the hypothesis:  
     _“Higher temperatures are positively correlated with higher water intake.”_

---

## 📅 Project Timeline  

| Milestone                         | Date         |
|----------------------------------|--------------|
| 🔹 Proposal Submission (README)  | **March 10** |
| 🔹 Data Collection & EDA         | **April 18** |
| 🔹 Machine Learning Phase        | **May 23**   |
| 🔹 Final Report Submission       | **May 30**   |

---
