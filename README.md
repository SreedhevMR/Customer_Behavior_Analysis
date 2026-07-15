# Data Analytics Project

## Overview
This project demonstrates an end-to-end data analytics workflow, covering data collection, cleaning, exploration, database management, and interactive visualization. The objective is to transform raw data into meaningful insights using industry-standard analytics tools and techniques.

## Dataset
The project uses a structured dataset containing customer and transaction-related information.
The dataset is used to:
* Analyze customer behavior and purchasing patterns
* Perform exploratory data analysis (EDA)
* Clean and preprocess data
* Store processed data in PostgreSQL
* Build an interactive Power BI dashboard
* 
## Tools & Technologies
* **Python**
  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
* **Jupyter Notebook**
* **PostgreSQL**
* **SQL**
* **Power BI**

## Project Workflow
### 1. Data Loading
* Imported the dataset into Python using Pandas.
* Inspected data structure, data types, and missing values.
  
### 2. Exploratory Data Analysis (EDA)
* Generated descriptive statistics.
* Analyzed distributions and trends.
* Identified outliers and correlations.
* Created visualizations to understand the data.

### 3. Data Cleaning
* Handled missing values.
* Removed duplicate records.
* Corrected inconsistent data formats.
* Created new features where necessary.
* Prepared the dataset for analysis.

### 4. Database Integration
* Created a PostgreSQL database.
* Loaded the cleaned dataset into PostgreSQL.
* Verified successful data import.

### 5. SQL Analysis
Performed SQL queries to:
* Retrieve customer insights
* Analyze purchase behavior
* Aggregate sales metrics
* Filter and sort records
* Generate analytical summaries

### 6. Power BI Dashboard
Connected PostgreSQL data to Power BI and developed an interactive dashboard featuring:
* KPI Cards
* Sales Overview
* Customer Analysis
* Product Category Analysis
* Purchase Trends
* Interactive Filters and Slicers

## Dashboard
The dashboard provides a clear overview of business performance through interactive visualizations that help users:
* Monitor key metrics
* Analyze customer behavior
* Compare product performance
* Identify sales trends
* Support data-driven decision-making

## Results
This project demonstrates:
* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* SQL querying and database management
* Business intelligence reporting
* Interactive dashboard development
* End-to-end data analytics workflow

## Project Structure
```text
Data-Analytics-Project/
│
├── dataset/
│   └── data.csv
│
├── notebooks/
│   └── data_analysis.ipynb
│
├── sql/
│   └── queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

## How to Run
1. Clone this repository.
2. Install the required Python packages.

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run the notebook to perform data loading, cleaning, and EDA.
5. Import the cleaned dataset into PostgreSQL.
6. Execute the SQL queries.
7. Open the Power BI (.pbix) file and refresh the data connection to explore the dashboard.

## Key Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* SQL Querying
* PostgreSQL Database Management
* Power BI Dashboard Development
* Business Analytics
* Data-Driven Decision Making
