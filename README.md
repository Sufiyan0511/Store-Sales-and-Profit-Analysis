# Superstore Sales Analysis

## Overview
This project performs a comprehensive sales and profit analysis on a sample superstore dataset. It includes visualizations of sales and profit trends by various dimensions such as month, category, sub-category, and customer segment. The analysis is done using Python libraries like **pandas**, **matplotlib**, and **seaborn**.

## Dataset
The dataset used for this analysis is `Sample - Superstore.csv`. It contains 9994 records with 21 columns, which include details like order date, ship date, sales, profit, category, and customer information.

## Libraries Used
- pandas
- matplotlib
- seaborn

## Data Exploration
- Loaded the dataset and displayed the first few rows.
- Checked the shape of the dataset and verified the presence of missing values.
- Displayed data types and memory usage.
- Provided summary statistics for both numeric and object columns.

## Data Preprocessing
- Converted date columns to datetime format.
- Extracted month, year, and day of the week from the Order Date.
- Mapped numeric months to month names.

## Sales Analysis
### Sales by Month
- Grouped data by order month and calculated total sales.
- Created a line plot to visualize sales trends by month.

### Sales by Category
- Grouped data by category and calculated total sales.
- Created a pie chart to visualize sales distribution by category.

### Sales by Sub-Category
- Grouped data by sub-category and calculated total sales.
- Created a bar plot to visualize sales distribution by sub-category.

## Profit Analysis
### Profit by Month
- Grouped data by order month and calculated total profit.
- Created a line plot to visualize profit trends by month.

### Profit by Category
- Grouped data by category and calculated total profit.
- Created a pie chart to visualize profit distribution by category.

### Profit by Sub-Category
- Grouped data by sub-category and calculated total profit.
- Created a bar plot to visualize profit distribution by sub-category.

## Sales and Profit by Segment
- Grouped data by segment and calculated total sales and profit.
- Reshaped data for visualization and created a clustered bar chart to compare sales and profit by segment.

## Sales to Profit Ratio
- Calculated the sales to profit ratio for each segment.

## Conclusion
This project demonstrates how to perform exploratory data analysis and visualize key insights using Python libraries. The analysis covers sales and profit trends by month, category, sub-category, and customer segment.

## How to Run
1. Clone the repository.
2. Install required libraries: `pandas`, `matplotlib`, and `seaborn`.
3. Run the Jupyter notebook or Python script to reproduce the analysis.

## Acknowledgements
- The dataset is provided by [Superstore](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final).

Feel free to contribute to this project by opening issues or submitting pull requests.
