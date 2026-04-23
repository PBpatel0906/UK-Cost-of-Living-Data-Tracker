# UK-Cost-of-Living-Data-Tracker
Data analytics project that processes UK cost of living datasets to visualise trends in rent, inflation, and daily expenses using Python and statistical analysis.
# UK Cost of Living Data Tracker

## Overview
This project is an open-source data analytics tool that tracks and analyses cost of living trends in the UK. It focuses on key areas such as rent, inflation, and essential daily expenses to understand how living costs change over time.

The goal is to turn raw public data into clear, visual insights that help users understand economic trends across different UK regions.

---

## Features
- Collects UK cost of living data from public sources  
- Cleans and processes raw datasets using Python  
- Analyses trends in rent, inflation, and expenses  
- Generates visualisations for easy interpretation  
- Modular structure for future expansion  

---

## Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- (Optional) Streamlit for dashboard  

---

## Project Structure
uk-cost-living-tracker/
│
├── data/
│   ├── raw/                  # Original datasets (unchanged)
│   ├── processed/           # Cleaned datasets ready for analysis
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_analysis_visualisation.ipynb
│
├── scripts/
│   ├── data_collector.py    # Fetch data from APIs / sources
│   ├── data_cleaning.py     # Cleaning and preprocessing
│   ├── analysis.py          # Core analysis functions
│
├── dashboard/
│   ├── app.py               # Streamlit dashboard (optional but strong)
│
├── visuals/
│   ├── charts/              # Saved graphs and plots
│
├── requirements.txt
├── README.md
└── .gitignore
