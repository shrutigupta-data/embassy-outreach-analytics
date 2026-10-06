# 🌍 Embassy Outreach Data Management & Analytics

### Data Management & Analytics Associate — Assessment Project

> **Turning raw outreach data into actionable leadership insights through Excel analytics, dashboarding, and data-quality assessment.**

---

<p align="center">

<img src="https://img.shields.io/badge/Excel-Leadership%20Dashboard-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
<img src="https://img.shields.io/badge/Data%20Quality-Review-5C6BC0?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Analytics-Business%20Insights-8E44AD?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AI-Assisted%20Analysis-FF6F00?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Status-Completed-2E7D32?style=for-the-badge"/>

</p>

---

## 📌 Project Overview

This project was completed as part of a **Data Management & Analytics Associate** assessment based on an Embassy Outreach Database.

The objective was to transform raw operational data into a **clear, leadership-focused analytical view** that enables management to understand outreach progress, assess engagement, identify data-quality gaps, monitor regional performance, and support prioritisation.

The project focuses on:

**📊 Dashboard Development**
**🔎 Data Quality Assessment**
**🌎 Regional & Engagement Analysis**
**🤖 AI-Assisted Analysis**
**💡 Management Recommendations**

The assessment specifically emphasises accuracy, analytical thinking, attention to detail, dashboard usability, effective AI use, and clarity of communication.

---

# 🎯 Business Objective

The leadership team required a concise and actionable overview of embassy outreach activities.

The analysis was designed to answer four key questions:

> **1. What is the current status of outreach?**
> **2. How engaged are embassies?**
> **3. Which regions require attention?**
> **4. What data-quality issues could affect decision-making?**

This aligns with the stated management requirements of the assessment.

---

# 📂 Dataset

The source dataset contains:

| Metric                           |  Value |
| -------------------------------- | -----: |
| 📄 Outreach Records              | **88** |
| 🏛️ Unique Non-Blank Embassy IDs | **85** |
| 🧩 Data Fields                   | **16** |

### Main Data Fields

* Embassy ID
* Country
* Region
* Contact Person
* Designation
* Email
* Phone
* Outreach Status
* Outreach Owner
* First Contact Date
* Last Contact Date
* Next Follow-up Date
* Interactions
* Engagement Level
* Channel
* Remarks

The source dataset was treated as the **raw operational data** and was not silently overwritten when data-quality issues were identified.

---

# 🛠️ Tools & Technologies

| Tool                                       | Purpose                                      |
| ------------------------------------------ | -------------------------------------------- |
| 📗 **Microsoft Excel / Excel for the Web** | Dashboard creation & analysis                |
| 📊 **Excel Formulas**                      | KPI and analytical calculations              |
| 🔎 **Data Quality Analysis**               | Missing values, duplicates & inconsistencies |
| 🤖 **OpenAI ChatGPT**                      | AI-assisted analysis & validation            |
| 📝 **PDF Reporting**                       | Executive summary & AI exercise              |

---

# 📁 Project Structure

```text
Embassy-Outreach-Analytics/
│
├── 📊 Embassy_Outreach_Dashboard.xlsx
│   ├── Leadership Dashboard
│   ├── BackEnd Data
│   └── Data Quality Review
│
├── 📄 Embassy_Outreach_Executive_Summary_AI_Exercise.pdf
│
└── 📘 README.md
```

---

# 📊 Leadership Dashboard

The Excel dashboard was designed for a **leadership review meeting**, with an emphasis on clarity and actionable information rather than unnecessary complexity.

### Key Dashboard Components

**🏛️ Total Tracked Embassies**
Distinct non-blank Embassy IDs represented in the source data.

**📈 Active Engagement Rate**
Calculated using records classified as **Engaged** or **In Discussion**.

**⚠️ Outreach Requiring Action**
Highlights records in stages requiring continued attention, including **On Hold, Not Started and Meeting Scheduled**.

**📋 Outreach Status Distribution**
Shows the overall distribution of outreach stages.

**🌎 Regional Engagement Breakdown**
Compares outreach activity and active engagement across regions.

**🎯 Engagement Level Distribution**
Shows Low, Medium, High and Missing/Unknown engagement classifications.

**🚨 Management Attention**
Highlights important operational and data-quality gaps requiring follow-up.

---

# 📈 Outreach Status Overview

| Outreach Status         | Records |    Share |
| ----------------------- | ------: | -------: |
| 🟢 Engaged              |  **22** |  **25%** |
| 🔵 Initial Contact Made |  **15** |  **17%** |
| 🟣 In Discussion        |  **14** |  **16%** |
| 🟠 Meeting Scheduled    |  **11** |  **13%** |
| 🟡 On Hold              |  **11** |  **13%** |
| ⚪ Not Started           |  **10** |  **11%** |
| ⚫ Closed                |   **5** |   **6%** |
| **Total**               |  **88** | **100%** |

### Key Observation

The largest individual category is **Engaged**, with 22 records. However, a sizeable portion of outreach remains in stages requiring further progression or monitoring.

---

# 🤝 Engagement Analysis

### Active Engagement Rate

**40.9%**

The rate represents records classified as:

> **Engaged + In Discussion**

This provides a straightforward measure of the proportion of source records currently showing active outreach progression.

---

# 🌎 Regional Engagement

| Region                     | Total Records | Engaged | In Discussion | Active Engagement Rate |
| -------------------------- | ------------: | ------: | ------------: | ---------------------: |
| Sub-Saharan Africa         |            16 |       7 |             2 |              **56.3%** |
| Middle East & North Africa |            12 |       4 |             2 |              **50.0%** |
| Asia-Pacific               |            15 |       3 |             4 |              **46.7%** |
| Europe                     |            19 |       3 |             4 |              **36.8%** |
| America                    |            14 |       4 |             1 |              **35.7%** |
| South & Central Asia       |             7 |       1 |             1 |              **28.6%** |
| Unknown / Missing          |             5 |       0 |             0 |               **0.0%** |

### Regional Insight

**Sub-Saharan Africa** shows the highest active engagement rate among classified regions at **56.3%**.

**South & Central Asia** has the lowest classified regional active engagement rate at **28.6%**.

Five records have no region classification, so they are explicitly shown as **Unknown / Missing** rather than excluded from the analysis.

---

# 🎯 Engagement-Level Distribution

| Engagement Level    | Records |
| ------------------- | ------: |
| 🔴 High             |  **19** |
| 🟡 Medium           |  **22** |
| 🟢 Low              |  **26** |
| ⚪ Missing / Unknown |  **21** |
| **Total**           |  **88** |

### Data Completeness Insight

The presence of **21 missing Engagement Levels** means the engagement dataset is incomplete and should be improved before being used as the sole basis for performance comparisons.

---

# 🔎 Data Quality Review

A detailed review was conducted to identify information that could affect reporting and operational decision-making.

## Missing Information

| Field               | Missing Records |
| ------------------- | --------------: |
| Embassy ID          |           **2** |
| Region              |           **5** |
| Email               |           **7** |
| Phone               |           **8** |
| Outreach Owner      |           **8** |
| First Contact Date  |          **10** |
| Last Contact Date   |          **11** |
| Next Follow-up Date |          **22** |
| Interactions        |           **6** |
| Engagement Level    |          **21** |
| Channel             |          **10** |
| Remarks             |           **3** |

---

## ⚠️ Other Data-Quality Findings

### Duplicate & Identifier Issues

* Duplicate Embassy identifiers require investigation.
* Missing Embassy IDs require verification against the source.
* Some records appear to represent possible duplicate/update entries and should be reconciled carefully.

### 📧 Email Issues

* Missing email addresses
* Malformed email structures
* Incomplete or suspicious domains

### ☎️ Phone Issues

* Missing telephone numbers
* Incomplete numbers
* Inconsistent formatting

### 📅 Date Issues

* Mixed date formats/types
* First Contact dates occurring after Last Contact dates
* Last Contact dates occurring after Next Follow-up dates
* Future-dated contact records requiring verification

### 🔢 Numeric Issues

* One negative interaction value was identified:

```text
Interactions = -3
```

Interaction counts should normally be non-negative.

### 🔗 Logical Consistency Issues

Examples include records where:

* Outreach is marked **Not Started** despite recorded activity
* Outreach is marked **Engaged** while remarks indicate participation was declined
* Records show zero interactions despite remarks describing substantive activity

These issues should be **verified rather than guessed or silently overwritten**.

---

# 🚨 Management Attention

The dashboard highlights operational and data-quality areas requiring management attention.

### Priority indicators

| Attention Area                    | Records |
| --------------------------------- | ------: |
| 📅 Missing Next Follow-up         |  **22** |
| 🎯 Missing Engagement Level       |  **21** |
| 👤 Missing Outreach Owner         |   **8** |
| 📧 Missing Email                  |   **7** |
| ☎️ Missing Phone                  |   **8** |
| ⚠️ Date / Data Consistency Issues |   **8** |
| 🔢 Invalid Interaction Count      |   **1** |

These indicators help distinguish between **outreach issues** and **data-quality issues** that could affect the interpretation of performance data.

---

# 💡 Key Business Insights

### 01 — Active engagement is significant but not dominant

**40.9%** of source records are classified as either Engaged or In Discussion.

### 02 — Follow-up tracking is a major gap

**22 records** have no Next Follow-up Date, creating a potential operational tracking risk.

### 03 — Engagement information is incomplete

**21 records** do not contain an Engagement Level.

### 04 — Regional performance varies

There is a notable difference between the strongest regional active engagement rate (**56.3%**) and the lowest classified rate (**28.6%**).

### 05 — Data quality can affect decision-making

Missing owners, contact information, dates, channels and engagement classifications reduce the completeness and reliability of operational reporting.

---

# ✅ Recommendations

### 📅 1. Strengthen Follow-up Tracking

Prioritise the records without a Next Follow-up Date and establish clear ownership for future actions.

### 👤 2. Improve Accountability

Complete missing Outreach Owner information so that every active relationship has clear operational responsibility.

### 🎯 3. Improve Engagement Data

Complete missing Engagement Levels using an agreed business definition and documented source information.

### 🧹 4. Standardise Data Entry

Introduce consistent values and formats for:

* Outreach Status
* Region
* Engagement Level
* Channel
* Dates
* Phone numbers
* Email addresses

### 🔎 5. Introduce Regular Data-Quality Checks

Run periodic checks for:

* Duplicate IDs
* Missing fields
* Invalid values
* Date inconsistencies
* Conflicting status/activity information

### 📋 6. Maintain an Audit Trail

Preserve the original raw dataset and document any future corrections or analytical standardisation separately.

---

# 🤖 AI Exercise

## AI Tool Used

**OpenAI ChatGPT**

AI was used as a supporting analytical tool during the project.

### AI-assisted activities

* Interpreting the assessment requirements
* Structuring the data-quality review
* Identifying potential data-quality issues
* Reviewing dashboard metrics
* Checking calculations and formulas
* Identifying management-focused insights
* Reviewing the project against the assessment requirements
* Supporting the preparation of the Executive Summary

### Validation Principle

AI-generated observations were cross-checked against the workbook data before being incorporated into the final analysis.

No uncertain source information was intentionally fabricated or treated as definitively corrected.

---

# 🧪 Validation Approach

The project was reviewed through multiple analytical validation passes covering:

```text
1. Assignment Requirements
2. Workbook Structure
3. Dashboard KPIs
4. Formula Logic
5. Outreach Status Reconciliation
6. Regional Calculations
7. Engagement-Level Completeness
8. Management Attention Metrics
9. Backend Data Quality
10. Final Cross-Check
```

The objective was to reduce calculation errors, omissions and inconsistencies before submission.

---

# 📦 Deliverables

| File                                                    | Description                                               |
| ------------------------------------------------------- | --------------------------------------------------------- |
| 📊 `Embassy_Outreach_Dashboard.xlsx`                    | Leadership Dashboard + Backend Data + Data Quality Review |
| 📄 `Embassy_Outreach_Executive_Summary_AI_Exercise.pdf` | Executive Summary + AI Exercise                           |
| 📘 `README.md`                                          | Project documentation                                     |

---

# 🎓 Skills Demonstrated

### Data Analytics

`Data Analysis` · `Data Validation` · `Data Interpretation` · `Business Insights`

### Excel

`Excel Formulas` · `Dashboard Development` · `KPI Design` · `Data Visualisation` · `Reporting`

### Data Quality

`Missing Data Analysis` · `Duplicate Detection` · `Data Consistency` · `Validation Rules`

### Business Analysis

`Management Reporting` · `Regional Analysis` · `Prioritisation` · `Actionable Recommendations`

### AI

`AI-Assisted Analysis` · `Prompting` · `Analytical Validation` · `Insight Generation`

---

# 🌟 Project Outcome

This project demonstrates an end-to-end approach to transforming a raw operational dataset into a **leadership-ready analytical solution**.

The focus was not on creating unnecessary complexity, but on answering the questions that matter most to management:

> **What is happening?**
> **Where is engagement strongest or weakest?**
> **What data can we trust?**
> **What requires attention?**
> **What should management do next?**

---

<p align="center">

### 📊 Analyse • 🔎 Validate • 💡 Recommend • 🚀 Act

</p>
