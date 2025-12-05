# customer_behavior_project

# 🛍️ **Customer Shopping Behavior Analysis**

A complete end-to-end data analysis project using **Python, SQL, and Power BI**, based on 3,900 customer transactions.
This project uncovers **shopping patterns, customer segments, product preferences, discount usage, and revenue trends** to support data-driven business decisions.

---

## 📘 **📌 Project Overview**

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across various product categories.
The goal is to identify:

* Spending behavior
* Top-performing products
* Customer segments (New, Loyal, Returning)
* Impact of discounts
* Subscription behavior
* Category performance
* Age-wise revenue contribution

---

## 📂 **Dataset Summary**

| Attribute Type | Details                                    |
| -------------- | ------------------------------------------ |
| Rows           | **3,900**                                  |
| Columns        | **18**                                     |
| Missing Values | 37 in Review Rating                        |
| File Format    | CSV/Excel                                  |
| Categories     | Clothing, Footwear, Accessories, Outerwear |

### **Key Features**

* **Demographics:** Age, Gender, Location, Subscription Status
* **Purchase Details:** Item Purchased, Category, Amount, Season, Size, Color
* **Behavior:** Frequency, Previous Purchases, Discount Applied, Review Rating, Shipping Type

---

## 🧼 **Data Preprocessing (Python)**

### ✔ Data Cleaning

* Checked data structure using `df.info()`
* Summary statistics using `df.describe()`
* Imputed missing values in **review_rating** by **category-wise median**

### ✔ Column Standardization

* Converted all columns to **snake_case**
* Ensured compatibility with SQL & Power BI

### ✔ Feature Engineering

* `age_group` (Young Adult, Adult, Middle-aged, Senior)
* `purchase_frequency_days`
* Removed redundant column: `promo_code_used`

### ✔ Database Integration

* Loaded cleaned data into **PostgreSQL** for SQL-based analysis

---

## 🗄️ **SQL Analysis (MySQL)**

### 🔹 **1. Revenue by Gender**

| Gender | Revenue |
| ------ | ------- |
| Female | 75,191  |
| Male   | 157,890 |

### 🔹 **2. High-Spending Discount Users**

✓ Identified **839 customers** who used discounts but still spent above average.

### 🔹 **3. Top 5 Products by Rating**

* Gloves: 3.86
* Sandals: 3.84
* Boots: 3.82
* Hat: 3.80
* Skirt: 3.78

### 🔹 **4. Shipping Type Comparison**

| Type     | Avg Spend |
| -------- | --------- |
| Standard | 58.46     |
| Express  | 60.48     |

### 🔹 **5. Subscribers vs Non-Subscribers**

| Status | Customers | Avg Spend | Total Revenue |
| ------ | --------- | --------- | ------------- |
| Yes    | 1053      | 59.49     | 62,645        |
| No     | 2847      | 59.87     | 170,436       |

### 🔹 **6. Discount-Dependent Products**

Top discounted items: **Hat, Sneakers, Coat, Sweater, Pants**

### 🔹 **7. Customer Segmentation**

| Segment   | Count |
| --------- | ----- |
| Loyal     | 3,116 |
| New       | 83    |
| Returning | 701   |

### 🔹 **8. Revenue by Age Group**

| Age Group   | Revenue |
| ----------- | ------- |
| Young Adult | 62,143  |
| Middle-aged | 59,197  |
| Adult       | 55,978  |
| Senior      | 55,763  |

---

## 📈 **Power BI Dashboard**

The Power BI report contains:

* Sales Overview
* Category Performance
* Top Products
* Customer Segments
* Subscription Analysis
* Review Ratings
* Discount Effects
* Demographic Insights

Interactive slicers include:

* Gender
* Category
* Season
* Shipping Type
* Age Group
* Subscription Status



---

## 🧠 **Business Recommendations**

### ✔ Boost Subscriptions

Offer exclusive benefits to increase conversion.

### ✔ Strengthen Loyalty Programs

Leverage repeat buyers (3,116 loyal customers).

### ✔ Revisit Discount Strategy

Identify products overly dependent on discounts.

### ✔ Promote Top-Rated Items

Gloves, Sandals, Boots, Hats perform strongly.

### ✔ Target High-Revenue Demographics

Young Adults and Middle-aged groups drive most revenue.

---

## 🛠️ **Tech Stack Used**

| Category      | Tools                                       |
| ------------- | ------------------------------------------- |
| Programming   | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Database      | MySQL                                       |
| Visualization | Power BI                                    |
| Environment   | Jupyter Notebook                            |
| Dashboard     | Power BI Desktop                            |

---




## ⭐ **Author**

**POTHULA RAGHAVENDRA REDDY**
📧 *pothularaghava90@gmail.com*


---
