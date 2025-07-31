
# 📊 Customer Churn Analysis Dashboard

This project presents an end-to-end **Customer Churn Analysis** and **Risk Profiling** using Power BI. It is designed to help telecom or subscription-based service providers identify at-risk customers, analyze behavioral and demographic patterns, and take data-driven decisions to reduce churn and improve customer retention.

## 🔍 Project Overview

The dashboard is divided into two key views:

### 1️⃣ Churn Dashboard

This page provides a high-level summary of churn-prone customers and insights into their profiles.

**Key Highlights:**
- **Customers at Risk**: 1,869 identified at-risk customers.
- **Demographics**: Balanced gender ratio, with 25% being senior citizens and 36% having partners.
- **Subscription Time**: Most churners have been subscribed for **less than 1 year (53%)**.
- **Payment Methods**: 57% use Electronic checks—this method is highly associated with churn.
- **Billing Method**: 75% of churners opted for paperless billing.
- **Contract Types**: 89% are on **Month-to-Month** contracts.
- **Service Usage**: High churn rate among users of phone service (91%), streaming services (44%), and device protection (29%).
- **Support Metrics**: 885 admin tickets and 2,173 tech tickets logged.

### 2️⃣ Risk Analysis Dashboard

This interactive dashboard drills down into the **churn risk** factors with filters for:
- **Risk of Churn**
- **Internet Service Type**
- **Contract Type**
- **Subscription Duration**

**Key Highlights:**
- **Total Customers**: 3,875
- **Overall Churn Rate**: **42.71%**
- **Churn by Internet Service**:
  - Fiber Optic: 54.61% churn rate
  - DSL: 32.22%
  - No Internet: 18.89%
- **Churn by Contract**:
  - Month-to-Month customers show the highest churn
- **Churn by Payment Method**:
  - Electronic checks again show the highest churn rate compared to other payment types
- **Churn by Subscription Time**:
  - Customers with < 1 year of service have the highest churn rate
- **Revenue Impact**:
  - Monthly charges are highest among Fiber Optic users, which correlates with their high churn rate
  - Total churned customer charges exceed **5.31M**, showing a significant revenue loss due to churn

## 📌 Combined Observations & Suggestions

### 1. New Customers More Likely to Churn
- **Observation**: 53% churned within 1 year.
- **Suggestion**: Strengthen onboarding, offer early loyalty rewards, and perform regular check-ins.

### 2. Month-to-Month Contracts Drive Churn
- **Observation**: 89% of churners are on short-term contracts.
- **Suggestion**: Encourage long-term contracts with discounts and exclusive features.

### 3. Electronic Checks Associated with High Churn
- **Observation**: 57% of churners used electronic checks.
- **Suggestion**: Promote more reliable payment options like credit cards and offer payment-based rewards.

### 4. High Churn Among Fiber Optic Users
- **Observation**: Fiber Optic customers have a 54.61% churn rate.
- **Suggestion**: Investigate service quality issues and enhance user experience for premium customers.

### 5. High Ticket Volumes = Poor Experience?
- **Observation**: 885 admin and 2,173 tech support tickets from churners.
- **Suggestion**: Use support ticket volume as a churn predictor and proactively intervene with better support.

### 6. High Paperless Billing, High Churn
- **Observation**: 75% use paperless billing.
- **Suggestion**: Use billing emails to send engagement content, retention offers, and satisfaction surveys.

### 7. Streaming & Phone Services Increase Risk
- **Observation**: 91% had phone service, 44% used streaming.
- **Suggestion**: Bundle services more attractively or enhance value-added features to improve retention.

### 8. High Revenue Loss from Churn
- **Observation**: Over 5.31M in charges lost.
- **Suggestion**: Prioritize retention of high-paying customers using predictive models.

## 💡 Tools Used
- **Power BI**: For interactive dashboard creation and data visualization
- **DAX (Data Analysis Expressions)**: For calculated columns and measures
- **Data Cleaning & Preprocessing**: Performed prior to visualization

## 📷 Dashboard Snapshots

| Churn Dashboard | Risk Analysis Dashboard |
|-----------------|--------------------------|
| ![Churn Dashboard](./churn%20dashboard.png) | ![Risk Analysis Dashboard](./Risk%20Analysis.png) |

---
