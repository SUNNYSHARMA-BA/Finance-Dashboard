# Finance Dashboard

Welcome to the **Finance Dashboard** repository! This project provides a comprehensive financial dashboard built using Power BI, leveraging a cleaned and structured version of the provided `Financial_Data.csv` file. The dashboard visualizes sales, profit, and other key metrics across different countries, segments, and products, providing valuable insights for financial analysis and decision-making.

---

## Table of Contents

- [About](#about)
- [Data Cleaning](#data-cleaning)
- [Power BI Dashboard](#power-bi-dashboard)
- [How to Use](#how-to-use)
- [Features](#features)
- [Screenshots](#screenshots)
- [Requirements](#requirements)
- [Acknowledgements](#acknowledgements)

---

## About

The Finance Dashboard is designed to help users and organizations analyze large-scale sales data quickly and efficiently. The dashboard provides interactive visualizations for:

- Units sold
- Sales and gross sales
- Profit and COGS (Cost of Goods Sold)
- Discounts and discount bands
- Performance across countries, products, segments, and time (monthly/yearly)

---

## Data Cleaning

Before importing the CSV into Power BI, it is important to clean the data for accurate visualizations. The following steps were performed:

1. **Removed Extra Spaces**: Trimmed leading and trailing spaces from headers and values.
2. **Standardized Numeric Formats**: Removed currency symbols (`$`), commas, and converted columns to appropriate numeric types (float/int).
3. **Date Formatting**: Converted date columns to a standard date format (`YYYY-MM-DD`).
4. **Fixed Column Names**: Ensured headers are consistent and free of special characters.
5. **Handled Missing/Invalid Values**: Checked for blanks or invalid entries and handled them appropriately (e.g., replacing with `0` or `N/A`).
6. **Consistent Casing**: Standardized the casing for categorical columns (e.g., segment, country, product).

> **Tip:** You can use Excel, Power Query, or pandas in Python to clean the CSV before importing into Power BI.

---

## Power BI Dashboard

The Power BI dashboard is built on the cleaned dataset and features:

- **Sales Overview**: Total sales, gross sales, and profit over time
- **Country/Region Analysis**: Sales and profit breakdown by country
- **Segment/Product Analysis**: Performance by segment and product
- **Discount Impact**: Insights into how discount bands affect sales and profit
- **Time Series**: Monthly and yearly trends

Interactive slicers and filters allow users to drill down into any combination of segment, country, product, and time period.

---

## How to Use

1. **Clone this Repository**
    ```bash
    git clone https://github.com/SUNNYSHARMA-BA/Finance-Dashboard.git
    ```
2. **Clean the CSV File**
    - Open `Financial_Data.csv` in Excel or Power Query.
    - Perform the cleaning steps as described above.
    - Save the cleaned file (you may name it `Financial_Data_Cleaned.csv`).

3. **Import into Power BI**
    - Open Power BI Desktop.
    - Import the cleaned CSV file.
    - Apply additional transformations if necessary using Power Query.
    - Build visuals using the fields provided.

4. **Publish or Share**
    - Publish the dashboard to Power BI Service or export as PDF/image for sharing.

---

## Features

- **Automated Data Cleaning Guidance**
- **Interactive Visuals and Filtering**
- **Comprehensive Financial KPIs**
- **Customizable Reports**

---

## Screenshots

> <img width="1133" height="636" alt="Screenshot 2025-07-25 124906" src="https://github.com/user-attachments/assets/c94161aa-94c3-448b-8473-c0e95b51cbfb" />


---

## Requirements

- Power BI Desktop (latest version recommended)
- Cleaned CSV data file
- Optional: Excel, Python (pandas), or other tools for data cleaning

---

## Acknowledgements

- Dataset: Your organization or source of data
- Power BI Community for tutorials and inspiration

---

**Author:** SUNNYSHARMA-BA  
**Repository:** [Finance Dashboard](https://github.com/SUNNYSHARMA-BA/Finance-Dashboard)

---
