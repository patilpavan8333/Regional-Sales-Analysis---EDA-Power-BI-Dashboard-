📊 Regional Sales Analysis (EDA & Power BI)
📌 Project Overview

This project presents an end-to-end analysis of five years of U.S. regional sales data to uncover revenue drivers, profitability patterns, and growth opportunities across products, customers, sales channels, and geographies. The objective is to address inconsistent regional performance and limited visibility into seasonality, SKU contribution, and channel profitability through data-driven insights.

The project combines Exploratory Data Analysis (EDA) with interactive Power BI dashboards to support strategic sales planning and informed business decision-making.

🎯 Business Problem

Sales teams often lack a clear, consolidated view of regional performance, seasonal trends, and product profitability. This makes it difficult to identify growth levers, optimize pricing and channel strategies, and allocate resources effectively.

Goal:
Leverage historical sales data to identify trends, evaluate performance, and enable data-backed strategic decisions.

🗂️ Dataset Description

Time Period: 5 years of historical sales data

Data Sources: Sales, Customers, Products, Regions, State Mapping, Budgets

Key Attributes:

Financials: revenue, cost, profit, profit margin

Geography: state, region, latitude/longitude

Products & Channels

Time-based features (month, year)

✅ No missing values or duplicate records after preprocessing.

🔄 Project Workflow

Data Preparation

Cleaned and normalized raw datasets

Merged multiple unlinked tables into a unified data model

Engineered features such as profit and profit margin

Exploratory Data Analysis (EDA)

Analyzed seasonality, sales cycles, and outliers

Evaluated product, customer, channel, and regional performance

Visualization & Dashboarding

Built interactive Power BI dashboards

Enabled self-service analysis with filters by time, product, region, and channel

🔍 Key Insights

Strong seasonality with revenue peaks in late spring/early summer and lows in January

SKU concentration, where a small number of products drive a large share of revenue

Channel trade-offs: Wholesale leads in volume, while Export delivers higher profit margins

Regional dominance by California and the West region

Customer segmentation identified high-value and at-risk accounts based on revenue and margin

🧰 Tools & Technologies

Python (Pandas, NumPy) – Data cleaning, preprocessing, feature engineering, EDA

Power BI – Interactive dashboards and visual analytics

Excel / CSV – Source data and validation

📈 Business Impact

Improved visibility into regional and seasonal sales performance

Supported SKU, pricing, and channel optimization strategies

Delivered a scalable Power BI dashboard for ongoing performance monitoring and strategic planning

📁 Repository Structure
├── data/
│   └── Sales_data(EDA Exported).csv
├── dashboard/
│   └── SALES REPORT.pbix
├── presentation/
│   └── Regional Sales Analysis.pptx
├── notebooks/
│   └── eda_analysis.ipynb
└── README.md

🚀 How to Use

Clone the repository

Run the Python notebook for data preprocessing and EDA

Open the Power BI .pbix file to explore interactive dashboards

👤 Author

Pavan Patil
Aspiring Data Analyst | Python | Power BI | Data Visualization
