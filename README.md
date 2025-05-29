## 🏏 IPL Cricket Data Analytics Project

This repository contains a complete data analytics pipeline applied to IPL (Indian Premier League) cricket data. It is part of the **CodeAlpha Data Analytics Internship**, and includes web scraping, exploratory data analysis (EDA), and data visualization tasks based on real-world sports data.

---

## 📁 Project Structure
```
CodeAlpha_DataAnalytics/
│
├── Task 1/
│   ├── matches.csv
│   └── deliveries.csv
│
├── Task 2 - EDA/
│   └── Task 2 ( EDA ).ipynb
│
└── Task 3 - Data Visualization/
    └── Task 3 ( Data Visualization ).ipynb
```

## ✅ Tasks Overview

### 🔹 TASK 1: Web Scraping

- Used tools like **BeautifulSoup** and **Scrapy** to scrape relevant IPL data from the web.
- Focused on identifying and collecting **relevant datasets**.
- Parsed and extracted match- and player-level data.
- Created `matches.csv` and `deliveries.csv` datasets.
- Learned and utilized HTML structure and web navigation for accurate data scraping.

### 🔹 TASK 2: Exploratory Data Analysis (EDA)

- Performed in-depth analysis of the datasets.
- **Asked meaningful questions** to guide the analysis.
- Explored data types, structures, and distributions.
- Detected trends, anomalies, and patterns:
  - Top-performing players
  - Toss decision impact
  - Team win/loss trends
  - Player dismissal types
- Validated assumptions using descriptive statistics.

### 🔹 TASK 3: Data Visualization

- Built compelling visual stories using:
  - `Matplotlib`
  - `Seaborn`
  - `Plotly`
- Created insightful visuals including:
  - Top batsmen and bowlers
  - Run trends per over
  - Match-winning patterns
- Focused on clarity, design, and storytelling impact.
- Developed visual dashboards to support strategic insights.

---

## 📊 Dataset Descriptions

### 🗂 matches.csv
Match-level data containing:
- Season, date, city, venue
- Toss winner & decision
- Match winner
- Team names, result status

### 🗂 deliveries.csv
Ball-by-ball data including:
- Over, ball, inning, batter, bowler
- Runs (batsman, extras, total)
- Type of extra (wide, no-ball, etc.)
- Wicket info: type, player dismissed, fielder

---

## 🛠 Tools & Technologies Used

- Python, Jupyter Notebook
- Pandas, NumPy
- BeautifulSoup, Scrapy
- Matplotlib, Seaborn, Plotly
