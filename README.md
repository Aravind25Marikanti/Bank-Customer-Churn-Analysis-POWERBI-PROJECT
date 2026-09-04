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

## 📂 Dataset

The dataset contains customer demographics, banking information, activity status, credit-card ownership, geography, and exit/retention information.

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
* Validated date and numeric fields
* Ensured consistency of IDs

---

## 📐 DAX Calculations

### Calculated Columns

* **Customer Age Group** – Young, Middle Age, Senior
* **Tenure Category** – New, Loyal
* **Balance Status** – Zero Balance, Has Balance

### Measures

* **Total Customers**
* **Exited Customers**
* **Retention Rate (%)**
* **Average Balance**
* **Average Salary**

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

## 🎯 Business Recommendations

* Identify and prioritize **high-churn customer segments**.
* Develop targeted retention campaigns for **at-risk customers**.
* Monitor regions with higher exit rates.
* Increase engagement among inactive customers.
* Analyze product usage to improve customer retention.
* Develop personalized strategies based on **age and tenure**.
* Monitor retention KPIs regularly using Power BI.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Star Schema Data Modeling**
* **Data Visualization**
* **Business Analysis**

---

## 📁 Project Structure

```text
Bank-Customer-Churn-Analysis/
│
├── Bank_Customer_Churn_Analysis_Project.pbix
├── README.md
│
└── Dashboard Screenshots/
    ├── Customer Overview.png
    ├── Churn Analysis.png
    └── Product & Credit Analysis.png
```

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open `Bank_Customer_Churn_Analysis_Project.pbix` using **Power BI Desktop**.
3. Navigate through the three dashboard pages.
4. Use the interactive filters and visuals to explore customer churn and retention.

---

## 📌 Project Outcome

An interactive **Power BI customer churn analytics dashboard** was developed to help the bank understand customer behavior, identify churn patterns, and support **data-driven customer retention strategies**.

---

## 👨‍💻 Author

**Aravind**
*Data Analyst*

**Skills:** Power BI | Power Query | DAX | Data Modeling | Data Visualization | Business Analysis
