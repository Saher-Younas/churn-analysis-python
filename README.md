
# 🔍 Customer Churn Analysis Using Python

## 📌 Project Overview
This project focuses on analyzing **customer churn** using **Python**. The goal is to explore customer behavior, identify key patterns, and derive insights to help businesses improve customer retention.

### 🎯 Key Objectives:
- Understand the factors leading to customer churn.
- Perform **Exploratory Data Analysis (EDA)** to uncover trends.
- Analyze how different factors like **contract type, payment methods, and tenure** impact churn.
- Visualize key insights using **graphs and charts**.

---

## 📂 Dataset Details
- The dataset contains customer details, usage behavior, and churn status.
- **Key Features:**
  - **Customer ID**: Unique identifier.
  - **Tenure**: Duration of customer relationship.
  - **Monthly Charges** & **Total Charges**: Customer’s spending pattern.
  - **Contract Type**: Monthly, yearly, or two-year contract.
  - **Payment Method**: Different modes used for billing.
  - **Internet Service & Tech Support**: Service types availed.
  - **Churn** (Target Variable): Whether the customer left (1) or stayed (0).

---

## 🛠 Data Cleaning & Preprocessing
Before analysis, data cleaning was performed to ensure accuracy and reliability.

✅ **Handling Missing Values:**
   - Identified missing values in **Total Charges** and replaced them with the median.
   - Checked for missing values in categorical and numerical features.

✅ **Encoding Categorical Variables:**
   - Converted categorical variables (e.g., Contract Type, Payment Method) using **One-Hot Encoding**.

✅ **Data Type Corrections:**
   - Ensured that numerical columns were properly formatted.
   - Converted **Total Charges** to numerical format for analysis.

✅ **Outlier Detection:**
   - Identified potential outliers in Monthly Charges and Total Charges.
   - Used visualization methods like boxplots to assess anomalies.

---

## 🔎 Exploratory Data Analysis (EDA)
### 📊 Graphs & Insights

1️⃣ **Churn Distribution (Bar Chart)** 📉
   - A bar chart shows that **~27% of customers churned**, highlighting the need for retention strategies.
   - The remaining **73% of customers stayed**, showing opportunities for improving loyalty.

2️⃣ **Tenure vs. Churn (Stacked Bar Chart)** ⏳
   - Customers with shorter tenures **churn at a much higher rate**.
   - Long-term customers tend to stay, emphasizing the importance of retention programs.
   - The stacked bar chart clearly differentiates churn rates across different tenure groups.

3️⃣ **Churn Breakdown by Payment Method (Pie Chart)** 💳
   - **Electronic check payments** account for the highest churn percentage (~45%).
   - Auto-payment methods like **bank transfers & credit cards** have lower churn (~15-20%).
   - The pie chart visually illustrates which payment method needs intervention.

4️⃣ **Monthly Charges & Total Charges Impact (Boxplot)** 💰
   - A boxplot reveals that customers with **higher monthly charges** are more likely to churn.
   - However, customers with high **total charges** tend to stay, suggesting contract-based stability.

5️⃣ **Contract Type vs. Churn (Grouped Bar Chart)** 📜
   - **Monthly contract customers** churn the most, indicating instability in short-term plans.
   - **Two-year contracts** have the lowest churn rates, indicating long-term commitment benefits.

6️⃣ **Tech Support & Internet Service Impact (Stacked Chart)** 📞
   - Customers with **no tech support** or **basic internet service** have higher churn rates.
   - Customers with premium internet services and tech support are more likely to stay.
   - The stacked chart provides a layered breakdown of service influence on churn.

---

## 📌 Key Features Influencing Churn
From the analysis, the most significant factors affecting churn are:
- 1. **Contract Type** (Most influential factor):
      - Customers with monthly contracts have the highest churn rate (~43%), indicating that short-term plans lead to higher 
        customer turnover.
      - Two-year contracts have the lowest churn rate (~10%), suggesting that long-term plans help retain customers.
      - Actionable Insight: Encourage customers to opt for longer-term contracts by offering discounts or bundled benefits.
- 2. **Monthly Charges**:
      - Customers with higher monthly charges (> $70) are more likely to churn, whereas those with lower charges (< $30) tend to stay.
      - Boxplot Analysis: Shows a clear upward trend in churn rates as monthly charges increase.
      - Actionable Insight: Offer personalized discounts or loyalty benefits for high-billing customers to improve retention.
- 3. **Total Charges**:
      - Customers with high total charges over time are less likely to churn.
      - This suggests that long-term customers are more loyal and satisfied with the service.
      - Actionable Insight: Focus on customer onboarding and early engagement to convert new customers into long-term users.
- 4. **Tech Support Availability**:
       - Customers without tech support have higher churn rates (~38%) compared to those who have access to support.
       - Stacked Chart Analysis: Shows a strong correlation between lack of tech support and higher churn.
       - Actionable Insight: Encourage customers to opt for tech support plans by highlighting their benefits.
- 5. **Payment Method**:
       - Electronic check payments have the highest churn rate (~45%), while credit card auto-pay has the lowest churn rate (~15%).
       - Pie Chart Analysis: Shows that churn is concentrated among customers using manual or single-time payment methods.
       - Actionable Insight: Promote auto-payment methods for better convenience and reduced churn risk.

---

# 🚀 Business Impact & Recommendations
✅ Offer **incentives/discounts** for customers on monthly contracts to encourage long-term plans.
✅ Improve **customer support** and offer proactive engagement.
✅ Target high-churn segments (e.g., senior citizens, high monthly billers) with **personalized offers**.
✅ Promote **auto-pay options** to ensure seamless payment experiences.
✅ Monitor and analyze customer feedback for service improvements.

---

## 🛠 Tech Stack Used
- **Python** 🐍
- **Pandas, NumPy** (Data Analysis)
- **Matplotlib, Seaborn** (Data Visualization)
- **Jupyter Notebook** (Execution Environment)


---

## 📌 Conclusion
This project provides a comprehensive **exploratory analysis** of customer churn. The insights derived can help businesses implement **data-driven retention strategies** and reduce customer attrition rates effectively.

📢 **Want to contribute?** Feel free to enhance the analysis by adding further visualizations or insights!


