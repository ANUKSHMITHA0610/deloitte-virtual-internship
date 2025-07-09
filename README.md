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

📂 [Click here to download or view the dashboard walkthrough (MP4)](./Task1_Telemetry_Dashboard/dashboard_walkthrough.mp4)


### 📈 Task 2: Equality Score Classification

## 🎯 Objective
Classify the level of gender pay equality per job role and location based on provided Equality Scores.

## 📁 Files
- `Equality Table.xlsx`: Original file
- `Updated_Equality_Table.xlsx`: With classification column added

## 🧮 Formula Used in Excel
```excel
=IF(ABS(C2)<=10, "Fair", IF(ABS(C2)<=20, "Unfair", "Highly Discriminative"))


## 🛠️ Tools & Skills Used
- Tableau
- Microsoft Excel
- Data Visualization
- Data Classification
- Excel Formulas
- Data Analytics
