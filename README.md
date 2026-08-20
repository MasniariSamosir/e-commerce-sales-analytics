# 📊 E-Commerce Sales Analytics

An end-to-end Data Analytics project using an Indonesia e-commerce transaction dataset to evaluate data quality, analyze business performance, and transform transactional data into actionable insights through Python analysis and Tableau visualization.

---

## 🎯 Problem Statement

Raw e-commerce transaction data did not provide a clear and structured view of sales performance, product performance, payment, and returns.

This project addresses the problem by applying data quality validation, exploratory analysis, and business analysis using Python, then transforming the analysis results into an interactive Tableau dashboard to support performance monitoring and data-driven decision making.

---

## 🔄 Project Workflow

```text
Public E-Commerce Dataset
        ↓
Data Understanding
        ↓
Data Quality & Validation
        ↓
Missing Value & Date Validation
        ↓
Exploratory Data Analysis (EDA)
        ↓
Outlier Investigation
        ↓
Final Dataset (df_final)
        ↓
Business Performance Analysis
        ↓
KPI & Business Metrics
        ↓
Business Insights & Recommendations
        ↓
Tableau Data Visualization
        ↓
Interactive E-Commerce Sales Dashboard

🐍 Python Data Analysis

Python was used as the main tool for data understanding, validation, exploratory analysis, and business analysis.

Python Workflow

Load Dataset
     ↓
Data Understanding
     ↓
Data Quality Check
     ↓
Missing Value Analysis
     ↓
Duplicate & Identifier Validation
     ↓
Date/Time Validation
     ↓
Exploratory Data Analysis
     ↓
Outlier Investigation
     ↓
Dataset Finalization (df_final)
     ↓
Business Performance Analysis
     ↓
Business Insights & Recommendations

Data Understanding & Quality

The dataset was examined to understand its structure, variables, transaction characteristics, and data quality.

Key activities include:

Understanding dataset structure and variables
Checking missing values
Checking duplicate rows
Validating transaction identifiers and Order Id
Validating Waktu Pesanan Dibuat
Checking data types and data integrity
Investigating missing values based on business context
Investigating outliers using the IQR method
Finalizing the dataset into df_final

Missing values were evaluated based on business context rather than automatically removed.

🔎 Exploratory Data Analysis (EDA)

EDA was performed on the finalized dataset to understand the characteristics and patterns within the transaction data.

EDA Areas
Descriptive statistics
Mean and median analysis
Quartiles
Minimum and maximum values
Standard deviation
Distribution analysis
Skewness analysis
Zero and negative value checks
Outlier investigation
Correlation analysis
Categorical distribution analysis

Outliers were investigated based on transaction context rather than automatically treated as errors.

📈 Business Analysis

The analysis focuses on several key areas of e-commerce business performance.

Key Performance Indicators
Total Transactions
Total Quantity
Total Payment
Total Discount
Total Returned Quantity
Total Weight
Return Rate

Sales & Payment Analysis
Monthly Sales Trend
Average vs Median Payment
Transaction value distribution
Quantity and payment analysis
Relationship between numerical variables and payment

Product & Category Analysis
Top 10 Products by Sales
Category Performance
Quantity by Category
Payment by Category

Return & Operational Analysis
Returned Quantity
Return Rate
Transactions with Returns
Return Performance by Category

Shipping Analysis
Shipping Method Performance
Payment by Shipping Method

📊 Key Business Metrics

The final analysis produced the following key metrics:
Metric	Value
Total Transactions	20,848
Total Quantity	53,388
Total Payment	Rp1,056,651,631
Total Discount	Rp8,447,596
Total Returned Quantity	370
Return Rate	0.69%

💡 Key Business Insights

Several business insights were identified from the analysis:

Seal / Baut / Roof generated the highest total payment, approximately Rp275.99 million.
Nampan / Tray recorded the highest quantity, with 9,942 units.
Transaction payment values show a positively skewed distribution, indicating the presence of higher-value transactions.
total_weight_gr has the strongest Spearman relationship with Total Pembayaran, with a correlation of approximately 0.524.
A total of 370 units were returned from 53,388 units, resulting in an overall return rate of approximately 0.69%.
Categories with high return rates should be evaluated together with transaction and quantity volume to avoid misleading conclusions from small samples.

📊 Tableau Dashboard

The results from the Python analysis were transformed into an interactive Tableau dashboard for business monitoring and data visualization.

Dashboard Components
KPI Cards
Monthly Sales Trend
Average vs Median Payment
Top 10 Category Performance
Top 10 Products by Sales
Shipping Method Performance
Order Date Filter
Dashboard Navigation Sidebar
Dashboard Preview

🧭 Dashboard Structure

The dashboard was designed with a structured navigation layout:
Overview
   │
   ├── Sales
   │
   ├── Product
   │
   ├── Shipping
   │
   └── Payment

The dashboard combines KPI cards and business visualizations to provide a concise overview of e-commerce performance.

🛠️ Tools & Technologies
Tool	Purpose
Python	Data analysis and preparation
Pandas	Data manipulation and analysis
Jupyter Notebook	Exploratory and business analysis
Tableau	Data visualization and dashboard
GitHub	Project documentation and version control

📚 Dataset

The project uses a publicly available Indonesia e-commerce transaction dataset.

The dataset was analyzed and validated before being used for exploratory analysis, business analysis, and Tableau visualization.

The final dataset was accepted for analysis with data quality notes. Missing values were retained when they represented valid or explainable conditions in the original dataset.

📌 Business Value

This project demonstrates how raw transactional data can be transformed into structured business information through:

Raw Data
   ↓
Data Quality
   ↓
Data Analysis
   ↓
Business Insights
   ↓
Data Visualization
   ↓
Data-Driven Decision Making

The resulting dashboard can support:

Sales performance monitoring
Identification of high-performing products and categories
Monthly sales evaluation
Payment performance analysis
Return monitoring
Operational performance evaluation
Data-driven business decision making


👩‍💻 Author
Masniari Samosir, S.Kom., M.Kom.
Master of Informatics Engineering – Data Science

