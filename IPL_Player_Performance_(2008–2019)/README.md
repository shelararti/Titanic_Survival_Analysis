# 🏏 IPL Exploratory Data Analysis (EDA)

A comprehensive exploratory data analysis (EDA) on the Indian Premier League (IPL) dataset. This project dives into team performance, player statistics, venue trends, and seasonal patterns using Python and popular data visualization libraries.

---

## 📁 Datasets Used

- `matches.csv` – Match-level details (teams, winner, toss, venue, etc.)
- `deliveries.csv` – Ball-by-ball records (runs scored, wickets, player names)

Both files are publicly available and used extensively in cricket analytics.

---

## 📊 Objectives

This project explores:

1. **Team Performances** – Match participation and win stats  
2. **Player Analysis** – Top batsmen and bowlers  
3. **Venue Trends** – Venues with highest average scores  
4. **Seasonal Patterns** – Runs per season  
5. **Data Cleaning & Merging** – Handling missing values, merging datasets  
6. **Storytelling via Visuals** – Insightful plots to uncover trends

---

## 🧠 Key Insights

- Which teams play and win the most matches?
- Who are the top 10 run scorers and wicket-takers?
- Which stadiums are high-scoring?
- How has scoring evolved over the years?
- Does winning the toss correlate with match results?

---

## 🛠️ Tech Stack

- **Python**
  - `pandas` – Data manipulation
  - `matplotlib`, `seaborn` – Plotting & visualization
  - `numpy` – Numerical computing

---

## 🧹 Data Cleaning Highlights

- Filled missing values in winner column with `"No Result"`
- Dropped columns with excessive nulls (`umpire1`, `umpire2`, etc.)
- Merged `deliveries.csv` and `matches.csv` for deep insights

---

## ✅ Dataset Source

- [Kaggle Dataset](https://www.kaggle.com/datasets/nowke9/ipldata)

---
