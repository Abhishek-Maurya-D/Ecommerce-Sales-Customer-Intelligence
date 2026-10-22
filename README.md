# E-Commerce Sales & Customer Intelligence Analytics

A data analytics portfolio project focused on cleaning, analyzing, and presenting e-commerce sales and customer data using **Google Sheets**.

The project follows an end-to-end spreadsheet analytics workflow: data quality checks, data cleaning, calculated metrics, sales and profitability analysis, customer analysis, pivot tables, charts, slicers, and dashboard development.

> **Dataset note:** This project uses synthetic/sample e-commerce data for learning and portfolio demonstration. Business findings should be based on the final analyzed workbook.

## Project Objectives

- Clean and validate raw e-commerce data.
- Identify missing values, duplicate records, inconsistent text, and invalid or unusual values.
- Create calculated fields for sales, discounts, costs, profit, and time-based analysis.
- Analyze sales performance, product/category performance, customer behavior, and order outcomes.
- Build pivot tables, charts, slicers, and an interactive dashboard.
- Turn the analysis into clear, practical business recommendations.

## Tools & Skills

- **Google Sheets** — data cleaning, formulas, analysis, pivot tables, charts, slicers, and dashboarding
- **Spreadsheet formulas** — calculated columns, conditional logic, lookups, date/time fields, and KPI calculations
- **Data analytics** — exploratory data analysis (EDA), data validation, segmentation, trend analysis, and business reporting
- **Data visualization** — KPI summaries, charts, and interactive dashboard elements

## Project Workflow

1. **Raw data review** — inspect the dataset structure and understand the available fields.
2. **Data quality assessment** — check for duplicate records, missing values, inconsistent text, and invalid values.
3. **Data cleaning** — standardize fields and handle quality issues using documented rules.
4. **Calculated columns** — derive gross sales, discount amount, net sales, total cost, profit, profit margin, age groups, month, year, quarter, and other useful flags where applicable.
5. **Sales analysis** — examine sales over time and compare performance across relevant segments.
6. **Product analysis** — compare products, sub-categories, and categories by sales and profitability.
7. **Customer analysis** — explore customer activity and available demographic or geographic segments.
8. **Order outcome analysis** — review order status, returns, cancellations, and ratings where the fields are available.
9. **Pivot tables and charts** — summarize the data and visualize the most useful comparisons.
10. **Dashboard** — bring key metrics, charts, and slicers together for interactive exploration.
11. **Business insights** — document evidence-based findings and practical recommendations.

## Key Metrics

The workbook may include the following metrics, depending on the completed analysis:

| Metric | Definition |
|---|---|
| Gross Sales | Quantity × Unit Price, before discount |
| Discount Amount | Gross Sales × Discount Rate |
| Net Sales | Gross Sales − Discount Amount |
| Total Cost | Quantity × Cost per Unit |
| Profit | Net Sales − Total Cost − Shipping Cost |
| Profit Margin | Profit ÷ Net Sales |
| Average Order Value (AOV) | Net Sales ÷ Number of distinct orders |
| Return Rate | Returned distinct orders ÷ distinct orders |
| Cancellation Rate | Cancelled distinct orders ÷ distinct orders |

**Metric note:** Confirm the exact formula definitions and treatment of cancelled/returned orders in the workbook before comparing results. Use distinct order counts when calculating order-level rates, and avoid mixing row counts with unique orders.

## Dataset

The dataset is organized around e-commerce transactions and supporting product/customer lookup tables. Fields may include:

- Order details: order ID, order date, customer ID, order status
- Product details: product ID, product name, category, sub-category
- Transaction details: quantity, unit price, discount, shipping cost, payment method
- Customer details: customer name, age, gender, city, state, region
- Customer feedback and sales channels: rating, sales channel, coupon code
- Derived analysis fields: gross sales, discount amount, net sales, cost, profit, profit margin, age group, month, year, quarter, and flags

Only include files in this repository that you are permitted to share. If the data is synthetic, state that clearly; if it contains any personal or confidential information, remove it before publishing.

## Repository Structure

```text
ecommerce-sales-customer-intelligence/
├── README.md
├── data/
│   ├── raw/                 # Optional: raw sample data
│   └── cleaned/             # Optional: cleaned analysis data
├── dashboard/
│   ├── screenshots/         # Dashboard screenshots
│   └── dashboard-export.pdf # Optional PDF export
├── analysis/
│   └── business-insights.md # Findings and recommendations
└── Ecommerce_Analytics_Project.xlsx  # Optional workbook export
```

This is a suggested structure. Adjust it to match the files you actually upload; remove any folders or filenames that are not present.

## Dashboard Preview

Add screenshots of your completed dashboard to `dashboard/screenshots/`, then uncomment and update the example below:

```markdown
![E-commerce Analytics Dashboard](dashboard/screenshots/dashboard.png)
```

## Business Insights & Recommendations

Add findings supported by your actual workbook. Useful questions to investigate include:

- Which months have the highest and lowest net sales?
- Which categories or products contribute most to sales and profit?
- Are high-sales products also high-profit products?
- Which regions or sales channels perform best?
- What are the observed return and cancellation rates?
- How do ratings vary across products or categories?
- Which areas may offer opportunities to improve profitability or customer experience?

For each finding, record:
1. **Finding:** What the data shows.
2. **Evidence:** The relevant metric, period, and segment.
3. **Business implication:** Why it matters.
4. **Recommendation:** A realistic action to consider.

Do not add example numbers as if they were real results. Populate this section after verifying the final analysis.

## How to Use

1. Download or clone this repository.
2. Open the `.xlsx` workbook in Microsoft Excel or import it into Google Sheets.
3. Review the raw data and documented cleaning steps.
4. Explore the calculated fields, pivot tables, charts, and dashboard.
5. Use available slicers/filters to investigate different periods and segments.
6. Read the business insights document for findings and recommendations.

## Limitations

- Results depend on the quality and assumptions of the supplied dataset.
- Synthetic data can demonstrate analytical methods but does not establish real-world business performance.
- Some advanced data-modeling features, such as Power Pivot and DAX, are outside the scope of this Google Sheets version.

## Future Improvements

- Add a verified set of business findings and recommendations.
- Include dashboard screenshots and a PDF export.
- Add a data dictionary and a concise explanation of cleaning decisions.
- Rebuild the dashboard in Power BI as a separate extension.
- Add time-series forecasting or customer segmentation if appropriate for the data.

## Author

**Abhishek Maurya**

- GitHub: [Abhishek-Maurya-D](https://github.com/Abhishek-Maurya-D)
- LinkedIn: [Abhishek Maurya](https://linkedin.com/in/abhishek-maurya-7b7228271/)
- Portfolio: [abhishekmaurya.space](https://abhishekmaurya.space)

---

*Built as a hands-on data analytics portfolio project using Google Sheets.*
