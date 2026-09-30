# 180-days--AIML--journey
My 180-day journey from Python fundamentals to AI/ML engineering.






# Day 14 — E-commerce Data Analysis

## Project

Today I worked on a small E-commerce dataset using Pandas and Matplotlib.

## Topics Covered

- Creating a DataFrame
- Data analysis using Pandas
- Mean, maximum and minimum
- Filtering data
- Total and average sales
- `groupby()`
- `sum()`
- Bar chart visualization
- Product-wise sales analysis
- Category-wise sales analysis

## Practice

- Found the average product price
- Found the highest and lowest price
- Found the product with highest sales
- Calculated total sales
- Calculated average sales
- Filtered products with sales greater than 50
- Created a Product vs Sales bar chart
- Calculated category-wise total sales

## Key Learnings

- `df["Price"].mean()` → Calculates average price
- `df["Price"].max()` → Finds highest price
- `df["Price"].min()` → Finds lowest price
- `df["Sales"].sum()` → Calculates total sales
- `df["Sales"].mean()` → Calculates average sales
- `df.groupby("Category")["Sales"].sum()` → Calculates category-wise total sales
- `plt.bar()` → Creates a bar chart

## Day 14 Summary

Today I completed an E-commerce Data Analysis mini project.
I practiced Pandas data analysis, filtering, grouping and
basic visualization using Matplotlib.



# Day 15 — SQL Basics

## Topics Covered

- Database basics
- SQLite
- Tables
- `SELECT`
- Selecting specific columns
- `WHERE`
- `ORDER BY`
- `ASC`
- `DESC`
- `LIMIT`
- `AVG()`

## Database Practice

Created a SQLite database named `day15.db`.

Created a `students` table with:

- Name
- Age
- Marks
- Course

Inserted 5 student records and practiced SQL queries.

## Practice

- Displayed all students
- Selected specific columns
- Filtered students using `WHERE`
- Sorted students using `ORDER BY`
- Used `ASC` and `DESC`
- Found top 3 students using `LIMIT`
- Filtered students based on marks and age
- Found the student with the lowest marks
- Calculated average marks using `AVG()`

## Key Learnings

- `SELECT` → Retrieves data
- `WHERE` → Filters data
- `ORDER BY` → Sorts data
- `ASC` → Lowest to highest
- `DESC` → Highest to lowest
- `LIMIT` → Restricts number of rows
- `AVG()` → Calculates average

## Day 15 Summary

Today I started learning SQL and practiced basic
database operations using SQLite. I learned how to
retrieve, filter, sort and analyze data using SQL queries.