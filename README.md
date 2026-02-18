# Power BI Customer_Segmentation_Analysis Project

## 📌 Project Overview

This project analyzes U.S. shopping trend data (3,900+ customer records) to:

- Identify product categories where discounts should be applied
- Analyze card spending behavior across age groups, seasons, and locations
- Segment customers into distinct clusters
- Generate data-driven marketing recommendations

The goal was to transform raw transactional data into strategic business insights using Python-based analytics.

## 🎯 Problem Statement

Retail businesses often apply discounts without understanding their actual impact on sales performance and profitability.

This project aims to:

1. Identify which product categories benefit from discounts.
2. Understand customer spending patterns across demographics and seasons.
3. Segment customers into meaningful groups to enable targeted marketing.
4. Provide actionable business recommendations based on analytical findings.

## 📊 Dataset Description

The dataset contains 3,900 customer records with the following attributes:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount (USD)
- Location
- Season
- Review Rating
- Discount Applied
- Promo Code Used
- Payment Method
- Subscription Status
- Previous Purchases
- Frequency of Purchases

This dataset enables behavioral, demographic, and transactional analysis.

## 🛠 Approach & Methodology

### 1️⃣ Data Cleaning & Preparation

- Checked missing values and data types
- Converted categorical variables where required
- Aggregated transactional metrics
- Created calculated metrics (Discount %, Avg Rating, Discount Lift)

### 2️⃣ Exploratory Data Analysis (EDA)

**Performed:**

- Univariate analysis (distribution of spend, age, ratings)
- Bivariate analysis (category vs sales, discount impact)
- Correlation analysis
- Seasonal and location-based analysis
- Payment method analysis

**Key visualizations included:**

- Correlation Heatmaps
- Bar Charts (Category Sales)
- Seasonal Spend Analysis
- Geographic Heatmap (Location-wise spend)
- Age vs Card Spend trend analysis

### 3️⃣ Discount Impact Analysis

**Calculated:**

- Discount Rate per category
- Average Review Rating
- Discount Average Lift (Impact on Sales)
- Discount Flag Logic (Continue/Stop Discounting)

### 🔎 Key Finding:

- Footwear showed positive discount lift (+4.6%)
- Clothing, Accessories, and Outerwear showed negative lift

### 📌 Business Conclusion:

Apply discounts strategically only to Footwear and stop discounting other categories to protect margins.

### 4️⃣ Customer Segmentation (Clustering)

Customers were segmented into three groups based on spending behavior:

| Cluster | Description | Avg Spend |
| --- | --- | --- |
| High Value | Frequent high spenders | ~$75 |
| Medium Value | Moderate spenders | ~$37 |
| Low Value | Low engagement customers | ~$22 |

**Cluster Distribution:**

- High Value: 2,386 customers
- Medium Value: 1,265 customers
- Low Value: 249 customers

## 📈 Key Insights

### 🔹 Spending Behavior

- Customers aged 35–45 show higher card spending.
- Fall season recorded the highest spend.
- Credit card and digital payments dominate transactions.

---

### 🔹 Category Performance

- Clothing drives highest total revenue.
- Footwear responds positively to discounts.
- Accessories and Outerwear show diminishing returns on discounts.

---

### 🔹 Customer Segmentation

- High Value customers contribute majority of revenue.
- Medium Value segment presents upselling opportunity.
- Low Value segment requires engagement strategies.

## 💡 Strategic Recommendations

### 🎯 Discount Strategy

- Continue discounting Footwear.
- Stop discounting Clothing, Accessories, and Outerwear.
- Introduce loyalty-based rewards instead of blanket discounts.

### 🎯 Marketing Strategy

- Target High Value customers with premium bundles.
- Upsell Medium Value customers with personalized offers.
- Re-engage Low Value customers with seasonal campaigns.

### 🎯 Seasonal Strategy

- Increase marketing spend during Fall & Winter.
- Focus geographic campaigns on high-spend states.

---

## 🖥 Dashboard Development

### 📸 Dashboard Preview

![Customer_segmentation1.png](attachment:3c377f4a-29fa-480b-bf04-bb87b7808cb1:Customer_segmentation1.png)

**Figure 1: Discount Optimization Dashboard**

Highlights discount lift by category and provides actionable recommendations.

![Customer_segmentation2.png](attachment:72f13d8b-aba3-4b92-838d-0380daacbfe9:Customer_segmentation2.png)

**Figure 2: Card Spending Analysis Dashboard**

Shows spending trends by age, season, and location with interactive filters.

![Customer_segmentation3.png](attachment:e4bf2c5f-4cbc-491b-9b8e-1396ea9c97d4:Customer_segmentation3.png)

**Figure 3 Customer Segmentation Dashboard**

Displays cluster distribution, average spend, seasonal analysis, and gender breakdown to identify high-value customers.

![Customer_segmentation4.png](attachment:9a3e4c45-b3a9-4112-983f-b72cb0d09ad0:Customer_segmentation4.png)

**Figure 4: Detail Dashboard Report**

**Developed an interactive dashboard showcasing:**

- Category-wise Sales & Discount Impact
- Age-based Card Spending Trends
- Seasonal & Location Analysis
- Customer Cluster Distribution
- Cluster-based Sales Comparison

**The dashboard enables real-time filtering by:**

- Gender
- Age Group
- Category
- Season
- Location

---

## 🧠 Business Value Delivered

✔ Improved discount optimization strategy

✔ Identified high-profit customer segments

✔ Reduced margin erosion from ineffective discounting

✔ Enabled targeted marketing decisions

✔ Provided data-backed strategic recommendations

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (for clustering)
- Jupyter Notebook
- Data Visualization Techniques
- Statistical Analysis

---

## 🚀 Skills Demonstrated

- Data Cleaning & Wrangling
- Exploratory Data Analysis
- Customer Segmentation
- Business Insight Generation
- Data Visualization
- Analytical Thinking
- Strategic Recommendation Development

---
