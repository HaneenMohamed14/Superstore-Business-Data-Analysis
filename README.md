# Superstore Business Data Analysis 📊

## 📌 Project Overview

This project presents a **business data analysis of the Superstore dataset** using Python.

The analysis focuses on understanding sales performance, profitability, customer behavior, product performance, discounts, shipping, and regional performance.

The project follows a complete data analysis workflow, from data preparation and feature engineering to exploratory data analysis, visualization, statistical analysis, and business insights.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Analyze overall sales and profit performance.
* Compare sales and profitability across categories and regions.
* Identify profitable and loss-making sub-categories.
* Analyze customer contribution to sales and profit.
* Investigate the relationship between sales, profit, discount, and quantity.
* Analyze monthly sales and profit trends.
* Examine shipping duration and shipping modes.
* Identify important business patterns and insights from the data.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 🔄 Analysis Workflow

The project follows these main steps:

### 1. Data Preparation

* Loaded the Superstore dataset.
* Checked data types and data quality.
* Handled missing and inconsistent values.
* Prepared the dataset for analysis.

### 2. Feature Engineering

Created additional features including:

* **Profit Margin**
* **Shipping Duration**
* **Order Quarter**
* **Sales Performance Category**

### 3. Exploratory Data Analysis

Performed analysis on:

* Sales
* Profit
* Categories
* Sub-Categories
* Regions
* Customers
* Segments
* Discounts
* Shipping Modes
* Monthly trends

### 4. Data Visualization

Created 10 visualizations using Matplotlib and Seaborn to identify important patterns and relationships in the data.

---

## 📊 Visualizations

The project includes the following 10 visualizations:

1. **Distribution of Sales**
2. **Distribution of Profit**
3. **Correlation Heatmap**
4. **Total Sales by Category**
5. **Total Profit by Sub-Category**
6. **Monthly Sales & Profit Trend**
7. **Discount Distribution by Category**
8. **Sales vs Profit by Category**
9. **Orders by Sales Performance Category**
10. **Shipping Duration by Ship Mode**

The chart images are available in the [`charts`](./charts) folder.

---

## 💡 Key Business Insights

### Category Performance

* **Technology** generated the highest total sales and strong profitability.
* **Furniture** had considerably lower profitability compared with the other categories.
* **Office Supplies** generated a high number of orders and maintained strong profitability.

### Regional Performance

* The **West** region recorded the highest total sales and profit.
* The **East** region also showed strong sales and profitability.
* The **Central** region had lower profitability compared with the other regions.

### Customer Contribution

The analysis showed that a relatively small group of customers contributes a significant share of total sales and profit.

The top 20% of customers accounted for approximately:

* **47.96% of total sales**
* **81.42% of total profit**

### Sales, Profit & Discount

The correlation analysis showed:

* Sales and profit have a **positive relationship**.
* Discount has a **negative relationship** with profit.
* Shipping duration has a very weak relationship with both sales and profit.

### Shipping

Shipping duration varies significantly by shipping mode:

* Same Day: approximately **0 days**
* First Class: approximately **2 days**
* Second Class: approximately **3 days**
* Standard Class: approximately **5 days**

---

## 📈 Business Questions

The analysis addresses multiple business questions, including:

* Which category generates the highest sales?
* Which category is the most profitable?
* Which sub-categories generate losses?
* Which region performs best?
* Which customers contribute most to revenue and profit?
* How does discount affect profitability?
* What is the relationship between sales and profit?
* How do sales and profit change over time?
* Which shipping mode has the longest delivery duration?
* How are orders distributed across sales performance levels?

---

## 📁 Repository Structure

```text
Superstore-Business-Data-Analysis/
│
├── Superstore_Business_Analysis.ipynb
├── README.md
├── requirements.txt
│
├── charts/
│   ├── sales_distribution.png
│   ├── profit_distribution.png
│   ├── correlation_heatmap.png
│   ├── sales_by_category.png
│   ├── profit_by_subcategory.png
│   ├── monthly_sales_profit.png
│   ├── discount_by_category.png
│   ├── sales_vs_profit.png
│   ├── sales_performance_category.png
│   └── shipping_duration_by_mode.png
│
└── data/
    └── .gitkeep
``

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/HaneenMohamed14/Superstore-Business-Data-Analysis.git
```

### 2. Install the required libraries

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

Open:

```text
Superstore_Business_Analysis.ipynb
```

using Jupyter Notebook or JupyterLab.

### 4. Run the cells

Run the notebook cells from beginning to end to reproduce the analysis and visualizations.

---

## 📦 Requirements

The main Python libraries used in this project are:

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## 👩‍💻 Author

**Haneen Mohamed**

Data Science Student | Data Analysis Enthusiast

GitHub: [HaneenMohamed14](https://github.com/HaneenMohamed14)
