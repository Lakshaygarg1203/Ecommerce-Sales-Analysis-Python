# E-Commerce Sales Analysis using Python

## About the Project

This project analyzes a synthetic e-commerce sales dataset using Python and pandas.

The goal is to clean the data, explore sales trends, understand customer purchases, and answer basic business questions using charts.

**Dataset:** Synthetic e-commerce transactions (not real customer data).

## Tools Used

- Python
- pandas
- NumPy
- Matplotlib
- Google Colab

## Data Cleaning

Before starting the analysis, I performed the following steps:

- Checked missing values and duplicate records.
- Removed duplicate rows.
- Filled missing region and payment method values with `Unknown`.
- Converted order dates into datetime format.
- Removed rows with invalid prices, quantities, or missing dates.
- Created `sales_amount` and `month` columns.

## Questions Answered

1. How did monthly completed sales change?
2. Which product categories generated the most sales?
3. Which regions generated the most sales?
4. How many customers made repeat purchases?
5. Which categories had the highest returned-order rates?

I also calculated the average completed order value.

## Visualizations

Created five charts using Matplotlib to compare monthly sales, product categories, regions, repeat customers, and returned-order rates.

## How to Run

1. Download `Ecommerce_Sales_Analysis.ipynb` and `ecommerce_sales_synthetic.csv`.
2. Open the notebook in Google Colab.
3. Upload the CSV file using:

```python
from google.colab import files
files.upload()
```

4. Run the notebook cells from top to bottom.

## Limitations

- This project uses synthetic data, so findings do not represent actual business performance.
- Sales value is not the same as profit.
- Return rates are calculated using orders marked Completed or Returned.
- Each row represents one order in this generated dataset.

## What I Learned

Through this project, I practiced data cleaning, filtering, grouping, aggregation, date handling, and visualization using pandas and Matplotlib.
