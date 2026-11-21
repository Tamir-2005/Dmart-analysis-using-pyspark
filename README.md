# 🛒 DMart Sales Analysis Using PySpark

## 📌 Project Overview

The **DMart Sales Analysis Using PySpark** project focuses on building a data pipeline to integrate, clean, transform, and analyze sales data from three different datasets: Products, Sales Transactions, and Customer Details.

Using Python, SQL, and PySpark, this project performs data preprocessing, data integration, and analytical queries to generate meaningful business insights about sales performance, customer purchasing behavior, product categories, profitability, and regional sales.

## 🎯 Problem Statement

The objective of this project is to develop a scalable data pipeline using PySpark to integrate sales information from multiple sources and perform data analysis.

The project involves loading CSV datasets into PySpark DataFrames, cleaning and transforming the data, joining datasets using relevant keys, and answering 10 business-related analytical questions.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Big Data Processing:** Apache PySpark
- **Query Language:** SQL
- **Data Format:** CSV
- **Data Processing:** PySpark DataFrames
- **Development Environment:** Jupyter Notebook / VS Code

## 📂 Dataset Description

This project uses three datasets:

| Dataset | Description |
|---|---|
| `products.csv` | Contains product information |
| `sales.csv` | Contains sales transaction details |
| `customer.csv` | Contains customer information |

The datasets are integrated using the following keys:

- Product ID
- Customer ID

## ⚙️ Project Workflow

### 1. Establish PySpark Connection
- Set up the PySpark environment.
- Initialize the Spark Session.
- Establish the connection to read CSV files.

### 2. Load Data into PySpark DataFrames
- Load Products data.
- Load Sales data.
- Load Customer data.
- Display and inspect the DataFrames.

### 3. Data Cleaning and Transformation
- Rename columns for consistency.
- Handle missing and null values.
- Correct data types.
- Perform necessary data transformations.
- Prepare datasets for integration.

### 4. Data Integration
- Join Products and Sales using Product ID.
- Join Customer and Sales using Customer ID.
- Create an integrated dataset for analysis.

### 5. Data Analysis and Querying
Use PySpark DataFrame operations and SQL queries to answer business-related questions.

## 📊 Business Analysis – 10 Analytical Questions

The project answers the following questions:

1. **Total Sales by Product Category:** What is the total sales amount for each product category?

2. **Highest Purchasing Customer:** Which customer has made the highest number of purchases?

3. **Average Discount:** What is the average discount given on sales across all products?

4. **Unique Products by Region:** How many unique products were sold in each region?

5. **Total Profit by State:** What is the total profit generated in each state?

6. **Highest-Selling Sub-Category:** Which product sub-category has the highest sales?

7. **Average Customer Age:** What is the average age of customers in each segment?

8. **Shipping Mode Analysis:** How many orders were shipped using each shipping mode?

9. **Quantity Sold by City:** What is the total quantity of products sold in each city?

10. **Profit Margin by Customer Segment:** Which customer segment has the highest profit margin?

## 🔄 Data Pipeline Architecture

```text
       Products.csv
            |
            |
        Sales.csv
            |
            |
       Customer.csv
            |
            v
      PySpark Session
            |
            v
       Data Loading
            |
            v
     Data Cleaning
            |
            v
    Data Transformation
            |
            v
      Data Integration
       (Data Joining)
            |
            v
     Integrated Dataset
            |
            v
    PySpark SQL Analysis
            |
            v
     Business Insights
```

## 💻 Installation and Setup

### Prerequisites

Make sure the following are installed:

- Python 3.x
- Java (compatible with your PySpark version)
- Apache Spark / PySpark
- Jupyter Notebook or VS Code

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the Project Folder

```bash
cd Dmart-analysis-using-pyspark
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment on Windows:

```bash
venv\Scripts\activate
```

### Step 4: Install Dependencies

```bash
pip install pyspark pandas
```

### Step 5: Run the Project

If your project is a Python file:

```bash
python main.py
```

If your project is a Jupyter Notebook, open it using:

```bash
jupyter notebook
```

Run the notebook cells sequentially.

**Note:** Update the execution command and file paths according to your actual repository structure.

## 📈 Expected Outcomes

- Successful integration of three datasets using PySpark.
- Improved data quality through cleaning and transformation.
- Analysis of product-wise and regional sales performance.
- Identification of high-value customers.
- Evaluation of discounts and profitability.
- Understanding of customer segments and purchasing behavior.
- Business insights through analytical queries.

## 🎓 Skills Demonstrated

- Python Programming
- Apache PySpark
- PySpark DataFrame Operations
- Data Cleaning and Preprocessing
- Data Transformation
- Data Integration
- Inner and Other SQL Joins
- PySpark SQL
- ETL Pipeline Development
- Business Data Analysis
- Problem Solving

## 🚀 Future Enhancements

- Automate the ETL pipeline using Apache Airflow.
- Store processed data in a SQL database.
- Integrate AWS S3 for cloud-based data storage.
- Use AWS Glue for managed ETL processing.
- Build interactive dashboards using Power BI or Tableau.
- Implement scheduled data processing.

## 👨‍💻 Author

**Tamir N**

Aspiring Data Engineer | Python | SQL | PySpark | ETL | AWS

## 📜 License

This project is developed for educational and learning purposes.

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback!
