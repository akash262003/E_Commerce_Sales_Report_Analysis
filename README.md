# E-Commerce Sales Report Analysis

## Overview

An exploratory data analysis (EDA) project on real-world e-commerce sales data using Python. The analysis uncovers revenue trends, top-performing products, city-wise sales distribution, and peak order timings to support data-driven business decisions.

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Dataset:** Monthly U.S. e-commerce sales data (December 2019, July 2019)
- **Environment:** Google Colab / Jupyter Notebook

---

## Objectives

- Identify top-selling products by quantity ordered
- Analyse revenue contribution by product
- Discover peak order hours to optimise advertisement timing
- Visualise city-wise sales distribution
- Identify frequently co-purchased products

---

## Analysis Performed

| Analysis | Description |
|---|---|
| Product Performance | Bar chart of quantity ordered per product |
| Revenue by Product | Sales revenue contribution of each product |
| Peak Order Hours | Line chart of orders by hour of the day |
| City-wise Sales | Distribution of orders across U.S. cities |
| Data Cleaning | Handling null values, duplicate Order IDs, data type conversion |
| Correlation Analysis | Heatmap of feature correlations |

---

## Key Findings

- **Highest ordered product:** USB-C Charging Cable (volume leader)
- **Highest revenue product:** MacBook Pro (premium price driver)
- **Peak order hours:** 11 AM–1 PM and 6 PM–8 PM (ideal for ad targeting)
- **Top sales city:** San Francisco, CA

---

## Tech Stack

```
Python 3.x
pandas
numpy
matplotlib
seaborn
plotly
scikit-learn
```

---

## Project Structure

```
E_Commerce_Sales_Report_Analysis/
├── e_commerce_sales_analysis.ipynb   ← Main analysis notebook
├── requirements.txt                  ← Python dependencies
└── README.md
```

---

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/akash262003/E_Commerce_Sales_Report_Analysis.git
cd E_Commerce_Sales_Report_Analysis
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook e_commerce_sales_analysis.ipynb
```

4. Update the dataset path in the notebook to your local CSV file path.

---

## Dataset

- Source: U.S. e-commerce monthly sales data
- Format: CSV
- Key columns: `Order ID`, `Product`, `Quantity Ordered`, `Price Each`, `Order Date`, `Purchase Address`

---

## Skills Demonstrated

- Data loading and cleaning with Pandas
- Exploratory Data Analysis (EDA)
- Data visualisation with Matplotlib, Seaborn, and Plotly
- Feature engineering (extracting hour, month, city from raw data)
- Business insight generation from raw transactional data

---

## Author

**Akash Saravanan**
- GitHub: [github.com/akash262003](https://github.com/akash262003)
- LinkedIn: [linkedin.com/in/akash26623](https://linkedin.com/in/akash26623)
- Email: akash26623@gmail.com
