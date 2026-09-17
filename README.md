# E-Commerce Sales Analysis

## 📌 Project Overview

This project analyzes e-commerce sales data to understand sales performance, product category trends, order patterns, fulfilment methods, and order cancellations.

The analysis was performed using Python, Pandas, and Matplotlib to clean, explore, and visualize the data and generate meaningful business insights.

---

## 🎯 Objectives

- Analyze overall sales performance
- Identify top-performing product categories
- Analyze monthly sales trends
- Compare Amazon and Merchant fulfilment
- Analyze order status and cancellations
- Understand product-wise quantity sold
- Generate useful business insights through data visualization

---

## 📊 Dataset

The project uses an e-commerce sales dataset containing **128,975 records and 24 original columns**.

After removing unnecessary columns, **22 relevant columns** were used for analysis.

The dataset contains information related to:

- Order ID
- Order Date
- Order Status
- Fulfilment Method
- Sales Channel
- Product Category
- Quantity
- Sales Amount
- Shipping Details
- Customer Order Information

### Dataset Source

Kaggle — E-Commerce Sales Dataset by The Devastator.
import kagglehub

# Download latest version
path = kagglehub.dataset_download("thedevastator/unlock-profits-with-e-commerce-sales-data")

print("Path to dataset files:", path)

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **Matplotlib**
- **Google Colab**
- **Jupyter Notebook**

---

## 🔍 Data Cleaning

The following data preparation steps were performed:

- Checked dataset structure and data types
- Identified missing values
- Checked for duplicate records
- Removed unnecessary columns
- Converted the `Date` column into datetime format
- Explored categorical variables and numerical data

---

## 📈 Analysis Performed

### 1. Overall Sales Analysis

- Total quantity sold: **116,649 units**
- Total sales amount: **₹78,592,678.30**
- Average Order Value: **₹648.56**

### 2. Category-wise Sales

The highest sales contribution came from:

| Category | Sales Amount |
|---|---:|
| Set | ₹39,204,124.03 |
| Kurta | ₹21,299,546.70 |
| Western Dress | ₹11,216,072.69 |
| Top | ₹5,347,792.30 |
| Ethnic Dress | ₹791,217.66 |

### 3. Monthly Sales Analysis

Sales were analyzed for March to June 2022.

| Month | Sales Amount |
|---|---:|
| March 2022 | ₹101,683.85 |
| April 2022 | ₹28,838,708.32 |
| May 2022 | ₹26,226,476.75 |
| June 2022 | ₹23,425,809.38 |

### 4. Fulfilment Analysis

| Fulfilment Method | Sales Amount |
|---|---:|
| Amazon | ₹54,322,151.00 |
| Merchant | ₹24,270,527.30 |

### 5. Order Cancellation Analysis

- Cancelled orders: **18,332**
- Cancellation rate: **14.21%**

---

## 📊 Visualizations

The project includes visualizations for:

- Sales by Product Category
- Monthly Sales Trend
- Sales by Fulfilment Method
- Quantity Sold by Product Category
- Order Status Distribution

These visualizations help identify patterns and compare different aspects of e-commerce performance.

---

## 💡 Key Insights

- **Set** generated the highest sales amount among all product categories.
- **Set and Kurta** were also the two categories with the highest quantities sold.
- **April 2022** recorded the highest monthly sales in the analyzed period.
- Amazon fulfilment generated higher sales than Merchant fulfilment.
- **18,332 records were marked as cancelled**, representing **14.21%** of the dataset.
- The analysis shows that a small number of major categories contributed a large portion of the overall sales.

---

## 📁 Project Structure

```text
E-Commerce-Sales-Analysis/
│
├── E-Commerce_Sales_Analysis.ipynb
└── README.md
