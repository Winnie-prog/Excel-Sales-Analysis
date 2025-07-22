# Excel-Sales-Analysis
Excel project for bike sales analysis including data cleaning, pivot tables, and dashboard visualizations.
 Excel Sales Analysis

This project showcases a complete sales data analysis using Microsoft Excel. It includes data cleaning, transformation, PivotTables, slicers, and interactive dashboards to visualize customer and purchasing behavior.

# Project Overview

The goal was to analyze sales data and understand trends across demographics, income levels, commute distances, and age groups using Excel's built-in tools.

# Data Cleaning

- Removed duplicate entries to ensure accuracy.
- Used **Find and Replace (Ctrl + H)** to replace abbreviations with full text:
  - `M` → `Male`, `F` → `Female`
  - `M` → `Married`, `S` → `Single`
- Standardized currency formatting for income fields.
- Created a new **"Age Bracket"** column using the `IF` function:
  - **Adolescent**, **Middle Age**, **Old**

# PivotTables & Visualizations

Several PivotTables and charts were created to analyze and compare:
# 1. **Average Income by Gender**
- Shows average income of each gender.
- Split by those who purchased vs. didn't purchase.

# 2. **Commute Distance Comparison**
- Displays commute distances for customers who purchased vs. didn't purchase.
- Visualized using a **line chart**.

# 3. **Age Bracket vs. Bike Purchase**
- Compares age groups of those who purchased vs. didn’t.
- Clearer than raw age values, which appeared cluttered.

# 4. **Raw Age vs. Bracket Comparison**
- Demonstrates why grouped data (brackets) is more insightful than raw values.
- Both visualized using **line charts**.


# 📊 Dashboard

An interactive Excel dashboard was created to consolidate the key insights:

- **Average Income by Gender**
- **Commute Distance vs. Purchase**
- **Age Brackets vs. Purchase Status**


# Slicers for Interactivity

Slicers were added for dynamic filtering across visuals:

- **Marital Status**
- **Region**
- **Education Level**

This enhances the usability and interactivity of the dashboard.


# Tools Used

- **Microsoft Excel**
  - Data Cleaning Tools (Find/Replace, TRIM, IF)
  - PivotTables
  - Line and Column Charts
  - Slicers
  - Dashboard Design
