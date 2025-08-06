# BIG-DATA-ANALYSIS
# 💻 CodTech Internship - Task 1: Big Data Analysis

## 🧑‍🎓 Intern Details

- **Name:** Chhavi Chhonker  
- **Intern ID:** CT04DZ1916  
- **Batch Duration:** 4 Weeks  
- **Mentor Name:** Neela Santhosh Kumar  
- **College:** CMR Engineering College  
- **Domain:** Data Analysis  
- **Task:** Task 1 - Big Data Analysis  

---

## 🛠️ Tools and Platforms Used

- **Language:** Python  
- **Libraries:** PySpark  
- **Platform:** Google Colab  
- **Version:** PySpark 3.5.1  
- **Repository:** GitHub  

---

## 📘 Task Description

The goal of this task was to perform **big data analysis** on a large dataset using **PySpark**, showcasing the ability to handle, process, and extract insights from structured data efficiently.

I worked with a dataset named **`CarData.csv`**, which contains detailed information about various car listings including their make, model, fuel type, popularity, and MSRP (price).

Using PySpark in Google Colab, I loaded the dataset and performed the following steps:

---

### 🔹 Data Loading and Exploration

- Imported and initialized a **Spark session**.
- Loaded the dataset into a **PySpark DataFrame**.
- Explored the data using `.show()`, `.columns`, and `.printSchema()`.

---

### 🔹 Categorical Analysis

Using `groupBy()` and `count()`, I analyzed several categorical columns like:
- **Make (Car Brands)**
- **Transmission Type**
- **Vehicle Size**
- **Engine Fuel Type**

This revealed the **most common car types**, **popular transmission styles**, and **distribution of car sizes** in the dataset.

---

### 🔹 Numerical Analysis

With `.describe()`, I computed statistics such as **mean**, **standard deviation**, **min**, and **max** for the `Popularity` column:
- Mean: ~1555
- Min: 2
- Max: 5657

This showed a **high variation** in how different car models are perceived in the market.

---

### 🔹 Correlation Analysis

I used the `.corr()` function to measure the relationship between **Popularity** and **MSRP (price)**.

- The correlation value was `-0.048`, indicating a **very weak negative correlation**.  
- Insight: Expensive cars are **not necessarily more popular**, and vice versa.

---

## 📌 Insights Summary

- The dataset shows a **wide range of car types**, with some brands appearing far more frequently than others.
- **Mid-size** and **automatic** cars dominate the listings.
- **Popularity is not dependent on car price** — there's no strong correlation.
- PySpark allowed scalable, efficient handling of this large dataset within an online notebook.

---
## OUTPUT

<img width="1234" height="453" alt="Image" src="https://github.com/user-attachments/assets/64315bad-0819-4aa5-b945-1cf18dbd8559" />
