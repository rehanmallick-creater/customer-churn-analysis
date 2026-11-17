# Customer Churn Analysis

I built this project to practice the full data analyst workflow on one dataset: pulling data from a database, cleaning it, exploring it, and turning it into something a business could act on.

## What I wanted to find out

Which customers are likely to leave, and why? If a company knows that, it can do something about it before the customer is gone.

## Tools I used

- SQLite for the database
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

## How I went about it

1. **Getting the data:** I connected Python to the SQLite database and loaded the tables with SQL queries.
2. **Cleaning:** I checked data quality, filled or handled missing values, renamed columns and fixed data types (like dates).
3. **Feature engineering:** I created new columns, such as customer tenure, to get more out of the data.
4. **EDA:** I used `groupby` and pivot tables to look for patterns in who churns.
5. **Visualization:** I made charts with Matplotlib and Seaborn so the trends are easy to see.
6. **Insights:** I wrote up what I found as simple recommendations.

## What I worked out

- Calculated the main KPIs: churn rate, escalation rate and average tenure.
- Ran a correlation analysis between support escalations and churn.
- Suggested a few actions based on the data, like improving the basic plan and looking into regions where churn is higher.

## How to run it

1. Clone this repo.
2. Make sure `customer_churn.db` is in the same folder as the notebook.
3. Install the libraries: `pip install pandas numpy matplotlib seaborn`
4. Open `Churn_Analysis.ipynb` in Jupyter Notebook and run the cells in order.

