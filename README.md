# Data Analytics Portfolio

Bilingual (English/Mandarin) professional in Taipei building practical skills in SQL, Power BI, Excel, and Python for analyst roles.

## About Me
I'm an American who has been living in Taiwan for about 19 years. I spent 10 years as a bilingual ESL teacher, two years at an immigration center giving presentations to potential clients, and a year in SEO where I first worked with web traffic data and found I truly enjoyed the analysis.

I'm looking for roles where I turn data into decisions: data analyst, business analyst, operations analyst, reporting/BI analyst, marketing or e-commerce analyst, or bilingual operations roles that use these tools. I'm especially interested in fintech, e-commerce, and tech.

## What I Bring Beyond the Tools

- Native English speaker who is fluent in everyday Mandarin after about 19 years in Taiwan, and I'm building    my business and analytics vocabulary. I can work with Taiwan-based teams and overseas stakeholders.
- Years of explaining complex ideas to non-experts which is what presenting findings involves.
- Hands-on experience with SEO data and web analytics. 

## Projects
Olist E-commerce: Late Deliveries and Review Scores (Power BI, PostgreSQL)

[olist-delivery-reviews-analysis](https://github.com/JTx3y4/olist-delivery-reviews-analysis)

Two-page Power BI report on about 98,000 orders from the Brazilian marketplace Olist that uses data mostly from 2017 to 2018.

I looked at where deliveries run late, what late orders line up with (seller handling time, carrier transit time, and the promised delivery date), and how review scores differ for late orders.

Main finding: late orders average 2.27 stars vs 4.29 for on-time orders, and late rates are the highest in the states with the shortest promise buffers.

I built a data model with one-to-many relationships and a custom date table, plus DAX measures for late delivery rate, promise buffer, and review score. Totals were cross-checked using PostgreSQL queries. 

## Fintech Transaction Analysis (SQL, Python) — in progress

Payment and crypto transaction analysis in PostgreSQL. Planned scope: merchant success rates, fraud flagging with window functions, and a pandas + SQLAlchemy pipeline from raw JSON into a designed schema with an ER diagram.

## Current Skills

**SQL (PostgreSQL)**
- SELECT, WHERE, JOINS (INNER, LEFT), including finding unmatched rows with LEFT JOIN + IS NULL
- GROUP BY, aggregations (COUNT, SUM, AVG), conditional counts with COUNT(CASE WHEN)
- CTEs and subqueries (including correlated subqueries, EXISTS / NOT EXISTS)
- Window functions: ROW_NUMBER, RANK, DENSE_RANK, LAG, LEAD, running totals with SUM() OVER
- Multi-step analysis, e.g. aggregating in a CTE, then ranking or bucketing the results (frequency
  distributions)
- Date handling: EXTRACT, DATE_TRUNC, rolling date ranges
- Data quality checks: inspecting schemas, NULLs, duplicates, deduplication with ROW_NUMBER
- UNION / UNION ALL, COALESCE, safe division with NULLIF

**Power BI** 
- Power Query: merging, grouping, custom columns, unpivot, fill down
- DAX: CALCULATE, FILTER, DIVIDE, RELATED, RELATEDTABLE, SWITCH, DISTINCTCOUNT, SUMX, ALL / REMOVEFILTERS, VAR / RETURN, time intelligence (TOTALYTD)
- Data modeling: relationships (one-to-many), cross-filter direction, date tables (CALENDAR / CALENDARAUTO)
- Report design: drill-through pages, custom tooltips, slicers, KPI cards
- Row-level security (roles, testing with "View as")

**Excel**
- Lookups: XLOOKUP (including multi-condition), INDEX/MATCH, VLOOKUP
- Conditional aggregation: SUMIFS, COUNTIFS, AVERAGEIFS
- Dynamic arrays: FILTER, SORT, UNIQUE
- Data cleaning: TRIM, CLEAN, SUBSTITUTE, text extraction (LEFT / MID / RIGHT / FIND)
- Pivot tables and PivotCharts, conditional formatting, data validation, Excel Tables
- Logic and error handling: IF / IFS, IFERROR

**Python**
- Pandas: loading CSV/JSON, cleaning, handling missing values, filtering, groupby, merge, date handling
- Matplotlib: basic charts
- SQLAlchemy: loading data from pandas into PostgreSQL

**SEO and Web Analytics**
- Google Analytics, Google Search Console, Ahrefs, Screaming Frog

