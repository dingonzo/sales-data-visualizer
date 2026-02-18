# Sales Bar Chart Generator
[![Java CI with Gradle](https://github.com/dingonzo/sales-data-visualizer/actions/workflows/gradle.yml/badge.svg)](https://github.com/dingonzo/sales-data-visualizer/actions/workflows/gradle.yml)
A lightweight Java console application that visualizes daily sales data across multiple store locations using ASCII bar charts.

# Description
This program prompts the user to enter the daily sales figures for five different stores. It then generates a horizontal bar chart where each asterisk (*) represents $100 of sales, allowing for a quick visual comparison of store performance.

# How to Run
Compile the code:
javac SalesData.java

# Execute the program:
java SalesData

# Example Output
text
Enter today's sales for store 1: 400
Enter today's sales for store 2: 250

SALES BAR CHART
Store 1: ****
Store 2: **

# Features
Simple CLI-based data entry.
Automatic scaling (1 asterisk = $100).
Clean, readable output format.

