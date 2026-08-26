# Sports Data Analysis — MDST Fall 2026

A beginner-friendly project for the **Michigan Data Science Team (MDST)** at the University of Michigan.

Members pick a sport and a dataset they actually care about and walk the full data science pipeline on it: **scrape → clean → visualize → model → explain**. 

> No prior experience required. If you know a little Python and can read a box score, you can do this project.

---

## Tech Stack

- **Python 3** — the whole project
- **Jupyter / Google Colab** — all coursework is notebooks; Colab cells are pre-written so you don't need a local setup
- **pandas** — DataFrames, cleaning, `groupby` aggregation, `read_html`
- **NumPy** — vectorized math, `argmax`, summary statistics
- **Matplotlib** — the core plotting library
- **seaborn** — correlation heatmaps and statistical plots
- **scikit-learn** — `train_test_split`, `LinearRegression`, `Ridge`, `Lasso`, `LogisticRegression`, `KNeighborsClassifier`, `cross_val_score`, `LeaveOneOut`
- **Git / GitHub** — version control for your own fork or branch

---

## Repository Structure

```
F26-SportsDataAnalysis/
├── Data/                  # 12 scraped datasets, each with the code that produced it
│   └── <Dataset>/
│       ├── *.csv          # the data
│       ├── scraping.py    # fetches the tables and writes the CSVs
│       └── check.py       # lists every table id on the source page (use this to find new tables)
├── Starter Code/          # weekly notebooks — fill in the blanks
│   ├── pandas_numpy_michigan_football.ipynb
│   ├── cleaning.ipynb
│   ├── visualization.ipynb
│   └── modeling.ipynb
└── Example Code/
    └── visualization_and_aggregation_example.ipynb   # worked end-to-end example (Lions 2024)
```

---


## Resources

- [pandas DataFrame API](https://pandas.pydata.org/docs/reference/frame.html)
- [NumPy routines](https://numpy.org/doc/stable/reference/routines.html)
- [Matplotlib pyplot](https://matplotlib.org/stable/api/pyplot_summary.html)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn user guide](https://scikit-learn.org/stable/user_guide.html)
- [Beautiful Soup docs](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

---
