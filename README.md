# Overview
This project focuses on analyzing and visualizing building-level energy consumption data. The goal was to clean raw interval data, detect anomalies, and design a Power BI dashboard that highlights usage trends, peak load times, and actionable insights for decision-makers.

# Data Pipeline
## Data Cleaning & Quality Checks
- Verified timestamps and validated conversions.
- Checked for missing values and duplicate rows.
- Flagged anomalies, including days with identical readings and extreme outliers (using 99.9th percentile thresholds).
- Identified intervals with zero consumption to investigate potential outages or sensor malfunctions.

## Exploratory Analysis
- Calculated average daily and hourly usage trends.
- Compared weekday vs. weekend patterns.
- Highlighted periods of irregular consumption.

## Dashboard Development
- Built KPI cards for key metrics (average daily usage, peak hours, highest weekday usage).
- Designed heatmaps to visualize usage by day of week and time of day.
- Included filters and slicers for flexible exploration.

## Tools & Libraries
- **Power BI:** KPI cards, DAX measures, heatmaps, slicers
- **Python** (pandas, matplotlib) for anomaly detection and preprocessing
- **Excel** for initial data validation

# Results & Insights
- Identified 90+ zero-usage intervals, scattered across weekdays and weekends, suggesting potential sensor issues.
- Detected two days with identical readings, likely due to frozen sensors or logging errors.
- Outlier detection flagged extreme spikes consistent with high-load equipment cycles.
- Dashboard enabled quick identification of peak demand hours and comparisons between weekdays and weekends.

# Author
## Daiki Sai
daikisai77@gmail.com | https://www.linkedin.com/in/daiki-sai/
