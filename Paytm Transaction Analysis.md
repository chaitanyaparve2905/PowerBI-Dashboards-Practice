# 💸 Paytm Transaction Analysis Dashboard

A dynamic Power BI dashboard that visualizes Paytm's transaction performance across multiple user metrics. This project provides key insights into user behavior, revenue patterns, city-wise transaction volumes, and time-slot engagement to support data-driven decision-making.

---

## 📊 Project Overview

This Power BI dashboard presents a comprehensive analysis of Paytm's transaction data, focusing on:

- Transaction Value & Revenue Insights
- User Retention, Acquisition & Churn Trends
- User Segmentation by Gender, Age Group & Type
- Geographic Distribution of Transactions
- Time-Slot Based Engagement Patterns
- Performance by Transaction Type

Key findings:
- Chennai leads in transaction volume.
- Morning hours show the highest transaction value.
- Middle-aged and senior users dominate transaction spending.
- Peer-to-peer and bill payments generate the most revenue per transaction.

---

## 🛠 Installation

### Requirements
- Power BI Desktop – [Download here](https://powerbi.microsoft.com/desktop/)
- Dataset – [Paytm.xlsx](https://github.com/user-attachments/files/20591782/Paytm.xlsx)

---
## 🧭 Usage
Navigate the dashboard using interactive visuals:

- Summary Cards: Show total transaction value, revenue, and user metrics.

- Bar & Column Charts: Reveal top-performing cities and transaction types.

- Pie Charts: Illustrate gender distribution and retention rates.

- Time Series Charts: Track transaction activity across different hours and days.

- Maps: Analyze geographic profit distribution (if included).
---
## Sample Dashboard Preview
![Image](https://github.com/user-attachments/assets/67da050f-65ef-48a4-b60e-72104d5e441c)

---
## 🧮 DAX Formulas and Additional Information
DAX Formulas

1. 
Age Group = SWITCH(
    TRUE(),
    Paytm[User Age] <= 25, "Young",
    Paytm[User Age] > 25 && Paytm[User Age] <= 45, "Middle-Aged",
    Paytm[User Age] > 45, "Senior"
)

2. 
Time Slot = SWITCH(
    TRUE(),
    Paytm[Time of Day] < 12, "Morning",
    Paytm[Time of Day] >= 12 && Paytm[Time of Day] < 18, "Afternoon",
    Paytm[Time of Day] >= 18, "Evening"
)

3. 
Transaction Day = WEEKDAY(Paytm[Date], 2)

Additional Details
- Data was cleaned and transformed using Power Query.
- Nulls, inconsistencies, and type mismatches were resolved.
- Calculated columns were created to enable filtering by age group, time slot, and day of the week.


## 📬 Contact Information

Have questions or suggestions? Feel free to reach out:

Maintainer: Chaitanya Parve

LinkedIn: www.linkedin.com/in/chaitanyaparve29

GitHub: https://github.com/chaitanyaparve2905
