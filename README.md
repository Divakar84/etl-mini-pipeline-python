# 🚀 ETL Mini Pipeline – Python

This project implements a simple **ETL (Extract → Transform → Load)** pipeline using Python and pandas.

## 🛠 Tech Stack
- Python (Colab)
- pandas
- SQLite
- CSV

## 🔄 ETL Steps

### 1️⃣ Extract
- Loaded raw Kaggle dataset (CSV)
- Stored in `raw/` folder

### 2️⃣ Transform
- Removed missing values and duplicates
- Standardized column names and data types
- Created derived columns (e.g., profit_margin, segment_flag)
- Validated row counts before & after cleaning

### 3️⃣ Load
- Exported cleaned data to `processed_data.csv`
- Split into customers/orders/products outputs
- Loaded final data into `database.sqlite`

## 📂 Project Files
- `task14_etl.ipynb`
- `processed_data.csv`
- `database.sqlite`

## 🎯 Objective
To demonstrate a real-world ETL workflow using Python and SQLite for data engineering practice.
