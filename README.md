# 🏏 IPL Performance Analytics Dashboard

A complete exploratory data analysis of **17 seasons of Indian Premier League cricket (2008–2024)** using Python, Pandas, Matplotlib, and Seaborn.

---

## 📌 Project Overview

This project analyzes **1,095 IPL matches** and **260,920 ball-by-ball deliveries** to uncover performance trends, team dominance, player statistics, and hidden stories that standard cricket coverage never talks about.

---

## 🔍 Key Questions Answered

- Which teams have won the most matches in IPL history?
- Does winning the toss give a meaningful advantage?
- Do teams prefer batting or fielding after winning the toss?
- Which venues host the most IPL matches?
- Who are the all-time top run scorers and wicket takers?
- Who dominates in death overs — with bat and ball?
- What is the greatest single season performance in IPL history?

---

## 🤯 Most Interesting Findings

| Finding | Stat |
|---|---|
| All-time top scorer | V Kohli — 8,014 runs |
| Greatest single season | V Kohli 2016 — 973 runs (untouched for 8 years) |
| Most sixes ever | CH Gayle — 359 sixes in 141 matches |
| Gayle's six rate | 2.55 sixes/match vs Rohit Sharma's 1.12 |
| Toss advantage | Only 50.6% — barely better than a coin flip |
| Best finisher | MS Dhoni — 2,786 death over runs (nearly double #2) |
| Best death bowler | Rashid Khan — 7.77 economy in death overs |

---

## 📊 Visualizations

### Phase 4 — Match Analysis
- Team win counts across all seasons
- Toss decision preference (bat vs field)
- Toss winner vs match winner correlation
- Matches played per season (2008–2024)
- Top 10 venues by matches hosted

### Phase 6 — Hidden Stories
- Sixes per match — Gayle vs The World
- Top scorer each season (2008–2024)
- Death over batting kings
- Best death over bowlers by economy

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| Pandas | Data loading, cleaning, groupby, merging |
| Matplotlib | Charts, layouts, annotations |
| Seaborn | Bar chart styling and color palettes |
| Jupyter Notebook | Analysis and presentation |

---

## 📁 Project Structure

```
ipl-performance-analytics/
│
├── IPL_Analysis.ipynb          # Main notebook — all analysis and charts
├── matches.csv                 # Match-level data (1,095 matches)
├── deliveries.csv              # Ball-by-ball data (260,920 deliveries)
│
├── chart1_team_wins.png        # All-time team wins
├── chart2_toss_decision.png    # Bat vs field preference
├── chart3_toss_effect.png      # Toss winner vs match winner
├── chart4_matches_per_season.png  # Matches per season trend
├── chart5_top_venues.png       # Top 10 venues
└── chart6_hidden_stories.png   # Advanced player analytics
```

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/YourUsername/ipl-performance-analytics.git
cd ipl-performance-analytics
```

**2. Install dependencies**
```bash
pip install pandas matplotlib seaborn jupyter
```

**3. Launch Jupyter Notebook**
```bash
jupyter notebook
```

**4. Open `IPL_Analysis.ipynb` and run Kernel → Restart & Run All**

---

## 📦 Dataset

- **Source:** [IPL Complete Dataset 2008–2024 — Kaggle](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)
- **matches.csv** — 1,095 rows, 20 columns (match results, toss, venue, teams)
- **deliveries.csv** — 260,920 rows, 17 columns (ball-by-ball data)

---

## 📈 Skills Demonstrated

- Data loading and exploration with Pandas
- Data cleaning — handling missing values, fixing data types, standardizing inconsistent labels
- Exploratory Data Analysis (EDA)
- Data visualization with Matplotlib and Seaborn
- Deriving and communicating insights from data

---

## 👤 Author

**Your Name**  Sumit Thakor
[GitHub](https://github.com/ThakorSumit)

---

*Built as a portfolio project to demonstrate Python data analytics skills.*
