# Customer Churn Analysis

Analysis of 600 cleaned customer records: churn rate, Customer Lifetime Value (CLV), monthly revenue (MRR) loss, churn drivers and recommendations.

## Files
- `Customer_Churn_Analysis_Report.pdf` – analytics report with charts and key findings
- `churn_analysis.ipynb` – Jupyter Notebook that reproduces every number and chart
- `customer_churn_clean.csv` – cleaned dataset used for the analysis

## Key findings
- Churn rate is **41.2%** (247 of 600 customers).
- **₹187,320 of monthly revenue (MRR) is lost**, which is 41.1% of the total.
- Estimated CLV is about **₹65,583** per customer.
- Month-to-month contracts churn at **59.8%**, against about 20% for annual contracts. They make up 77% of all churn.
- Late payments are the strongest warning sign. Churn rises from 24% (none) to 55% (two) and 69% (three).
- Customers with 3 or more support tickets churn at about 50% or more.
- First-year customers churn at 54%, against 35% after four years.
- Age, price, plan type, auto-pay and region show little or no effect.

## Recommendations
1. Move month-to-month customers onto annual contracts.
2. Act on the first late payment.
3. Escalate customers with repeated support tickets.
4. Build a first-year onboarding programme.
5. Encourage card or net-banking auto-debit.
6. Prioritise retention of Pro customers, who account for 51% of lost MRR.

## Method
- Churn rate = churned customers ÷ all customers
- MRR loss = monthly charges of churned customers
- CLV = average monthly charge ÷ monthly churn rate

CLV assumes churn stays constant, so use it to compare segments, not as an exact forecast. The data shows patterns, not proven causes.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
