![INSIDER PROGRAM](https://github.com/user-attachments/assets/624e20ce-07b5-4aeb-b1cf-c5d48e524217)

# Insiders Program — High-Value Customer Segmentation for E-Commerce


## Project Overview

This project develops a **customer clustering model to identify the highest-value customers in an e-commerce business**, objectively defining who should be part of the **Insiders Program** (VIP loyalty group).

Using historical transaction data and advanced behavioral metrics, the model segments customers into **6 distinct groups**, enabling the business to:

* Identify the **elite revenue-driving customers**
* Understand behavioral differences across the base
* Predict revenue impact
* Support smarter CRM and marketing strategies

The solution outputs:

| customer_id | is_insider |
| ----------- | ---------- |
| 1314        | 1          |

And delivers a complete business report answering key strategic questions related to eligibility, value contribution, and marketing actions.

---

## Business Problem

The company wanted to build a **VIP loyalty program based on data**, not intuition. The goal was to:

* Identify **who truly deserves to be an Insider**
* Quantify their financial relevance
* Define **clear entry and removal criteria**
* Estimate the expected future revenue impact
* Support decision-making with analytical evidence

Key business challenges:

* Large heterogeneous customer base
* Need for objective, measurable VIP criteria
* Risk of investing benefits in low-value customers
* Ensuring that the Insider group truly outperforms the rest of the base

---

## Solution

A **Gaussian Mixture Model (GMM — Euclidean)** clustering approach was implemented to group customers based on:

* Gross revenue
* Purchase frequency
* Recency
* Lifetime
* Number of orders
* Return behavior
* Monetary_per_day (revenue velocity)

### Segmentation Quality

* **Silhouette Score:** **0.7048**
* **Number of clusters:** **6**
* **Distinct and interpretable behavioral profiles**

This ensures solid, well-separated customer segments suitable for strategic decision-making.

---

## Key Results

### Identification of the Insider Group (Cluster 1)

The most valuable segment identified:

* **419 customers (14.8% of the base)**
* Responsible for **≈ 62.3% of total company revenue**
* Highest revenue
* Highest purchase volume
* Highest number of orders
* Low recency (high activity)
* Longest customer lifetime
* Low return rate
* Highest **monetary_per_day**

#### Revenue Expectation

Based on their current purchasing behavior:

| Period  | Expected Revenue  |
| ------- | ----------------- |
| 30 days | ≈ **£ 1,030,000** |
| 90 days | ≈ **£ 3,100,000** |

The Insider group is not only historically important — it sustains future revenue.

---

## Cluster Summary

The model generated **6 behavioral groups** with clear strategic meaning:

* **Cluster 1 — Elite / High-Value Insiders**
  VIP core segment, extremely profitable and loyal.

* **Cluster 2 — Strong, Consistent Customers**
  Reliable, profitable, candidates to evolve into VIPs.

* **Cluster 0 — Mid-Value Opportunity Customers**
  Reasonable revenue, good base for growth strategies.

* **Cluster 4 — Low Value but Recoverable Customers**
  Cooling down but still salvageable with campaigns.

* **Cluster 3 — Very Low Value / High Churn Risk**
  Almost lost customers; engage only if low cost.

* **Cluster 5 — Problematic Customers**
  High return rate, operationally risky; do not prioritize.

---

## Eligibility & Removal Criteria

### Eligibility Criteria for Insider Program

Customers should demonstrate:

* High revenue
* High purchase recurrence
* Low recency (recent engagement)
* Strong long-term relationship
* Low return rate
* High monetary_per_day

### Removal Criteria

Customer leaves the program if:

* Recency increases significantly
* Frequency drops
* Revenue declines
* Return behavior worsens
* Engagement weakens

---

## Why the Insider Group Is Better Than the Rest

Compared to all other clusters, the Insider group clearly leads in:

* **Revenue**
* **Orders**
* **Volume purchased**
* **Lifetime**
* **Activity**
* **Revenue velocity**
* **Low return rate**

> They buy more, buy more often, stay longer, generate more money, and cause fewer problems.

This objectively confirms that they are the most strategic and profitable customers.

---

## Marketing Strategy Recommendations

### Cluster 1 — Insiders

* Exclusive benefits
* Priority access
* Loyalty rewards
* Avoid heavy discounts

### Cluster 2

* Loyalty reinforcement
* Upsell → move to Insider
* Frequency campaigns

### Cluster 0 & 4

* Moderate incentives
* Reactivation campaigns
* Bundles and targeted offers

### Cluster 3

* Low-cost reactivation only

### Cluster 5

* Operational monitoring
* No premium benefits

---

## Conclusion

This project successfully delivered a **data-driven VIP program strategy**, enabling the company to:

1. Identify the most valuable customers
2. Quantify their financial relevance
3. Define objective eligibility rules
4. Support strategic CRM and marketing decisions
5. Maximize revenue and retention
6. Reduce waste and business risk

The model transforms customer management into a **strategic, intelligent, and profit-driven process**, proving the real value of Data Science in business operations.
