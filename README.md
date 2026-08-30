# 📊 Data Science with Python — 4-Week Internship Project

A 1-month, hands-on Data Science internship covering the full workflow — from Python fundamentals to exploratory data analysis to a machine learning model — completed in four weekly milestones, each with its own dataset, tasks, and deliverables.

## 🗓️ Internship Structure

| Week | Focus | Dataset | Key Skill |
|---|---|---|---|
| [Week 1](#-week-1--python-for-data-science-basics) | Python for Data Science Basics | Student Marks Dataset | Pandas, NumPy, Data Cleaning |
| [Week 2](#-week-2--data-visualization) | Data Visualization | COVID-19 Global Data | Matplotlib, Seaborn |
| [Week 3](#-week-3--machine-learning-introduction) | Machine Learning Introduction | Student Performance Dataset | Scikit-Learn, Linear Regression |
| [Week 4](#-week-4--capstone-project--certificate) | Capstone Project | IPL Match Data (2008–2026) | End-to-end EDA & Reporting |

---

## 📘 Week 1 — Python for Data Science Basics

**Objective:** Learn Pandas + NumPy fundamentals and basic data cleaning.

**Dataset:** Student Marks Dataset (Kaggle) — gender, race/ethnicity, parental education, test preparation course, math/reading/writing scores.

**Tasks Completed:**
- Loaded and explored the dataset with Pandas
- Cleaned missing data
- Calculated average, max, and min scores across subjects
- Displayed and summarized results using Pandas

**Notebook:** `Week1_DataScience.ipynb`

---

## 📗 Week 2 — Data Visualization

**Objective:** Practice Matplotlib & Seaborn visualizations through exploratory data analysis.

**Dataset:** COVID-19 Global Data (Our World in Data) — location, date, total cases, total deaths, total vaccinations.

**Tasks Completed:**
- Plotted confirmed case trend lines over time (India)
- Compared top 5 countries by confirmed cases
- Built a correlation heatmap (Confirmed, Deaths, Recovered, Active)
- Created a scatter plot of confirmed cases vs. deaths, with a strong positive correlation (**r ≈ 0.912**)

**Notebook:** `Week2_DataScience.ipynb`

---

## 📙 Week 3 — Machine Learning Introduction

**Objective:** Learn and apply a regression model using Scikit-Learn.

**Dataset:** Student Performance Dataset (Kaggle) — hours studied, previous scores, sleep hours, sample papers practiced, performance index.

**Tasks Completed:**
- Cleaned data and encoded categorical features (Extracurricular Activities → binary)
- Split data into training and test sets (80/20)
- Applied Linear Regression to predict student performance index
- Evaluated model accuracy: **R² = 0.9884**, **MAE = 1.65**

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
├── Week1_DataScience.ipynb
├── Week2_DataScience.ipynb
├── Week3_DataScience.ipynb
├── Week4_IPLanalysis.ipynb
└── IPL_Analysis_Report.pdf
```

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Open any notebook in Jupyter or Google Colab and run all cells. Datasets are sourced from Kaggle / Our World in Data — links are provided in each notebook's introductory section.

## 👤 Author

**Rohan Kumar**
MCA Student, Sage University, Indore
[GitHub Portfolio](https://github.com/rohanjha023/Rohan-DataAnalyst-Internship-Portfolio)
