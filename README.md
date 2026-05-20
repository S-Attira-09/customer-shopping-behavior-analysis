
# 🛍️ Customer Shopping Behavior Analysis

> An end-to-end data analytics project analyzing 3,900 customer transactions using Python, SQL, and Power BI to uncover insights on customer behavior, revenue patterns, and business opportunities.



## 📌 Overview

This project analyzes retail customer data to identify key business insights and support data-driven decision-making.

It covers the full analytics pipeline:

* Data loading and cleaning in Python
* Exploratory Data Analysis (EDA)
* SQL-based business analysis
* Interactive dashboard creation in Power BI

**Goal:** Understand customer behavior, spending patterns, and opportunities for growth.



## 📊 Dataset

* **Total Records:** 3,900
* **Features:** 18 columns
* **Missing Values:** 37 (handled during preprocessing)

**Key Data Includes:**

* Customer demographics (Age, Gender, Location)
* Purchase details (Product, Category, Amount)
* Behavior (Discount usage, Reviews, Frequency, Subscription)



## 🛠️ Tools

* **Python (Pandas)** → Data cleaning & EDA
* **PostgreSQL / MySQL / SQL Server** → Data querying
* **SQLAlchemy** → Database connection
* **Power BI** → Dashboard visualization



## 🔄 Steps

1. **Data Loading**

   * Imported dataset using pandas

2. **Data Cleaning**

   * Handled missing values (median imputation)
   * Standardized column names
   * Removed redundant fields

3. **Feature Engineering**

   * Created age groups
   * Derived purchase frequency

4. **SQL Analysis**

   * Wrote 10 business queries to extract insights

5. **Visualization**

   * Built an interactive Power BI dashboard


## 📊 Dashboard

The Power BI dashboard provides an interactive view of:

* Revenue by gender and age
* Customer segmentation
* Product performance
* Subscription trends
* Discount behavior

**Key Metrics:**

* Total Customers: 3,900
* Avg Purchase: $59.76
* Avg Rating: 3.75
* Subscription Rate: 27%



## 📈 Results

* Male customers generate the majority of revenue
* 80% of customers are repeat/loyal buyers
* Discount usage is high (~50% for some products)
* Subscription adoption is low (27%)
* Young adults are the top spending group
* Product ratings are below 4.0 → improvement opportunity



## ▶️ How to Run

### 1. Clone Repository

```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```

### 2. Install Dependencies

```bash
pip install pandas sqlalchemy psycopg2
```

### 3. Run Python Notebook

```bash
jupyter notebook notebooks/eda_cleaning.ipynb
```

### 4. Setup Database

```bash
createdb shopping_analysis
```

(Update database credentials in the notebook)

### 5. Execute SQL Queries

```bash
psql -d shopping_analysis -f sql/queries.sql
```

### 6. Open Dashboard

Open the `.pbix` file in Power BI Desktop


