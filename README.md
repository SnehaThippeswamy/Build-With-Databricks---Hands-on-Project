# Build-With-Databricks---Hands-on-Project

# 📈 Fundamental Investment Scoring – Stock Picks

## 🚀 Project Overview

This project was developed as part of the **“Build With Databricks: Hands-On Project Challenge”** in collaboration with **Codebasics and Databricks**.

The objective of this project is to build a data-driven framework to evaluate and score stocks based on fundamental financial metrics. The final outcome is a ranked list of stocks that can help investors make more informed decisions.

The analysis is implemented in Databricks using PySpark, SQL, and Python-based data processing and analytics.

---

## 🎯 Objectives

The key goals of this project are:

- Ingest and process financial stock data using Databricks
- Clean and transform raw financial data into an analysis-ready format
- Engineer meaningful financial features for investment scoring
- Normalize financial metrics using Min-Max scaling
- Compute a composite **Investment Score** for each stock
- Rank stocks based on their investment attractiveness

---

## 📂 Project Structure

📁 Fundamental_Investment_Scoring/
 │
 ├── Stock picks.ipynb        # Main Databricks / Jupyter notebook
 ├── README.md                # Project documentation

---

## 🧠 Methodology

### 1️⃣ Data Ingestion
- Loaded financial stock data into Databricks using Spark.
- Explored the dataset using SQL and PySpark DataFrames.

### 2️⃣ Data Cleaning & Transformation
- Handled missing values and outliers.
- Filtered relevant stocks based on liquidity and market capitalization.

### 3️⃣ Feature Engineering

Key financial features used:

- P/E Ratio (Price to Earnings)
- P/B Ratio (Price to Book)
- PEG Ratio (Growth Adjusted)
- ROE (Return on Equity)
- Revenue Growth
- EPS Growth

These features were standardized using Min-Max scaling within each sector.

### 4️⃣ Investment Scoring Model

A composite score was computed using weighted financial metrics to rank stocks:

Investment Score = f(normalized_pe, normalized_pb, normalized_peg,
normalized_roe, normalized_revenue_growth,
normalized_eps_growth)

Stocks were then ranked from highest to lowest score.

---

## 🛠️ Tools & Technologies

- **Databricks**
- **PySpark**
- **Python**
- **Spark SQL**
- **Pandas (for analysis where applicable)**

---

## 📊 Results

- Generated a ranked list of top investment-worthy stocks.
- Identified high-performing stocks based on fundamental analysis.
- Enabled sector-wise comparison and ranking.

---

## 📌 How to Run the Notebook

1. Upload `Stock picks.ipynb` to Databricks.
2. Attach it to a running cluster.
3. Run all cells sequentially.
4. Review final stock rankings in the output.

---

## 🙏 Acknowledgments

This project was completed as part of the **Codebasics & Databricks Hands-On Project Challenge**. Special thanks to the instructors and community for guidance and support.

---

## 👤 Author

**Sneha Thippeswamy**  
AI/ML Practitioner 
