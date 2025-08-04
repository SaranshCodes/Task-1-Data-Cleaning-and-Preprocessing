# 📊 Netflix Dataset Cleaning with Python

This repository contains the data cleaning process performed on the Netflix dataset from Kaggle using **Python (pandas)**.

## 🧹 Cleaning Steps Performed

- ✅ **Identified missing values** using `.isnull()` to get a clear view of incomplete data.
- ✅ **Handled missing values**:
  - Filled `'Not Available'` in place of missing values **only in text-based columns** to preserve data types.
- ✅ **Converted date columns** (like `date_added`) into proper `datetime` format for consistency.
- ✅ **Standardized column names**:
  - Renamed all column headers to be **lowercase** and **underscore-separated**, removing spaces for uniformity.
- ✅ **Fixed incorrect data types**:
  - Converted numeric fields like `release_year` to `int`.
  - Ensured `date_added` is in proper datetime format.
- ✅ **Removed duplicate rows** using `.drop_duplicates()` to avoid redundancy.
- ✅ **Cleaned textual data**:
  - In the `title` column, removed unwanted characters like `#` from the beginning of titles using string cleaning techniques.
