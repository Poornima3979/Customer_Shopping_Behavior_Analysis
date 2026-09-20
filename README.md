<div align="center">

# 📊 Customer Shopping Behaviror Analysis Using Python, SQL & Power Bi
### Data Analysis | Business Insights | Interactive Dashboard


### Data Analysis | Business Insights | Interactive Dashboard# Customer Shopping Behavior Analysis

An end-to-end data analytics project analyzing **3,900 customer transactions** to uncover spending patterns, customer segments, product preferences, and business opportunities.

## 📊 Project Overview

This project explores customer shopping behavior using Python, PostgreSQL, SQL analysis, and Power BI. The analysis focuses on revenue, customer segmentation, subscriptions, products, discounts, demographics, and shipping preferences.

The dataset contains **3,900 transactions and 18 features**, with missing values identified in the Review Rating field. The average purchase amount is **$59.76**. fileciteturn0file0L7-L21

## 🛠️ Tools & Technologies

- **Python** – Data cleaning and feature engineering
- **Pandas** – Data manipulation
- **PostgreSQL** – Database integration and SQL analysis
- **SQL** – Business analysis and insights
- **Power BI** – Interactive dashboard and visualization

## 🔄 Data Preparation

The data preparation process included:

- Imputing missing Review Ratings using the median rating by category
- Standardizing column names to `snake_case`
- Creating `age_group` categories
- Creating `purchase_frequency_days`
- Removing the redundant `promo_code_used` feature
- Loading the cleaned DataFrame into PostgreSQL for SQL analysis fileciteturn0file0L23-L36

## 🔍 Key Insights

### Revenue & Spending

- Male customers generated more than twice the revenue of female customers: **$157,890 vs. $75,191**.
- **839 customers** used discounts while still spending above the average purchase amount.
- Average Express shipping purchase value was **$60.48**, compared with **$58.46** for Standard shipping. fileciteturn0file0L38-L50

### Subscription Analysis

- Only **27% of customers subscribe**.
- Average spending was similar between subscribers and non-subscribers: **$59.49 vs. $59.87**.
- Among customers with more than five purchases, **958 were subscribers** compared with **2,518 non-subscribers**, indicating an opportunity to convert repeat buyers.
- Subscribers were identified as a potential revenue-growth lever. fileciteturn0file0L51-L67

### Product & Category Analysis

- Clothing was the leading category, with **1,800 sales and approximately $100K revenue**.
- Jewelry, Sunglasses, and Belts led the Accessories category.
- Sandals led Footwear with **160 orders**.
- Jackets and Coats each recorded approximately **160 orders**.
- Hats, Sneakers, and Coats had the highest discount rates at approximately **49–50%**. fileciteturn0file0L69-L84

### Customer Segmentation

Customers were grouped into three segments:

| Segment | Customers | Description |
|---|---:|---|
| Loyal | 3,116 | Dominant segment driving repeat revenue |
| Returning | 701 | Engaged customers with potential for retention |
| New | 83 | Smallest segment with onboarding and growth potential |

fileciteturn0file0L86-L97

### Age Group Analysis

Revenue was broadly distributed across age groups, ranging from **$55,763 for Seniors to $62,143 for Young Adults**.

Young Adults recorded the highest sales volume with **900 transactions**, followed by Middle-aged customers with 850, Seniors with 800, and Adults with 750. No single age group dominated revenue, supporting broad customer targeting. fileciteturn0file0L99-L114

## 📈 Power BI Dashboard

The Power BI dashboard provides interactive filters for:

- Subscription Status
- Gender
- Category
- Shipping Type

These filters enable users to dynamically explore revenue, sales, and demographic patterns.

Key dashboard metrics include:

- **3.9K** customers
- **$59.76** average purchase amount
- **3.75** average review rating fileciteturn0file0L115-L127

## 💡 Business Recommendations

Based on the analysis:

1. **Boost Subscriptions** – Promote exclusive subscriber benefits to convert the 73% non-subscribed customer base.
2. **Strengthen Loyalty Programs** – Reward repeat buyers and encourage movement into the Loyal segment.
3. **Review Discount Policy** – Balance discount-driven sales with margin control, particularly for heavily discounted products such as Hats and Sneakers.
4. **Targeted Marketing** – Use customer age, revenue, and shipping behavior to support targeted marketing strategies. fileciteturn0file0L128-L140

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis
│
├── 01_Report
│   └── Customer Shopping Behavior Analysis_Report.pdf
│
├── 02_Python
│   └── Python Notebook.ipynb
│
├── 03_SQL
│   └── SQL script.sql
│
├── 04_PowerBI
│   ├── Power BI.pdf
│   └── dashboard.png
│
├── 05_Presentation
│   └── Presentation.pdf
│
└── README.md
└── requirements.txt
```

> Update the filenames and folders above to match the files you actually upload to your GitHub repository.

## 🚀 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning & Preparation using Python
     ↓
MySQL Database
     ↓
SQL Business Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights & Recommendations
```

## 🎯 Project Objective

The objective of this project is to transform raw customer transaction data into actionable business insights that can support decisions related to customer retention, subscription growth, product strategy, discounts, and targeted marketing.

## 👩‍💻 Author

** Poornima N  **


---

⭐ If you found this project useful, feel free to explore the analysis and dashboard files in this repository.

