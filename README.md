# Python Data Analysis – Global Superstore

## Project Overview

This project focuses on analyzing the **Global Superstore dataset from 2011 to 2015** using Python. The analysis explores sales, profit, shipping modes, regional performance, product categories, and sales trends to identify useful business insights.

The project demonstrates the use of Python libraries for data cleaning, exploratory data analysis, grouping, aggregation, and data visualization.

## Objectives

* Understand the structure and characteristics of the dataset.
* Perform data cleaning and preprocessing.
* Analyze profit across different product categories.
* Compare sales performance across regions.
* Identify monthly sales trends.
* Analyze negative-profit transactions based on shipping mode.
* Examine profit variations across different days of the week.
* Visualize business insights using charts.

## Technologies and Libraries Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Seaborn** – Data visualization
* **Matplotlib** – Creating charts and graphs
* **Jupyter Notebook** – Project development environment

## Dataset Description

The dataset contains global sales transaction records from **2011 to 2015**.

The original dataset contains:

* **51,290 records**
* **24 columns**

Important columns include:

* Order Date
* Ship Date
* Ship Mode
* Customer Name
* Segment
* City
* State
* Country
* Market
* Region
* Category
* Sub-Category
* Product Name
* Sales
* Quantity
* Discount
* Profit
* Shipping Cost
* Order Priority

## Project Workflow

### 1. Data Loading

The dataset was imported into a Pandas DataFrame using `read_csv()` with the required encoding.

### 2. Data Exploration

The dataset was explored using:

* `head()`
* `tail()`
* `shape`
* `info()`
* `describe()`
* `columns`

### 3. Data Cleaning

The following data-cleaning steps were performed:

* Checked for missing values.
* Checked for duplicate records.
* Identified missing values in the `Postal Code` column.
* Removed unnecessary columns such as:

  * Row ID
  * Order ID
  * Customer ID
  * Postal Code

### 4. Exploratory Data Analysis

The following analyses were performed:

* Profit analysis by product category.
* Sales analysis by region.
* Monthly sales trend analysis.
* Analysis of negative-profit transactions by shipping mode.
* Profit analysis by day of the week.

### 5. Data Visualization

Bar charts and line charts were created using Matplotlib to understand patterns and compare business performance.

## Key Analysis and Findings

* **Category-wise profit analysis** was performed to compare the profitability of different product categories.
* **Regional sales analysis** showed that the Central region recorded the highest sales among the analyzed regions.
* **Monthly sales analysis** was conducted to identify variations in sales across different months.
* **Shipping-mode analysis** examined the percentage of transactions with negative profit across different shipping modes.
* **Day-wise profit analysis** was performed to understand how profit varied across the days of the week.



## Conclusion

This project demonstrates how Python can be used to explore and analyze business data. Through data cleaning, aggregation, and visualization, the project examines sales and profit patterns across categories, regions, time periods, shipping modes, and weekdays.

The analysis provides a foundation for understanding business performance and making data-driven observations.

## 👩‍💻 Author

**Ananya Goel**

BTech – Computer Science and Engineering
