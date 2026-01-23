# Banking_Finance_Transactions

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRoqbfNVLowJijAv9rbyYulJJNs_9IhQ4Cvmg&s)

📊 Overview of customer behavior, payment patterns, and transaction performance.

This repository contains visualizations and key insights from two main dashboards:
1. **Customer & Payment Behavior Analysis**
2. **Transaction Performance Overview**

## Dashboard 1: Customer & Payment Behavior Analysis

![](https://github.com/Shital9090/Banking_Finance_Transactions/blob/main/Customer%20%26%20Payment%20Behavior%20Analysis.png)

Focuses on how customers pay, account usage, and high-value transaction patterns.

### Key Metrics
- **Total Active Customers**: 615
- **Highest Single Transaction Amount**: $49,986

### Payment Method Distribution
| Payment Mode   | Percentage |
|----------------|------------|
| Cash           | 17.40%     |
| Credit Card    | 20.80%     |
| Debit Card     | 21.30%     |
| Net Banking    | 20.10%     |
| UPI            | 20.40%     |

→ **Insight**: Very balanced distribution — Debit Card slightly leads, showing diverse payment preferences.

### Transaction Amount by Account Type
- Credit  → **$8,059,202.80**
- Current → **$8,332,405.48** (highest)
- Savings → **$6,616,798.53**

→ **Insight**: Current accounts handle the largest total transaction volume.

### High-Value Transactions (Monthly Breakdown)
- Stacked bar chart showing monthly high-value transactions colored by top customer IDs
- Notable customers contributing to peaks: 1041, 1058, 1190, 1220, 1225, 1511, 1659, 1776, 1929, 1958
- Visible seasonal spikes in Feb, Apr, Jul, etc.

## Dashboard 2: Transaction Performance Overview

![](https://github.com/Shital9090/Banking_Finance_Transactions/blob/main/Transaction%20Performance%20Overview.png)

High-level summary of overall activity, trends, and top customers.

### Summary KPIs
| Metric                        | Value              |
|-------------------------------|--------------------|
| Total Customers               | 615                |
| Total Transactions            | 1,000              |
| Total Transaction Amount      | $251,285,089.48    |
| Average Transaction Value     | $251,285           |

### Account Balance Trend Over Time (2023–2025)
- Line chart showing monthly account balance fluctuations
- Started ~$8–8.5M in 2023
- Multiple peaks and dips (lowest observed ~$0.5M in 2025)
- General downward trend observed over the period

### Top 10 Customers by Transaction Amount
| Rank | Customer ID | Amount       |
|------|-------------|--------------|
| 1    | 1099        | $2,402,818   |
| 2    | 1190        | $1,770,648   |
| 3    | 1872        | $1,721,782   |
| 4    | 1659        | $1,573,339   |
| 5    | 1393        | $1,536,696   |
| 6    | 1958        | $1,504,255   |
| 7    | 1682        | $1,262,344   |
| 8    | 1220        | $1,230,881   |
| 9    | 1039        | $1,200,572   |
| 10   | 1253        | $1,175,551   |

→ **Insight**: Top customer (1099) significantly outperforms others — potential key account for retention/upsell.

## Business Insights Summary
- **Balanced payment adoption** across all popular modes (no single dominant channel)
- **Current accounts** drive the highest transaction volume
- **High concentration** — top 10 customers represent a large portion of value
- **Downward balance trend** — may indicate increased spending, withdrawals, or churn risk
- **High average transaction value** — suggests B2B, high-net-worth, or institutional activity

Feel free to contribute improved visualizations, SQL queries, or Power BI/Tableau files!

## License
MIT License (or choose your preferred license)
