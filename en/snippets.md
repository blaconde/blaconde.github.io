---
layout: default
title: "SQL / Python Snippets"
---

<p style="text-align: right;">
  <a href="/snippets">
    <img src="../assets/poland.png" alt="Polski" width="28">
  </a>
</p>

## Address data validation (SQL + Python)

This project demonstrates an approach to working with historical data and validating its correctness.

### Scope:
- selecting active contracts from historical data (date_from / date_to)
- handling duplicates and missing data
- identifying the current customer
- preparing data for address validation (NUTS)

### Approach:
- analytical functions (ROW_NUMBER, MAX OVER)
- business logic instead of system flags
- filtering activity based on the current date

### Code:
👉 [View SQL / Python repository](https://github.com/blaconde/data-analysis-snippets)

👉 [Back to main page](/en)
