# Uber Data Analysis Project

## Overview

This project focuses on analyzing Uber trip data to extract valuable insights, implement machine learning models, and create interactive dashboards for visual exploration. It incorporates advanced features such as geospatial analysis, sentiment analysis, cost analysis.

---

## Features

### 1. Data Cleaning

- Parsed `START_DATE` and `END_DATE` into datetime format.
- Filled missing values for `CATEGORY` and `PURPOSE`.
- Dropped rows with invalid or missing data.
- Calculated trip durations and categorized trips based on distance.

### 2. Geospatial Analysis

- Simulated `START_LAT`, `START_LONG`, `END_LAT`, and `END_LONG` coordinates for trip origins and destinations.
- Calculated actual travel distances using geodesic formulas.

### 3. Data Augmentation

- Simulated traffic conditions (`Light`, `Moderate`, `Heavy`).
- Adjusted trip durations based on traffic levels.

### 4. Cost Analysis

- Implemented an Uber pricing model:
  - Base fare: \$2.5
  - Cost per mile: \$1.5
  - Cost per minute: \$0.25
- Estimated trip costs based on distance and adjusted duration.

### 5. Machine Learning Models

- **Random Forest Classifier**: Predicts trip categories (`Business`, `Personal`, etc.) based on distance and duration.
- Model evaluation using:
  - Classification Report
  - Confusion Matrix

### 6. Sentiment Analysis

- Simulated trip descriptions.
- Analyzed sentiments (`Positive`, `Neutral`, `Negative`) based on keyword matching.

### 7. Advanced Dashboards

Interactive dashboard built with **Dash** and **Plotly**, featuring:

- **Trip Statistics**:
  - Bar chart for trips by day of the week.
  - Pie chart for trip purposes.
  - Dropdown filter for specific days.
- **Time Series Analysis**:
  - Line chart for miles traveled over time.
  - Date range picker for filtering.
- **Geospatial Analysis**:
  - Scatter mapbox for trip start locations.
- **Cost Analysis**:
  - Histogram and boxplot for estimated costs.
- **Traffic Analysis**:
  - Bar chart showing the impact of traffic levels on trip durations.
- **Sentiment Analysis**:
  - Histogram for sentiment distribution.

### 8. Detailed Reports

- PDF report generation using **FPDF**, summarizing:
  - Key insights (e.g., average trip cost, total miles traveled).
  - Advanced analytics and visualizations.

---

## Setup Instructions

### Prerequisites

1. Python 3.7+
2. Required libraries:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - sklearn
   - dash
   - plotly
   - fpdf
   - geopy

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn dash plotly fpdf geopy
```

### Running the Project

1. Place the dataset (`UberDataExtracted.csv`) in the same directory as the script.
2. Run the script:
   ```bash
   python uber_data_analysis.py
   ```
3. Open the dashboard link in your browser (it will automatically open).
4. Interact with the tabs and filters to explore the data.

---

## How to Use the Dashboard

### Tabs

1. **Trip Statistics**:
   - View trips by day and purpose.
   - Filter by specific days to refine insights.
2. **Time Series Analysis**:
   - Analyze miles traveled over time.
   - Use the date range picker for custom time frames.
3. **Geospatial Analysis**:
   - Visualize trip start locations on a map.
4. **Cost Analysis**:
   - Explore estimated costs and their distributions.
5. **Traffic Analysis**:
   - Assess how traffic conditions impact trip durations.
6. **Sentiment Analysis**:
   - Review sentiment trends in trip descriptions.

---

## Key Insights

- **Average Trip Cost**: `$<calculated_value>`
- **Total Miles Traveled**: `<calculated_value>` miles
- **Most Common Trip Day**: `<calculated_value>`

---

## Future Enhancements

1. Integration with live Uber APIs for real-time data.
2. More sophisticated sentiment analysis using NLP libraries like `spaCy` or `TextBlob`.
3. Enhanced geospatial analytics with heatmaps and clustering.

---

## Acknowledgments

- Dataset provided as part of Uber Data Analysis.
- Libraries and tools: Dash, Plotly, FPDF, Scikit-learn, Geopy.

---

## Contact
**Name**: [NEERAJ KONDAVEETI]\
**Email**: [neerajkondaveeti1901@gmail.com]\
**LinkedIn**: [www.linkedin.com/in/neeraj-kondaveeti-806b67208]

