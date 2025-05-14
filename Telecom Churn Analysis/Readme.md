# 📊 Telco Inc. Churn Analysis Dashboard – May 2025
![Screenshot 2025-05-14 134019](https://github.com/user-attachments/assets/a89ab3de-bade-40d9-97f2-b82af1701503)

- An interactive dashboard that analysis customer churn behaviour for **7032 Customers** of **Telco Inc.**.
- This Dashboard indentifies churn behaviours across demographics, services, contracts and payment preferences.
----
## Objectives 
To explore churn patterns and provide **actionable business decisions** that can help reduce the **26.6% churn rate**, retain customers, and protect revenue.

---

## 📦 Key KPIs

| Metric                     | Value     |
|----------------------------|-----------|
| 📈 Total Customers         | 7,032     |
| ❌ Customers Who Left      | 1,869     |
| 🔻 Churn Rate              | 26.6%     |
| 📅 Avg. Customer Tenure    | 32 months |
| 💳 Avg. Monthly Charges    | $64.8     |
| 💸 Revenue Loss (Est.)     | 17.8%     |

---
### 👤 Demographics & Churn

- **Gender Distribution**:
  - Female: 930 churned (49.76%)
  - Male: 939 churned (50.24%)  
  → Gender does **not significantly impact** churn.

- **Senior Citizens**:
  - 6.8% churn rate – higher vulnerability due to fixed income or tech discomfort

- **Partner Status**:
  - 9.5% churn from customers with partners

- **Dependents**:
  - 4.6% churn from customers with dependents

---
### 🔌 Services & Churn Impact

- **Phone Service**: 24.2% churn – most commonly used service
- **Streaming TV & Movies**: Each 11.6%
- **Device Protection**: 7.8%
- **Online Backup**: 7.4%
- **Tech Support**: 4.4%
- **Online Security**: 4.2%
- **No Internet Service**: Only 1.6% churn – lowest risk

> 🔒 **Customers without Online Security or Tech Support are more likely to churn.**

- **Multiple Lines**:
  - Yes: 12.1%
  - No: 12.1%
  - ➤ Suggests line count doesn't directly impact churn

---
### 🌐 Internet Service Type & Churn

- **Fiber Optic**: Highest churn (over 1,000 customers)
- **DSL**: Moderate churn
- **No Internet**: Least churn (~100)

> Fiber Optic users have the **highest dissatisfaction**, possibly due to cost or reliability issues.

---
### 💳 Payment Methods & Churn

- **Electronic Check**: Highest churn – dominant method among leavers
- **Paperless Billing**:
  - Yes: Higher churn rate
  - No: More loyal

> Customers using **electronic checks and paperless billing** are **more likely to churn**.

---
## 🧠 Business Recommendations

| Focus Area        | Recommendation                                              | Estimated Impact |
|-------------------|--------------------------------------------------------------|------------------|
| 📄 Contract Type   | Encourage annual/two-year contracts over month-to-month     | ↓ churn by ~20%  |
| 🔐 Security/Support| Bundle tech support + online security at a discount         | ↓ churn by ~30%  |
| 🌐 Fiber Optic     | Survey pain points; consider loyalty offers                 | ↑ satisfaction   |
| 💳 Payment Methods | Incentivize auto-pay via card/transfer over e-check         | ↓ payment churn  |
| 🤝 New Users       | Provide onboarding + discount for first 3 months            | ↑ early retention|

---

## 🖼️ Dashboard Interactions

- **Contract Type Filter**: Slice by Month-to-Month, One-Year, Two-Year
- **Churn KPIs**: Instant view of total customers, churn %, and revenue risk

---

## 🛠️ Tools Used

- 🧩 Power BI Desktop
- 📊 Power Query Editor
- 📐 DAX Measures & KPIs
- 🗃️ Excel Source Data

---
