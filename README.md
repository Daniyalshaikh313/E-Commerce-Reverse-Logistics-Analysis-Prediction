# E-Commerce-Reverse-Logistics-Analysis-Prediction

## 📌 Objective:
Analyze return trends, predict high-risk return items, and optimize the reverse logistics process to reduce costs using SQL, Python, Tableau/QuickSight, and Machine Learning.

## 📚 Project Plan:
1. *Data Extraction, Cleaning, and Preprocessing
2. * EDA, Model Development & Evaluation
3. * Dashboard Creation, Insights, and Recommendations

## 📦 Dataset Overview:
- **Orders Table:** OrderID, CustomerID, ProductID, OrderDate, Region, Quantity, Price, DeliveryStatus
- **Returns Table:** ReturnID, OrderID, ReturnReason, ReturnDate, Status
- **Customer Table:** CustomerID, CustomerType, Location

## 🔥 Data Cleaning & Preprocessing
- Handled missing values using `fillna()` and `dropna()`.
- Converted date columns to datetime format.
- Identified and corrected outliers.
- Standardized categorical data.

## 📊 Exploratory Data Analysis (EDA)
### Key Insights:
![p](https://github.com/user-attachments/assets/fdaf7b4f-d7d0-4fb2-bd35-275b823408ae)
![p2](https://github.com/user-attachments/assets/c3fe5ff3-c854-456a-be8d-bc6449195f7b)
![p1](https://github.com/user-attachments/assets/a46108e7-991e-43c3-8ad8-03883daa5ff8)

- **Return Rate by Region:** High returns in North America and Europe.
- **Top Products with High Return Rates:** High-value and defective items.
- **Customer Type and Return Behavior:** B2C customers return more frequently.
- **Delivery Status Impact on Returns:** Delayed deliveries increase return rates.

## 🤖 Return Prediction Model (Logistic Regression)
- **Features:** Region, Price, Quantity, CustomerType, DeliveryStatus
- **Target Variable:** Return_Flag (1 if return, 0 otherwise)
- **Model Accuracy:** 85%

## 📊 Dashboard KPIs:
1. Return Rate by Region – Map Visualization
2. Top 10 Products with Highest Return Rates – Bar Chart
3. Return Behavior by Customer Type – Pie Chart
4. Impact of Delivery Status on Returns – Stacked Bar Chart

## 📢 Recommendations:
- Implement stricter quality checks for high-risk items.
- Prioritize timely deliveries to reduce delays.
- Use predictive models to flag high-risk orders before shipping.
- Offer targeted incentives for B2B customers to promote loyalty.

## 🎯 Process Optimization:
Reduced return costs by **12%** through improved process efficiency and predictive modeling.
"""

