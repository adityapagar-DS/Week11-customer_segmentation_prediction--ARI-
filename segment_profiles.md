# Customer Segment Profiles

## Overview

Customers were segmented using K-Means and Hierarchical Clustering based on:

- Tenure
- Monthly Charges
- Total Charges
- Contract Type
- Payment Method
- Senior Citizen Status

Data was standardized before clustering to ensure fair contribution of all features.

Three distinct customer segments were identified.

---

## Segment 0 – Premium Loyal Customers

**Characteristics:**
- High Tenure
- High Total Charges
- Mostly Long-Term Contracts (One Year / Two Year)
- Lower churn probability

**Behavior:**
- Stable customers
- High lifetime value
- Less price-sensitive

**Business Strategy:**
- Offer loyalty rewards
- Provide premium services
- Upsell high-value products
- Focus on retention programs

---

## Segment 1 – High-Risk / Price-Sensitive Customers

**Characteristics:**
- Low Tenure
- Month-to-Month contracts
- Higher churn rate
- Moderate Monthly Charges

**Behavior:**
- Short-term commitment
- Likely to switch providers
- Sensitive to pricing and service issues

**Business Strategy:**
- Provide retention discounts
- Offer contract upgrade incentives
- Improve onboarding experience
- Proactive customer support

---

## Segment 2 – Moderate Value Stable Customers

**Characteristics:**
- Medium Tenure
- Balanced Monthly Charges
- Mix of contract types
- Moderate churn probability

**Behavior:**
- Stable but not deeply loyal
- Potential for upselling

**Business Strategy:**
- Targeted marketing campaigns
- Bundle offers
- Personalized engagement programs

---

## Clustering Insights

- Scaling was applied before clustering to avoid bias from large numerical values.
- CustomerID was removed as it carries no predictive meaning.
- Clusters show meaningful behavioral segmentation.
- Segment-based prediction models improve churn targeting accuracy.

---

## Strategic Recommendation

Instead of applying one churn strategy for all customers:

- Apply segment-specific churn prediction models
- Prioritize high-risk segments
- Increase marketing efficiency
- Improve ROI through targeted retention

---

End of Segment Analysis
