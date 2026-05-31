# Retail Sales Dashboard – Power BI

## Project Overview

This project presents an interactive **Retail Sales Analytics Dashboard** built using **Microsoft Power BI**.

The dashboard analyzes retail transaction data to uncover key business insights, monitor performance trends and support data-driven decision-making.

The report is designed as a **multi-page interactive dashboard** with navigation buttons, KPI cards, filters and advanced visualizations.

---

## Business Objective

The goal of this dashboard is to help retail decision-makers:

* Monitor sales performance
* Track customer purchasing behavior
* Identify top-performing product categories
* Analyze sales trends over time
* Understand customer demographics
* Improve strategic decision-making

---

## Dataset Information

The dataset contains retail transaction records with the following fields:

* Transaction ID
* Date
* Customer ID
* Gender
* Age
* Product Category
* Quantity
* Price per Unit
* Total Amount

---

## Tools & Technologies Used

* **Microsoft Power BI**
* DAX (Data Analysis Expressions)
* Data Modeling
* Interactive Navigation
* Data Transformation
* Dashboard Design

---

## Key Metrics Created

### Total Revenue

Measures total sales generated.

### Total Transactions

Tracks the total number of unique transactions.

### Average Sale Value

Calculates average transaction value.

### Total Quantity Sold

Measures total products sold.

---

## Calculated Columns

### Spender Category

Segments customers into:

* Low Spenders
* Medium Spenders
* High Spenders

---

### Age Group

Customer segmentation by age:

* 18–25
* 26–35
* 36–50
* 51+

---

## Dashboard Pages

## 1. Executive Overview

Provides high-level business performance metrics.

### Visualizations:

* KPI Cards
* Revenue Trend Line Chart
* Revenue by Product Category
* Gender Distribution Donut Chart

---

## 2. Sales Performance

Tracks operational sales trends.

### Visualizations:

* Monthly Sales Trend
* Daily Transaction Volume
* Revenue vs Quantity Scatter Plot

---

## 3. Customer Insights

Analyzes customer purchasing behavior.

### Visualizations:

* Revenue by Age Group
* Gender Revenue Comparison
* Spending Category Treemap
* Age vs Spending Scatter Plot

---

## 4. Product Analysis

Evaluates product category performance.

### Visualizations:

* Product Category Treemap
* Quantity Sold by Category
* Average Sale by Category

---

## 5. Time Analysis

Identifies seasonal and time-based trends.

### Visualizations:

* Sales Heatmap
* Ribbon Chart for Category Trends

---

## Interactive Features

The dashboard includes:

* Page Navigation Buttons
* Interactive Filters / Slicers
* Drill-through Analysis
* Hover Tooltips
* Dynamic Cross-filtering

---

## DAX Measures Used

### Total Revenue

```DAX
Total Revenue = SUM('Retail Sales'[Total Amount])
```

### Total Transactions

```DAX
Total Transactions = DISTINCTCOUNT('Retail Sales'[Transaction ID])
```

### Average Sale Value

```DAX
Average Sale Value = AVERAGE('Retail Sales'[Total Amount])
```

### Total Quantity Sold

```DAX
Total Quantity Sold = SUM('Retail Sales'[Quantity])
```

---

## Business Insights Generated

This dashboard enables stakeholders to:

* Identify high-performing product categories
* Detect customer purchasing trends
* Evaluate demographic spending patterns
* Monitor revenue growth
* Support strategic retail planning

---

## Project Outcome

This project demonstrates practical skills in:

* Data Visualization
* Business Intelligence
* Dashboard Design
* DAX Calculations
* Interactive Reporting
* Analytical Storytelling

---

## Author

Sibulelo Mafrika
