# 📊 Retail Sales Analytics & Customer Churn Prediction



<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20Application-FF4B4B?logo=streamlit)

</p>

---

# 📌 Project Overview

This project presents an end-to-end Retail Sales Analytics solution that combines **Python**, **Machine Learning**, **Web Scraping**, and **Microsoft Power BI** to transform raw retail transaction data into meaningful business insights.

The workflow starts with data preprocessing and feature engineering, followed by exploratory data analysis (EDA), customer churn prediction, web scraping for additional product information, and interactive dashboard development using Power BI.

---

# 🎯 Project Objectives

- Clean and preprocess retail sales data
- Merge and transform multiple datasets
- Perform Exploratory Data Analysis (EDA)
- Generate automated business insights
- Engineer features for machine learning
- Predict customer churn using Logistic Regression
- Improve model performance using SMOTE and Hyperparameter Tuning
- Collect product information using Web Scraping
- Build an interactive Power BI dashboard

---

# 🛠 Technologies Used

## Programming Languages

- Python

## Python Libraries

- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- BeautifulSoup
- Requests
- Streamlit

## Business Intelligence

- Microsoft Power BI
- Power Query
- DAX

---

# 📂 Repository Structure

```text
Retail-Sales-Analytics/
│
├── Dashboard/
│   └── Retail_Sales_Analytics.pbix
│
├── Data/
│   ├── Retail_Sales.xlsx
│   └── Retail_Sales_Cleaned.csv
│
├── Notebook/
│   └── Retail_Analytics_Project.ipynb
│
├── Streamlit/
│   └── app.py
│
├── Web_Scraping/
│   └── scraper.py
│
├── Images/
│   ├── Dashboard.png
│   ├── Overview.png
│   ├── Customer_Product.png
│   ├── Store_Performance.png
│   ├── Churn_Model.png
│   └── WebScraping.png
│
├── requirements.txt
├── LICENSE
├── .gitignore
└── README.md
```

---

# 🔄 Project Workflow

```text
Raw Retail Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Data Transformation
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Business Insights
        │
        ▼
Customer Churn Prediction
        │
        ▼
Web Scraping
        │
        ▼
Power BI Dashboard
```

---

# 🧹 Data Preprocessing

The retail dataset was cleaned and transformed before analysis.

Main preprocessing tasks include:

- Handling missing values
- Removing duplicate records
- Data type conversion
- Date transformation
- Dataset merging
- Feature engineering
- Data validation

---

# 📊 Exploratory Data Analysis (EDA)

EDA was performed to identify trends, patterns, and business opportunities.

Analysis includes:

- Sales Trend Analysis
- Product Performance
- Customer Analysis
- Store Performance
- Category Analysis
- Profit Analysis
- Correlation Analysis
- Business KPI Evaluation

---

# 📈 Feature Engineering

Additional features were created to improve business analysis and machine learning performance.

Examples include:

- Sales Metrics
- Customer Metrics
- Date-Based Features
- RFM Features
  - Recency
  - Frequency
  - Monetary

---

# 🤖 Customer Churn Prediction

A machine learning model was developed to predict customer churn.

The workflow includes:

- Data Preparation
- Feature Selection
- Train/Test Split
- Logistic Regression
- Model Evaluation
- Confusion Matrix
- ROC Curve
- Cross Validation
- Grid Search
- Threshold Tuning
- SMOTE Oversampling
- Bootstrap Evaluation

---

# 🌐 Web Scraping

A web scraping module was implemented using **BeautifulSoup** and **Requests** to collect product information from online sources.

The scraped data is cleaned and analyzed to complement the retail sales dataset.

Technologies used:

- BeautifulSoup
- Requests
- Pandas

---

# 💻 Streamlit Application

A Streamlit web application was developed to provide an interactive interface for the Customer Churn Prediction model.

Users can enter customer information and receive real-time churn predictions.

---

# 📊 Power BI Dashboard

The cleaned dataset was imported into Microsoft Power BI to develop an interactive dashboard for business analysis.

Dashboard features include:

- Sales Performance
- Customer Analysis
- Product Performance
- Store Performance
- Interactive Filters
- KPI Cards
- Drill-Down Analysis
- DAX Measures
- Power Query Transformations

---

# 📸 Dashboard Preview

## 📈 Overview Dashboard

![Overview](Overview.png)

---

## 👥 Customer & Product Dashboard

![Customer](Customer_Product.png)

---

## 🏪 Store Performance Dashboard

![Store](Store_Performance.png)

---

# 📊 Key Performance Indicators

- Total Sales
- Total Profit
- Total Orders
- Profit Margin
- Average Order Value
- Customer Count
- Product Performance
- Store Performance

---

# 💼 Business Questions Answered

- Which stores generate the highest sales?
- Which products generate the highest profit?
- Which product categories perform best?
- How do customers behave across different segments?
- Which customers are likely to churn?
- What factors influence store profitability?
- How can business performance be improved?

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/YourUsername/Retail-Sales-Analytics.git
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run the Notebook

Open:

```text
Notebook/Retail_Analytics_Project.ipynb
```

Run all notebook cells.

## Launch Streamlit

```bash
streamlit run app.py
```

## Open Power BI Dashboard

Open the following file using Microsoft Power BI Desktop:

```text
Dashboard/Retail_Sales_Analytics.pbix
```

---

# 📈 Future Improvements

- Sales Forecasting
- Customer Segmentation
- SQL Database Integration
- Cloud Deployment
- Real-Time Dashboard

---

# 👨‍💻 Author

**Ahmed [Your Last Name]**


## ⭐ If you found this project useful, consider giving it a star!
