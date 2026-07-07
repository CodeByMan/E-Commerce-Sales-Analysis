<div align="center">

<img src="image%20files/ECommerce_Sales_Analysis_Diagram3.png" alt="E-Commerce Sales Analysis Workflow" width="900"/>

<p>
<b>Data analysis project using Python, Pandas, Matplotlib, and Seaborn to explore e-commerce sales, profit, discounts, shipping modes, product categories, customer segments, and regional performance.</b>
</p>

<p>
<img src="https://img.shields.io/badge/Python-Data%20Analysis-blue">
<img src="https://img.shields.io/badge/Pandas-Data%20Cleaning-orange">
<img src="https://img.shields.io/badge/Matplotlib-Visualization-green">
<img src="https://img.shields.io/badge/Seaborn-Statistical%20Charts-purple">
<img src="https://img.shields.io/badge/Jupyter-Notebook-F37626">
<img src="https://img.shields.io/badge/Dataset-Superstore-red">
</p>

</div>

---


## 📌 Project Overview

This project analyzes an e-commerce sales dataset to uncover business insights related to sales performance, profitability, shipping modes, customer segments, product categories, regional trends, and discount impact.

The analysis is performed in a Jupyter Notebook using Python data analysis libraries. The repository also includes a PDF report, source dataset, and project visuals for better presentation.

---

## 🎯 Objectives

- Clean and prepare e-commerce sales data
- Analyze sales and profit trends
- Identify top-performing categories and sub-categories
- Study customer segment behavior
- Compare shipping mode usage
- Analyze regional and state-level performance
- Understand how discounts affect profit
- Present findings using visual charts and report files

---

## 🖼️ Project Infographic

<p align="center">
<img src="image%20files/E_Commerce_Sales_Analysis_Infographic.png" alt="E-Commerce Sales Analysis Infographic" width="900"/>
</p>

---

## 🔄 Analysis Process

```text
Superstore Dataset
        │
        ▼
Data Loading
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ├── Shipping Mode Analysis
        ├── Segment Analysis
        ├── Category Analysis
        ├── Regional Analysis
        ├── Sales Analysis
        └── Profit Analysis
        │
        ▼
Visual Insights
        │
        ▼
PDF Report / Notebook Output
```

---

## 📁 Project Structure

```text
E-Commerce-Sales-Analysis/
│
├── dataset/
│   └── Superstore Dataset.csv
│
├── image files/
│   ├── ECommerce_Sales_Analysis_Diagram3.png
│   └── E_Commerce_Sales_Analysis_Infographic.png
│
├── Project-notebooks/
│   ├── E-Commerce Sales Analysis.ipynb
│   └── diagram.ipynb
│
├── Project PDF file/
│   └── E-Commerce Sales Analysis.pdf
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## 📊 Dataset Description

The dataset contains **9,994 e-commerce order records** with customer, product, shipping, sales, discount, and profit details.

### Dataset File

```text
dataset/Superstore Dataset.csv
```

### Main Columns

| Column | Description |
|---|---|
| `Order ID` | Unique order identifier |
| `Order Date` | Date when the order was placed |
| `Ship Date` | Date when the order was shipped |
| `Ship Mode` | Shipping method used |
| `Customer ID` | Unique customer identifier |
| `Customer Name` | Customer name |
| `Segment` | Customer segment |
| `Country` | Customer country |
| `City` | Customer city |
| `State` | Customer state |
| `Postal Code` | Postal code |
| `Region` | Sales region |
| `Product ID` | Unique product identifier |
| `Category` | Product category |
| `Sub-Category` | Product sub-category |
| `Product Name` | Product name |
| `Sales` | Sales amount |
| `Quantity` | Number of units sold |
| `Discount` | Discount applied |
| `Profit` | Profit earned |

---

## 📈 Key Analysis Areas

### Shipping Mode Analysis

The project studies which shipping modes are used most frequently and how they contribute to sales.

### Customer Segment Analysis

The analysis compares performance across segments such as:

- Consumer
- Corporate
- Home Office

### Category and Sub-Category Analysis

The project explores sales and profit contribution from categories such as:

- Furniture
- Office Supplies
- Technology

### Regional Analysis

The notebook compares performance across regions and states to identify stronger and weaker markets.

### Discount and Profit Analysis

The project reviews how discounting affects profitability and highlights areas where high discounts may reduce profit.

---

## 📒 Notebook

Main analysis notebook:

```text
Project-notebooks/E-Commerce Sales Analysis.ipynb
```

The notebook includes:

- Dataset loading
- Missing value checks
- Data cleaning
- Exploratory data analysis
- Visualizations
- Business insights

---

## 📄 Project Report

A PDF report is included:

```text
Project PDF file/E-Commerce Sales Analysis.pdf
```

This report can be used for presentation or assignment submission.

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/CodeByMan/E-Commerce-Sales-Analysis.git
cd E-Commerce-Sales-Analysis
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Activate it on macOS/Linux:

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Open and run:

```text
Project-notebooks/E-Commerce Sales Analysis.ipynb
```

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas | Data cleaning and analysis |
| NumPy | Numeric processing |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts |
| Jupyter Notebook | Interactive analysis |
| CSV | Dataset storage |
| PDF | Final report/presentation |

---

## 📌 Key Learning Outcomes

- Data cleaning with Pandas
- Exploratory Data Analysis
- Sales and profit analysis
- Customer segmentation analysis
- Product category analysis
- Regional performance analysis
- Business insight generation
- Visual storytelling using charts

---

## 👤 Author

**Muhammad Ali Nawaz**  
Data Analyst

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">
<b>⭐ If you found this project useful, consider giving it a star!</b>
</p>
