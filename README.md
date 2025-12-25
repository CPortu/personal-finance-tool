# Personal Finance Analysis Tool

## Course
Programming

## Project Overview
This project analyzes personal expense data to better understand spending
patterns over time and across different expense categories. The analysis
includes data cleaning, exploratory data analysis, summary statistics, and
visualizations.

The goal of the project is to transform raw financial data into meaningful
insights using Python and common data analysis libraries.

---

## Project Structure
personal-finance-tool/
│── data/
│ └── expenses_sample.csv
│── outputs/
│ ├── tables/
│ │ ├── expenses_cleaned.csv
│ │ ├── summary_by_category.csv
│ │ ├── summary_by_month.csv
│ │ ├── amount_statistics.csv
│ │ ├── average_by_category.csv
│ │ ├── transactions_by_category.csv
│ │ └── category_percentage.csv
│ └── figures/
│ ├── spend_by_category.png
│ ├── spend_by_month.png
│ └── expense_distribution_pie.png
│── finance_analysis.ipynb
│── README.md

---

## Data Description
The dataset contains individual expense records with the following fields:
- **date**: date of the transaction
- **description**: short description of the expense
- **category**: expense category (e.g. Food, Rent, Transport)
- **amount**: monetary value of the expense

---

## Analysis Performed
The analysis includes:
- Loading and inspecting the expense dataset
- Cleaning and preparing the data:
  - Converting data types
  - Handling missing and invalid values
  - Standardizing category names
- Exploratory data analysis:
  - Total expenses
  - Expenses by category
  - Monthly expenses
  - Descriptive statistics of expense amounts
  - Percentage distribution of expenses by category
- Data visualization:
  - Bar chart of total spending by category
  - Line chart of monthly spending trends
  - Pie chart of expense distribution by category

---

## Outputs
All generated outputs are automatically saved in the `outputs/` folder:
- **Tables** (`outputs/tables/`): cleaned dataset and summary statistics
- **Figures** (`outputs/figures/`): charts and visualizations used for analysis

---

## How to Run the Project
1. Clone or download the repository
2. Open `finance_analysis.ipynb` in Jupyter Notebook
3. Run all cells from top to bottom
4. Review the generated tables and figures in the `outputs/` folder

---

