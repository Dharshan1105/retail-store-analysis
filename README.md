# Retail Store Analysis

An end-to-end retail data analysis project focused on understanding **customer purchasing behaviour** and evaluating the performance of **trial stores** using retail transaction data.

The project uses Python and Jupyter Notebooks to explore customer demographics, purchasing patterns, transaction trends, and trial-store performance to generate actionable business insights.

## Project Overview

Retail businesses generate large amounts of transactional data that can be used to understand customer behaviour and improve business decisions.

This project focuses on two key areas:

1. **Customer Purchasing Behaviour Analysis**
2. **Trial Store Evaluation**

The analysis explores purchasing patterns, customer characteristics, transaction trends, and store performance to identify meaningful insights that can support retail decision-making.

## Repository Structure

```text
retail-store-analysis/
│
├── Customer Purschasing Behaviour Analysis.ipynb
├── Trial Store Evaluation.ipynb
│
├── purchase_behaviour.csv
├── trail_store_data.csv.gz
├── transaction_data.xlsx
│
└── README.md
```

## Projects

### 1. Customer Purchasing Behaviour Analysis

This analysis focuses on understanding how customers purchase products and identifying patterns within transaction data.

Key areas explored include:

* Customer purchasing behaviour
* Customer demographics
* Product purchasing patterns
* Transaction frequency
* Sales and purchase trends
* Customer segmentation
* Identification of high-value customer groups
* Business insights from transaction data

**Notebook:** `Customer Purschasing Behaviour Analysis.ipynb`

### 2. Trial Store Evaluation

This analysis evaluates the performance of selected trial stores against comparable stores.

The objective is to determine whether trial-store performance indicates a meaningful improvement and to identify factors that may influence store performance.

Key areas explored include:

* Store-level sales performance
* Transaction trends
* Store comparison
* Trial vs. control store performance
* Monthly performance patterns
* Sales and transaction metrics
* Evaluation of potential trial-store impact

**Notebook:** `Trial Store Evaluation.ipynb`

## Datasets

### `purchase_behaviour.csv`

Contains customer-level purchasing information used to analyze customer behaviour and purchasing patterns.

### `transaction_data.xlsx`

Contains retail transaction data used for analysing purchases, products, and transaction-level trends.

### `trail_store_data.csv.gz`

Contains store-level data used for evaluating and comparing trial-store performance.

## Tools & Technologies

* Python
* Jupyter Notebook
* Pandas – Data manipulation and analysis
* NumPy – Numerical analysis
* Matplotlib – Data visualization
* Seaborn – Statistical visualization
* Excel – Supporting transaction data

## Analysis Workflow

```text
Raw Data
   ↓
Data Cleaning & Preparation
   ↓
Exploratory Data Analysis
   ↓
Customer & Store Analysis
   ↓
Data Visualization
   ↓
Performance Evaluation
   ↓
Business Insights
```

## Key Objectives

The project aims to answer questions such as:

* Who are the most valuable customer segments?
* What purchasing patterns can be identified from transaction data?
* Which products or customer groups contribute most to sales?
* How does customer behaviour vary across different segments?
* How are trial stores performing compared with comparable stores?
* Are there measurable differences in store performance?
* What insights can help improve retail decision-making?

## Business Value

The analysis can help retailers:

* Better understand their customers
* Identify valuable customer segments
* Improve marketing strategies
* Identify purchasing trends
* Evaluate store performance
* Make data-driven decisions
* Improve retail operations and sales strategies

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Dharshan1105/retail-store-analysis.git
cd retail-store-analysis
```

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter openpyxl
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open either:

```text
Customer Purschasing Behaviour Analysis.ipynb
```

or

```text
Trial Store Evaluation.ipynb
```

and run the cells sequentially.

## Project Highlights

| Area                 | Analysis                                   |
| -------------------- | ------------------------------------------ |
| Customer Analytics   | Purchasing behaviour and customer patterns |
| Transaction Analysis | Transaction-level trends                   |
| Product Analysis     | Product purchasing patterns                |
| Store Analytics      | Trial-store performance                    |
| Data Visualization   | Charts and statistical insights            |
| Business Analytics   | Actionable retail recommendations          |

## Future Improvements

Possible extensions to this project include:

* Building an interactive Power BI dashboard
* Customer RFM analysis
* Customer segmentation using K-Means clustering
* Market Basket Analysis
* Sales forecasting
* Product recommendation systems
* Automated reporting
* Advanced statistical testing for store evaluation

## Author

**Dharshan**

GitHub: [Dharshan1105](https://github.com/Dharshan1105)

## If You Find This Project Useful

If you find this project helpful, consider giving the repository a star and sharing your feedback.
