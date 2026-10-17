# Page View Time Series Visualizer

This project analyzes daily freeCodeCamp Forum page views from May 2016 to December 2019 using Python, Pandas, Matplotlib, and Seaborn.

## Project Overview

The project visualizes page-view trends over time and examines yearly trends and monthly seasonality.

## Features

- **Line Plot:** Displays daily page views from May 2016 to December 2019.
- **Bar Plot:** Compares average daily page views for each month across different years.
- **Box Plots:** Visualizes yearly growth trends and monthly seasonal patterns.
- **Data Cleaning:** Removes the top and bottom 2.5% of page-view values to reduce the influence of extreme values.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn

## Project Files

- `time_series_visualizer.py` — Data cleaning and visualization functions.
- `main.py` — Runs the visualization functions.
- `fcc-forum-pageviews.csv` — Page-view dataset.
- `test_module.py` — Unit tests.

## How to Run

Install the required libraries:

```bash
py -3.13 -m pip install --only-binary=:all: pandas matplotlib seaborn
```

Run the project:

```bash
py -3.13 main.py
```

Run the tests:

```bash
py -3.13 -m unittest test_module.py
```

## Generated Visualizations

Running the project generates:

- `line_plot.png`
- `bar_plot.png`
- `box_plot.png`

## Learning Outcomes

- Data cleaning with Pandas
- Time-series data analysis
- Grouping data by year and month
- Creating visualizations with Matplotlib and Seaborn
- Testing Python code using `unittest`

## Author

Sharvesh K
