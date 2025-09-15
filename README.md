# Exploratory Data Analysis & Descriptive Statistics

This exercise is designed to give you hands-on practice with applying simple summary functions to columns in a pandas `DataFrame`.

## Goal
You will write functions to compute descriptive statistics (like the interquartile range and a modified standard deviation), and then apply them across multiple columns. Along the way, you’ll learn how pandas handles missing values and how to use `.agg()` for multiple functions.

## Files
- **eda-dv.ipynb** — The starter notebook. Begin here.
- **eda-dv-solution.ipynb** — A worked solution for reference.

## Key Concepts
- **Custom functions** in Python: e.g., `iqr()` and `std_2()`.
- **Handling missing values**: use `Series.quantile()` or NumPy’s `nan`-aware functions like `np.nanquantile` and `np.nanstd`.
- **pandas `.agg()`**: apply multiple functions to one or more columns.

