
---

## 3. Data Analysis — README.md

```md
# Data Analysis Using Pandas

## Overview

This folder contains my practice and learning materials for analyzing datasets using Python and Pandas.

The focus of this section is to summarize data and extract meaningful insights using GroupBy and Pivot Tables.

## Topics Covered

- GroupBy
- Aggregation Functions
- Multiple Aggregations
- Grouping by Multiple Columns
- Pivot Tables
- Summary Reports
- Business Insights

## GroupBy Operations

The following aggregation functions were practiced:

- `sum()`
- `mean()`
- `count()`
- `min()`
- `max()`
- `agg()`

Example:

```python
df.groupby("Region")["Sales"].sum()