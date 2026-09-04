# Data Combining Using Pandas

## Overview

This folder contains my practice and learning materials for combining multiple datasets using Python and Pandas.

In real-world data analysis, information is often stored in multiple datasets. These datasets need to be combined to perform complete analysis.

## Topics Covered

- Merge
- Inner Merge
- Left Merge
- Right Merge
- Outer Merge
- Join
- Left Join
- Inner Join
- Right Join
- Outer Join

## Merge

The `merge()` function is used to combine DataFrames based on a common column.

Example:

```python
pd.merge(left_dataframe, right_dataframe, on="CustomerID")