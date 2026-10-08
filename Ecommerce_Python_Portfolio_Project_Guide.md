# E-Commerce Sales & Customer Analytics — Python Portfolio Project

## Project type
Real-world-style Data Analyst project using Python, NumPy, pandas, Matplotlib and Seaborn.

## Business scenario
You are working as a Junior Data Analyst for an Indian e-commerce company. Management wants to understand sales performance, profitability, customer behavior, product performance and regional trends from 2025 transaction data.

The supplied dataset is intentionally **uncleaned** so that the project demonstrates a complete analyst workflow rather than only visualization.

## Dataset
**File:** `Ecommerce_Sales_Analytics_Uncleaned.csv`

Approx. 5,000+ transaction rows and 17 columns.

### Main fields
- Order_ID — unique order identifier
- Order_Date — transaction date
- Customer_ID — customer identifier
- City / Region — geography
- Category / Product — product hierarchy
- Quantity / Unit_Price / Discount — order economics
- Sales / Profit — business KPIs
- Payment_Method / Sales_Channel — transaction channel
- Customer_Type — New vs Returning
- Customer_Rating — customer feedback
- Shipping_Type — delivery option

## Project objective
Answer business questions such as:
1. What is the overall sales and profit performance?
2. Which categories and products generate the most sales?
3. Which products/categories generate the most profit?
4. Which regions and cities perform best?
5. How do new and returning customers differ?
6. Which sales channels contribute most to revenue?
7. Does discount level appear related to profit?
8. Which payment methods are most commonly used?
9. How do sales and profit change month by month?
10. Which products have high sales but comparatively weak profit?
11. What customer-rating patterns are visible?
12. What recommendations can be supported by the analysis?

## Required analyst workflow

### Phase 1 — Problem understanding
Write:
- Business problem
- Business objectives
- KPIs
- Questions to answer
- Assumptions

### Phase 2 — Data loading
Use:
- pandas
- `read_csv()` / `read_excel()`

### Phase 3 — Data understanding
Perform:
- `shape`
- `head()`, `tail()`
- `info()`
- `describe()`
- `nunique()`
- unique-value inspection
- datatype checks

### Phase 4 — Data cleaning
Investigate and handle:
- Missing values
- Duplicate rows
- Incorrect datatypes
- Inconsistent text/case
- Impossible/suspicious quantity values
- Suspicious discount values
- Date formatting
- Any other issues you discover

**Important:** Do not blindly delete data. For every cleaning decision, document WHY you made it.

### Phase 5 — Univariate analysis
Analyze distributions of:
- Sales
- Profit
- Quantity
- Unit_Price
- Discount
- Customer_Rating

Use suitable histograms, boxplots and countplots.

### Phase 6 — Bivariate / multivariate analysis
Study relationships such as:
- Category vs Sales
- Category vs Profit
- Region vs Sales
- Region vs Profit
- Discount vs Profit
- Quantity vs Sales
- Customer Type vs Sales
- Sales Channel vs Sales
- Rating vs Sales

Use suitable charts and explain the business meaning.

### Phase 7 — Time-series analysis
Create:
- Monthly sales
- Monthly profit
- Monthly order volume

Identify peaks, low periods and trends.

### Phase 8 — Business insights
For every important chart, write 1–3 sentences:
- What happened?
- Why might it matter?
- What should the business investigate/do next?

Do not write observations that cannot be supported by the data.

### Phase 9 — Final recommendations
Give 5–8 data-backed recommendations.

Each recommendation should connect:
**Finding → Business impact → Suggested action**

## Portfolio deliverables
Create these files:
1. `01_Data_Cleaning.ipynb`
2. `02_EDA_Analysis.ipynb`
3. `03_Business_Insights.ipynb`
4. `Ecommerce_Sales_Analytics_Uncleaned.csv`
5. `README.md`
6. Optional: `Ecommerce_Sales_Analytics_Report.pdf`

## Suggested GitHub structure

```text
ecommerce-sales-analytics/
│
├── data/
│   └── Ecommerce_Sales_Analytics_Uncleaned.csv
│
├── notebooks/
│   ├── 01_Data_Cleaning.ipynb
│   ├── 02_EDA_Analysis.ipynb
│   └── 03_Business_Insights.ipynb
│
├── reports/
│   └── Ecommerce_Sales_Analytics_Report.pdf
│
├── README.md
└── requirements.txt
```

## Skills demonstrated
- Python
- NumPy
- pandas
- Matplotlib
- Seaborn
- Data cleaning
- Exploratory Data Analysis
- Business analysis
- Data visualization
- Insight generation

## Important portfolio rule
Do not copy a finished analysis from the internet. Your portfolio should show your own cleaning decisions, code, visualizations and business reasoning.

## Next step
Start with **Phase 1 and Phase 2 only**. Do not jump directly to charts. The goal is to make the project look like a professional analyst workflow.
