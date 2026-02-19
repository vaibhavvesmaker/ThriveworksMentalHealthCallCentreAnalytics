# 📊 Patient Access & Operational Intelligence Case Study
**Project Objective:** Transforming raw call center data into a governed, "Single Source of Truth" to improve patient intake and operational efficiency at Thriveworks.

---

## 🚀 The Business Problem
In the high-growth mental health sector, a missed call isn't just a lost lead—it’s a missed opportunity for care. During the initial audit of the raw data, I identified three core structural challenges:

* **SLA Friction:** 38% of callers waited longer than 30 seconds for an answer, risking patient abandonment.
* **Data Silos:** Conflicting definitions for "Conversion" across Marketing and Operations led to reporting discrepancies.
* **Manual Overhead:** Monthly reporting cadences were reliant on manual Excel refreshes, delaying executive decision-making.

---

## 🛠️ The Solution: A Two-Phase Architecture

### Phase 1: The Excel Prototype (Speed to Insight)
**Goal:** Rapidly visualize immediate bottlenecks and validate data logic.
* **Key Insight:** Identified **Billing Questions** as the #1 call driver (23k+ calls). 
* **Action:** Proposed real-time FAQ routing to reduce agent handle time on non-clinical inquiries.

### Phase 2: The Looker Production Layer (Scalability)
I transitioned the logic into a **LookML Semantic Layer** to provide a governed, enterprise-grade environment:
* **Centralized KPIs:** Codified `SLA_Achievement` and `Patient_Conversion` as standard measures in LookML to ensure data consistency.
* **Geographic Insights:** Developed heatmaps of volume by state to align licensed clinician recruitment with regional patient demand.
* **Real-time Alerts:** Integrated Slack webhooks to notify Team Leads whenever abandonment rates spike above 5%.

---

## 📊 Technical Stack & Skills
| Area | Technology | Implementation |
| :--- | :--- | :--- |
| **BI Layer** | Looker / Power BI | LookML Views, Explores, and DAX modeling |
| **Data Logic** | SQL (BigQuery/Snowflake) | Advanced CTEs for cleaning mixed-format timestamps |
| **Integration** | Salesforce + Google Analytics | Correlating CRM leads with web funnel progression |
| **Finance** | Excel / Accounting | Budget vs. Actual (OPEX) and marketing spend pacing |

---

## 📈 Impact & Recommendations

> **"Data-driven decisions to bridge the gap between operations and patient care."**

1.  **Staffing Optimization:** Recommended proactive shift-rebalancing for **Mondays (Peak Volume)** to recover lost SLA performance.
2.  **Sentiment Recovery:** Identified a **41% negative sentiment trend** linked to billing friction; proposed a "Warm Transfer" protocol to improve the patient experience.
3.  **Operational Efficiency:** Automated the daily/weekly reporting cadence, saving an estimated **10+ hours/week** of manual data manipulation.

---

## 📁 Repository Structure
* `sql_scripts/`: Data cleaning and KPI logic.
* `lookml_models/`: Mock-ups of Looker Views and Explores.
* `dashboards/`: Screenshots of the Power BI and Looker interfaces.
* `documentation/`: Deep-dive into metric definitions and logic.

---
**Contact:** Vaibhav Vesmaker
