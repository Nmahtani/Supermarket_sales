# Supermarket_sales
Supermarket Sales Analysis ETL Project

## Description

This project is a beginner-to-intermediate level data science pipeline focusing on the **ETL (Extract, Transform, Load)** process. Using Python and Jupyter Notebook, we analyze supermarket sales data to uncover trends and generate visual insights. 

The project demonstrates the complete lifecycle of a data analysis task, from importing raw data to cleaning, transforming, analyzing, and visualizing it.

---

## Objectives

- Practice the ETL process with real-world data.
- Gain insights into supermarket sales trends across cities, categories, and time.
- Showcase data visualization and storytelling skills using Python.

---

## Dataset

- **Source:** [Supermarket Sales Dataset on Kaggle](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales)
- **Description:** The dataset includes details of sales transactions from three branches of a supermarket. It contains attributes such as:
  - City
  - Gender
  - Product Line
  - Payment Method
  - Sales Date and Time
  - Total Amount

---

## Tools and Libraries

- **Environment:** Jupyter Notebook
- **Libraries:**
  - `pandas` (Data Manipulation)
  - `numpy` (Numerical Analysis)
  - `matplotlib` and `seaborn` (Visualization)

---

## ETL Process

### 1. **Extract**
- Load the data from a CSV file into a Pandas DataFrame.

### 2. **Transform**
- Perform data cleaning:
  - Handle missing values and duplicates.
- Generate new columns:
  - Extract year, month, day, and hour from timestamps.
  - Categorize sales based on total revenue into "Low", "Medium", and "High".
- Format data for better readability and analysis.

### 3. **Load**
- Export the cleaned and transformed data to a new CSV file for future use.

---

## Visualizations

1. **Total Sales by City**: Bar chart showing revenue distribution across branches.
2. **Category Distribution**: Pie chart showing sales share of different product lines.
3. **Hourly Sales Trend**: Line graph illustrating revenue patterns during the day.
4. **Revenue by Gender**: Bar chart comparing sales performance by gender.


