# Telco Customer Churn — Exploratory Data Analysis (Python)

## Project Description
The Telco Customer Churn EDA project is a Python data analysis project
that performs full exploratory data analysis on a real telecom company
customer dataset. The project identifies why customers are leaving the
company by analyzing 7043 customer records across 21 features.

This project demonstrates practical data analysis skills including data
cleaning, univariate analysis, bivariate analysis, correlation analysis,
and business insight generation using Pandas and Matplotlib.

---

## Key Findings
- Overall churn rate is 26.5% — 1 in 4 customers is leaving
- Month-to-month contract customers churn at 42.7%
- Electronic check payment customers churn at 45.3%
- Fiber optic internet customers churn at 41.9%
- Senior citizens churn at 41.7% — almost double non-seniors
- Customers without tech support churn at 41.6%
- New customers (low tenure) are the highest risk group
- Gender has almost no impact on churn (26.9% vs 26.2%)

---

## Features
- Load and explore real world telecom dataset
- Detect and fix incorrect data types
- Handle missing values using business logic
- Encode categorical target column
- Univariate analysis of all numeric and categorical columns
- Bivariate analysis of churn vs every feature
- Correlation analysis between numeric columns
- Business recommendations based on findings

---

## Concepts Used

### Python Fundamentals
- Variables, conditions, loops
- String formatting
- Functions and lambda

### Pandas Concepts
- read_csv() for data loading
- info(), describe(), head() for exploration
- isnull(), fillna(), dropna() for missing values
- to_numeric() for dtype conversion
- map() for label encoding
- groupby() and agg() for group analysis
- value_counts() for frequency analysis
- corr() for correlation matrix
- Boolean indexing for filtering

### Matplotlib Concepts
- plt.subplots() for multiple charts
- hist() for distribution analysis
- bar() for category comparison
- alpha for transparency in overlapping charts
- flatten() for 2D subplot grids
- enumerate() for loop-based chart generation
- tight_layout() and suptitle() for clean layout

### Analysis Concepts
- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Class imbalance observation
- Business insight generation

---

## Project Structure
telco-churn-eda/
│
├── telco_churn_eda.ipynb
├── Telco-Customer-Churn.csv
└── README.md

---

## How to Run

### Requirements
- Python 3.x
- Pandas library
- NumPy library
- Matplotlib library

### Install Libraries
pip install pandas numpy matplotlib

### Steps
1. Clone or download this repository
2. Place Telco-Customer-Churn.csv in the project folder
3. Open telco_churn_eda.ipynb in Jupyter Notebook or VS Code
4. Run all cells from top to bottom

---

## Analysis Performed

Load dataset and explore shape, dtypes, statistics
Fix TotalCharges column from object to float
Handle 11 missing values using business logic (tenure = 0)
Encode Churn column from Yes/No to 1/0
Univariate analysis of tenure, MonthlyCharges, TotalCharges
Univariate analysis of 8 categorical columns
Bivariate analysis of churn vs all features
Correlation heatmap of numeric columns
Business conclusions and recommendations


---

## Business Recommendations

Push customers toward annual or two year contracts
Encourage automatic payment setup
Investigate fiber optic service quality or reprice plans
Create simplified plans for senior citizens
Provide tech support to all customers especially in year one
Focus retention campaigns on new customers (0-12 months)


---

## Dataset
- Source: Telco Customer Churn Dataset
- Rows: 7043 customers
- Columns: 21 features
- Target: Churn (Yes/No)

---

## Author
Meet Tailor
Data Science Learner
GitHub: https://github.com/MeetTailor-Data

---

## License
This project is created for learning and educational purposes only.

---

## Project Status
Completed
Last Updated: May 2026
