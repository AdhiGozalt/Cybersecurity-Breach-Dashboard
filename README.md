# Cybersecurity Breaches Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Analysis-yellow)
![Data Analysis](https://img.shields.io/badge/Focus-Data%20Analysis-blue)
![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-red)

## Overview

This project analyzes historical cybersecurity breach incidents to identify
patterns in breach frequency, exposed records, leak methods, and affected
organization types.

The analysis was developed using Microsoft Power BI, with the goal of
transforming raw cybersecurity breach data into an interactive dashboard
that makes key patterns and trends easier to understand.

---

## Dashboard Preview

![Cybersecurity Breaches Dashboard]([screenshots/dashboard-overview.png])

> **Note:** The dashboard screenshot above provides an overview of breach
> incidents, exposed records, breach methods, organization types, and trends
> over time.

---

## Key Metrics

| Metric | Value |
|---|---:|
| Total Breaches | 73 |
| Records Exposed | ~96 Million |

---

## Objectives

The main objectives of this analysis are:

- Analyze the number of cybersecurity breaches over time.
- Identify the most common methods of data leakage.
- Analyze the number of exposed records.
- Identify organization types most affected by breaches.
- Provide an interactive dashboard for exploring cybersecurity breach data.
- Transform raw data into actionable analytical insights.

---

## Key Analysis

### 1. Breaches Over Time

The dashboard analyzes the distribution of reported cybersecurity breaches
across different years.

This visualization helps identify periods with relatively higher or lower
numbers of recorded breach incidents.

---

### 2. Breach Methods

The analysis categorizes breaches based on the reported method of leakage,
including:

- Hacked
- Lost / Stolen Computer or Media
- Poor Security
- Accidentally Published
- Inside Job

This allows the frequency of different breach methods to be compared.

---

### 3. Records Exposed

The project analyzes the number of records affected by each breach.

The analysis helps distinguish between:

- Frequency of breach incidents
- Scale of records exposed

A breach occurring less frequently can still have a significant impact if it
involves a large number of exposed records.

---

### 4. Target Organization Types

The dashboard analyzes exposed records according to organization type,
including categories such as:

- Financial
- Healthcare
- Government
- Military
- Retail
- Academic
- Web
- Technology

This provides an overview of which types of organizations experienced the
largest exposure of records within the dataset.

---

## Interactive Dashboard

The dashboard includes several interactive components:

- **Year filter** — filter breach incidents by year.
- **Method of Leak filter** — analyze specific breach methods.
- **Total Breaches KPI** — display the total number of recorded breaches.
- **Records Exposed KPI** — display the total number of exposed records.
- **Breach Method Analysis** — compare breach methods.
- **Organization Type Analysis** — compare affected organization types.
- **Timeline Analysis** — examine breach trends over time.
- **Detailed Breach Table** — inspect individual breach records.

---

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Visualization
- Exploratory Data Analysis

---

## Data Analysis Process

The project follows a general data analysis workflow:

```text
Raw Dataset
     ↓
Data Preparation
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Exploratory Analysis
     ↓
Data Visualization
     ↓
Interactive Dashboard
     ↓
Insights
