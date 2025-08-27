# 🚦 A Deep Dive into the Causes of Road Accidents in Pennsylvania  

## 📌 Introduction  
This project aims to analyze the reasons behind road accidents in Pennsylvania. By combining crash, roadway, and flag datasets, we identify patterns, trends, and major factors contributing to accidents.  

---

## 🎯 Goal  
The main goal is to conduct an in-depth analysis of road accident data to:  
- Identify contributing factors to crashes.  
- Understand accident trends over the years.  
- Provide insights that can be used to improve road safety.  

---

## 👥 Audience  
The insights from this project are relevant for:  
- Road safety organizations  
- Road constructors and engineers  
- Policy makers and politicians  

---

## 🛠️ Methodology  
**1. Data Collection & Integration**  
- Accident data (2010–2021) from COMMVEH, ROADWAYS, and FLAG datasets.  
- Raw data: ~11 JSON files merged into a single CSV.  
- Tools: **Python (Pandas)** for data wrangling.  

**2. Data Cleaning & Preprocessing**  
- Removed irrelevant columns.  
- Merged subsets of datasets (Crash + Roadway + Flag).  
- Standardized formats for analysis.  

**3. Visualization & Analysis**  
- Loaded cleaned data into **Tableau** for interactive dashboards.  
- Created multiple visualizations to explore accident causes.  

---

## 📊 Key Visualizations  
1. **Accidents per Year** – Peak in **2016**; significant drop in **2020** (likely due to COVID-19).  
2. **Accidents vs Speed Limit** – Most accidents occurred on **25 mph roads**.  
3. **Accidents by Road Type** – **State highways** recorded the most crashes.  
4. **State Highways vs Road Conditions** – State highways have the most **icy roads**, contributing to accidents.  
5. **Unexplained Accidents** – Many accidents reported with **“no apparent reason”** in the dataset.  
6. **Alcohol vs Road Conditions** – Road conditions (ice, design) caused more accidents than alcohol or driver negligence.  

---

## 🔑 Key Findings  
- Sudden drop in crashes in **2020**.  
- **25 mph speed limit** roads show unusually high accident rates.  
- **State highways** are accident hotspots.  
- Many accidents lack a clearly recorded cause.  
- Alcohol is **not** the main factor – road conditions and poor design are bigger contributors.  

---

## ✅ Recommendations  
1. Improve **road maintenance** on state highways (especially winter).  
2. Investigate accidents with **no recorded cause** further.  
3. Enforce **stricter rules** regarding driver demographics (e.g., driver age).  

---

## 📈 Tools & Tech Stack  
- **Python (Pandas, NumPy)** – data preprocessing & integration  
- **Tableau** – data visualization & dashboards  
- **CSV/JSON** – data storage & cleaning 
