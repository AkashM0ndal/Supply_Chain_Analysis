# 📦 Supply Chain Performance Analysis & Late Delivery Prediction

> An end-to-end Data Analytics and Machine Learning project that analyzes supply chain operations, uncovers business bottlenecks, measures operational performance, and predicts late delivery risks using historical transaction data.
---

<img width="1536" height="1024" alt="Supply Chain Analysis project Photo" src="https://github.com/user-attachments/assets/b44a6eb7-a101-4531-8034-93cf5aebc567" />




hgjhgkjhjkhjkh

## 📖 Project Overview

Efficient supply chain management is essential for reducing operational costs, improving customer satisfaction, and increasing profitability. This project performs comprehensive analysis on a real-world supply chain dataset to identify operational inefficiencies, evaluate business performance through meaningful KPIs, and build a machine learning model capable of predicting delivery delays before shipment.

The project follows the complete Data Analytics lifecycle—from data cleaning and exploratory analysis to business insight generation and predictive modeling.


---

## 🎯 Business Objectives

This project aims to answer key business questions such as:

- Which operational factors contribute most to delivery delays?
- How do delayed deliveries impact business profitability?
- Which customer segments, shipping modes, and regions experience the highest delay rates?
- What seasonal or time-based patterns exist in delivery performance?
- Can late deliveries be predicted using historical operational data?

---

## 📂 Dataset

The dataset contains historical supply chain transaction records, including:

- Orders
- Customers
- Products
- Shipping Information
- Departments
- Regions
- Delivery Status
- Order Status
- Profit
- Sales
- Scheduled Delivery Dates
- Actual Delivery Dates

These attributes enable both business analytics and predictive modeling.

---

# 🛠️ Tech Stack

| Category | Tools & Libraries |
|-----------|-------------------|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Imbalanced Data Handling | SMOTE (Imbalanced-learn) |
| Development Environment | Jupyter Notebook |

---

# 📊 Project Workflow

```text
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Feature Engineering
      │
      ▼
Business KPI Analysis
      │
      ▼
Root Cause Analysis
      │
      ▼
Time-Based Trend Analysis
      │
      ▼
Machine Learning Model
      │
      ▼
Late Delivery Prediction
```

---

# 🧹 Data Cleaning

The dataset was prepared through several preprocessing steps:

- Removed duplicate records
- Handled missing values
- Removed unnecessary columns
- Converted date columns into datetime format
- Standardized data types
- Filtered invalid records
- Created additional business features for analysis

---

# ⚙️ Feature Engineering

To enhance business analysis and model performance, several new features were created:

- Order Processing Time
- Delivery Delay (Actual vs Scheduled)
- Late Delivery Indicator
- Order Month
- Order Day
- Order Hour
- Profitability Flag
- Delay Status

These engineered features helped uncover operational patterns and improved predictive accuracy.

---

# 📈 Exploratory Data Analysis (EDA)

The exploratory analysis focused on understanding operational performance across multiple business dimensions.

### Analysis Performed

- Dataset overview
- Missing value analysis
- Duplicate analysis
- Numerical feature distribution
- Categorical feature distribution
- Correlation analysis
- Profitability analysis
- Delivery delay distribution

---

# 📌 Business KPIs

The project calculates several business-critical Key Performance Indicators (KPIs), including:

- Total Orders
- Total Revenue
- Total Profit
- Average Profit per Order
- Total Delayed Orders
- Delay Percentage
- Average Delivery Delay
- Average Order Processing Time
- Profit from Delayed Deliveries
- Profit from On-Time Deliveries

These KPIs provide a high-level overview of supply chain performance.

---

# 💰 Profitability Analysis

This section investigates how delivery performance influences business profitability.

Analysis includes:

- Profit distribution
- Profit by delivery delay
- Average profit by delay duration
- Order volume by delay days
- Profit comparison between delayed and on-time deliveries

---

# 🚚 Delivery Performance Analysis

The project analyzes delivery performance across multiple operational dimensions.

### Delay Analysis By

- Shipping Mode
- Customer Segment
- Department
- Order Type
- Region
- Order Status

This helps identify operational bottlenecks and inefficiencies.

---

# 🔍 Root Cause Analysis

A detailed root cause analysis was performed to identify the primary drivers of late deliveries.

The analysis investigates the impact of:

- Shipping Mode
- Customer Segment
- Department
- Region
- Order Status
- Order Type

These insights help identify areas requiring operational improvements.

---

# 📅 Time-Based Trend Analysis

Delivery performance was analyzed over different time dimensions to identify seasonal and operational trends.

### Monthly Analysis

- Delay percentage by month

### Weekly Analysis

- Delay percentage by weekday

### Hourly Analysis

- Delay percentage by order hour

These analyses reveal hidden temporal patterns affecting delivery performance.

---

# 🤖 Machine Learning

The final stage of the project predicts **Late Delivery Risk** using supervised machine learning.

## Target Variable

```text
Late_delivery_risk
```

### Features Used

- Shipping Mode
- Customer Segment
- Department
- Category
- Order Type
- Region
- Scheduled Shipping Days
- Order Month
- Order Hour

---

## Data Preprocessing

Before training the model:

- Frequency Encoding applied to categorical variables
- Train-Test Split
- Feature Scaling (where applicable)
- SMOTE used to handle class imbalance

---

## Model Used

- Random Forest Classifier

---

## Model Evaluation

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix

---

# 📈 Key Business Insights

The analysis provides several actionable business insights:

- Identified the major operational factors causing delivery delays.
- Measured the financial impact of delayed shipments.
- Detected high-risk customer segments and regions.
- Identified shipping modes with the highest delay rates.
- Revealed seasonal delivery trends.
- Built a predictive model capable of identifying high-risk deliveries before shipment.

---

# 💼 Business Value

This project demonstrates how data analytics can support operational decision-making by helping organizations:

- Improve delivery performance
- Reduce operational bottlenecks
- Increase customer satisfaction
- Optimize shipping operations
- Improve profitability
- Predict delivery risks proactively
- Support data-driven business decisions

---

# 📁 Repository Structure

```text
Supply-Chain-Analysis/
│
├── data/
│   └── DataCoSupplyChainDataset.csv
│
├── notebooks/
│   └── supply_chain_analysis.ipynb
│
├── images/
│   ├── kpi_dashboard.png
│   ├── delay_analysis.png
│   ├── profitability_analysis.png
│   ├── root_cause_analysis.png
│   └── model_results.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Supply-Chain-Analysis.git
```

Navigate to the project directory:

```bash
cd Supply-Chain-Analysis
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

# 📦 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
```

---

# 🔮 Future Improvements

- Develop an interactive Power BI dashboard
- Compare Random Forest with XGBoost and LightGBM
- Perform Hyperparameter Tuning
- Add SHAP Explainability for model interpretation
- Build a real-time prediction pipeline
- Integrate inventory optimization analysis
- Deploy the model using Streamlit or Flask

---

# 👨‍💻 Author

**Akash Mondal**
- LinkedIn profile: https://www.linkedin.com/in/akash-m0ndal/
- Contact No.: +91 9083666706

 Data Analyst | SQL | Python | Power BI | Machine Learning

---

## ⭐ If you found this project useful, consider giving it a Star!
