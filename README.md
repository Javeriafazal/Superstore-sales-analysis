#Superstore Sales Data Analysis
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Javeriafazal/Superstore-sales-analysis/blob/main/Superstore_Sales_Analysis.ipynb)

An end-to-end exploratory data analysis (EDA) project using SQL and Python on the Superstore Sales dataset from Kaggle.

---

## Project Summary

In this project, I:

- Downloaded real-world sales data from Kaggle using Kaggle API.
- Cleaned and explored the dataset using pandas.
- Stored and queried the data using SQLite directly inside Python.
- Performed SQL queries to extract business insights.
- Created beautiful visualizations using seaborn and matplotlib.

---

## Tools & Technologies

- Python (pandas, sqlite3, seaborn, matplotlib)
- SQL (SQLite)
- Google Colab (Jupyter environment)
- Kaggle API (for automated data download)

---

## Dataset

- Source: [Kaggle - Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- File used: `Sample - Superstore.csv`

> *Note:* Due to Kaggle's terms, the raw dataset is not included in this repo. You can download it directly from Kaggle.

---

## Project Workflow

### 1️. Download Dataset via Kaggle API

Automated download directly inside Google Colab.

### 2️. Load Data

Read the CSV file into pandas, handle encoding issues using `latin1` encoding.

### 3. Explore Data

- Checked column names, data types, missing values.
- Generated summary statistics.

### 4️. Store Data in SQLite Database

- Created a local SQLite database file (`superstore.db`).
- Loaded the cleaned DataFrame into SQL table `Orders`.

### 5️. SQL Queries

- Total Sales by Region
- Top 5 Products by Sales
- Total Sales per Category
- Total Profit per Region
- Monthly Sales Trends

### 6️. Visualizations

Created various charts to visualize business insights:

- Bar plots for sales and profits
- Line plot for sales trends over time

---

## 7. Sample Visualizations

*(Insert your screenshots here after uploading to GitHub)*

---

## Key Insights

- Sales distribution across regions
- Top-performing products
- Profitability by region
- Monthly sales fluctuations

---

## Future Scope

- More advanced SQL queries (joins, subqueries)
- Build a dashboard (e.g. using Streamlit)
- Predictive modeling on sales trends

---

##  Running the Project

1️. Clone the repository  
2️. Download the dataset from Kaggle and place it in the `/data/` folder  
3️. Open and run `Superstore_Sales_Analysis.ipynb` inside the `/notebook/` folder

---

 If you like this project, feel free to fork, star, or suggest improvements!

