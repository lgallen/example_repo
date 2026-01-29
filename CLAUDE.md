# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A tutorial repository demonstrating scikit-learn pipelines with GridSearchCV hyperparameter tuning, using NCAA basketball data.

## Development Environment

- Python 3.12 with virtual environment in `venv/`
- Dependencies listed in `requirements.txt`: pandas, numpy, scikit-learn, jupyter, requests

## Setup & Running

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter notebook sklearn_pipeline_example.ipynb
```

## Repository Contents

- `sklearn_pipeline_example.ipynb`: Complete ML pipeline tutorial — web scraping, feature engineering, preprocessing pipelines, GridSearchCV hyperparameter tuning, and model evaluation using NCAA basketball data
