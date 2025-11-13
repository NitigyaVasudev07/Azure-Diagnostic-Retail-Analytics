# Azure Diagnostic Retail Analytics

## 📌 Overview
This project investigates the root causes of declining sales in a retail business using Microsoft Azure's cloud-based analytics tools. It demonstrates how to build a diagnostic analytics framework that transforms raw data into actionable insights.

## 🧰 Tools & Technologies
- **Azure Data Factory**: For data ingestion and transformation
- **Azure Synapse Analytics**: For SQL-based data exploration
- **Power BI**: For interactive dashboards and visualizations
- **Python & Pandas**: For preprocessing and feature engineering

## 📊 Dataset
- **Source**: Superstore Sales Dataset (Kaggle)
- **Format**: CSV
- **Features**: Region, Category, State, Segment, Sub-Category, Order Date, Total Sales, Profit, Discount, Quantity, Orders

## 🔍 Project Workflow

### 1. Azure Setup
- Created Azure account and configured services
- Set up Azure Data Factory, Synapse Workspace, and Blob Storage

### 2. Data Ingestion & Cleaning
- Imported raw dataset into Azure Blob Storage
- Used Data Factory pipelines to clean and transform data
- Aggregated metrics: Total Sales, Average Discount, Total Profit

### 3. Data Exploration
- Queried cleaned data in Synapse Analytics
- Identified seasonal trends, regional performance, and segment profitability

### 4. Visualization
- Built Power BI dashboards:
  - Total Sales by Year
  - Sales by Category and Region
  - Monthly Sales Trends
  - Regional Contributions

### 5. Actor Interaction Diagram
- Mapped roles: Customer, Data Engineer, Data Analyst
- Visualized flow across Azure services

### 6. Recommendations
- Launch seasonal campaigns in June, September, December
- Boost marketing in underperforming regions (South, Central)
- Optimize discounting in low-profit categories (Furniture)
- Focus on high-value segments (Consumer)

## 📁 Repository Structure
- `data/`: Raw and cleaned datasets
- `notebooks/`: Python notebooks for analysis
- `reports/`: Assignment documents and final reports
- `diagrams/`: Actor interaction diagrams
- `visuals/`: Power BI charts and dashboards

## 📈 Key Insights
| Metric           | 2014     | 2015     | 2016     | 2017     | Insight                                      |
|------------------|----------|----------|----------|----------|----------------------------------------------|
| Total Sales (USD)| $45,273  | $56,329  | $61,782  | $59,614  | Peak in 2016, decline in 2017                |
| Top Month        | December | December | September| December | Seasonal spikes in Q4                        |
| Lowest Month     | January  | February | January  | March    | Q1 underperforms consistently                |
| Top Region       | West     | East     | West     | West     | West dominates, East spikes in 2015          |
| Top Segment      | Consumer | Consumer | Consumer | Consumer | Consumer segment most profitable             |
| Top Category     | Office Supplies | Furniture | Office Supplies | Technology | Shifting demand across years                 |
Diagnostic Analytics Project | March 2025

