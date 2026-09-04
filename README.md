# Red Wine Quality Modeling — Historical ML Project

> Historical machine-learning project. The repository name is kept for continuity, but the checked-in dataset is presented here conservatively as **red wine quality data**, rather than being described as specifically Port wine.

## Overview

This project explores regression-style modeling for wine-quality scores using physicochemical variables from the included `winequality-red.csv` dataset.

The original notebook includes exploratory analysis, correlation analysis, visualization and predictive modeling. It also experiments with AutoML tooling.

## Repository structure

```text
.
├── red_wine_quality_modeling.ipynb  # EDA and modeling notebook
├── winequality-red.csv               # red-wine quality dataset
├── requirements.txt                  # stable core dependencies
└── .github/workflows/quality.yml
```

## Modeling workflow

```text
CSV dataset
   ↓
Exploratory analysis
   ↓
Feature inspection / correlation analysis
   ↓
Train / validation workflow
   ↓
Regression model evaluation
```

## Reproduce locally

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook red_wine_quality_modeling.ipynb
```

The legacy notebook may reference environment-sensitive AutoML packages. Those are intentionally not forced into the core requirements because compatibility depends on Python and operating-system versions.

## What this project demonstrates

- exploratory data analysis with structured data;
- regression-oriented model evaluation;
- correlation and feature analysis;
- notebook experimentation with Python data-science tooling.

## Portfolio context

This is preserved as earlier Data Science work. My current focus is **Data Engineering, lakehouse architecture, distributed processing, dbt, data quality and cloud platforms**. See [`harrisvailvelame/pedrohvel`](https://github.com/harrisvailvelame/pedrohvel).

---

**Author:** Harrison Grant Vail  
[LinkedIn](https://www.linkedin.com/in/harrison-grant-vail) · [GitHub](https://github.com/harrisvailvelame)
