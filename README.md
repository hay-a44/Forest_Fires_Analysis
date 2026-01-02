# Forest Fires Data Analysis

## Overview
This project analyzes the Forest Fires dataset from the UCI Machine Learning Repository to explore how weather and environmental factors influence forest fire severity.

## Data Source
UCI Machine Learning Repository  
https://archive.ics.uci.edu/ml/machine-learning-databases/forest-fires/forestfires.csv

## Tools & Technologies
- Python
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook

## Project Structure
```
Project Structure
Forest-Fires-Data-Analysis/
│
├── data/
│   ├── raw/
│   │   └── forestfires.csv
│   └── processed/
│       └── forestfires_cleaned.csv
│
├── notebooks/
│   └── forest_fire_analysis.ipynb
│
├── outputs/
│   ├── tables/
│   │   ├── significant_fires.csv
│   │   ├── top_five_fires.csv
│   │   └── monthly_summary.csv
│   └── figures/
│       ├── fire_count_by_month.png
│       ├── area_vs_wind.png
│       └── area_vs_rain.png
│
├── README.md
└── requirements.txt
```
## Analysis Objectives

## The project performs the following analyses:

1-Load the dataset directly from the URL and inspect its structure.

2-Count the total number of observations and identify significant fires (area burned > 0).

3-Display the month, day, and burned area for all significant fire observations.

4-Identify the top five fires based on total area burned.

5-Extract corresponding month, temperature, relative humidity (RH), wind, rain, and area for the top fires.

6-Reorder the dataset by month (January–December).

7-Add a boolean column indicating whether a fire burned any area.

8-Compute monthly averages of wind, temperature, RH, and burned area.

## Visualize:

1-Monthly fire counts using a bar plot

2-Relationships between burned area and wind and rainfall using scatter plots

## Key Insights

1-Fire occurrence varies significantly by month.

2-Larger burned areas tend to be associated with specific weather conditions.

3-Wind and rainfall show observable relationships with fire severity.

## Run Project
1-Download ipynb file from "Data" Folder.

2-Open Jupyter Notebook either online or on your Desktop.

3-Load file in to Notebook.

4- Run Code.
