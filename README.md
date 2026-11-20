# Supermarket Sales Analysis (Power BI)

A two-page Power BI report on supermarket sales across three branches in Nigeria: **Sales Performance** (the big picture) and **Product Performance** (which product lines sell best).

![Sales Performance Dashboard](Screenshot%202026-10-13%20033043.png)

![Product Performance Dashboard](Screenshot%202026-10-13%20033434.png)

## The question

Where do sales come from (city, branch, payment method, customer group, month), and which product lines perform best?

## The data

- A practice dataset of **227 invoices** and 17 columns (`sells power bi.xlsx`).
- Period covered: **1 January to 30 March 2019**.
- Fields include branch, city, customer type, gender, product line, unit price, quantity, tax, total, date, payment method and rating.
- There are no missing values and no duplicate invoice IDs.
- The Excel sheet ends with a summary row called "Total". I removed it so it is not counted as a sale (it would double every total).
- Each city has exactly one branch (Lagos = Lekki, Ibadan = Bodija, Abuja = Central Area), so city and branch show the same numbers.
- Sales are spread very evenly across groups, which suggests the data is simulated. This project is about dashboard design and analysis skills, not real business conclusions.

## What I built

**Page 1: Sales Performance**
- KPI cards: Total Sales, Gross Income, Quantity Sold, Total Tax, Average Rating, Total COGS
- Total Sales by City, Branch, Payment method, Gender, Month and Customer type
- Gross Income by Product line

**Page 2: Product Performance**
- Total Sales, Gross Income and Quantity Sold by Product line
- Slicers: City, Branch, Product line, Gender, Payment and Month
- Business insights, key findings and recommendations

## Key numbers

| Measure | Value |
|---|---|
| Total sales | ₦159.55K |
| Gross income | ₦7.60K |
| Gross margin | 4.76% |
| Total COGS | ₦151.96K |
| Quantity sold | 1,901 units |
| Average rating | 6.86 / 10 |

## My Findings

| Group | Result |
|---|---|
| Top city / branch | Lagos (Lekki branch): ₦58.09K, 36.4% of total sales |
| Next | Ibadan (Bodija) ₦52.84K, then Abuja (Central Area) ₦48.62K |
| Top payment method | Cash ₦54.65K, then Credit card ₦53.04K, Ewallet ₦51.87K |
| Top product line | Sports and travel ₦27.87K; lowest is Fashion accessories ₦25.19K |
| Gender | Female 53.4%, Male 46.6% of sales |
| Customer type | Members ₦83.3K, Normal customers ₦76.2K |
| Best month | January ₦59.06K, then March ₦52.77K and February ₦47.72K |

- The gap between the best and worst product line is small (about ₦2.7K), so no single line dominates.
- Home and lifestyle has the lowest average rating (6.33); Fashion accessories has the highest (7.16).
- Gross income equals the 5% tax column in this dataset, so the two KPI cards show the same figure (₦7.60K).

## Recommendations

1. Focus marketing on Lagos (Lekki), the strongest branch.
2. Look at why ratings average only 6.86 and try to raise them above 8.
3. Promote digital payments, since cash is still the most used method.
4. Review the lower-selling branches and product lines for improvement.

## How I built it

1. Loaded `sells power bi.xlsx` into Power BI and cleaned the data in Power Query (removed the summary "Total" row, set data types).
2. Built the KPI cards and charts.
3. Added slicers so the report can be filtered by city, branch, product line, gender, payment method and month.
4. Wrote the insights and recommendations from the verified figures.

## Tools

Power BI, Power Query, DAX, Excel

## Files

- [sells performaces file.pbix](sells%20performaces%20file.pbix): the Power BI report
- [sells power bi.xlsx](sells%20power%20bi.xlsx): the dataset
- [Sales Performance screenshot](Screenshot%202026-10-13%20033043.png)
- [Product Performance screenshot](Screenshot%202026-10-13%20033434.png)

## About me

Osavibie Deborah Edoruyi, aspiring data analyst.

[LinkedIn](https://www.linkedin.com/in/osavibie-edoruyi-1131a6329)
