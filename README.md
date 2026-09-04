# 🏦 Bank Customer Churn Analysis – Power BI

## 📌 Project Overview

This project analyzes **customer churn in the banking sector** using **Microsoft Power BI**.

The objective is to understand customer retention and identify patterns associated with customers leaving the bank. The project covers **data cleaning, data modeling, DAX calculations, interactive dashboards, and business insights**.

---

## 🎯 Business Objective

The analysis focuses on:

* Understanding **customer retention and churn**
* Identifying churn patterns across **demographics and geography**
* Analyzing customer **activity, tenure, balance, and products**
* Understanding **credit-card ownership** patterns
* Providing insights to support **customer retention strategies**

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Star Schema Data Modeling**
* **Data Visualization**
* **Business Analysis**


---

## 📂 Dataset

The dataset contains customer demographics, banking information, activity status, credit-card ownership, geographical information, and customer exit/retention information.

### Main Tables

* `BankChurn` – Main fact table
* `CustomerInfo` – Customer information
* `Geography` – Country details
* `Gender` – Gender mapping
* `CreditCard` – Credit-card ownership
* `ActiveCustomer` – Customer activity status
* `ExitCustomer` – Customer exit/retention status

---

## 🧩 Data Modeling

A **Star Schema** was implemented in Power BI.

* **Fact Table:** `BankChurn`
* **Dimension Tables:** `CustomerInfo`, `Geography`, `Gender`, `CreditCard`, `ActiveCustomer`, `ExitCustomer`
* **Relationships:** One-to-Many
* ID columns were hidden from the report view where appropriate.
* Dimension tables were used for filtering and analysis.

---

## 🧹 Data Preparation

The following data-cleaning steps were performed:

* Removed duplicate records
* Handled missing/null values
* Standardized column names
* Validated date formats and numeric columns
* Ensured consistency of customer IDs

---

## 📐 DAX Calculations

### Calculated Columns

* **Customer Age Group** – Categorized customers as Young, Middle Age, or Senior
* **Tenure Category** – Categorized customers as New or Loyal
* **Balance Status** – Classified customers as Zero Balance or Has Balance

### Measures

* **Total Customers**
* **Exited Customers**
* **Retention Rate (%)**
* **Average Balance**
* **Average Salary**
* **Active Member (%)**
* **Exit Rate (%)**
* **Active Member Count**
* **Inactive Member Count**

---

# 📊 Dashboard Pages

## 1️⃣ Customer Overview

Provides a high-level view of the customer base.

**Visuals:**

* Total Customers
* Retention Rate
* Active Member %
* Gender Distribution
* Customers by Geography
* Age Group Distribution

---

## 2️⃣ Churn Analysis

Focuses on customer exits and retention patterns.

**Visuals:**

* Exited vs Retained Customers
* Churn by Geography & Gender
* Active → Inactive → Exit
* Average Balance vs Age

---

## 3️⃣ Product & Credit Analysis

Analyzes customer products, credit-card ownership, geography, and retention.

**Visuals:**

* Credit Card Holders vs Non-Holders
* Exit Rate by Number of Products
* Geography vs Exit Rate
* Retention Rate

---

## 🎯 Business Recommendations

* Identify and prioritize **high-churn customer segments**.
* Develop targeted retention campaigns for **at-risk customers**.
* Monitor regions with higher exit rates.
* Increase engagement among inactive customers.
* Analyze product usage to improve customer retention.
* Develop personalized strategies based on **age and tenure**.
* Monitor retention KPIs regularly using Power BI.

---

## 💡 Key Insights

The dashboards help identify:

* Customer churn and retention patterns
* Differences in churn across geographical locations
* Churn patterns across age groups and genders
* Relationship between customer activity and exits
* Relationship between number of products and exit rate
* Credit-card ownership patterns
* Differences between new and loyal customers
* Balance-related customer patterns

> **Note:** Specific numerical findings are based on the final dashboard analysis.

---

## 📌 Project Outcome

An interactive **Power BI customer churn analytics solution** was developed to provide a consolidated view of customer behavior, churn patterns, and retention metrics.

The dashboards enable data-driven analysis across **customer demographics, geography, activity, tenure, balance, products, and credit-card ownership**, helping support more targeted **customer retention strategies**.
