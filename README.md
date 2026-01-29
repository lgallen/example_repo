# Scikit-learn Pipeline Tutorial

A brief hands-on tutorial demonstrating how to build production-ready machine learning pipelines using scikit-learn, with hyperparameter tuning via GridSearchCV. My first experience with Claude Code. 

## Purpose

This notebook teaches:
- **Pipelines**: Chaining preprocessing and model training into a single estimator
- **ColumnTransformer**: Applying different transformations to numeric vs categorical features
- **GridSearchCV**: Systematic hyperparameter tuning with cross-validation
- **Web scraping**: Acquiring real-world data using `pandas.read_html()`

## Dataset

The notebook uses **NCAA Men's Basketball NET Rankings** scraped live from [ncaa.com](https://www.ncaa.com/rankings/basketball-men/d1/ncaa-mens-basketball-net-rankings).

**Features:**
- `Wins` / `Losses` - Team's season record
- `Conference` - Conference affiliation (categorical)
- `Non_D1_Wins` - Wins against non-Division I opponents

**Target:** Predict which quad (1-4) a team belongs to based on their wins and other features.

## Setup

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

# Run the notebook
jupyter notebook sklearn_pipeline_example.ipynb
```

## Scikit-learn Documentation

- [Pipeline](https://scikit-learn.org/stable/modules/compose.html#pipeline) - Chaining estimators
- [ColumnTransformer](https://scikit-learn.org/stable/modules/compose.html#columntransformer-for-heterogeneous-data) - Heterogeneous data transformations
- [GridSearchCV](https://scikit-learn.org/stable/modules/grid_search.html#grid-search) - Exhaustive parameter search
- [Cross-validation](https://scikit-learn.org/stable/modules/cross_validation.html) - Model evaluation
- [Pipelines and composite estimators](https://scikit-learn.org/stable/modules/compose.html) - Full guide
