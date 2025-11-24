# Customer_behavior_Analysis
This project analyzes customer shopping behavior using an end-to-end data analytics workflow. It covers data loading, exploratory data analysis (EDA), data cleaning, SQL queries, database management, dashboard creation in Power BI, and a final presentation built with Gamma. The goal is to uncover actionable insights about purchase patterns and customer segments.
📂 Dataset
Format: Excel / CSV
Contains customer attributes, transactions, and purchase behavior
Loaded and explored using Python (Jupyter Notebook)
Cleaned, transformed, and stored in a relational database
🛠 Tools & Technologies
| Category        | Tools Used                                 |
| --------------- | ------------------------------------------ |
| Programming     | Python (Pandas, NumPy, Matplotlib/Seaborn) |
| Database        | PostgreSQL / MySQL / SQL Server            |
| Visualization   | Power BI                                   |
| Documentation   | Jupyter Notebook                           |
| Presentation    | Gamma (AI Presentation Builder)            |
| Version Control | Git & GitHub                               |

📁 Project Steps

1️⃣ Data Loading (Python)
Imported dataset into Jupyter Notebook
Verified schema, data types, and missing values
Saved cleaned output for database ingestion

2️⃣ Exploratory Data Analysis (EDA)
Summary statistics
Distribution plots, correlations
Customer segmentation patterns
Outlier detection and handling

3️⃣ Data Cleaning & Transformation
Handled missing or inconsistent values
Removed duplicates
Feature engineering (optional)
Exported cleaned data for SQL database

4️⃣ SQL Database Setup (PostgreSQL / MySQL / SQL Server)
Created database and tables
Loaded cleaned dataset into the database
Wrote analytical SQL queries:
Customer segmentation
Purchase trends
Revenue insights
High-value vs low-value customers

5️⃣ Power BI Dashboard
Connected to SQL database
Built interactive visualizations:
Revenue trends
Demographic insights
Product-wise performance
Customer behavior metrics
Applied filters, drill-downs, and slicers

6️⃣ Final Report & Presentation
Summarized findings in a business-focused report
Created a Gamma AI presentation covering:
Problem
Approach
Insights
Dashboard highlights
Recommendations
## 📊 Dashboard Preview
### sample dashboard
![Customer Behavior Dashboard](screenshots/Screenshot%202025-11-21%20163750.png)
![Customer Behavior Dashboard](screenshots/customer%20behavior%202025-11-24.png)
## 🎯 Results & Key Insights

* Identified top customer segments
* Found drivers of repeat purchases
* Highlighted revenue patterns and seasonal trends
* Built a functional BI dashboard for decision-makers

(You can update this with real insights later.)

---

## 🚀 How to Run This Project

### *Prerequisites*

* Python 3.8+
* PostgreSQL/MySQL/SQL Server installed
* Power BI Desktop
* Git installed

### *Steps to Run*

1. Clone the repository:

   bash
   git clone https://github.com/nagvanshi781-pixel/Customer_behavior.git
   cd Customer_behavior
   
2. Install Python requirements:

   bash
   pip install -r requirements.txt
   
3. Open Jupyter Notebook and run EDA/cleaning scripts
4. Import cleaned data into your SQL database
5. Run provided SQL queries
6. Open the Power BI file (.pbix) and refresh the connection
7. View the dashboard and presentation

