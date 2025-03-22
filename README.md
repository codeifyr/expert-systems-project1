# Advanced Heart Disease Detection Project

## Overview
This project implements an advanced heart disease detection system with fuzzy logic, ensemble machine learning, and a comprehensive Streamlit UI. It includes data preprocessing, advanced visualization, model interpretability, and deployment options.

## Setup
1. Clone the repository: `git clone <repo-url>`
2. Install dependencies: `pip install -r requirements.txt`
3. Place the raw dataset in `data/raw_data.csv`.

## Usage
- Use the Streamlit UI for interactive predictions: `streamlit run ui/app.py`
- Run basic data analysis: `python notebooks/data_analysis.py` (outputs saved to reports/)
- Run advanced data analysis: `python notebooks/advanced_analysis.py` (outputs saved to reports/)
- Compare model performance in `reports/accuracy_comparison.md`

## Deployment
- Use `docker-compose.yml` for containerized deployment:
  ```bash
  docker-compose up