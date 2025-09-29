# Instagram Influencer Analysis & Prediction

**Project**: Analysis and prediction on Top Instagram Influencers data  
**Author**: Sneha  

## Project Overview
This project analyzes a dataset of top Instagram influencers (ranked by followers) to explore relationships between follower counts, engagement metrics and a computed `influence_score`. It also builds a regression model to predict `influence_score` from engagement and follower features.

## Dataset
- File: `top_instagram_influencers.csv`
- Columns (key): `rank`, `channel_info`, `influence_score`, `posts`, `followers`, `avg_likes`, `60_day_eng_rate`, `new_post_avg_like`, `total_likes`, `country`
- Notes: `total_likes` may be represented in large units (e.g., billions) in the dataset — check the units before using directly in ratios.

## Repository Structure
├─ insta_influence.ipynb # Jupyter notebook with analysis and modeling
├─ top_insta_influencers.csv
└─ README.md


## Requirements
- Python 3.8+
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, joblib
(install via `pip install -r requirements.txt`)

## How to run
1. Clone the repo and place `top_insta_influencers.csv` in the project folder.
2. Open `Insta-Influencer-Analysis.ipynb` with Jupyter Notebook / JupyterLab.
3. Run cells sequentially. Recommended to run from top to bottom after reading the notebook comments.

## What’s included
- Data loading and preprocessing
- Exploratory data analysis (EDA) and visualizations
- Feature engineering (ratios for likes and posts normalized by followers)
- Regression modeling using Random Forest
- Model evaluation (MSE, R²) and feature importance

## Results (summary)
- The Random Forest model provides a baseline for predicting `influence_score`. Key predictive features include follower count and recent engagement measures (`60_day_eng_rate`, `avg_likes`). Exact metrics (MSE, R²) are reported within the notebook.
