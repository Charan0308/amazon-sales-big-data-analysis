# Amazon Sales Analysis Using Apache Spark

## Project Overview

This project analyzes a 2025-labelled Amazon sales dataset containing 15,000 records using **Python, PySpark, and Matplotlib**. The objective is to explore sales performance, identify trends, and generate meaningful insights through Big Data processing and visualization.

## Objectives

- Analyze overall sales and net sales.
- Identify the highest-performing product categories.
- Compare sales performance across Indian states.
- Analyze monthly sales trends.
- Understand customer payment method preferences.
- Examine delivery and return outcomes.
- Practice data processing and analysis using Apache Spark.

## Dataset Description

**Dataset file:** `Amazon_Sales_2025_INR.csv`

- Number of records: 15,000
- Number of columns: 17
- Data format: CSV
- Currency: Indian Rupees (INR)

The dataset includes sales-related information such as order IDs, dates, product categories, quantities, sales amounts, customer locations, payment methods, delivery status, and review ratings.

*Note: The dataset's official provenance has not been independently verified. It should not be interpreted as confirmed internal Amazon transaction data.*

## Technologies Used

- **Python** — programming and data analysis
- **Apache Spark / PySpark** — distributed data processing
- **Pandas** — handling aggregated results
- **Matplotlib** — charts and visualizations
- **Google Colab** — notebook development environment
- **GitHub** — project version control and sharing

## Project Workflow

1. Load the CSV dataset into PySpark.
2. Inspect the schema, record count, and data quality.
3. Remove duplicate records and handle missing or invalid values.
4. Perform sales analysis by category, state, and month.
5. Analyze payment methods and delivery status.
6. Create charts to communicate the findings.
7. Interpret the results and identify business insights.

## Key Findings

Based on the analysis performed:

- **Total sales:** ₹1,118,161,916
- **Net sales:** ₹981,786,144
- **Top product category:** Beauty
- **Highest-sales month:** December 2025
- **Lowest-sales month:** February 2025
- **Most frequent payment method by order count:** Cash on Delivery
- **Payment method with the highest total sales:** Credit Card
- **Delivery status:** 13,182 records were marked Delivered and 1,818 were marked Returned.

These findings are based on the dataset and the analysis performed in the notebook.

## Repository Structure

```text
amazon-sales-big-data-analysis/
├── Amazon_Sales_Big_Data_Project.ipynb
├── Amazon_Sales_2025_INR.csv
└── README.md
```

The report and presentation can also be added to the repository when ready.

## How to Run the Project

### Option 1: Google Colab

1. Open the notebook `Amazon_Sales_Big_Data_Project.ipynb`.
2. Upload `Amazon_Sales_2025_INR.csv` to your Colab session.
3. Install PySpark if it is not already installed:

   ```python
   !pip install pyspark
   ```

4. Update the CSV file path in the notebook if necessary.
5. Run the notebook cells in order to reproduce the analysis and visualizations.

### Option 2: Local Python Environment

Install the required libraries:

```bash
pip install pyspark pandas matplotlib
```

Open the notebook using Jupyter Notebook or JupyterLab, ensure the CSV path is correct, and run the cells.

## Expected Outputs

- Data quality checks and cleaned data
- Category-wise sales analysis
- State-wise sales comparison
- Monthly sales trend
- Payment method analysis
- Delivery and return analysis
- Charts and visualizations

## Conclusion

This project demonstrates how PySpark can be used to process and analyze a sales dataset and how data visualization can help communicate useful findings. The results provide an overview of sales trends, category performance, regional differences, payment preferences, and delivery outcomes.

## Author

**Project:** Amazon Sales Analysis Using Apache Spark  
**Repository:** [amazon-sales-big-data-analysis](https://github.com/Charan0308/amazon-sales-big-data-analysis)

