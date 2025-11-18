# YouTube-Trending-Videos-Dataset

This repository contains a simple analysis of the YouTube-Trending-Videos-Dataset (160k videos),
aimed at extracting actionable recommendations to increase video views.

## Key findings
- Posting time (4:00–5:00) correlates with higher views.
- Optimal title length appears under 100 characters.
- Like rate (likes/views) is a useful proxy for video quality (target ~0.03).

## Files
- `YouTube_Trending_Videos_Dataset.ipynb` : Jupyter/Colab notebook with code and plots.
- `figures/` : Saved plots (PNG).
- `_YouTube Trending Videos Dataset.pdf` : 1-page summary (ready to send to clients).

## How to reproduce
1. Open `YouTube_Trending_Videos_Dataset.ipynb` in Google Colab.
2. Upload `youtube.csv` (Kaggle dataset) to Colab.
3. Run all cells.

## Tech
Python, pandas, matplotlib, seaborn, Google Colab
