# 📊 Sales Data Analysis

## What I Did

### 1. Data Cleaning
- Checked for missing values using `df.isnull().sum()` — no nulls found
- Dropped null rows using `df.dropna()`

### 2. Total Revenue
- Calculated overall total sales amount → **$5,019,265.23**

### 3. Sales by Region
- Grouped sales by region to compare regional performance

| Region | Total Sales |
|--------|-------------|
| North  | $1,369,612.51 |
| East   | $1,259,792.93 |
| West   | $1,235,608.93 |
| South  | $1,154,250.86 |

### 4. Monthly Sales Trend
- Converted `Sale_Date` to datetime format
- Extracted `Month` from `Sale_Date`
- Grouped sales month-wise to identify trends

| Month | Sales Amount |
|-------|-------------|
| 2023-01 | $476,092.36 |
| 2023-02 | $368,919.36 |
| 2023-03 | $402,638.77 |
| 2023-04 | $438,992.61 |
| 2023-05 | $389,078.76 |
| 2023-06 | $418,458.34 |
| 2023-07 | $374,242.88 |
| 2023-08 | $443,171.28 |
| 2023-09 | $367,837.60 |
| 2023-10 | $460,378.78 |
| 2023-11 | $467,482.90 |
| 2023-12 | $392,643.58 |

---

## 🛠️ Tools Used
- Python, Pandas, Jupyter Notebook
