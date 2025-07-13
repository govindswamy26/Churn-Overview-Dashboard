


# 📊 Netflix Engagement & Churn Analysis Dashboard

## 📁 Project Overview

This Power BI dashboard provides a comprehensive analysis of customer behavior, engagement patterns, and churn trends based on user activity and demographics. The aim is to help stakeholders identify key factors driving customer churn and highlight opportunities for retention and targeted marketing strategies.

---

## 📌 Objectives

- Analyze overall churn rate and retention trends
- Identify churn patterns by subscription plan, region, income, and engagement
- Understand the impact of satisfaction, support, and promotional offers on churn
- Recommend actionable insights based on user behavior

---

## 🧾 Dataset Description

The dataset contains user-level data from a streaming service with the following key columns:

- `Customer ID`
- `Subscription Length (Months)`
- `Customer Satisfaction Score (1–10)`
- `Daily Watch Time (Hours)`
- `Engagement Rate (1–10)`
- `Device Used Most Often`
- `Genre Preference`
- `Region`
- `Payment History (On-Time/Delayed)`
- `Subscription Plan` (Basic, Standard, Premium)
- `Churn Status (Yes/No)`
- `Support Queries Logged`
- `Age`
- `Monthly Income ($)`
- `Promotional Offers Used`
- `Number of Profiles Created`

---

## 📊 Key Metrics (DAX Measures)

- `ChurnRate`: % of customers who churned
- `ActiveCustomers`: Count of users with Churn = "No"
- `AvgWatchTime_Churned` / `AvgWatchTime_Retained`
- `ChurnRateByPlan`, `ChurnRateByRegion`, `ChurnRateByDevice`
- `ChurnRateByPromoUse`
- `SupportQueryGroup` and `ChurnRateBySupportLevel`

---

## 📈 Visualizations & Insights

### 🟠 **Churn Overview**
- **Donut Chart**: Churned vs Retained users
- Insight: Overall churn rate % and active customer base

### 🟦 **Churn by Subscription Plan**
- **Clustered Column Chart**
- Insight: Basic users show higher churn; Premium users churn less

### 🌍 **Churn by Region**
- **Filled Map / Bar Chart**
- Insight: Specific regions (e.g., Asia) show higher churn levels

### 📱 **Churn by Device**
- **Bar Chart**
- Insight: Mobile users have higher churn compared to desktop/TV users

### ⏱️ **Engagement & Watch Time**
- **Scatter Plot**: Engagement Rate vs Churn Probability
- **Bar Chart**: Avg Watch Time for Churned vs Retained users
- Insight: Lower engagement and watch time correlates with churn

### 💬 **Customer Satisfaction & Support**
- **Bar Chart**: Satisfaction Score Group vs Churn %
- **Line Chart**: Satisfaction Score vs Avg Support Queries
- Insight: Low satisfaction and high support queries indicate higher churn

### 🎟️ **Promotional Offers**
- **Donut Chart**: Promo Used vs Churn %
- Insight: Users with promo offers churn less → retention lever

### 💵 **Income vs Churn**
- **Box Plot**: Monthly Income by Churn Status
- Insight: Lower-income users are more prone to churn

---

## 🎛️ Interactive Features

- **Slicers**: Filter dashboard by Subscription Plan, Region, Device, Age Group, etc.
- **Drill-downs**: Analyze churn patterns across multiple dimensions
- **Tooltips**: Hover to get detailed stats per segment

---

## 📌 Recommendations

- **Retarget low-income, basic plan users** with discounts/promos
- **Improve support** for users with high query volume
- **Boost engagement** for mobile and low-watch-time users
- **Reward high satisfaction users** to improve retention

---

## 👨‍💼 Target Audience

- Marketing & Retention Teams
- Product Managers
- Business Analysts
- Customer Support Strategy Teams

---

## 🧠 Technologies Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Custom Visuals (Box and Whisker Chart by MAQ Software, Filled Map)


