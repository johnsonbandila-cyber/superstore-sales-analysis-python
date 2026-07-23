# 📊 Superstore Sales Analysis using Python

## 📌 Project Overview

This project analyzes Superstore sales data using **Python**, **Pandas**, and **Matplotlib**. The dataset is divided into four relational tables (**Sales, Orders, Products, and Shipping**) to simulate a real-world business database.

The project demonstrates **data cleaning, data modeling, exploratory data analysis (EDA), data visualization, and business insight generation** using Python.

---

## 🎯 Objectives

- Analyze sales performance across product categories.
- Compare sales across different regions.
- Identify top-performing customers.
- Find the highest-selling products.
- Analyze profit by category.
- Compare shipping costs across different markets.
- Practice relational data modeling using Pandas.
- Generate business insights through visualizations.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- VS Code
- OpenPyXL

---

## 📂 Dataset

The project uses four datasets.

| Dataset | Description |
|----------|-------------|
| Sales.csv | Sales transactions including Sales, Quantity, and Profit |
| Orders.csv | Order details including Customer Name and Order Date |
| Products.csv | Product information including Category and Sub-Category |
| Shipping.csv | Shipping details including Region, Market, and Shipping Cost |

---

## 🔗 Data Model

The project simulates a relational database by connecting multiple datasets using **Pandas merge()**.

### Relationships

- **Sales ↔ Products** using `product_id`
- **Sales ↔ Orders** using `order_id` and `product_id`
- **Sales ↔ Shipping** using `order_id`

This approach demonstrates practical data modeling techniques commonly used in analytics projects.

---

## 📊 Business Questions Solved

### 1️⃣ Sales by Category
- Merged **Sales** and **Products**
- Calculated total sales for each category
- Visualized using a Bar Chart

---

### 2️⃣ Sales by Region
- Merged **Sales** and **Shipping**
- Compared sales across regions
- Visualized using a Bar Chart

---

### 3️⃣ Top Customers by Sales
- Merged **Sales** and **Orders**
- Identified top customers based on total sales
- Visualized using a Bar Chart

---

### 4️⃣ Profit by Category
- Merged **Sales** and **Products**
- Compared profit across categories
- Visualized using a Pie Chart

---

### 5️⃣ Shipping Cost by Market
- Used Shipping dataset
- Compared shipping costs across markets
- Visualized using a Bar Chart

---

### 6️⃣ Top 10 Products by Sales
- Used Sales dataset
- Ranked products based on sales
- Visualized using a Bar Chart

---

## 📈 Visualizations

- Bar Charts
- Pie Charts

---

## 📂 Project Structure

```
superstore-sales-analysis-python/
│
├── data/
│   ├── Sales.csv
│   ├── Orders.csv
│   ├── Products.csv
│   └── Shipping.csv
│
├── notebook/
│   └── Python_Sales_Data_Analysis.ipynb
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/johnsonbandila-cyber/superstore-sales-analysis-python.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## 📋 Requirements

```
pandas
matplotlib
openpyxl
jupyter
```

---

## 🛠 Skills Demonstrated

- Python
- Pandas
- Matplotlib
- Data Cleaning
- Data Modeling
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insight Generation

---


## 🚀 Key Learning Outcomes

- Reading Excel files using Pandas
- Data cleaning and exploration
- Working with multiple datasets
- Data modeling using `pd.merge()`
- Grouping and aggregation using `groupby()`
- Sorting and filtering data
- Creating business reports using Matplotlib
- Extracting meaningful business insights from raw data

---

## 📊 Key Insights

- Office Supplies generated the highest total sales.
- Central region recorded the highest overall sales.
- Aaron Bergman was the top customer based on total sales.
- Office Supplies generated the highest profit.
- APAC incurred the highest shipping cost.
- Apple Smart Phone, Full Size was the highest-selling product.

---

## 💼 Business Impact

This analysis helps businesses:

- Identify high-performing product categories.
- Understand regional sales performance.
- Recognize valuable customers.
- Optimize shipping costs.
- Support data-driven decision making.

---

## 📌 Future Enhancements

- Monthly Sales Trend Analysis
- Sales Distribution (Histogram)
- Profit Distribution
- Scatter Plot (Sales vs Profit)
- Box Plot for Outlier Detection
- Correlation Analysis
- Interactive Dashboard using Power BI
- Advanced Visualizations using Seaborn

---


## 👨‍💻 Author

**Johnson Bandila**

Aspiring Data Analyst

### Skills

- Python
- SQL
- Excel
- Power BI
- Pandas
- Matplotlib
- Data Visualization

### GitHub

https://github.com/johnsonbandila-cyber

---

## 📄 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

Thank you for visiting this repository!
