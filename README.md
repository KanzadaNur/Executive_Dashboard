# 📊 Executive Dashboard: Retail Sales Analysis

## 🎯 Project Overview
This project focuses on the end-to-end processing of retail data, from raw CSV ingestion to a functional Executive Dashboard. The goal is to provide actionable insights into product performance, regional sales, and customer acquisition channels.

## 🛠️ Data Cleaning & Preparation
Before visualization, the data underwent a rigorous cleaning process using **Python (Pandas)**:
* **Handling Missing Values:** Identified and treated null entries in sales records to ensure data integrity.
* **Data Type Standardization:** Converted date columns to datetime objects and ensured monetary values were formatted as floats.
* **Merging Datasets:** Joined Sales, Product, and Customer tables using `product_id` and `customer_id` keys.
* **Feature Engineering:** Created calculated columns for total revenue and profit margins.

## 📈 Dashboard Features
The final dashboard provides insights into:
* **Revenue by Category:** A breakdown of which products (Monitors, Tablets, etc.) drive the most value.
* **Regional Analysis:** Visualizing performance across the West Midlands, London, and other key regions.
* **Acquisition Channels:** Evaluating the effectiveness of Referral, Organic, and Paid marketing.

## 🚀 How to Run
1. Clone the repo: `git clone https://github.com/KanzadaNur/Executive_Dashboard.git`
2. Install dependencies: `pip install pandas matplotlib seaborn`
3. Open `TechHub_Retail.ipynb` in Jupyter or VS Code.
