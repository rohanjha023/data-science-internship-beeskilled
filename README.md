# 📊 Data Science with Python — 4-Week Internship Project

A 1-month, hands-on Data Science internship covering the full workflow — from Python fundamentals to exploratory data analysis to a machine learning model — completed in four weekly milestones, each with its own dataset, tasks, and deliverables.

## 🗓️ Internship Structure

| Week | Focus | Dataset | Key Skill |
|---|---|---|---|
| [Week 1](#-week-1--python-for-data-science-basics) | Python for Data Science Basics | Student Marks Dataset (1,000 rows) | Pandas, NumPy, Data Cleaning |
| [Week 2](#-week-2--data-visualization) | Data Visualization | COVID-19 Clean Complete Data (49,068 rows) | Matplotlib, Seaborn |
| [Week 3](#-week-3--machine-learning-introduction) | Machine Learning Introduction | Student Performance Dataset (9,873 rows) | Scikit-Learn, Linear Regression |
| [Week 4](#-week-4--capstone-project--certificate) | Capstone Project | IPL Match Data (2008–2026) | End-to-end EDA & Reporting |

---

## 📘 Week 1 — Python for Data Science Basics

**Objective:** Learn Pandas + NumPy fundamentals and basic data cleaning.

**Dataset:** Student Marks Dataset (Kaggle) — 1,000 rows × 8 columns: gender, race/ethnicity, parental education, lunch, test preparation course, math/reading/writing scores.

**Tasks Completed:**
- Loaded and inspected the dataset's structure with Pandas
- Checked for missing values and duplicates — dataset was fully clean (0 missing, 0 duplicates)
- Calculated average, maximum, and minimum scores across subjects
- Generated full descriptive statistics with `df.describe()`

**Key Results:**
- Average scores: Math — 66.1, Reading — 69.2, Writing — 68.1 (out of 100)
- Math had the widest spread (std ≈ 15.2) and was the only subject with a minimum score of 0

**Notebook:** `Week1_DataScience.ipynb`

---

## 📗 Week 2 — Data Visualization

**Objective:** Practice Matplotlib & Seaborn visualizations through exploratory data analysis.

**Dataset:** COVID-19 Clean Complete Data — 49,068 rows × 10 columns: Province/State, Country/Region, Date, Confirmed, Deaths, Recovered, Active, WHO Region.

**Tasks Completed:**
- Plotted a confirmed-cases trend line over time (India)
- Compared the top 5 countries by confirmed cases
- Built a correlation heatmap (Confirmed, Deaths, Recovered, Active)
- Created a scatter plot of confirmed cases vs. deaths

**Key Results:**
- India's cases stayed flat until ~April 2020, then rose sharply through mid-2020
- Top 5 by confirmed cases: US (4.29M), Brazil (2.44M), India (1.48M), Russia (817K), South Africa (453K)
- Confirmed cases correlate most strongly with Active cases (**0.950**), then Deaths (**0.912**), then Recovered (**0.896**)

**Notebook:** `Week2_DataScience.ipynb`

---

## 📙 Week 3 — Machine Learning Introduction

**Objective:** Learn and apply a regression model using Scikit-Learn.

**Dataset:** Student Performance Dataset (Kaggle) — 10,000 original rows, reduced to **9,873 rows** after removing 127 duplicates; hours studied, previous scores, sleep hours, sample papers practiced, extracurricular activities, performance index.

**Tasks Completed:**
- Cleaned data and removed duplicate rows
- Encoded categorical feature (Extracurricular Activities → binary)
- Split data into training and test sets (80/20)
- Applied Linear Regression to predict student performance index

**Key Results:**
- **R² = 0.9884** — the model explains almost all the variance in performance
- **MAE = 1.65** — predictions are typically within ~1.65 points of the actual value

**Notebook:** `Week3_DataScience.ipynb`

---

## 📕 Week 4 — Capstone Project + Certificate

**Project:** IPL Data Analysis — Exploratory Data Analysis on IPL match data (2008–2026), going beyond the base requirement (team performance) to build a full data story suitable for a portfolio.

**Objective:** Apply the full skillset (cleaning, visualization, statistical reasoning) to a real, self-directed dataset and produce a professional report.

**Dataset:** `ipl_comprehensive_dataset.csv` — match-level data covering every IPL season: teams, toss details, venues, scores, results, and player-of-the-match records.

**Key Insights:**
- Mumbai Indians lead all-time with **155 wins**, but win % (not raw count) is a fairer measure of consistency — CSK (55.6%) and MI (53.3%) rank highest among teams with a long history.
- Toss outcome barely matters (**51.56%** win rate for toss winners), but toss **decision** does — fielding first wins **53.7%** of matches vs. **44.3%** for batting first, independently confirmed by the overall runs-vs-wickets win split (**660 vs. 558**).
- Top 10 venues host **45.45%** of all matches ever played — IPL cricket is heavily venue-concentrated.
- A "normal" competitive score falls between **141–184 runs** (league average: 161.6).
- AB de Villiers leads all-time Player of the Match awards (25), followed by Chris Gayle and Virat Kohli (22 each).

**Deliverables:**
- `IPLanalysis.ipynb` — full notebook with code, charts, and observations
- `IPL_Analysis_Report.pdf` — 2-page summary report of all findings

---

## 🛠️ Tools & Libraries Used

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Scikit-Learn` · `Google Colab`

## 📁 Repository Structure

```
DataScience-Python-Internship/
├── README.md
├── Week1-DataScience/
│   ├── README.md
│   └── Week1_DataScience.ipynb
├── Week2-DataScience/
│   ├── README.md
│   └── Week2_DataScience.ipynb
├── Week3-DataScience/
│   ├── README.md
│   └── Week3_DataScience.ipynb
└── Week4-DataScience/
|   ├── README.md
|   ├── IPLanalysis.ipynb
|   └── IPL_Analysis_Report.pdf
|___Internship_Analysis_Report.pdf
```

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Open any notebook in Jupyter or Google Colab and run all cells. Datasets are sourced from Kaggle / public COVID-19 repositories — each notebook loads its dataset from the same directory it's run in.

## 👤 Author

**Rohan Kumar**
MCA Student, Sage University, Indore
[GitHub Portfolio](https://github.com/rohanjha023/Rohan-DataAnalyst-Internship-Portfolio)
