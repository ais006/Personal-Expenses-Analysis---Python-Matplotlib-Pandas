# Personal-Expenses-Analysis---Python-Matplotlib-Pandas
 Python project analyzing personal expenses using Pandas and Matplotlib. The project explores spending patterns, monthly trends, expense categories, and payment methods through data analysis and visualizations.
 
# Personal Expenses Analysis

 Data analysis project built with **Python, Pandas and Matplotlib**.

## Project Overview

The goal of this project is to analyze personal spending patterns and answer questions such as:

- How much money was spent in total?
- What is the average transaction amount?
- Which category has the highest spending?
- Which month has the highest spending?
- Which payment method is used most?
- What are the largest individual expenses?

## Dataset

The dataset contains **268 expense transactions** from January to June 2026.

Columns:

| Column | Description |
|---|---|
| `id` | Unique transaction ID |
| `date` | Transaction date |
| `category` | Expense category |
| `description` | Type of expense |
| `amount` | Expense amount |
| `payment_method` | Payment method |

> The dataset is synthetic and was created for educational/portfolio purposes.

## Technologies

- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Structure

```text
personal-expenses-analysis/
│
├── data/
│   └── expenses.csv
│
├── notebooks/
│   └── expenses_analysis.ipynb
│
├── images/
│   ├── expenses_by_category.png
│   ├── monthly_expenses.png
│   ├── expenses_by_category_pie.png
│   └── expenses_by_payment_method.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Key Results

- **Total expenses:** $15,890.46
- **Average transaction:** $59.29
- **Highest single expense:** $178.27
- **Largest spending category:** Shopping
- **Highest-spending month:** 2026-03

## Visualizations

### Expenses by Category

![Expenses by Category](images/expenses_by_category.png)

### Monthly Expenses

![Monthly Expenses](images/monthly_expenses.png)

### Expense Distribution

![Expense Distribution](images/expenses_by_category_pie.png)

### Payment Methods

![Payment Methods](images/expenses_by_payment_method.png)

## How to Run

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
cd personal-expenses-analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

Open:

```text
notebooks/expenses_analysis.ipynb
```

## Skills Demonstrated

- Data loading with Pandas
- Data cleaning and validation
- GroupBy aggregation
- Date/time analysis
- KPI calculation
- Exploratory Data Analysis (EDA)
- Data visualization with Matplotlib
- Writing a reproducible analysis
- Presenting results in GitHub

## Author

**Aisana Serikzhanova**

Portfolio project — Data Analysis / Python / SQL
