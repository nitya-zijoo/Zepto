# Exploratory Data Analysis (EDA) Plan

## Purpose

The purpose of Exploratory Data Analysis (EDA) is to understand the structure of the dataset, identify data quality issues, discover patterns, and generate hypotheses that will guide the dashboard design and business recommendations.

---

# EDA Objectives

- Understand the distribution of restaurant ratings.
- Analyze pricing trends across cities.
- Identify the most popular cuisines.
- Evaluate customer engagement through votes.
- Study the impact of online delivery and table booking.
- Detect anomalies and outliers.

---

# Dataset Overview

The first step is to understand the dataset structure.

## Tasks

- View first and last records
- Check dataset dimensions
- Inspect column names
- Identify data types
- Generate summary statistics

---

# Data Quality Assessment

## Missing Values

- Count missing values
- Calculate percentage missing
- Decide whether to remove or impute

## Duplicate Records

- Identify duplicate restaurants
- Remove exact duplicates

## Data Types

Verify and correct:

- Numerical columns
- Categorical columns
- Boolean fields

---

# Univariate Analysis

Analyze individual variables.

## Numerical Columns

- Aggregate Rating
- Votes
- Average Cost for Two

Metrics:

- Mean
- Median
- Standard Deviation
- Minimum
- Maximum
- Quartiles

Visualizations:

- Histogram
- Box Plot

---

## Categorical Columns

Analyze:

- City
- Cuisine
- Online Delivery
- Table Booking

Visualizations:

- Bar Chart
- Pie Chart
- Frequency Table

---

# Bivariate Analysis

Study relationships between variables.

Questions:

- Does cost influence rating?
- Do votes influence rating?
- Does online delivery improve ratings?
- Does table booking affect ratings?

Visualizations:

- Scatter Plot
- Correlation Matrix
- Grouped Bar Chart

---

# Multivariate Analysis

Analyze combinations of variables.

Examples:

- City vs Cuisine vs Rating
- Cost vs Rating vs Votes
- Cuisine vs Delivery vs Rating

Visualizations:

- Heatmaps
- Bubble Charts
- Treemaps

---

# Key Business Questions

- Which cities have the highest average ratings?
- Which cuisines receive the highest ratings?
- Which restaurants receive the most customer votes?
- What pricing range performs best?
- How does online delivery influence customer satisfaction?

---

# Expected Outputs

- Clean understanding of the dataset
- Business insights
- Features for Power BI dashboard
- Recommendations for SQL analysis
```
