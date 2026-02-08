# Covid-Death
SQL project for data analysis using real datasets. Includes data cleaning, exploratory analysis, and business insights using advanced SQL queries.
# Covid-19 Data Exploration using SQL

## 📌 Project Overview

This project focuses on **exploratory data analysis (EDA)** of global Covid-19 data using **SQL**.
The goal is to analyze infection rates, death rates, and vaccination progress across countries and continents, and to prepare clean, structured data for further visualization in tools like **Power BI** or **Tableau**.

The project demonstrates strong SQL fundamentals and real-world data analysis techniques commonly used by **Data Analysts**.

---

## 🗂️ Dataset

The analysis is based on two datasets:

* **CovidDeaths** – cases, deaths, population, and dates per country
* **CovidVaccinations** – vaccination data per country and date

> Data Source: Public Covid-19 datasets (commonly used in analytics portfolios)

---

## 🛠️ Skills & Concepts Used

* SQL Joins
* Common Table Expressions (CTEs)
* Window Functions (`OVER`, `PARTITION BY`)
* Aggregate Functions (`SUM`, `MAX`, `AVG`)
* Data Type Conversion (`CAST`)
* Creating SQL Views
* Data Cleaning & Filtering
* Analytical Thinking

---

## 🔍 Analysis Performed

### 1️⃣ Base Data Cleaning

* Filtered out non-country records (World, Continents, EU)
* Converted text-based numeric columns into integers
* Created a reusable base dataset using a CTE

---

### 2️⃣ Covid Impact Analysis

* Total cases vs total deaths
* Death percentage per country
* Percentage of population infected
* Countries with the highest infection rate
* Countries with the highest death count

---

### 3️⃣ Global Overview

* Total global cases
* Total global deaths
* Global death percentage

---

### 4️⃣ Vaccination Analysis

* Joined deaths and vaccination datasets
* Calculated **rolling (cumulative) vaccinations per country** using a window function
* Calculated percentage of population vaccinated

---

### 5️⃣ View Creation for Visualization

* Created a SQL View (`PercentPopulationVaccinated`) to simplify future dashboards
* Ready for direct use in Power BI or Tableau

---

## 📊 Example Insights

* Infection and death rates vary significantly across countries
* Some countries show high infection rates but relatively lower death percentages
* Vaccination rollout speed differs greatly between regions

---

## 🚀 How to Use

1. Import the Covid datasets into SQL Server
2. Run the SQL script step by step
3. Use the created **View** for visualization
4. Connect Power BI / Tableau to the database for dashboards

---

## 📁 Project Structure

```
├── Covid-19-Data-Exploration.sql
├── README.md
```

---

## 🎯 Why This Project Matters

This project showcases:

* Real-world SQL problem solving
* Clean and structured analytical thinking
* Ability to transform raw data into actionable insights
* Skills required for **Junior / Entry-Level Data Analyst roles**

---

## 👤 Author

**Ahmed Magdy**
Aspiring Data Analyst | SQL | Data Visualization

---

## 📬 Contact

Feel free to connect or provide feedback through GitHub.

⭐ If you found this project useful, consider giving it a star!
