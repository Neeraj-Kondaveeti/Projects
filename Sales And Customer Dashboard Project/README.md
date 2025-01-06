# Sales and Customer Dashboard

## Project Overview
The Sales and Customer Dashboard is an interactive Tableau visualization designed to provide insights into sales performance, customer trends, and location-based analytics. The dashboard leverages multiple data sources to create an integrated view for business decision-making.

## Files Included
### Tableau Dashboard
- **`Sales And Customer Dashboard.twbx`**: This Tableau packaged workbook contains the interactive dashboard created using the data files.

### Data Files
- **`Customers.csv`**: Contains customer demographic and behavioral information.
- **`Location.csv`**: Includes data on locations where sales transactions occurred.
- **`Orders.csv`**: Details of sales orders, including product IDs, quantities, and order dates.
- **`Products.csv`**: Information on products, including descriptions, categories, and pricing.

## Features of the Dashboard
1. **Sales Analysis**
   - Monthly and yearly sales trends.
   - Revenue comparison across product categories.
2. **Customer Insights**
   - Demographic breakdown of customers.
   - Top customers based on sales volume and revenue.
3. **Location-Based Analysis**
   - Sales distribution across regions.
   - Performance of individual stores.

## Data Preparation
- **Data Cleaning**: All CSV files were preprocessed to ensure consistency in data types and remove missing or duplicate records.
- **Joining Data**: The data files were joined in Tableau using relevant keys (e.g., `Customer ID`, `Product ID`, `Location ID`).
- **Calculated Fields**: Additional metrics such as total revenue, average order value, and customer lifetime value were computed.

## Prerequisites
To view or modify the dashboard, you need:
1. Tableau Desktop or Tableau Public (latest version recommended).
2. Basic knowledge of Tableau for exploring and interacting with the dashboard.

## How to Use
1. Open `Sales And Customer Dashboard.twbx` in Tableau.
2. Navigate through different views and filters to explore insights.
3. Use provided filters (e.g., date range, product category, location) to customize your analysis.

## Future Enhancements
- Incorporate real-time data integration for live updates.
- Expand the dashboard with predictive analytics capabilities.
- Include additional dimensions such as marketing and inventory data.

