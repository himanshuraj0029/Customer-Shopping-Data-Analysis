# 🛍️ Customer Shopping Data Analytics

## 📌 Project Overview

Customer Shopping Data Analytics is a data analysis project focused on understanding customer purchasing behavior, sales performance, product preferences, and shopping trends.

The project uses a dataset containing **10,000 records and 26 columns**. Python, Pandas, and SQL are used to explore and analyze the data and extract meaningful business insights.

The goal is to transform raw shopping data into actionable insights that can help businesses understand their customers and make better data-driven decisions.

## 🎯 Project Objectives

- Analyze overall sales performance and customer purchasing patterns.
- Identify top-performing product categories and brands.
- Compare online and offline shopping behavior.
- Analyze sales trends across locations and time periods.
- Understand customer preferences and purchasing frequency.
- Practice data cleaning, exploratory data analysis (EDA), and SQL.

## 🛠️ Tools and Technologies

- **Python** – Data analysis and programming
- **Pandas** – Data cleaning, manipulation, and aggregation
- **NumPy** – Numerical operations
- **MySQL** – Data storage and SQL-based analysis
- **SQLAlchemy** – Connecting Python to MySQL
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization


## 📂 Dataset Information

The dataset contains 10,000 rows and 26 columns.

Important columns include:

| Column | Description |
|---|---|
| Transaction ID | Unique transaction identifier |
| Customer ID | Customer identifier |
| Purchase Date | Date of purchase |
| Age | Customer age |
| Gender | Customer gender |
| Location | Customer location |
| Online/Offline | Shopping channel |
| Category | Product category |
| Item Purchased | Purchased product |
| Brand | Product brand |
| Quantity | Number of items purchased |
| Purchase Amount | Purchase value |
| Discount (%) | Discount applied |
| Payment Method | Payment method used |
| Review Rating | Customer rating |
| Return Status | Indicates return information |
| Frequency of Purchases | Customer purchasing frequency |

## 🔍 Project Workflow

### 1. Data Loading
- Imported the shopping dataset into Python using Pandas.
- Inspected the dataset's structure and dimensions.

### 2. Data Cleaning and Preparation
- Checked for missing values and duplicate records.
- Reviewed and corrected data types where required.
- Prepared the data for analysis.

### 3. Exploratory Data Analysis (EDA)
- Calculated total purchase amount and average purchase value.
- Analyzed sales by category, brand, gender, and location.
- Compared online and offline shopping channels.
- Examined monthly and yearly sales trends.

### 4. SQL Analysis
- Loaded the cleaned CSV data into MySQL.
- Practiced SQL queries for filtering, grouping, aggregation, and business analysis.
- Used SQL alongside Pandas to strengthen data analysis skills.

### 5. Data Visualization
- Used charts to understand sales performance and purchasing patterns.
- Prepared the analysis for a future Power BI dashboard.

## 📊 Key Analysis Results

The following results were obtained during the Pandas analysis.

| Metric | Result |
|---|---:|
| Total records | 10,000 |
| Total purchase amount | 64,676,945 |
| Average purchase amount per transaction | 6,467.69 |
| Total quantity | 14,259 |
| 2023 total purchase amount | 31,522,993 |
| 2024 total purchase amount | 33,153,952 |

### Category-wise Sales

| Category | Total Purchase Amount |
|---|---:|
| Footwear | 37,462,463 |
| Clothing | 21,809,421 |
| Accessories | 5,405,061 |

### Online vs. Offline Shopping

| Channel | Transactions | Total Purchase Amount |
|---|---:|---:|
| Online | 7,417 | 47,817,573 |
| Offline | 2,583 | 16,859,372 |

### Top Brands by Purchase Amount

1. Nike
2. Puma
3. Adidas
4. HRX
5. FabIndia

## 💡 Business Insights

- Footwear contributed the largest purchase amount among the three analyzed categories.
- Online shopping generated a higher total purchase amount than offline shopping.
- The total purchase amount was higher in 2024 than in 2023.
- Nike, Puma, and Adidas were among the leading brands by purchase amount.
- Location-wise analysis helps identify areas with higher customer spending.

*These observations are based on the dataset analyzed in this project.*

## 🚀 How to Run the Project

### Prerequisites

Install Python and MySQL. Jupyter Notebook is recommended for running the analysis.

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd YOUR_REPOSITORY_NAME
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql jupyter
```

### Step 3: Load the Dataset

```python
import pandas as pd

df = pd.read_csv("customer_shoppings.csv")

print(df.head())
print(df.shape)
print(df.info())
```

Replace `customer_shoppings.csv` with the actual dataset filename in your repository.

### Step 4: Run the Analysis

Open the Jupyter Notebook containing the project analysis and run the cells in order.

### Step 5: Connect to MySQL

Configure your MySQL connection using SQLAlchemy. Keep database passwords private and use your own database credentials.

## 📈 Future Improvements

- Build an interactive Power BI dashboard.
- Add KPIs, slicers, and filters for customer and sales analysis.
- Develop deeper customer segmentation.
- Analyze return patterns and customer ratings.
- Create a more detailed business report with actionable recommendations.

## 🎓 Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Pandas and NumPy
- SQL and MySQL
- Python–MySQL integration
- Business insights and data interpretation
- Data visualization

## 👨‍💻 Author

**Himanshu Raj**

Aspiring Data Analyst

Skills: Python | Pandas | NumPy | SQL | MySQL | Matplotlib | Seaborn

## ⭐ Acknowledgement

This project was developed as part of my Data Analytics learning journey to strengthen my practical skills in data analysis, SQL, and business insight generation.

If you find this project useful, feel free to explore the repository and share your feedback.
