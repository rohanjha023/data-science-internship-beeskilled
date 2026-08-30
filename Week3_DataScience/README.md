# 📙 Week 3 — Machine Learning Introduction

Part of a 4-week Data Science with Python internship. This week introduces regression modeling using Scikit-Learn.

## 🎯 Objective

Learn and apply a regression model (Scikit-Learn) to predict student performance.

## 📂 Dataset

**Student Performance Dataset** ([Kaggle](https://www.kaggle.com))

**10,000 original rows × 6 columns** — `Hours_studied`, `Previous_scores`, `Sleep_hours`, `sample_question_papers_practiced`, `Extracurricular Activities`, `performance_index`. After removing 127 duplicate rows, **9,873 clean rows** were used for modeling.

## ✅ Tasks Completed

- Cleaned the data and dropped duplicate rows (10,000 → 9,873)
- Encoded the categorical `Extracurricular Activities` column into binary form
- Split the data into training and test sets (80/20)
- Trained a Linear Regression model to predict the performance index
- Evaluated the model using R² and Mean Absolute Error (MAE)

## 🔍 Key Results

- **R² Score: 0.9884** — the model explains almost all of the variance in student performance.
- **MAE: 1.65** — predictions are typically within about 1.65 points of the actual performance index.
- Together, these indicate a very strong linear relationship between the input features (study hours, previous scores, sleep, practice) and final performance.

## 🛠️ Tools Used

`Python` · `Pandas` · `Scikit-Learn` · `Google Colab`

## 📁 Files

```
Week3-DataScience/
├── README.md
└── Week3_DataScience.ipynb
```

## ▶️ How to Run

```bash
pip install pandas scikit-learn
```

Open `Week3_DataScience.ipynb` in Jupyter Notebook or Google Colab and run all cells.

## 👤 Author

**Rohan Kumar**
MCA Student, Sage University, Indore
[GitHub Portfolio](https://github.com/rohanjha023/Rohan-DataAnalyst-Internship-Portfolio)
