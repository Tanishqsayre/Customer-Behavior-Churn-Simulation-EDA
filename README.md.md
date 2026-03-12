# Customer Behavior & Churn Analysis

### End‑to‑End Exploratory Data Analysis for Customer Retention Strategy

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![EDA](https://img.shields.io/badge/Analysis-Exploratory%20Data%20Analysis-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Dataset](https://img.shields.io/badge/Dataset-15K%2B%20Customers-lightgrey)

------------------------------------------------------------------------

# Project Overview

Customer churn is one of the most critical challenges for
subscription‑based businesses. When customers stop using a service, it
directly impacts revenue, growth, and long‑term sustainability.

This project performs **comprehensive Exploratory Data Analysis (EDA)**
on a simulated **Customer Behavior & Churn dataset** to identify
behavioral, engagement, and service-related factors that influence
churn.

The analysis focuses on discovering patterns in:

-   Customer demographics
-   Engagement behavior
-   Service usage
-   Satisfaction levels
-   Subscription and billing patterns

The goal is to **identify early churn signals and generate actionable
business insights** that can help organizations improve customer
retention strategies.

------------------------------------------------------------------------

# Business Problem

Customer acquisition is expensive, and losing existing customers
significantly affects profitability. Organizations need a **data-driven
approach** to understand why customers leave and how to prevent it.

Key business questions addressed in this project:

-   Which customers are most likely to churn?
-   What behavioral patterns indicate churn risk?
-   How does satisfaction impact retention?
-   What role do subscription plans and pricing play?
-   Can we identify early churn warning signals?
-   How can businesses proactively reduce churn?

------------------------------------------------------------------------

# Project Objectives

The main objectives of this analysis are:

-   Analyze customer demographics and service usage patterns
-   Identify key drivers of customer churn
-   Evaluate engagement and inactivity patterns
-   Study the impact of satisfaction and support interactions
-   Perform churn risk segmentation
-   Generate strategic business recommendations

------------------------------------------------------------------------

# Dataset Information

**Dataset:** Customer Behavior & Churn Simulation Dataset\
**Records:** 15,000+ customers\
**Source:** Kaggle\
**Type:** Simulated subscription service data

### Dataset Includes

-   Customer demographics
-   Subscription details
-   Service usage behavior
-   Billing information
-   Customer support interactions
-   Satisfaction ratings
-   Churn status

------------------------------------------------------------------------

# Tech Stack

  Category          Tools
  ----------------- ---------------------
  Programming       Python
  Data Analysis     Pandas, NumPy
  Visualization     Matplotlib, Seaborn
  Environment       Jupyter Notebook
  Version Control   Git & GitHub

------------------------------------------------------------------------

# Project Workflow

## 1. Data Loading

The dataset is loaded using Pandas for analysis.

\`\`\`python import pandas as pd

df = pd.read_csv("customer_churn_dataset.csv") df.head()

------------------------------------------------------------------------

## 2. Data Cleaning

Key preprocessing steps:

-   Missing value detection
-   Duplicate record removal
-   Data type validation
-   Statistical summary analysis

These steps ensure **high data quality and reliability** for analysis.

------------------------------------------------------------------------

## 3. Feature Engineering

New features were created to enhance behavioral analysis.

### Customer Tenure

Calculated from signup date to determine customer lifecycle stage.

Examples:

-   Tenure in days
-   Tenure in months

### Engagement Metrics

Derived metrics include:

-   Average Monthly Spend
-   Usage Intensity
-   Lifecycle Stage Classification

These features help understand **customer lifecycle and loyalty
patterns**.

------------------------------------------------------------------------

# Exploratory Data Analysis

## Target Variable Analysis

Churn is defined as:

  Value   Meaning
  ------- -------------------
  0       Customer Retained
  1       Customer Churned

EDA includes:

-   Churn distribution
-   Percentage comparison
-   Visualization using count plots and pie charts

------------------------------------------------------------------------

# Customer Demographics Analysis

Demographic variables analyzed:

-   Age
-   Gender
-   Region
-   Income level

Key finding:

**Demographics have weaker impact on churn compared to behavioral
indicators.**

------------------------------------------------------------------------

# Customer Behavior Analysis

Behavioral variables examined:

  Feature              Description
  -------------------- ------------------------------
  Usage Frequency      Service usage frequency
  Session Duration     Average session length
  Last Login Days      Customer inactivity
  Support Tickets      Customer complaints
  Satisfaction Score   Customer satisfaction rating

Behavioral patterns show **clear differences between retained and
churned users.**

------------------------------------------------------------------------

# Subscription & Billing Analysis

Features analyzed:

-   Subscription Type
-   Payment Method
-   Monthly Charges
-   Total Spending
-   Discount Usage
-   Promotional Response

Insights help determine how **pricing and promotional incentives affect
retention.**

------------------------------------------------------------------------

# Univariate Analysis

Univariate analysis explores distribution of individual variables:

-   Age
-   Monthly Charges
-   Total Spending
-   Usage Frequency
-   Session Duration
-   Inactivity Duration
-   Satisfaction Score

This analysis helps detect:

-   Skewed distributions
-   Outliers
-   Engagement trends

------------------------------------------------------------------------

# Feature Impact on Churn

Key churn drivers identified:

1.  Satisfaction Score
2.  Customer Inactivity
3.  Usage Frequency
4.  Support Tickets
5.  Subscription Plan

Low satisfaction and high inactivity significantly increase churn risk.

------------------------------------------------------------------------

# Correlation Analysis

A correlation matrix and heatmap were used to identify relationships
between features.

Strong correlations observed with:

-   Satisfaction score
-   Inactivity levels
-   Support ticket frequency
-   Usage frequency

------------------------------------------------------------------------

# Churn Risk Segmentation

Customers were grouped into churn risk categories based on behavior.

  Segment       Characteristics
  ------------- ----------------------------------------------
  Low Risk      High engagement and satisfaction
  Medium Risk   Moderate activity
  High Risk     Low usage, low satisfaction, high inactivity

This segmentation enables **proactive retention strategies.**

------------------------------------------------------------------------

# Key Insights

### Customer Satisfaction Is the Strongest Predictor

Customers with low satisfaction scores show significantly higher churn
probability.

### Low Engagement Signals Future Churn

Customers who rarely use the platform are more likely to leave.

### Inactivity Is an Early Warning Signal

Customers inactive for long periods have higher churn risk.

### Support Issues Increase Churn

Customers with many support tickets tend to churn more often.

### Long-Term Customers Are More Loyal

Customers with longer tenure and higher spending show stronger
retention.

### Promotions Improve Retention

Customers responding to promotions show lower churn rates.

------------------------------------------------------------------------

# Business Recommendations

### Improve Customer Satisfaction

-   Collect feedback regularly
-   Improve service quality
-   Resolve issues faster

### Increase Customer Engagement

-   Personalized notifications
-   Feature recommendations
-   Behavioral targeting

### Monitor Inactive Users

Identify and re-engage inactive customers with reminders or special
offers.

### Improve Customer Support

Faster response time and better resolution processes reduce churn.

### Target High-Risk Customers

Use churn risk segmentation to provide personalized retention offers.

------------------------------------------------------------------------

# Conclusion

This project demonstrates how **Exploratory Data Analysis (EDA)** can
reveal hidden patterns in customer behavior and identify key churn
drivers.

Important churn indicators include:

-   Customer satisfaction
-   Platform engagement
-   Inactivity duration
-   Support interactions
-   Spending patterns

Using these insights, organizations can implement **data-driven
retention strategies**, improve customer experience, and maximize
long-term customer value.

------------------------------------------------------------------------

# Repository Structure

customer-churn-analysis

data/ customer_churn_dataset.csv

notebooks/ churn_analysis.ipynb

visualizations/ charts

README.md

requirements.txt

------------------------------------------------------------------------

# Author

**Tanishq Sayre**\
Aspiring Data Analyst \| Python \| Data Analysis \| EDA \| Visualization

------------------------------------------------------------------------
