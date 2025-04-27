# Chocolate Sales Analysis Project

## Project Overview

This project aims to analyze chocolate sales data by utilizing a SQLite database for data storage, an ER diagram to illustrate table relationships, Python scripts for data management and querying, and a dashboard built with Power BI.

The primary objective is to evaluate the sales performance of employees and identify the top-selling products, with a focus on database management and using SQL queries to extract and prepare data for further business analysis.

## Contents

- **Dataset**: Chocolate sales data in CSV format.
- **Database**: SQLite database (`chocolate_sales.db`) containing sales data.
- **ER Diagram**: ER Diagram depicting the relationship between tables in the database.
- **Python Code**: Python scripts used to load data into the database, perform queries, and analyze sales data.
- **Queries**: CSV files containing the results of various queries on the database.
- **Dashboard**: A Power BI dashboard visualizing the sales data.

## Technologies Used

- **SQLite**: Database management for storing sales data.
- **Python**: Used for querying and analyzing the data (via Pandas, SQLAlchemy, and SQLite3).
- **Power BI**: For creating a sales dashboard with visualizations.

## Methodology

- Sourced a chocolate sales dataset from Kaggle in CSV format
- Designed an ER diagram to plan the database table structure
- Created a SQLite database
- Connected to the database using Python with Object-Oriented Programming (OOP) principles
- Read the CSV data using Python and inserted it into the database following the designed schema
- Wrote SQL queries to extract the required information for analysis
- Exported the query results into CSV files using Python
- Built a dashboard in Power BI to visualize and analyze the results

## Results

The analysis reveals the top-selling chocolate products and the best-performing salespersons.

The Power BI dashboard provides an interactive view of the sales performance of each salesperson, allowing for easy and in-depth exploration of the data.

**The insights from this analysis can be applied in several ways:**

- **Sales Strategy Development**: Companies can study the working methods of top-performing salespersons to develop effective training programs or share best practices across the sales team.
- **Inventory Management**: Insights into the best-selling products allow companies to optimize inventory planning, ensuring alignment with market demand and reducing the risk of overstocking or stockouts.
- **Promotional Planning**: Sales data can be leveraged to design targeted promotions, either by boosting the sales of already popular products or encouraging sales of underperforming items.

## Future Development

While this project serves as a foundational analysis, there are several potential areas for future enhancement, including:

- **Advanced Data Extraction**: Extend the ability to query and extract data based on more specific business objectives, allowing for more targeted insights and flexible reporting.
- **Machine Learning Integration**: Implement predictive analytics, such as time series forecasting for sales predictions, or apply clustering techniques to segment customers based on buying behavior or demographics.
- **Enhanced Data Visualization**: Improve visualizations by incorporating more advanced charts and interactivity to provide deeper insights into trends, correlations, and performance metrics.
- **Customer Segmentation**: Use clustering algorithms to categorize customers into meaningful segments for personalized marketing strategies or targeted promotions.
