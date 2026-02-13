
# Hospital & Pharmacy Data Analysis — Power BI

## Project Overview

This project presents a comprehensive **Hospital & Pharmacy Data Analysis** conducted using **Power BI** for a hospital. The objective was to transform messy, multi-departmental hospital data into meaningful insights that support **clinical, operational, and financial decision-making**.

The analysis focuses on **patient visits, disease patterns, pharmacy costs, and medication consumption trends**, delivered through interactive dashboards and clear written insights.

---

## Business Objectives

Hospital management sought answers to the following key questions:

1. Which diseases are most common across counties?
2. Does a higher number of patient visits always lead to higher pharmacy revenue?
3. Which drug categories generate the highest pharmacy costs?
4. Are there age groups that consume more medication than others?
5. Are some diagnoses associated with longer hospital stays but lower pharmacy spending?


## Data Description

The dataset was sourced from multiple hospital departments and included:

* **Patients**: demographic data (age, gender, county)
* **Visits**: diagnoses, departments, visit dates, length of stay
* **Pharmacy Transactions**: drug categories, quantities, unit prices, total costs

The data required cleaning, modeling, and relationship management before analysis.

---

## Data Modeling & Preparation

* Cleaned and standardized fields using **Power Query**
* Created a **star-schema style model**:

  * Patients → Visits → Pharmacy Transactions
* Added calculated fields and measures using **DAX**, including:

  * Total Visits
  * Total Pharmacy Revenue
  * Average Length of Stay
  * Age Group classification

This ensured accurate aggregation and cross-filtering across visuals.

---

## Dashboard Structure

### Page 1: Executive Dashboard

Designed for quick decision-making at a management level.

**Key Components:**

* KPI Cards:

  * Total Visits
  * Total Pharmacy Revenue
  * Average Length of Stay
* Disease trends over time (monthly)
* Pharmacy cost breakdown by drug category
* County-level comparison of visits vs pharmacy revenue

**Key Insight:**
High patient volume does not always translate into high pharmacy revenue, indicating differences in case complexity and treatment types across counties.

---

### Page 2: Deep-Dive Analysis

Focused on operational and clinical insights.

**Visuals Included:**

* Medication consumption by age group
* Scatter analysis of average length of stay vs average pharmacy cost by diagnosis
* Interactive slicers for County, Diagnosis, and Date

**Key Insight:**
Patients aged **51+** account for the highest medication costs, while some diagnoses show longer hospital stays with relatively low pharmacy spending suggesting monitoring - intensive rather than drug-intensive care.

---

## Key Findings

* **Malaria** is the highest pharmacy cost driver.
* **Older patients (51+)** consume significantly more medication.
* Some counties generate high visit volumes but lower pharmacy revenue.
* Certain diagnoses require longer stays without proportional pharmacy spending.
* Disease patterns exhibit **seasonal trends**, useful for planning and stock management.

---

## Tools used

* **Power BI Desktop**


## Author
**David Mungai**


