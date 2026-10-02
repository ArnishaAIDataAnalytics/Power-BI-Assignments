Power BI Assignment 1 – Data Transformation & Data Modeling

E-Commerce Sales Analysis

This assignment focuses on e-commerce sales analysis using Power BI. You will import, transform, model, and analyze the provided datasets to generate insights into sales performance and business trends.

Dataset Files

List of Orders.csv
Order Details.csv
Sales Target.csv

## Instructions

### 1. Import Data

- Import `List of Orders.csv` into Power BI.
- Open `List of Orders` in the Power Query Editor by selecting **Transform Data**.
- Import `Order Details.csv` and `Sales Target.csv` into the Power Query Editor as well.

### 2. Data Transformation

Apply the following transformations in Power Query Editor:

- Restrict the `List of Orders` table to the first 500 rows.
- Set the `Order Date` column to the **Date** data type.
- Change `Amount` and `Target` columns to **Fixed Decimal Number**.
- Format the `CustomerName` column to **Proper Case** so each word is capitalized.
- Merge the `State` and `City` columns into a new `Location` column in the following format:

```text
City, State
```

- Create a custom column named `Profit Margin` using:

```text
(Profit / Amount) * 100
```

## Learning Outcomes

By completing this assignment, you will be able to:

- Import and clean data in Power BI
- Apply data type conversions and formatting consistently
- Perform column transformations and create calculated fields
- Prepare clean data for modeling and visualization

## Submission Checklist

- PBIX file with all three tables imported and transformed
- Screenshots of Power Query steps
- Documentation of all transformations applied
- Custom columns created for `Location` and `Profit Margin`

