# 🧠 Retail Customer Behavior & Shopping Trends Analysis

## 📌 Project Overview

This project demonstrates a **real-world, end-to-end data analytics pipeline** built to analyze  **retail customer behavior and shopping patterns** .

It mirrors how analytics teams operate in modern organizations—bridging  **raw data, databases, analysis, and business storytelling** .

The objective is to transform transactional customer data into **actionable business insights** that support  **customer segmentation, retention strategies, and revenue optimization** .

---

## 🎯 Business Objectives

* Understand **customer purchasing behavior**
* Identify **high-value and loyal customer segments**
* Analyze **shopping frequency, spend patterns, and trends**
* Enable **data-driven decision-making** for marketing and sales teams

---

## 🧩 End-to-End Analytics Workflow

This project follows a  **corporate-grade analytics lifecycle** :

### 1️⃣ Data Preparation & Exploratory Data Analysis (Python)

* Data ingestion using **Pandas**
* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA) to uncover patterns and anomalies
* Feature understanding for downstream analysis

### 2️⃣ Database Integration (MySQL + SQLAlchemy)

* Designed a relational database schema
* Loaded cleaned data from Python into **MySQL**
* Ensured reproducibility using SQLAlchemy engine

### 3️⃣ Business Analysis Using SQL

* Wrote analytical SQL queries to answer business questions such as:
  * Customer segmentation
  * Purchase frequency analysis
  * Spending behavior insights
* Simulated real-world analyst workflows where **SQL is the source of truth**

### 4️⃣ Visualization & Insights (Power BI)

* Built an **interactive dashboard**
* Highlighted:
  * Customer segments
  * Shopping trends
  * Revenue distribution
* Designed dashboards for **non-technical stakeholders**

### 5️⃣ Insights, Reporting & Storytelling

* Converted analytical results into **business recommendations**
* Structured insights to support **marketing, retention, and growth strategies**

---

## 🛠️ Tech Stack

| Layer              | Tools         |
| ------------------ | ------------- |
| Programming        | Python        |
| Data Analysis      | Pandas, NumPy |
| Database           | MySQL         |
| ORM / Connectivity | SQLAlchemy    |
| Querying           | SQL           |
| Visualization      | Power BI      |
| IDE                | VS Code       |
| Version Control    | Git & GitHub  |

---

## 📂 Project Structure

<pre class="overflow-visible! px-0!" data-start="2662" data-end="3031"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>Retail-Customer-Behavior-and-Shopping-Trends/
│
├── Customer_Shopping_Behavior_Analysis.ipynb   </span><span># Data analysis & DB loading</span><span>
├── customer_shopping_behavior.csv              </span><span># Raw dataset</span><span>
├── customer_behavior_sql_queries.sql            </span><span># Business SQL queries</span><span>
├── customer_behavior_dashboard.pbix             </span><span># Power BI dashboard</span><span>
├── .gitignore
├── README.md
</span></span></code></div></div></pre>



---

## 🚀 How to Run This Project

### 1️⃣ Clone the Repository

git clone https://github.com/shekhus/Retail-Customer-Behavior-and-Shopping-Trends.git
cd Retail-Customer-Behavior-and-Shopping-Trends

### 2️⃣ Set Up Python Environment

<pre class="overflow-visible! px-0!" data-start="3227" data-end="3270"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>pip install -r requirements.txt
</span></span></code></div></div></pre>

### 3️⃣ Run the Jupyter Notebook

Open:

<pre class="overflow-visible! px-0!" data-start="3311" data-end="3364"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-text"><span><span>Customer_Shopping_Behavior_Analysis.ipynb
</span></span></code></div></div></pre>

This notebook covers:

* Data loading
* EDA
* Data cleaning
* Loading data into MySQL using SQLAlchemy

### 4️⃣ Execute SQL Analysis

* Import data into MySQL
* Run queries from:

<pre class="overflow-visible! px-0!" data-start="3542" data-end="3587"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-text"><span><span>customer_behavior_sql_queries.sql
</span></span></code></div></div></pre>

### 5️⃣ Visualize in Power BI

* Open:

<pre class="overflow-visible! px-0!" data-start="3627" data-end="3671"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-text"><span><span>customer_behavior_dashboard.pbix
</span></span></code></div></div></pre>

* Connect Power BI to the MySQL database
* Explore interactive dashboards

---

## 📊 Key Insights Generated

* Identification of **high-value customer segments**
* Understanding of **purchase frequency vs spending**
* Detection of **behavioral trends useful for targeted marketing**
* Insights enabling **customer retention and upsell strategies**
