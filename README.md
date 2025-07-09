# Deloitte Virtual Internship – Data Analytics

This repository contains completed tasks from the Deloitte Australia Virtual Internship on Forage.

## 🧠 Overview
Completed a self-paced internship focused on real-world data analytics and forensic technology applications. Tasks included interactive data dashboards and classification of equality scores.

## 📁 Tasks

### 📊 Task 1: Daikibo Telemetry Dashboard

## 🎯 Objective
Analyze machine downtime data from four factories and identify where machines break down the most.

## 🗂 Data
- Source: `daikibo-telemetry-data.json`
- Collected across Tokyo, Osaka, Berlin, and Shenzhen factories.

## 📊 Visualizations Created

### 1️⃣ Sheet: **Down Time per Factory**
- Bar chart showing total downtime for each factory.
- Helps identify which factory experienced the most machine breakdowns.

### 2️⃣ Sheet: **Down Time per Device Type**
- Bar chart showing total downtime by machine type.
- Reveals which machines were most prone to failure.

### 3️⃣ Final Dashboard
- Combines both charts into a single interactive dashboard.
- The factory bar chart acts as a filter — selecting a factory updates the machine-type chart accordingly.


## 🛠️ Tools Used
- Tableau Public 
- Calculated fields to quantify "unhealthy" machine status.

## 🎥 Walkthrough Video

📂 [Click here to download or view the dashboard walkthrough (MP4)](https://github.com/ANUKSHMITHA0610/deloitte-virtual-internship/blob/main/Task1_Telemetry_Dashboard/dashboard%20walkthrough.mp4)

## ✅ Outcome

- Identified the factory with the highest machine downtime.
- Filtered and analyzed machine-level failures within that factory.
- Created an interactive Tableau dashboard to assist stakeholders with data-driven decision-making.

---
### 📈 Task 2: Equality Score Classification

## 🎯 Objective
Classify the level of gender pay equality per job role and location based on provided Equality Scores.

## 📁 Files
- `Equality Table.xlsx`: Original file
- `Updated_Equality_Table.xlsx`: With classification column added

## 🧠 Classification Logic

The Equality Score is categorized into three classes based on the following ranges:

| Equality Score Range     | Classification          |
|--------------------------|--------------------------|
| -10 to +10               | Fair                     |
| -20 to -11 or 11 to 20   | Unfair                   |
| Less than -20 or over 20 | Highly Discriminative    |


## 🧮 Formula Used in Excel
```excel
=IF(ABS(C2)<=10, "Fair", IF(ABS(C2)<=20, "Unfair", "Highly Discriminative"))

## ✅ Outcome

- Added a new column **“Equality class”** based on classification rules.
- Enabled HR teams to assess pay fairness and take corrective action.
- Improved visibility into **salary-based gender inequality** across factories.

---

## 🛠 Skills Demonstrated

- Data Cleaning and Analysis  
- Tableau Dashboard Development  
- JSON Data Handling  
- Excel Formula Writing and Logic Building  
- Business Insight Interpretation  
- Data-Driven Decision Support


## 📅 Completion

- ✅ **Completed:** July 2025  
- 🌐 **Platform:** Forage  
- 🏢 **Organization:** Deloitte Australia (Forensic Technology team simulation)  
- 🔗 **Program Link:** [Deloitte Australia – Data Analytics Job Simulation (Forage)](https://www.theforage.com/virtual-internships/prototype/TzTg5R9AqtnnB2mJ6/Deloitte-Australia-Data-Analytics-Virtual-Internship)

