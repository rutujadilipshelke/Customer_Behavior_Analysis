# Customer Behavior Analytics Dashboard

## Overview

This project focuses on analyzing **customer behavior and purchasing patterns** using Python, PostgreSQL, and Power BI.

The project follows a complete data analytics workflow — from loading and cleaning raw data to performing exploratory data analysis, writing SQL queries, creating an interactive Power BI dashboard, and preparing a final analytical report.

### Project Workflow

**Raw Dataset → Python EDA → Data Cleaning → PostgreSQL Analysis → Power BI Dashboard → Report & Insights**

---

## Dataset

The project uses a customer behavior dataset containing information related to customer demographics, purchasing behavior, and transaction-related attributes.

The dataset was initially loaded and explored using **Python** to understand its structure, data types, missing values, duplicates, and overall data quality.

---

## Tools & Technologies

| Tool                      | Purpose                                 |
| ------------------------- | --------------------------------------- |
| **Python**                | Data loading, cleaning, and EDA         |
| **Pandas**                | Data manipulation and preprocessing     |
| **NumPy**                 | Numerical operations                    |
| **Matplotlib / Seaborn**  | Data visualization                      |
| **PostgreSQL**            | SQL-based data analysis                 |
| **pgAdmin**               | PostgreSQL database management          |
| **Power BI**              | Interactive dashboard and visualization |
| **Microsoft Excel / CSV** | Dataset handling                        |

---

## Project Steps

### 1. Data Loading

The dataset was loaded into Python using Pandas.

Initial checks were performed to understand:

* Number of rows and columns
* Column names
* Data types
* Missing values
* Duplicate records
* Basic statistical information

### 2. Exploratory Data Analysis (EDA)

EDA was performed to identify patterns and relationships in the data.

The analysis included:

* Distribution analysis
* Customer demographic analysis
* Purchasing behavior analysis
* Outlier detection
* Correlation analysis
* Visualization of important variables

### 3. Data Cleaning

The dataset was cleaned and prepared for further analysis.

Major cleaning activities included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing categorical values
* Handling inconsistent data
* Removing unnecessary columns where required

### 4. PostgreSQL Analysis

The cleaned dataset was imported into **PostgreSQL** for SQL-based analysis.

SQL queries were created to answer business-related questions such as:

* How many customers belong to different categories?
* What are the most common purchasing patterns?
* Which customer segments generate higher purchases?
* What are the key customer behavior trends?
* How do different customer attributes affect purchasing behavior?

### 5. Power BI Dashboard

The analyzed data was connected to **Power BI** to create an interactive dashboard.

The dashboard includes:

* Key Performance Indicators (KPIs)
* Customer segmentation
* Purchase analysis
* Demographic analysis
* Interactive charts and graphs
* Filters and slicers
* Business-focused visualizations

---

## Dashboard

The Power BI dashboard provides an interactive view of customer behavior and purchasing patterns.

Users can use filters and slicers to explore the data based on different customer attributes and identify important trends.

**Power BI File:** `customer_behavior_dashboard.pbix`

---

## Results & Insights

The analysis helped identify important patterns in customer behavior, purchasing activity, and customer segmentation.

Key outcomes include:

* Identification of major customer segments
* Analysis of purchasing patterns
* Understanding of customer demographics
* Identification of important behavioral trends
* SQL-based extraction of business insights
* Interactive visualization of findings through Power BI

The final report provides a detailed explanation of the analysis, findings, and conclusions.

---

## Project Structure

```text
customer-behavior-analysis/
│
├── dataset/
│   └── customer_behavior.csv
│
├── python/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_queries.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── report/
│   └── customer_behavior_report.pdf
│
└── README.md
```

---

## How to Run

### 1. Clone the Repository

```bash
git clone <repository-url>
cd customer-behavior-analysis
```

### 2. Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Run the Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Open the Python notebook and run the cells sequentially to perform data loading, EDA, and data cleaning.

### 4. Set Up PostgreSQL

1. Install PostgreSQL and pgAdmin.
2. Create a PostgreSQL database.
3. Create the required table.
4. Import the cleaned dataset.
5. Execute the SQL queries provided in the `sql` folder.

### 5. Open the Power BI Dashboard

Open:

```text
customer_behavior_dashboard.pbix
```

If required, update the data source connection and refresh the dashboard.

---

## Skills Demonstrated

* Python for Data Analysis
* Exploratory Data Analysis
* Data Cleaning & Preprocessing
* Pandas & NumPy
* Data Visualization
* SQL
* PostgreSQL
* Business Analysis
* Power BI
* Dashboard Development
* Data Storytelling

---

## Conclusion

This project demonstrates an end-to-end **data analytics workflow**, combining Python, SQL, PostgreSQL, and Power BI to transform raw customer data into meaningful business insights and an interactive dashboard.

