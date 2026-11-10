
# 🛒 Grocery Store Sales Analytics Dashboard

An end-to-end grocery store sales analytics project developed using Python, Pandas, and Microsoft Power BI to analyze sales performance, customer purchasing behavior, discounts, payment preferences, and store performance.

---

## 📌 Overview

This project focuses on analyzing grocery store sales data to identify business trends, understand customer behavior, evaluate discount strategies, and measure store performance.

The project processes **10,000 grocery store transactions** covering the year 2023. It involves data cleaning, preprocessing, exploratory data analysis (EDA), outlier detection, feature engineering, and interactive dashboard development using Power BI.

The analysis provides insights into **category-wise revenue, monthly and quarterly sales trends, city-wise performance, customer age groups, payment preferences, product performance, and store-level revenue**.

---

## ✅ Features

### 🧹 Data Cleaning & Preprocessing
- Load grocery sales data from CSV files using Pandas.
- Identify and remove duplicate records.
- Handle missing values.
- Convert date columns into proper datetime format.
- Convert numerical columns into appropriate data types.
- Validate quantity and unit price values.
- Filter invalid discount percentages (0–80%).
- Create high-discount flags for discounts greater than or equal to 20%.

### 📊 Outlier Detection
- Apply the Interquartile Range (IQR) method.
- Detect outliers in Quantity, Unit Price, and Total Amount.
- Create individual outlier flags.
- Identify transactions containing one or more outliers.

### ⚙️ Feature Engineering
- Calculate gross revenue.
- Calculate discount amount.
- Calculate actual revenue per unit.
- Calculate expected transaction totals.
- Identify mismatches between calculated and recorded transaction amounts.
- Extract Month, Quarter, and Week from transaction dates.
- Create digital payment indicators.

### 📈 Exploratory Data Analysis (EDA)

**1. Discount Analysis**
- Analyze average discounts by product category.
- Calculate revenue loss by category.
- Study the relationship between discounts and quantity sold.
- Calculate average revenue per transaction.

**2. Time-based Sales Analysis**
- Analyze monthly and quarterly sales.
- Identify the best-performing month and quarter.
- Calculate category-wise seasonality indexes.
- Identify peak sales months for each category.
- Rank categories based on seasonal sales variations.

**3. Geographical Analysis**
- Analyze city-wise revenue.
- Analyze region-wise revenue.
- Calculate transaction counts by city.
- Identify top and bottom-performing cities.

**4. Customer Analysis**
- Calculate average spending by customer age group.
- Identify the top three product categories for each age group.
- Analyze UPI usage percentages across age groups.

**5. Payment Analysis**
- Calculate the percentage share of each payment method.
- Compare monthly UPI and Cash transaction trends.
- Analyze digital payment adoption by city.

**6. Product & Category Analysis**
- Calculate category-wise revenue contribution.
- Perform cumulative revenue analysis.
- Identify the top 10 revenue-generating products.
- Identify the 10 slow-moving products based on quantity sold.

**7. Store Performance Analysis**
- Identify the top 10 and bottom 10 stores by revenue.
- Calculate average transaction value per store.
- Compare average transaction values across cities.
- Identify stores performing below their respective city averages.

### 📊 Power BI Dashboard
- Interactive grocery sales dashboard.
- Sales performance monitoring.
- Category and geographical analysis.
- Customer and payment behavior analysis.
- Store performance comparison.

---

## 📊 Dataset Summary

| Attribute | Description |
|-----------|-------------|
| Dataset | Grocery Store Sales Dataset |
| Total Records | 10,000 Transactions |
| Total Columns | 15 |
| Data Period | January – December 2023 |
| File Format | CSV |
| Total Categories | 10 |
| Total Cities | 10 |
| Total Regions | 4 |
| Total Stores | 50 |
| Unique Customers | 6,055 |
| Unique Products | 100 |

### Dataset Columns

| Column Name | Description |
|-------------|-------------|
| `Transaction_ID` | Unique transaction identifier |
| `Date` | Transaction date |
| `Customer_ID` | Unique customer identifier |
| `Customer_Age_Group` | Customer age category |
| `City` | City where the transaction occurred |
| `Region` | Geographical region |
| `Store_ID` | Unique store identifier |
| `Category` | Product category |
| `Product_Name` | Name of the purchased product |
| `Brand` | Product brand |
| `Quantity` | Number of units purchased |
| `Unit_Price_INR` | Price per unit |
| `Discount_Percent` | Discount percentage applied |
| `Total_Amount_INR` | Final transaction amount |
| `Payment_Method` | Mode of payment |

---

## 🗂️ Tech Stack

| Component | Technology Used |
|-----------|-----------------|
| Programming Language | Python |
| Data Manipulation | Pandas |
| Data Visualization | Microsoft Power BI |
| Data Analysis | Exploratory Data Analysis (EDA) |
| Statistical Analysis | Correlation Analysis |
| Outlier Detection | IQR Method |
| Data Processing | Feature Engineering |
| Data Source | CSV |
| Development Environment | VS Code |

---

## 🔧 Setup Instructions

### ✅ Install Required Python Modules

```bash
pip install pandas
```

### ✅ Prepare the Dataset

Place the original dataset in the project directory:

```text
Grocery_Store_Sales_Dataset.csv
```

### ✅ Run Python Source Code

```bash
python main.py
```

The Python script performs:
- Data cleaning and preprocessing.
- Outlier detection.
- Feature engineering.
- Exploratory data analysis.
- Business performance analysis.
- Export of the cleaned dataset.

### ✅ Exported Dataset

After successful execution, the cleaned dataset is generated as:

```text
cleaned_grocery_data.csv
```

### ✅ Open Power BI Dashboard

1. Open Microsoft Power BI Desktop.
2. Open the `PowerBI Report.pbix` file.
3. If required, update the dataset source path.
4. Refresh the data.
5. Explore the interactive dashboard.

---

## 📁 Project Structure

```text
Grocery-Store-Sales-Analytics/
│
├── main.py
├── Grocery_Store_Sales_Dataset.csv
├── cleaned_grocery_data.csv
├── PowerBI Report.pbix
└── README.md
```

---

## 🏁 Conclusion

This project demonstrates an end-to-end **Grocery Store Sales Analytics workflow**, covering data cleaning, preprocessing, feature engineering, exploratory data analysis, statistical analysis, and interactive dashboard development.

The analysis helps businesses understand sales performance, identify profitable product categories, evaluate customer purchasing patterns, monitor discount strategies, and improve store-level performance.

It demonstrates practical skills in **Python, Pandas, Power BI, Data Cleaning, EDA, Feature Engineering, Statistical Analysis, and Business Intelligence**.

---

## 📬 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/deepali-cilamkoti/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Visit%20Profile-blue?style=for-the-badge&logo=linkedin" />
  </a>
</p>

---