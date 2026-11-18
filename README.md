# sql-project-cricket-datasets-


# 🏏 Cricket Match Performance & Business Analytics Project (SQL)

This repository contains a comprehensive set of advanced SQL analytical queries designed to extract, aggregate, and evaluate multi-season cricket match statistics. The project explores team success metrics, toss impact, venue distributions, and player performance milestones.

---

## 📂 Project Overview & Key Insights

The queries in this project answer 12 core performance and operational questions based on the `cricket_data1` dataset:

### 1. Match Trends & Season Dynamics
* **Season-wise Match Volume:** Analyzes the total number of matches played across different seasons (`Q2`).

### 2. Team Performance & Win Metrics
* **Top Winning Teams:** Identifies the team with the highest number of overall victories (`Q3`) as well as the top 5 performing franchises (`Q4`).
* **Home vs. Away Performance:** Evaluates venue advantages and geographical performance scores (`Q12`).

### 3. Match Dynamics (Toss & Decision Impact)
* **Toss & Match Correlation:** Measures how often the team winning the toss also wins the match (`Q5`).
* **Captaincy/Strategy Analysis:** Breaks down toss decision preferences (choosing to Bat vs. Bowl) across the dataset (`Q6`).

### 4. Innings Scoring & Run Chase Records
* **1st Innings Extremes:** Tracks the highest (`Q7`) and lowest (`Q8`) scores recorded in the opening innings.
* **Chasing Success:** Captures the highest successful run chase achieved in the 2nd innings (`Q9`).

### 5. Player Accolades & Venue Logistics
* **Player of the Match Dominance:** Highlights individual standout performers with the most match awards (Top 1 and Top 5 lists) (`Q10`, `Q11`).
* **Busiest Venues:** Identifies the stadium/venue that has hosted the highest volume of matches (`Q13`).

---

## 🛠️ Tech Stack & Database
* **Database Management System:** SQL Server / MySQL
* **Key Functions Used:** Aggregations (`COUNT`, `SUM`, `MAX`, `MIN`), `GROUP BY`, `ORDER BY`, Conditional Filtering (`WHERE`), and Result Limiting (`LIMIT`).

---

## 🚀 How to Run the Script
1. Open your SQL environment (e.g., SQL Server Management Studio or MySQL Workbench).
2. Create or select your database: `USE cricket;`
3. Execute the queries sequentially to view structured match analytics and performance insights.
