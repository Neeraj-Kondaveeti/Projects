
# State-by-State Carbon Emission Trends: A Decade of Insights Among U.S. States

## Project Overview
This project investigates greenhouse gas (GHG) emissions trends across U.S. states from 2010 to 2022. Using data from the EPA’s Greenhouse Gas Reporting Program (GHGRP), it aims to provide actionable insights through interactive visualizations. The project emphasizes spatial, temporal, and sectoral emissions analysis, highlighting key contributors and the effectiveness of environmental policies such as the Clean Power Plan and the Paris Agreement.

## Features
- **Interactive Dashboard**: Built with Python Dash, allowing dynamic filtering by state, sector, and time period.
- **Data Analysis**: Aggregation and visualization of emissions data at state and sector levels.
- **Policy Insights**: Annotation of emissions trends with key policy milestones to evaluate their impact.

## Key Visualizations
- **Bar Charts**: Compare total emissions across states.
- **Line Graphs**: Temporal trends with policy annotations.
- **Choropleth Maps**: Visualize geographic intensity of emissions.
- **Pie Charts**: Breakdown of emissions by sector.

## Tools and Technologies
- **Programming Languages**: Python (pandas, matplotlib, plotly)
- **Visualization Framework**: Dash for building the interactive dashboard
- **Data Source**: EPA’s Greenhouse Gas Reporting Program (GHGRP)

## Installation and Usage

### Prerequisites
Ensure the following are installed on your system:
- Python 3.8+
- pip package manager

### Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Dashboard
1. Launch the application:
   ```bash
   python app.py
   ```
2. Open the local server URL (usually `http://127.0.0.1:8050`) in your web browser.

## Dataset
The data is sourced from the EPA’s Greenhouse Gas Reporting Program (GHGRP) and includes:
- Annual emissions data (2010-2022)
- Sectoral breakdown (energy, industrial, etc.)
- State-level aggregation

## Challenges and Solutions
- **Data Cleaning**: Addressed missing values and outliers using imputation and exclusion techniques.
- **Large Dataset Handling**: Optimized workflows for efficient processing and visualization.
- **Policy Impact Integration**: Annotated visualizations with policy events for enhanced insights.

## Results
- Identified Texas and Louisiana as leading emitters.
- Energy and industrial sectors as dominant contributors.
- Policies showed limited immediate impact, underscoring the need for stronger enforcement and targeted actions.

## Future Enhancements
- Incorporate real-time emissions data.
- Expand analysis to include predictive modeling.
- Enhance dashboard with advanced features like "what-if" scenarios and sectoral breakdowns.

## References
1. U.S. Environmental Protection Agency. *GHGRP emissions by location.*
2. International Energy Agency (IEA). (2023). *Global CO2 emissions report.*

## Contributors
- **Naga Deepak Pagadala**
- **Neeraj Kondaveeti**

