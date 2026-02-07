# dmnn-2526-sem2

# Week 1 Project - Online Retail Analysis

## Language

This project uses **Python** for data analysis and visualization.

## Project Overview

This project focuses on **Data Wrangling & Exploratory Data Analysis (EDA)** of an online retail dataset. The analysis involves cleaning, transforming, and exploring transaction data to understand customer behavior, sales patterns, and business insights.

## Prerequisites

- Python 3.9.6 or higher
- pip (Python package manager)

## Installation

Install required packages:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## How to Run the Notebook

### Option 1: Using Jupyter Notebook

1. Navigate to the project directory:
   ```bash
   cd week1-project
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open the analysis notebook:
   - Navigate to `notebooks/week1-analysis.ipynb` in the Jupyter interface
   - Run all cells (Cell → Run All) or execute cells individually

## Project Structure

```
week1-project/
├── data/
│   └── online_retail_II.csv          # Dataset (not committed to git)
├── notebooks/
│   └── week1-analysis.ipynb         # Main analysis notebook
├── outputs/                          # Generated visualizations
│   ├── monthly_revenue.png
│   ├── basket_size.png
│   ├── top_products.png
│   ├── customer_frequency.png
│   ├── hourly_sales.png
│   └── country_revenue.png
└── README.md                         # This file
```

