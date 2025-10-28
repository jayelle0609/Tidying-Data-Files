# Tidying Data Files

## Overview
This repository contains a chunk of my Python scripts for **tidying and cleaning data** before visualization in Tableau. 
Often, the datasets I download from data.gov.sg comes in a **wide format**, 
which can be very inconvenient for analysis and visualization in Tableau, as Tableau Public's interface does not pivot data very effectively. 

Hence, I will first clean the data and tidy it into long format in Python, before creating any Tableau Visualizations.

---

## Features
- Convert wide datasets to long/tidy format using **pandas.melt()**.
- Separate combined columns into single observations.
- Handle inconsistencies and bad formats with **pd.replace()**.
- Prepare datasets for visualizations like bar charts, heatmaps, and dashboards.
- Optional cleaning steps including:
  - Dropping unnecessary rows or columns
  - Renaming columns for clarity
  - Resetting indexes

---

