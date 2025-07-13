# Sales Analysis

This repository contains a Jupyter Notebook (`Sales_Analysis.ipynb`) that performs a comprehensive sales data analysis. The notebook processes monthly sales data, cleans it, augments it with additional features, and then explores key business questions using data aggregation and visualization.

## Project Overview

This project aims to analyze sales data from various months to identify trends, best-performing periods, and top-selling products. The analysis involves:

* Merging individual monthly sales CSV files into a single comprehensive dataset.
* Cleaning the merged data by handling missing values and incorrect entries.
* Augmenting the dataset with new columns such as 'Month', 'Sales', and 'City' for deeper insights.
* Performing data exploration to answer specific business questions related to sales performance.

## Features

* **Data Merging:** Combines multiple monthly sales CSV files into a single Pandas DataFrame.
* **Data Cleaning:** Handles `NaN` values and corrects data types for analysis.
* **Feature Engineering:** Creates new columns like `Month`, `Sales` (Quantity Ordered \* Price Each), and `City` extracted from the purchase address.
* **Sales Trend Analysis:** Identifies the best month for sales and the total revenue generated.
* **Geographical Sales Analysis:** Determines which city has the highest number of sales.
* **Product Performance Analysis:** Identifies the most sold products and their average prices.
* **Time-Series Analysis:** Explores sales patterns throughout the day to determine optimal advertising times.
* **Co-purchased Products Analysis:** Discovers products that are frequently sold together.
* **Visualizations:** Utilizes `matplotlib.pyplot` to create informative bar charts and other plots to visualize sales trends and product performance.


## Dependencies

The following Python libraries are required to run this notebook:

* `pandas`
* `matplotlib`
* `os` (standard Python library)

## Analysis Questions

The notebook specifically addresses the following business questions:

1.  **What was the best month for sales? How much was earned that month?**
2.  **Which city has the highest number of sales?**
3.  **What time should we display advertisements to maximize the likelihood of customers buying products?**
4.  **What products are most often sold together?**
5.  **What product sold the most? Why do you think it sold the most?**
