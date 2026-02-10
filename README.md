# ⚽ Football Insights 360° – Club & Player Analytics Dashboard

Football Insights 360° is an interactive Power BI dashboard built to analyze professional football data across players, clubs, competitions, matches, and market value trends. This project demonstrates how business intelligence and data visualization techniques can be applied to sports analytics for performance evaluation and strategic decision-making.

---

## 📌 Project Objective

The objective of this project is to transform raw football data into meaningful insights that help analyze:
- Player performance and efficiency
- Club dominance and squad strength
- Competition-level trends
- Market value distribution and growth over time

The dashboard simulates a real-world football analytics system used by analysts, scouts, and management teams.

---

## 📊 Dataset Overview

The dataset is based on Transfermarkt-style football data and includes:
- Player details (age, position, market value)
- Club and competition information
- Match and appearance-level statistics
- Goals, assists, minutes played, and discipline metrics

The data is structured across multiple related tables to support scalable analysis.

**Dataset Link :**
https://www.kaggle.com/datasets/davidcariboo/player-scores

---

## 🧩 Data Model

A **Star Schema** design is used to ensure efficient querying and accurate filtering:

- **Fact Table:** Appearances (match-level performance metrics)
- **Dimension Tables:** Players, Clubs, Matches, Competitions, Date

This structure enables advanced DAX calculations and smooth interactivity across visuals.

---

## 📈 Dashboard Pages

1. **Executive Overview**
   - High-level KPIs and overall football trends

2. **Club Dashboard**
   - Squad composition, market value, and performance metrics

3. **Player Dashboard**
   - Individual performance analysis using per-90 statistics and match-by-match data

4. **Match & Competition Dashboard**
   - League-level comparison and club performance within competitions

5. **Market Value Analysis**
   - Financial insights, top-valued players/clubs, and year-over-year trends

---

## 🧠 Key Metrics & Analysis

- Goals, assists, and minutes played
- Goal contribution per game and per 90 minutes
- Market value distribution and trends
- Year-over-year market value growth
- Competition-level scoring intensity

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **DAX** for advanced calculations
- **Power Query** for data transformation
- **Star Schema** data modeling

---

## 🚀 Key Features

- Interactive slicers and filters
- Drill-through navigation
- Match-by-match performance tables
- Football-themed visual design
- Time intelligence using DAX

---

## 🔮 Future Enhancements

- Transfer history and player movement analysis
- Advanced match event data (shots, passes)
- Predictive modeling for player market value
- Integration with real-time or live datasets

---

## 📎 Project Files

- `Football.pbix` – Power BI report file
- `README.md` – Project documentation


*This project is created for educational and portfolio purposes.*
