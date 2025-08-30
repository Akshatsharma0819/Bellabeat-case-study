# Bellabeat Case Study – Google Data Analytics Capstone

## 📌 Business Objective
Analyze Fitbit usage data to uncover trends in activity and sleep, then translate insights into marketing strategies for Bellabeat’s Time watch.

## ❓ Key Questions
- What are the key usage patterns in daily activity and sleep?
- How do activity levels relate to calorie burn and sleep quality?
- When and how should Bellabeat Time engage users for maximum impact?

## 🧰 Tools Used
- MySQL (cleaning and transformation)
- Tableau (visualization and dashboard)
- Excel (initial exploration)

## 🧼 Data Cleaning Approach
- Imported raw Excel data into MySQL using `VARCHAR(50)` for flexible ingestion.
- Standardized dates and times; cast to proper types (`DATE`, `DATETIME`, `INT`, `DECIMAL`).
- Produced clean tables: `cleaned_dailyactivity`, `cleaned_steps`, `cleaned_sleepday`.

## 📊 Visualizations
- Average Daily Steps Over Time
- Sleep Duration Distribution
- Steps vs Calories Burned
- Average Steps by Activity Level
- Combined Dashboard (steps, sleep, calories)

## 📁 Repository Structure
- `Business-Problem/` – problem_statement.md
- `Data/Raw/` – Raw data tables
- `Data/Cleaned/` – final cleaned CSVs
- `SQL/` – raw table creation scripts
- `Visuals/` – PNG exports of Tableau charts
- `Presentation/` – slides 

## 👤 Author
- Akshat Sharma — Google Data Analytics Certificate
- Last modified - 30-08-2025
