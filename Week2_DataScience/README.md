# 📗 Week 2 — Data Visualization

Part of a 4-week Data Science with Python internship. This week focuses on exploratory data visualization using Matplotlib and Seaborn.

## 🎯 Objective

Practice Matplotlib & Seaborn visualizations through an exploratory data analysis on COVID-19 data.

## 📂 Dataset

**COVID-19 Clean Complete Dataset** — `covid_19_clean_complete.csv`

**49,068 rows × 10 columns:** `Province/State`, `Country/Region`, `Lat`, `Long`, `Date`, `Confirmed`, `Deaths`, `Recovered`, `Active`, `WHO Region`

## ✅ Tasks Completed

- Checked data quality (no missing values in case/death/recovery columns; `Province/State` had expected nulls for countries without state-level reporting)
- Converted the `Date` column to proper datetime format
- Plotted a confirmed COVID-19 cases trend line over time (India)
- Compared the top 5 countries by confirmed cases with a bar chart
- Built a correlation heatmap (Confirmed, Deaths, Recovered, Active)
- Created a scatter plot of confirmed cases vs. deaths

## 🔍 Key Results

- **India trend:** Confirmed cases stayed low and nearly flat until around April 2020, then rose sharply through mid-2020, reflecting the rapid acceleration of the outbreak.
- **Top 5 countries by confirmed cases:** US (4,290,259), Brazil (2,442,375), India (1,480,073), Russia (816,680), South Africa (452,529) — with a steep drop-off after the US, showing cases were concentrated in a small set of countries.
- **Correlation heatmap:** Confirmed cases correlate most strongly with Active cases (**0.950**), followed by Deaths (**0.912**) and Recovered cases (**0.896**).
- **Scatter plot:** Confirmed cases and deaths show a strong positive relationship (consistent with the 0.912 correlation), though the exact ratio varies by country — likely due to differences in healthcare capacity and testing coverage.

## 🛠️ Tools Used

`Python` · `Pandas` · `Matplotlib` · `Seaborn` · `Google Colab`

## 📁 Files

```
Week2-DataScience/
├── README.md
└── Week2_DataScience.ipynb
```

## ▶️ How to Run

```bash
pip install pandas matplotlib seaborn
```

Open `Week2_DataScience.ipynb` in Jupyter Notebook or Google Colab and run all cells (`covid_19_clean_complete.csv` should be in the same directory or uploaded when prompted).

## 👤 Author

**Rohan Kumar**
MCA Student, Sage University, Indore
[GitHub Portfolio](https://github.com/rohanjha023/Rohan-DataAnalyst-Internship-Portfolio)
