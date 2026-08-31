# Retail Sales Analysis

## Project overview

Analysis of retail sales data from the MySklad system for the period from 25 July to 24 August 2026.

The project explores sales performance, product profitability, customer purchasing behaviour and time-based demand patterns.

## Business task

Identify key sales and profit drivers, analyse customer purchase behaviour and provide recommendations for pricing, assortment management and sales growth.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- MySklad API
- Jupyter Notebook

## Dataset

- 1,000 receipts
- 2,038 sales line items
- 275 product names
- Analysis period: 25 July — 24 August 2026

## Key metrics

| Metric | Value |
|---|---:|
| Revenue | 698,311.54 RUB |
| Gross profit | 195,147.60 RUB |
| Gross margin | 27.95% |
| Number of receipts | 1,000 |
| Average receipt | 698.31 RUB |
| Average items per receipt | 2.04 |

## Analysis performed

- Data collection from MySklad API
- Data cleaning and cost-price preparation
- Revenue, profit and margin calculation
- Daily, weekday and hourly sales analysis
- Best-selling and most profitable products
- Product-pair analysis
- Discount analysis
- ABC analysis by revenue and profit

## Key findings

- Revenue leaders are not always profit leaders.
- Some high-revenue products have very low or zero calculated profit and require a pricing and cost review.
- Products such as beef tenderloin and chicken wings kebab show high profitability and are candidates for promotion.
- Weekends generate the highest revenue in the analysed period.
- Discounts are almost not used, which creates an opportunity to test loyalty offers.
- Popular product pairs can be used for bundles and cross-selling.

## Business recommendations

1. Review prices and costs for high-revenue, low-profit products.
2. Ensure stock availability of key products on weekends and during peak hours.
3. Promote high-margin products.
4. Use frequent product pairs for bundled offers and cross-selling.
5. Test discounts or a loyalty programme to increase repeat purchases and average receipt value.

## Note

Some cost prices were estimated using business assumptions.
