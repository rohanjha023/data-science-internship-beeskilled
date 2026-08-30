# 📘 Week 1 — Python for Data Science Basics

Part of a 4-week Data Science with Python internship. This week focuses on Pandas and NumPy fundamentals through basic data cleaning and exploration.

## 🎯 Objective

Learn Pandas + NumPy fundamentals and basic data cleaning.

## 📂 Dataset

**Student Marks Dataset** ([Kaggle](https://www.kaggle.com)) — `StudentsPerformance.csv`

**1,000 rows × 8 columns:** `gender`, `race/ethnicity`, `parental level of education`, `lunch`, `test preparation course`, `math score`, `reading score`, `writing score`

## ✅ Tasks Completed

- Loaded the dataset and inspected its structure (shape, columns, dtypes) using Pandas
- Checked for missing values and duplicate records
- Calculated average, maximum, and minimum scores across subjects
- Generated full descriptive statistics with `df.describe()`

## 🔍 Key Results

- **Data quality:** No missing values and no duplicate records — the dataset was clean out of the box.
- **Average scores:** Math — 66.1, Reading — 69.2, Writing — 68.1 (out of 100). Reading had the highest average of the three subjects.
- **Range:** Math had the widest spread (std ≈ 15.2) and was the only subject with a score of 0. Minimum scores were 0 (Math), 17 (Reading), and 10 (Writing); all three subjects had at least one perfect score of 100.

## 🛠️ Tools Used

`Python` · `Pandas` · `NumPy` · `Google Colab`

## 📁 Files

```
Week1-DataScience/
├── README.md
└── Week1_DataScience.ipynb
```

## ▶️ How to Run

```bash
pip install pandas numpy
```

Open `Week1_DataScience.ipynb` in Jupyter Notebook or Google Colab and run all cells (`StudentsPerformance.csv` should be in the same directory or uploaded when prompted).

## 👤 Author

**Rohan Kumar**
MCA Student, Sage University, Indore
[GitHub Portfolio](https://github.com/rohanjha023/Rohan-DataAnalyst-Internship-Portfolio)
