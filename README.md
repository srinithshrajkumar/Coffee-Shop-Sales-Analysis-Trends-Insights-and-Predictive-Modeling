# ☕ Coffee Shop Sales Analysis Dashboard 📊

An end-to-end data analysis and visualization project built using **Python** 🐍, focusing on **sales performance**, **product trends**, and **store insights** from transactional data collected across multiple locations of a coffee shop chain.

---

## 📈 Project Summary

This project dives deep into a dataset of **149,116 transactions** 🧾, uncovering valuable insights related to:

- 🛍️ **Products**: Exploring category, type, price 💲, and quantity sold 🔢  
- 🏪 **Stores**: Analyzing performance based on ID and location 📍  
- ⏰ **Transactions**: Examining date 🗓️, time ⏱️, and revenue generated 💰

The project follows a comprehensive **data science lifecycle**:

1. 🔍 **Data Loading and Initial Exploration**
2. ✨ **Data Cleaning & Preparation**
3. 🧐 **Exploratory Data Analysis (EDA)**
4. 🛠️ **Feature Engineering**
5. 🤖 **Predictive Modeling**
6. 📊 **Interactive Dashboard with Plotly**

---

## 🧰 Tools & Technologies

- 🐍 **Python**  
- 🐼 **Pandas**  
- 🔢 **NumPy**  
- 📈 **Matplotlib** & **Seaborn**  
- 📊 **Plotly** (for interactive visualizations)  
- 🧠 **Scikit-learn** (for machine learning)  
- 🧩 **KMeans Clustering** (for segmentation)

---

## 🚀 Workflow Overview

### 1. 🧐 Data Loading & Initial Exploration

- Loaded the `Coffee Shop Sales.csv` file 📂  
- Checked for missing values 🧹 and ensured data types are consistent ⚙️  
- Dataset contains **149,116 records × 11 columns**

---

### 2. ✨ Data Cleaning & Preparation

- Merged `transaction_date` 🗓️ and `transaction_time` ⏱️ into a unified `transaction_datetime` 📅  
- Derived time-based features:
  - `day_of_week` 📆
  - `month` 📅
  - `hour` ⌛  
- Calculated `total_revenue` 💰 using `transaction_qty` × `unit_price` 💲

---

### 3. 🔍 Exploratory Data Analysis (EDA)

- 📅 **Revenue Over Time**: Trends across weeks and months  
- 🥇 **Top Categories & Products**: Best-sellers by revenue and quantity  
- 🏪 **Store Performance**: Revenue and transactions by store  
- ⏰ **Temporal Patterns**: Hourly, daily, and weekend sales behaviors

---

### 4. 🛠️ Feature Engineering

- 🧪 Created derived features:
  - Product-level 📦 (e.g., average price, total sold)
  - Store-level 🏬 (e.g., revenue per store, weekend ratio)
  - Time-series-based ⏱️ (e.g., hour, day, month breakdown)

---

### 5. 🤖 Predictive Modeling

Basic predictive models were implemented to simulate future sales trends:

- 🎯 **Objective**: Predict `total_revenue` 💰 based on time ⏳, product category ☕, and store location 📍  
- 🔧 **Models Used**:
  - 📏 `Linear Regression`: Baseline model
  - 🌳 `Decision Tree`: Captures non-linear relationships
- 📊 **Evaluation Metrics**:
  - 📉 RMSE (Root Mean Squared Error)
  - 📉 MAE (Mean Absolute Error)
  - 📈 R² Score (Coefficient of determination)

> These models serve as a foundation to understand key revenue drivers and simulate sales scenarios 🔮.

---

### 6. 📊 Interactive Dashboard (Plotly)

An interactive dashboard allows stakeholders to explore insights visually and intuitively:

#### 🧭 Key Features

- 📆 **Sales Calendar Heatmap**: Visual sales activity by date  
- 📍 **Store Revenue Map**: Compare store performance across locations  
- 📦 **Product Category Breakdown**: Visualize top product categories  
- ⏰ **Hourly Sales Activity**: Discover peak sales hours  
- 🧩 **Cluster Visualization**: Display store clusters from KMeans analysis

