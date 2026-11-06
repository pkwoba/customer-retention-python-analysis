# Customer Retention & Revenue Analysis | Python

## Project Overview

This project analyzes real-world retail transaction data using Python to understand revenue performance, repeat purchasing behavior, and customer retention.

The analysis uses the **UCI Online Retail dataset**, covering transactions from December 2010 through December 9, 2011.

**Business Objective:** Identify revenue trends, understand the value of repeat customers, and uncover opportunities to improve customer retention.

## Tools & Technologies

- **Python** — Data analysis and calculations
- **pandas** — Data cleaning, transformation, and aggregation
- **Matplotlib** — Revenue and retention visualizations
- **NumPy** — Missing-value handling for cohort visualizations
- **Jupyter Notebook** — Reproducible analysis and documentation

## Key Business Findings

- **£10.67 million** in gross positive sales revenue during the observed period.
- **65.58%** of identifiable customers made purchases on at least two distinct invoices.
- **93.08%** of identifiable-customer revenue came from repeat customers.
- The top **10% of identifiable customers** generated **61.38%** of identifiable-customer revenue.
- Month-to-month customer retention ranged from **31.21% to 45.60%** across complete-month comparisons.
- Cohort analysis revealed substantial differences in repeat purchasing across customer groups.

## Business Recommendations

1. Test targeted follow-up communications to encourage early repeat purchases.
2. Investigate the purchasing patterns of high-value customers.
3. Examine late-year sales patterns to support demand planning.
4. Monitor customer retention by cohort to identify changes in purchasing behavior.

## Data Source

**UCI Machine Learning Repository — Online Retail Dataset**

https://archive.ics.uci.edu/dataset/352/online+retail

## Important Notes

- Revenue represents positive-value sales and does not account for refunds, costs, or profit.
- Customer-level analyses exclude transactions without identifiable customer IDs.
- December 2011 is incomplete and is excluded from complete-month retention comparisons.
- Cohorts are based on first **observed** purchases, which may not represent customers' first-ever purchases.

## How to Run This Project

1. Download or clone this GitHub repository.
2. Make sure Python and Jupyter Notebook are installed.
3. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Open `customer_retention_analysis.ipynb` in VS Code or Jupyter Notebook.
5. Run all notebook cells from top to bottom.

The original dataset, `Online Retail.xlsx`, is included in the repository so the analysis can be reproduced without downloading additional data.

## Project Files

- `customer_retention_analysis.ipynb` — Complete Python analysis, visualizations, and business findings.
- `Online Retail.xlsx` — Original UCI Online Retail dataset.
- `requirements.txt` — Required Python libraries.
- `README.md` — Project documentation.