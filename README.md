# weather-data-analysis
Exploring weather patterns with Python! Analyzing weather data, uncovering trends, and creating insightful visualizations using NumPy, Pandas, and Matplotlib.
# Weather Data Analysis Using Python

## Overview

This project explores historical weather data using Python, NumPy, Pandas, and Matplotlib. It analyzes daily temperatures and precipitation to identify patterns and compare weather conditions across months.

## Objectives

- Calculate average, minimum, and maximum temperatures.
- Analyze daily and monthly temperature trends.
- Calculate total precipitation and identify wettest days.
- Visualize weather patterns using line charts, histograms, and bar charts.
- Practice data cleaning, statistical analysis, and CSV file handling.

## Dataset

- **Location:** Delhi, India
- **Period:** January–December 2025
- **Source:** [Open-Meteo Historical Weather API](https://open-meteo.com/en/docs/historical-weather-api)
- **Format:** CSV

The dataset includes daily mean, maximum, and minimum temperatures and total precipitation. Historical values are derived from weather reanalysis data.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook
- Requests

## Project Structure

```text
weather-data-analysis/
├── Weather_Data_Analysis.ipynb
├── weather_data_real.csv
├── monthly_weather_summary.csv
├── requirements.txt
├── README.md
└── charts/
    ├── daily_temperature.png
    ├── monthly_temperature.png
    └── monthly_rainfall.png
```

## Key Analysis

1. Daily temperature statistics and trends
2. Monthly average temperature comparison
3. Monthly precipitation analysis
4. Distribution of daily mean temperatures
5. Identification of the hottest and wettest days

## How to Run

1. Clone or download this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Open `Weather_Data_Analysis.ipynb` in Jupyter Notebook.
4. Run the notebook cells in order.

The notebook downloads historical weather data through the Open-Meteo API. An internet connection is required to retrieve fresh copies of the dataset.

## Learning Outcomes

This project demonstrates beginner-level skills in data collection, CSV handling, data cleaning, descriptive statistics, time-based grouping, and data visualization.

## Data Attribution

Weather data provided by [Open-Meteo](https://open-meteo.com/). Review its [terms and attribution requirements](https://open-meteo.com/en/features#terms) before redistributing the dataset.

## Future Improvements

- Compare multiple cities.
- Analyze humidity and wind speed.
- Study seasonal weather patterns across multiple years.
- Build an interactive weather dashboard.

