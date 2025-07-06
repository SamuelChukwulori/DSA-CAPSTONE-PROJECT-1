
# 📊 Amazon Product Review Analysis

## 📝 Project Overview

This project is part of the DSA Data Analysis Capstone and focuses on analyzing product and customer review data scraped from Amazon. The goal is to generate actionable insights for sellers — helping them improve products, enhance marketing strategies, and boost customer satisfaction. Each row in the dataset represents a unique product, with customer engagement, pricing, and ratings included.

---

## 📂 Dataset Description

The dataset contains the following:

- Product details (name, category, price, discount, rating)
- Customer engagement metrics (review counts, review titles, review content)
- Multi-level product categorization (Category 1 to Category 5)

Each row represents a **unique product**, and review-related data is aggregated.

---

## 🛠 Tools Used

- **Microsoft Excel** [Download Here](https://excel.cloud.microsoft/?utm_source=chatgpt.com)
  - Power Query (data transformation)
  - Pivot Tables (for analysis)
  - Formulas & Calculated Columns
  - Charts & Dashboard Visualization

---

## 📈 Key Analytical Tasks

The following business questions were answered:

1. Average discount percentage by product category
2. Number of products listed under each category
3. Total number of reviews per category
4. Products with the highest average ratings
5. Average actual vs discounted price by category
6. Products with the highest number of reviews
7. Count of products with 50% or more discount
8. Distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)
9. Total potential revenue by category (actual price × rating count)
10. Number of unique products per price range bucket
11. Relationship between rating and level of discount
12. Count of products with fewer than 1,000 reviews
13. Categories with products offering the highest discounts
14. Top 5 products by combined impact of rating × number of reviews

---

## 🔧 Project Steps

1. **Data Cleaning**:
   - Removed blanks, formatted price/discount fields
   - Converted columns to usable formats
   - Checked for consistency across columns
   - Removed Duplicate Product Id
   - After Removing Duplicate Product Id, I also removed 3 additional product Id, because the rows contained blanks in columns relevant to the Analysis

2. **Data Transformation**:
   - Used Power Query to unpivot `Category 1–5` into a single column
   - Created calculated columns such as:
     - `Combined Score = Rating × Rating Count`
     - `Potential Revenue = Actual Price × Rating Count`
     - Price Range Buckets for grouping

3. **Analysis**:
   - Used Excel Pivot Tables for aggregation, grouping, filtering
   - Answered all 14 project questions using data slicing and calculated fields

4. **Dashboard Creation**:
   - Visualized key metrics using:
     - Bar charts, scatter plots, KPI cards, and slicers
     - Highlighted top-performing products and categories

---

## 💡 Insights

- **Most Impactful Product** had a combined score of **1.88 million**, reflecting both high rating and high number of reviews.
- **High Discounts ≠ High Ratings**: No strong correlation between discount and product rating.
- **Top Categories by Discount**: *Computers & Accessories*, *Electronics*, and *Home Improvement*
- **Underexposed Products**: Several high-rated products had low review counts — marketing opportunity.
- **Revenue Potential**: Categories with higher unit prices and review counts offer stronger long-term revenue.

---

## 🧠 Recommendations to the Management

Based on the insights from the Amazon product review analysis, the following data-driven recommendations are proposed to improve product performance, customer engagement, and revenue growth:

### 🎯 1. Boost Visibility of Under-Reviewed Products
- Over **58% of products** have fewer than **1,000 reviews**.
- These products likely suffer from low exposure or discoverability.
- 📌 **Action:** Invest in advertising campaigns, sponsored product placements, or influencer partnerships to increase visibility and reviews.

---

### 🎯 2. Optimize Discounting Strategy
- Products with **very high discounts (≥50%)** often show **lower average ratings**.
- This suggests a risk of reduced product quality or customer satisfaction.
- 📌 **Action:** Avoid over-discounting products with poor review history. Instead, apply strategic discounts to **well-rated products** to maintain brand value while encouraging conversions.

---

### 🎯 3. Prioritize High-Impact Categories and Products
- Categories like **Electronics**, **Books**, and **Computers** have strong revenue potential based on their **review volume and pricing**.
- 📌 **Action:** Allocate more marketing resources to these categories and use high-performing products as flagships in promotions.

---

### 🎯 4. Promote Top Performing Products
- The **top 5 products** by (rating × review count) are strong indicators of success.
- 📌 **Action:** Feature these products prominently on landing pages, email campaigns, and product bundles.

---

### 🎯 5. Reevaluate Underperforming Segments
- Some categories show **high discounting and low engagement**, indicating weak customer interest.
- 📌 **Action:** Reassess the value proposition of these segments — consider discontinuation, repositioning, or product improvements.

---

> These recommendations aim to help management improve profitability, product quality, and customer satisfaction in alignment with data-driven decisions.


---


### 📂 File Uploaded:
- [Amazon Case Study.xlsx](Amazon%20Case%20Study.xlsx)

### 🧾 Workbook Contents:
- **Cleaned Dataset** – The preprocessed data used for analysis
- **Pivot Table** – Used to aggregate metrics such as average rating, sales by category, and price buckets
- **Dashboard** – Final visual report combining charts and filters

> 📌 This Excel report sh

