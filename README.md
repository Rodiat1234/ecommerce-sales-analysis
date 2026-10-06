# E-commerce Sales & Profitability Analysis

## Project Overview

This project analyzes e-commerce sales data to understand sales performance, profitability, and factors associated with business performance.

The main business question is:

**What factors are affecting e-commerce sales and profitability?**

## Dataset

The dataset contains 34,500 e-commerce orders across 17 variables, including:

- Product category
- Price
- Discount
- Quantity
- Payment method
- Order date
- Region
- Total amount
- Shipping cost
- Profit margin
- Customer information

## Analysis Approach

The analysis follows two main stages:

### Descriptive Analysis
I examined:
- Sales by category
- Average order value by category
- Sales by region
- Average order value by region
- Sales trends over time
- Profitability by category

### Diagnostic Analysis
I investigated important patterns identified during the descriptive analysis, including:
- The decline in sales from 2024 Q2 to Q3
- The factors associated with weaker Electronics performance
- The negative profitability of the Grocery category
- The relationship between product price, shipping costs, and Grocery profitability

## Key Findings

1. **Electronics was the strongest category.** It generated the highest total sales (about 3.32M, over half of all sales), the highest average order value (537.09), and the highest average profit margin (55.72).

2. **The South region had the highest total sales (about 1.30M), driven by order volume.** The West had the highest average order value (174.26), even with fewer orders than the South.

3. **Sales fell 10.4% from 2024 Q2 to Q3 (764,627 to 684,857), even though orders rose slightly (4,244 to 4,297).** Electronics drove the drop. Its sales fell 17.9%, with orders down from 763 to 721 and average order value down from 582.81 to 506.23. Average discounts stayed broadly stable.

4. **Grocery was the only category with a negative average profit margin (-2.26).** It also had the lowest average order value (20.21), and 97.7% of Grocery orders were priced below 50.

5. **Shipping cost took a much bigger share of price on cheap Grocery items.**

| Price group | Orders | Avg profit margin | Shipping / price |
|---|---|---|---|
| 0-5 | 1,081 | -1.95 | 0.85 |
| 5-10 | 905 | -2.59 | 0.47 |
| 10-20 | 1,101 | -2.76 | 0.31 |
| 20-50 | 877 | -2.02 | 0.19 |
| 50-100 | 91 | 0.22 | 0.11 |
| 100-150 | 3 | 18.04 | 0.07 |

Only the orders above 50 broke even, and those are just 2.3% of Grocery orders.

## Recommendations

The analysis suggests that the business could:

- Prioritize the Electronics category.
- Investigate the factors behind the Electronics sales decline.
- Review pricing and shipping strategies for Grocery products.
- Encourage higher-value orders through bundles and cross-selling.
- Monitor profitability alongside sales when evaluating category performance.

## Tools Used

- Python
- pandas
- Matplotlib
- Jupyter Notebook

## Project Type

Data Analysis | Descriptive Analysis | Diagnostic Analysis

## Dataset Source

The dataset used in this project was obtained from Kaggle.
