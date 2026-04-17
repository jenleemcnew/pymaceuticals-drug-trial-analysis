# Pymaceuticals Drug Trial Analysis

## Overview
A data analysis and visualization project examining the results of an animal study 
conducted by Pymaceuticals, Inc., a fictional pharmaceutical company. The study 
tested the effectiveness of various drug regimens on mice with squamous cell 
carcinoma (SCC) tumors over a 45-day period, with a focus on comparing Capomulin 
against other treatment regimens.

---

## Analysis
- Cleaned duplicate mouse data from the dataset
- Generated summary statistics (mean, median, variance, standard deviation, SEM) 
  for tumor volume across all drug regimens
- Visualized the number of timepoints per drug regimen using bar charts
- Plotted the distribution of male vs. female mice using pie charts
- Calculated final tumor volumes for the four most promising regimens: 
  Capomulin, Ramicane, Infubinol, and Ceftamin
- Identified potential outliers using IQR method and box plots
- Plotted tumor volume over time for a single Capomulin-treated mouse
- Generated a scatter plot of mouse weight vs. average tumor volume for Capomulin
- Computed correlation coefficient and linear regression for weight vs. tumor volume

---

## Tech Stack
- Python (Pandas, Matplotlib, SciPy, NumPy)
- Jupyter Notebook

---

## Repository Contents
| File | Description |
|------|-------------|
| `pymaceuticals_starter.ipynb` | Full analysis notebook |
| `data/Mouse_metadata.csv` | Mouse subject metadata |
| `data/Study_results.csv` | Tumor measurement study results |
