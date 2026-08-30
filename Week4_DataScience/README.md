
# 📕 Week 4 — Capstone Project: IPL Data Analysis

Final week of a 4-week Data Science with Python internship. A self-directed capstone project applying the full skillset (cleaning, visualization, statistical reasoning) to a real dataset, going beyond the base requirement to build a full portfolio-ready data story.

## 🎯 Objective

Perform an end-to-end exploratory data analysis on IPL match data — uncovering what actually drives team success, from toss decisions to venue trends to winning strategies.

## 📂 Dataset

**`ipl_comprehensive_dataset.csv`** — match-level IPL data (2008–2026), covering teams, toss details, venues, scores, results, and player-of-the-match records for every match.

## ✅ Tasks Completed

- Cleaned data (missing values, duplicates) and standardized team names (e.g., RCB rebrand)
- Analyzed team-wise wins and win percentage
- Investigated toss impact and toss-decision success rate
- Compared winning methods (by runs vs. by wickets) across seasons
- Analyzed venue-wise match distribution and scoring patterns
- Identified top Player of the Match award holders

## 🔍 Key Insights

- Mumbai Indians lead all-time with **155 wins**, but win % is a fairer consistency measure — CSK (55.6%) and MI (53.3%) rank highest among long-history teams.
- Toss outcome barely matters (**51.56%** win rate for toss winners), but toss **decision** does — fielding first wins **53.7%** of matches vs. **44.3%** for batting first, independently confirmed by the overall runs-vs-wickets split (**660 vs. 558**).
- Top 10 venues host **45.45%** of all matches ever played — IPL cricket is heavily venue-concentrated.
- A "normal" competitive score falls between **141–184 runs** (league average: 161.6).
- AB de Villiers leads all-time Player of the Match awards (25), followed by Chris Gayle and Virat Kohli (22 each).

## 🛠️ Tools Used

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Google Colab`

## 📁 Files

```
Week4-IPL-Analysis/
├── README.md
├── IPLanalysis.ipynb
└── IPL_Analysis_Report.pdf
```

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn
```

Open `IPLanalysis.ipynb` in Jupyter Notebook or Google Colab and run all cells.

## 📄 Full Report

A detailed 2-page summary of all findings is available in [`IPL_Analysis_Report.pdf`](./IPL_Analysis_Report.pdf).

## 🚀 Future Scope

- Incorporate ball-by-ball data to compute individual batsman run totals (top run scorers) — not possible with the current match-level dataset
- Build a head-to-head rivalry analysis between specific teams (e.g., CSK vs. MI)
- Extend the toss-decision analysis by venue to check if the chasing advantage holds everywhere or is pitch-specific

## 👤 Author

**Rohan Kumar**
MCA Student, Sage University, Indore
[GitHub Portfolio](https://github.com/rohanjha023/Rohan-DataAnalyst-Internship-Portfolio)
