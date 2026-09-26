# Customer Churn Analysis

## Overview

This project analyzes customer churn for a telecommunications company using a sample customer dataset.

The objective was to identify the key factors associated with customer churn, perform exploratory analysis, and provide actionable recommendations for reducing churn.

## Dataset

The dataset contains customer-level information including:

* Customer ID
* Subscription Type
* Tenure
* Monthly Charges
* Total Complaints in the Last 3 Months
* Retention Offer Status
* Churn Status

## Analysis Performed

The analysis examined churn rates across:

* Subscription type
* Customer tenure groups
* Complaint count
* Monthly charge bands
* Retention offer status

Churn rates were calculated for each segment and compared with the overall churn rate.

## Key Findings

* The overall observed churn rate in the sample was **50%**.
* Customers with **7–12 months of tenure** recorded a **100% observed churn rate**.
* **Quarterly subscribers** recorded a **100% observed churn rate**.
* Customers who received a retention offer recorded **0% observed churn**, compared with **71.4%** among customers who did not receive an offer.
* Complaint count and monthly charges did not show a consistent relationship with churn in this sample.

## Recommendations

### 1. Strengthen early-tenure retention

Prioritize proactive engagement and retention interventions for customers within their first 12 months, particularly customers in the 7–12 month tenure group.

### 2. Review high-risk subscription segments

Investigate the customer experience and value proposition for monthly and quarterly subscribers and test targeted retention interventions.

## Methodology

Customers were grouped according to subscription type, tenure, complaints, monthly charges, and retention-offer status. Churn rate was calculated as the number of churned customers divided by the total number of customers in each segment.

The analysis was then used to identify the strongest observed patterns and develop recommendations.

## Limitation

The dataset contains only **10 customers**, so the findings should be treated as directional and should be validated using a larger customer population before making broader business decisions.

## Tools

* Microsoft Excel
* Pivot Tables
* Excel Charts
* Data Analysis
