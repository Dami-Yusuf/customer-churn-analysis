# Customer Churn Analysis

## 📌 Project Overview

This project analyzes customer churn for a telecommunications company using customer-level subscription and service data.

The objective of the analysis was to identify the key factors associated with customer churn, perform exploratory analysis across relevant customer segments, and provide actionable recommendations for reducing churn.

---

## 🎯 Business Questions

The analysis was designed to answer the following questions:

1. What are the top two factors contributing to customer churn?
2. What patterns can be identified through exploratory analysis?
3. What actions can be taken to reduce customer churn?
4. What methodology was used to arrive at the findings?

---
## 📊 Dashboard Preview

The dashboard provides an executive summary of the customer churn analysis, highlighting the overall churn rate, key churn patterns across subscription type and tenure, retention-offer performance, and recommended actions.

<p align="center">
  <img src="images/dashboard.png" alt="Customer Churn Analysis Dashboard" width="900">
</p>

---

## 📊 Dataset

The dataset contains the following customer attributes:

* **Customer ID**
* **Subscription Type** — Monthly, Quarterly, Yearly
* **Tenure (Months)**
* **Monthly Charges**
* **Total Complaints in the Last 3 Months**
* **Was Retention Offer Given** — Yes / No
* **Churn** — Yes / No

---

## 🔍 Exploratory Analysis

Churn rates were analyzed across the following dimensions:

* Subscription Type
* Tenure Group
* Complaint Count
* Monthly Charge Band
* Retention Offer Status

The analysis compares churn rates across customer segments against the overall churn rate.

---

## 📈 Key Findings

### Overall Churn

The sample has an overall observed churn rate of **50%**, with **5 out of 10 customers** having churned.

* Customers with **7–12 months of tenure** recorded a **100% observed churn rate**.
* **Quarterly subscribers** recorded a **100% observed churn rate**.
* Customers who received a retention offer recorded **0% observed churn**, compared with **71.4%** among customers who did not receive an offer.
* Churn Rate by **SubscriptionType and TenureGroup** are the top 2 factors contributing to customer churn.
* Complaint count and monthly charges did not show a consistent relationship with churn in this sample.

---
## 💡 Recommendations

### 1. Strengthen Early-Tenure Retention

Prioritize proactive engagement and retention activities for customers within their first 12 months, particularly customers in the 7–12 month tenure group where the observed churn rate is highest.

Potential actions include:

* Structured onboarding programmes
* Proactive customer check-ins
* Targeted retention campaigns
* Early identification of disengaged customers

### 2. Review Higher-Risk Subscription Segments

Investigate the customer experience and value proposition for monthly and quarterly subscribers and test targeted retention interventions.

The observed difference in churn between customers who received retention offers and those who did not also provides a useful hypothesis for further testing.

---

## 🧮 Methodology

Customers were grouped according to subscription type, tenure, complaints, monthly charges, and retention-offer status. 
Churn rate was calculated as the number of churned customers divided by the total number of customers in each segment.
For each segment, churn rate was calculated as:

Churn Rate = Churned Customers / Total Customers in Segment

Segment-level churn rates were then compared with the overall churn rate to identify the strongest observed differences. 

These findings were used to develop the recommendations while accounting for the small sample size and the inability to infer causation from the available data.

---
## ⚠️ Limitations

The dataset contains only **10 customers**, so the findings should be treated as directional and should be validated using a larger customer population before making broader business decisions.
There is also a strong relationship between tenure and subscription type in this sample. The observed subscription groups correspond closely with the tenure groups, making it difficult to determine the independent effect of each factor.

In addition, observed associations should not be interpreted as proof of causation.

---
## 🛠️ Tools Used

* Microsoft Excel
* Pivot Tables
* Excel Charts
* Data Analysis

---
## 📁 Workbook Structure

The Excel workbook contains the following main sections:

| Sheet                     | Description                                                  |
| ------------------------- | ------------------------------------------------------------ |
| `Dashboard`               | Executive summary of the churn analysis                      |
| `Analysis`                | Detailed exploratory analysis, findings, and recommendations |
| `Pivott`                  | Supporting calculations and summarized analysis              |
| `churn_dataset`           | Source customer-level dataset                                |
| `churn_subscription type` | Subscription-type churn analysis                             |
| `Churn_tenure`            | Tenure-based churn analysis                                  |
| `churn_complaints`        | Complaint-based churn analysis                               |

---

## 📌 Conclusion

The analysis identified **tenure and subscription type as the two strongest observed factors associated with churn in the sample**, while retention-offer status showed an additional notable association.

The findings suggest that retention efforts should pay particular attention to **early-tenure customers and higher-risk subscription segments**, while further analysis using a larger customer population would be required to validate these patterns.

---

## 📂 Project File

**Customer_Churn_Analysis.xlsx** — Complete Excel workbook containing the analysis, supporting calculations, charts, and dashboard.
