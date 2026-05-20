# Bank Marketing Campaign Analysis

> EDA and feature analysis on a real-world telemarketing dataset to identify the drivers of term deposit subscriptions — with implications for targeting strategy and ML modelling.

---

## Overview

This project analyses a bank's direct marketing campaign dataset (phone calls to clients) to understand which customer segments and call characteristics are most likely to result in a term deposit subscription. The analysis is structured to feed directly into a classification model.

## Key questions explored

- Which customer profiles (age, job, marital status) convert at higher rates?
- Does call duration correlate with subscription outcome?
- How does previous campaign contact affect current conversion?
- Which features carry the most predictive signal for downstream ML?

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

## Project structure

```
bank-marketing-eda-python/
├── data/
│   └── bank_marketing.csv         # Source dataset
├── notebooks/
│   └── bank_marketing_eda.ipynb   # Full analysis notebook
└── README.md
```

## Selected findings

- **Call duration** is the strongest single predictor of subscription — calls under 5 minutes rarely convert
- **Retired and student** segments show disproportionately high conversion rates versus their population share
- Clients **not previously contacted** show lower baseline conversion, but respond well to longer calls
- **May** is the highest-volume campaign month but not the highest-converting — suggesting inefficient resource allocation

## How to run

```bash
git clone https://github.com/Sunil12Subu/bank-marketing-eda-python
cd bank-marketing-eda-python
pip install pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook notebooks/bank_marketing_eda.ipynb
```

---

*Part of a data analysis portfolio by [Sunil Subramaniam Sreedhar](https://linkedin.com/in/sunil-subramaniam-sreedhar) — Senior Data Analyst based in Dortmund, Germany.*
