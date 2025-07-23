# 📊 Executive Summary: Customer Churn Analysis

This project aims to understand customer churn behavior within a telecom company using exploratory data analysis (EDA) techniques. It highlights churn patterns across demographics, contract types, service usage, and payment methods to uncover actionable insights that can support customer retention strategies.

## 🔍 Key Findings & Insights

### 1. Churn Overview
- Out of the total customers analyzed, **26.54%** have churned, while **73.46%** have stayed.
- This **1 in 4 churn rate** indicates a critical business concern and the need for targeted retention strategies.

### 2. Demographic Analysis

#### Senior Citizens
- Approximately **42%** of senior citizens have churned.
- Only **24%** of non-senior citizens churned.
- 📌 **Insight**: Age is a significant predictor—senior citizens are more than 1.5x likely to leave the service.

#### Gender and Partner Status
- Gender has **minimal effect** on churn (almost equally distributed).
- Customers **without a partner** are more likely to churn (**32%**) than those **with a partner** (**20%**).

### 3. Tenure and Churn Relationship
- Sharp drop in churn observed after the **first 12 months** of service.
- Customers in their **first 1–6 months** show high churn rates (**~50–60%**).
- Customers with a **tenure of 24+ months** churn less than **15%**.
- 📌 **Insight**: Early engagement programs and onboarding experience are key to improving retention.

### 4. Contract Types and Churn
- **Month-to-Month**: **43.9%** churn rate.
- **One-Year Contracts**: **11.5%** churn.
- **Two-Year Contracts**: Lowest churn at **2.8%**.
- 📌 **Insight**: Long-term contracts strongly indicate loyalty and satisfaction.

### 5. Internet & Streaming Services

#### Internet Service
- **Fiber Optic** users have the **highest churn** (~41%).
- **DSL** users churn at ~19%.
- **No Internet** users show a very low churn (~7%).
- 📌 Fiber users may be dissatisfied—possibly due to pricing or quality.

#### Streaming Services
- Users of **Streaming TV** and **Streaming Movies** churn at ~38%.
- Customers **not using streaming services** churn at ~21%.
- 📌 Streaming users may be more tech-savvy and exposed to competitors.

### 6. Online & Tech Support Services
- Customers **without Online Security, Backup, Tech Support, or Device Protection** churn at **~40–45%**.
- Those **with these services** churn at only **15–20%**.
- 📌 These features offer value and satisfaction, supporting retention.

### 7. Phone Service & Multiple Lines
- Customers **without Phone Service** or **Multiple Lines** churn slightly more.
- Difference is **less pronounced** compared to other service-related features.

### 8. Payment Method
- **Electronic Check** users: Highest churn rate at **45.5%**.
- **Mailed Check**: ~19% churn.
- **Bank Transfer (auto)** and **Credit Card (auto)**: ~15–16% churn.
- 📌 Automatic payments encourage commitment and reduce churn.

## 📈 Visualization Highlights
- 9 well-structured Seaborn **count plots** arranged in a 3x3 grid.
- **Blue and Orange colors** clearly differentiate churn status.
- **Horizontal legends** and **rotated tick labels** improve readability.
- Visuals effectively highlight churn trends across multiple service dimensions.

## 🧩 Recommendations Based on Analysis
- Target **Month-to-Month** and **Electronic Check** users with **retention incentives**.
- Offer **discounts for contract upgrades** to encourage long-term commitment.
- Promote **value-added services** like security and tech support.
- Strengthen **onboarding and engagement programs** during the first 6 months.
- Investigate **Fiber Optic issues** to improve satisfaction and reduce churn.

