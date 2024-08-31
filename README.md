# Retail Orders Data Analysis

![System Overview](https://github.com/rohitaragde/OrderDataSQL-ETL-Analysis/blob/master/system_overview.png)

This project demonstrates the process of downloading, cleaning, processing, and analyzing retail order data using Python, Kaggle API, and SQL. The dataset used is from Kaggle, and the analysis is performed on SQL Server.

## Project Objectives
- **Sales Trends Analysis:** Identify top-selling products and regions, and analyze revenue generation across different periods.
- **Profitability Insights:** Determine the most profitable product subcategories and analyze profit growth trends.
- **Month-Over-Month Sales Comparison:** Compare sales performance between 2022 and 2023 to assess growth trends.
- **Product Performance Analysis:** Evaluate the highest revenue-generating products and regions to inform inventory and marketing strategies.

## Deliverables
- **SQL Scripts:** A set of SQL scripts designed to extract insights from the retail orders dataset.
- **Data Analysis Report:** A detailed report summarizing the findings and insights derived from the data analysis.
- **System Overview Image:** Visual representation of the data flow from extraction to analysis.

## Technologies Used
- **Python**: For scripting and automating data processing tasks.
- **Pandas**: For handling, cleaning, and transforming the dataset.
- **Kaggle API**: For downloading the dataset programmatically from Kaggle.
- **SQL Server**: For storing the cleaned data and performing analysis.
- **SQLAlchemy**: For database connection and operations.
- **pyODBC**: For connecting Python with SQL Server.

## Project Overview

The project involves:
1. **Data Extraction**: Downloading the dataset from Kaggle using the **Kaggle API** in Python.
2. **Data Cleaning & Processing**: Cleaning and transforming the data using Pandas in Python.
3. **Data Loading**: Importing the processed data into SQL Server using SQLAlchemy and pyODBC.
4. **Data Analysis**: Performing SQL queries on the data in SQL Server to derive meaningful insights.

## Dataset

- **Source**: [Kaggle - Retail Orders](https://www.kaggle.com/datasets/ankitbansal06/retail-orders)
- **File**: `orders.csv`

## Project Structure

- **Python Script**: Handles data download using the Kaggle API, cleaning, processing, and loading into SQL Server.
- **SQL Script**: Contains queries to perform ETL analysis on the loaded data.
