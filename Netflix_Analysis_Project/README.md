# Netflix Data Analysis and Machine Learning Project

![Netflix Logo](https://github.com/Neeraj-Kondaveeti/Data-Analysis-Projects/blob/main/Netflix_Analysis_Project/Netflix-Logo.webp)

## Project Overview
This project is a comprehensive exploration of the Netflix dataset, integrating SQL analysis, Python-based data visualization, recommendation system development, sentiment analysis, and predictive modeling. It demonstrates the application of data analysis and machine learning techniques to extract insights, predict trends, and create interactive tools.

## Dataset Description
The Netflix dataset contains information on 8,807 titles, including:
- **Type**: Movie or TV Show
- **Title**: Name of the content
- **Director**: Directors involved
- **Cast**: Cast members
- **Country**: Country of production
- **Date Added**: Date content was added to Netflix
- **Release Year**: Year of release
- **Rating**: Content rating (e.g., PG, R)
- **Duration**: Length of movies or number of seasons for TV shows
- **Listed In**: Genres/categories
- **Description**: Brief summary of the content

## Modules

### 1. SQL Analysis
- **Objective**: Extract foundational insights from the Netflix database.
- **Tasks**:
  - Create and populate the `netflix` table.
  - Analyze content distribution by genres, countries, and ratings.
  - Identify trends and popular categories.
- **Tools Used**: SQL.

### 2. Python Data Analysis and Visualization
- **Objective**: Perform exploratory data analysis and visualize trends.
- **Tasks**:
  - Identify missing data using heatmaps.
  - Visualize content distribution by year, genre, and country.
  - Generate insights on top directors, cast members, and content durations.
- **Tools Used**: Python, pandas, matplotlib, seaborn, plotly.

### 3. Recommendation System
- **Objective**: Build an interactive recommendation engine.
- **Tasks**:
  - Use cosine similarity to recommend similar titles based on genres.
  - Integrate with a Dash web application for user interaction.
  - Implement filters for genres, release year, and content type.
- **Tools Used**: Python, Dash, sklearn, fuzzywuzzy.

### 4. Sentiment Analysis
- **Objective**: Analyze sentiment polarity in content titles.
- **Tasks**:
  - Apply TextBlob to score sentiments.
  - Visualize sentiment distributions.
  - Highlight the most positive and negative titles.
- **Tools Used**: Python, pandas, TextBlob, matplotlib, seaborn.

### 5. Predictive Analysis
- **Objective**: Predict trends and classify content.
- **Tasks**:
  - Perform regression analysis to predict future trends in content addition.
  - Use K-means clustering to group content based on metadata.
  - Evaluate model performance with visualization.
- **Tools Used**: Python, sklearn, matplotlib, numpy.

## Connection Between Modules
The modules complement each other to provide a unified analysis:
- **SQL Analysis** builds the foundation by preparing and exploring the dataset.
- **Python Analysis** visualizes trends and insights, bridging raw data with storytelling.
- **Recommendation System** applies insights interactively, enabling user engagement.
- **Sentiment Analysis** explores emotional aspects of the dataset, adding depth.
- **Predictive Analysis** extends the project into future trend forecasting and clustering.

## Technologies Used
- **Languages**: SQL, Python
- **Libraries**: pandas, matplotlib, seaborn, plotly, Dash, sklearn, TextBlob, fuzzywuzzy
- **Tools**: Jupyter Notebooks, Dash Web Framework

## How to Run
### 1. Clone the Repository
```bash
git clone https://github.com/your-repo/netflix-analysis
cd netflix-analysis
```

### 2. Set Up Environment
```bash
pip install -r requirements.txt
```

### 3. Execute Modules
- **SQL Analysis**: Use any SQL client to execute the queries in `NetflixSQLproject.sql`.
- **Python Notebooks**: Run Jupyter Notebooks for analysis, recommendation system, and predictive modeling.
- **Recommendation System Dashboard**:
  ```bash
  python app.py
  ```

## Key Insights
- The United States, India, and the United Kingdom dominate content production.
- The recommendation system accurately suggests similar titles.
- Sentiment analysis reveals a neutral to positive tone in most titles.
- Predictive modeling effectively forecasts trends in content addition.

## Conclusion
This project integrates multiple data science techniques to provide a comprehensive analysis of the Netflix dataset. It showcases expertise in SQL, data visualization, machine learning, and interactive application development.

## Future Scope
- Incorporate live data for real-time analysis.
- Use advanced NLP models for deeper sentiment analysis.
- Enhance recommendation system with collaborative filtering.
- Expand predictive modeling to include other metadata features.

