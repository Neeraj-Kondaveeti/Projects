# Netflix Data Analysis Project

This project involves analyzing Netflix data to derive insights about the platform's content library. Using a structured SQL database derived from a CSV dataset, various queries are executed to uncover patterns, trends, and valuable information for business decisions.

---

## Project Overview

### Objective
The primary objective of this project is to:
- Analyze Netflix's content catalog using SQL queries.
- Provide insights into content distribution, trends, and other critical metrics.
- Practice and demonstrate proficiency in SQL for data analysis.

### Dataset
**Filename:** `netflix_titles.csv`

The dataset contains metadata about Netflix's titles, including:
- `show_id`: Unique identifier for each show.
- `type`: Type of content (e.g., Movie, TV Show).
- `title`: Name of the show.
- `director`: Director of the show (if available).
- `cast`: List of actors involved.
- `country`: Country where the show was produced.
- `date_added`: Date the show was added to Netflix.
- `release_year`: Year the show was released.
- `rating`: Content rating (e.g., TV-MA, PG-13).
- `duration`: Duration of the content (minutes or number of seasons).
- `listed_in`: Genres/categories of the content.
- `description`: Brief description of the show.

---

## Project Workflow

### 1. Data Preparation
The dataset is imported into a SQL database, with a table named `netflix` created to store the data. The following steps are performed:
- Dropping any existing `netflix` table to avoid conflicts.
- Creating the `netflix` table with appropriate data types for each column.
- Verifying successful data import using exploratory queries.

### 2. SQL Queries
Various SQL queries are executed to analyze the data. Highlights include:
- **Content Distribution:**
  - Count of Movies vs. TV Shows.
  - Distribution of content by rating and genre.
- **Temporal Analysis:**
  - Number of shows added each year.
  - Trends in release years for content.
- **Country-Specific Insights:**
  - Top countries contributing to the content library.
- **Director and Cast Analysis:**
  - Most frequent directors and actors in the dataset.

### 3. Insights
Key insights are derived, including:
- Dominant genres on Netflix.
- Yearly trends in content additions.
- Popular countries of production.
- Viewer preferences based on content rating.

---

## Folder Structure

- **`data/`**: Contains the original `netflix_titles.csv` dataset.
- **`scripts/`**: SQL script file (`NetflixSQLproject.sql`) for creating the database, importing data, and running queries.

---

## Prerequisites
To run the project, ensure the following:

### Software
- SQL Server/MySQL/PostgreSQL (compatible with the provided SQL code).
- A SQL client or IDE (e.g., MySQL Workbench, DBeaver).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/username/netflix-analysis-project.git
   ```
2. Load the `netflix_titles.csv` into your local environment.
3. Execute the SQL script (`NetflixSQLproject.sql`) in your SQL client.
4. Run and modify queries as needed.

---

## How to Use

1. **Import Data**:
   - Ensure the `netflix_titles.csv` file is accessible.
   - Execute the table creation and data import sections of the SQL script.
2. **Run Analysis**:
   - Use the predefined queries to analyze the data.
   - Customize or add queries for additional insights.
3. **Interpret Results**:
   - Analyze the query outputs to derive meaningful conclusions.

---

## Future Enhancements

- Incorporate visualizations using tools like Tableau or Python.
- Automate SQL query execution and reporting.
- Expand the dataset with real-time updates for more dynamic analysis.

---

## Contact
For questions or feedback, reach out via:
- **Email**: [neerajkondaveeti1901@gmail.com](mailto:neerajkondaveeti1901@gmail.com.com)
- **GitHub**: [Your GitHub Profile](https://github.com/Neeraj-Kondaveeti)

---

Explore and uncover Netflix trends with data-driven insights!
