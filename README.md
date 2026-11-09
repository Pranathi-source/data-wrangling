 Python & Data Wrangling

## Project Overview

This project cleans a messy workout dataset using Python and Pandas. It handles missing values, duplicates and wrong values, creates new columns, filters rows, and visualizes the results with Matplotlib and Seaborn.

## Dataset

`data.csv` has 32 rows and 5 columns:

| Column | Description |
|--------|-------------|
| Duration | Length of the workout in minutes |
| Date | Date of the workout |
| Pulse | Average heart rate |
| Maxpulse | Maximum heart rate |
| Calories | Calories burned |


## Row Filters

- Workouts of 60 minutes or longer: 23
- High-intensity workouts: 2
- Weekend workouts: 8
- Long (60 min or more) weekend workouts: 6
- Workouts with more than 350 calories: 7

## Visualizations

1. **Line chart (Matplotlib):** calories burned per day
2. **Scatter plot (Seaborn):** Duration vs Calories, coloured by Intensity
3. **Heatmap (Seaborn):** correlation between the numeric columns

## Tools Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Files in This Repository

- The `.ipynb` notebook: full code, outputs and charts

## How to Run

1. Open the notebook in Google Colab or Jupyter.
2. Upload `data.csv` to the same folder as the notebook.
3. Run all cells from top to bottom.
