# 📊 Sales & Business Data Analysis (EDA)

## 📌 Project Overview

This project is my **Python Final Project** as part of the Data Analysis course at **Instant Software Solutions**.

The goal of this project is to perform Exploratory Data Analysis (EDA) on a retail customer transaction dataset to understand sales patterns, explore data quality, and extract meaningful business insights.

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Google Colab

## 📂 Dataset

- **Dataset Name:** Retail Customer Transaction Data
- **Source:** OpenDataBay
- **Initial Dataset Size:** 302,010 rows and 30 columns

The dataset contains retail transaction information, including customer details, product categories, purchase quantities, transaction amounts, payment methods, and order statuses.

## 🔍 Project Workflow

### 1. Data Understanding
- Loaded and explored the dataset.
- Examined dataset shape, columns, and data types.
- Generated statistical summaries.
- Explored categorical variables using `value_counts()`.

### 2. Data Manipulation
- Selected relevant columns for sales analysis.
- Filtered transactions using single and multiple conditions.
- Applied `groupby()` and aggregation functions.
- Analyzed sales by product category and country.

### 3. Data Quality & Cleaning
- Identified and removed duplicate records.
- Investigated missing values and handled essential sales attributes.
- Used the relationship between `Amount`, `Total_Purchases`, and `Total_Amount` to recover missing values where possible.
- Corrected inconsistent month values using the transaction dates.
- Converted columns to appropriate data types.
- Detected outliers using the Interquartile Range (IQR) method.
- Retained potential genuine high-value transactions instead of removing them automatically.

### 4. Data Visualization

Created four visualizations using Matplotlib:

- **Bar Chart:** Total Sales by Product Category.
- **Line Chart:** Monthly Sales Trend.
- **Histogram:** Distribution of Transaction Amounts.
- **Scatter Plot:** Amount vs Total Purchases.

## 📈 Key Insights

- Electronics recorded the highest total sales among all product categories.
- Monthly sales remained relatively stable throughout the analyzed period.
- Most transactions had relatively low to moderate amounts.
- The scatter plot showed no clear visual linear relationship between unit price and the number of items purchased.

## 📁 Project Files

- `Retail_Customer_Transaction_EDA.ipynb` – Complete Jupyter Notebook containing the analysis and visualizations.

## 👨‍💻 Author

**John Gerges**

- LinkedIn: [John Gerges](https://www.linkedin.com/in/john-gerges-a59592336/)
- Email: [johngwanes@gmail.com](mailto:johngwanes@gmail.com)

---

*This project was completed as part of the Data Analysis course at Instant Software Solutions.*
