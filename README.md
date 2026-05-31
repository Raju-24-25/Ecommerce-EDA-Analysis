# 📊 Global E-Commerce Exploratory Data Analysis

## Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) performed on a Global E-Commerce Dataset. The objective was to transform raw transactional data into meaningful business insights through data cleaning, statistical analysis, and visualization techniques.

The analysis focuses on understanding customer behavior, product performance, revenue trends, and key business drivers that can support data-driven decision-making.

---

## Business Objectives

* Understand dataset structure and quality
* Identify missing values and duplicate records
* Detect and treat outliers
* Analyze customer demographics
* Evaluate product category performance
* Explore revenue-driving factors
* Generate actionable business insights
* Formulate hypotheses for future statistical testing

---

## Dataset Information

| Metric        | Value      |
| ------------- | ---------- |
| Records       | 15,200     |
| Clean Records | 15,000     |
| Features      | 16         |
| Domain        | E-Commerce |

### Key Variables

* Customer Age
* Product Category
* Product Price
* Revenue
* Rating
* Shipping Cost
* Country
* Payment Method
* Membership Status

---

## Data Quality Assessment

### Missing Values

| Column        | Missing Rate |
| ------------- | ------------ |
| Rating        | 3.0%         |
| Customer Age  | 2.0%         |
| Delivery Days | 1.0%         |

### Duplicate Records

* 200 duplicate rows identified
* Duplicate records removed before analysis

### Outlier Treatment

* IQR Method applied
* Extreme Product Price values detected
* Winsorization performed at 99th percentile

---

## Exploratory Data Analysis

### Univariate Analysis

* Revenue Distribution
* Customer Age Distribution
* Product Category Distribution
* Rating Distribution

### Bivariate Analysis

* Revenue by Product Category
* Revenue by Country
* Customer Age vs Revenue
* Rating vs Revenue

### Multivariate Analysis

* Correlation Heatmap
* Category Performance Comparison
* Revenue Drivers Analysis

---

## Key Business Insights

### Category Performance

* Electronics generated the highest revenue.
* Clothing ranked second in overall revenue contribution.
* Home & Garden showed stable performance.

### Customer Behavior

* Members generated higher average order values.
* Younger customers preferred electronics products.
* Spending behavior varied across age groups.

### Revenue Trends

* Revenue distribution exhibited strong right skewness.
* A small proportion of transactions generated a large share of revenue.

### Geographic Analysis

* USA generated the highest revenue.
* UK and Germany followed closely.

### Payment Analysis

* Crypto and Bank Transfer transactions showed higher average order values.

---

## Statistical Hypotheses Generated

### H1: Membership Impact

Customers with membership status generate higher revenue than non-members.

### H2: Seasonality Effect

Q4 sales are significantly higher than other quarters.

### H3: Product Price Influence

Higher product prices significantly increase transaction revenue.

### H4: Age-Based Purchasing Behavior

Customer age influences spending patterns.

### H5: Payment Method Impact

Payment methods affect average order value.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Visualizations

* Missing Value Analysis
* Duplicate Analysis
* Outlier Detection
* Revenue Distribution
* Category Analysis
* Country Revenue Analysis
* Correlation Heatmap

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Missing Value Handling
4. Duplicate Removal
5. Outlier Detection
6. Exploratory Data Analysis
7. Data Visualization
8. Business Insight Generation
9. Hypothesis Formulation

---

## Results

The project successfully identified key revenue drivers, customer purchasing patterns, and category-level performance metrics. These insights can be leveraged to improve marketing strategies, customer retention initiatives, and revenue optimization efforts.

---

## Author

Raju Mondal

Data Science & AI Enthusiast

LinkedIn: https://www.linkedin.com/in/raju-mondal-24-25-ds/

GitHub: https://github.com//Raju-24-25
