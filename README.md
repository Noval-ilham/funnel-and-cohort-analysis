# Funnel and Cohort Analysis

## Project Overview
This repository presents an end to end customer acquisition and retention analysis built in Power BI. By combining Funnel Analysis and Cohort Analysis, this project identifies conversion bottlenecks across customer segments, evaluates monthly retention patterns, and translates data insights into actionable business growth strategies.

## Tools and Technical Skills
* **Business Intelligence:** Power BI Desktop
* **Data Modeling and Measures:** DAX (`DIVIDE`, `SWITCH`, `SELECTEDVALUE`)
* **Analytical Methods:** Funnel Conversion Analysis, Dropoff Analysis, Cohort Retention Analysis

## Dataset and Methodology
* **Funnel Dataset:** Tracks 630,338 total leads across four sequential stages (`Leads`, `Bookings`, `Free Trials`, and `Register New User`) segmented into three customer groups (`Kindergarten & Elementary School`, `Middle School`, and `High School`).
* **Cohort Dataset:** Groups customers based on their first transaction month throughout 2024 to measure repeat activity and retention rates over subsequent months (`Month 0` to `Month 11`).

## Key Analytical Findings

### 1. Funnel Performance
* **Overall Conversion Rate:** 28.33% (178,560 registered users converted from 630,338 leads).
* **Stage Conversion and Dropoff Rates:**
  * `Leads` to `Bookings`: 66.22% conversion | 33.78% dropoff
  * `Bookings` to `Free Trials`: 62.68% conversion | 37.32% dropoff (steepest bottleneck)
  * `Free Trials` to `Registered Users`: 68.25% conversion | 31.75% dropoff
* **Segment Breakdown:** At the critical `Bookings` to `Free Trials` stage, the **High School** segment experiences the highest dropoff at **39.96%**, compared to **Middle School** (**36.54%**) and **Kindergarten & Elementary School** (**31.85%**).

### 2. Cohort Retention Performance
* **General Trend:** Average retention across all cohorts starts at **58.6%** in `Month 1` and gradually declines over subsequent periods.
* **Top Performing Cohort:** The **July** cohort achieved the highest `Month 1` retention at **90.0%**, maintaining that level through `Month 5`.
* **Lowest Performing Cohort:** The **February** cohort recorded the lowest `Month 1` retention at **26.7%**.

## Strategic Recommendations
* **Minimize Trial Dropoffs:** Implement automated reminders, faster followup workflows, and clearer communication of free trial benefits between booking and trial stages, prioritizing the High School segment.
* **Replicate High Retention Drivers:** Audit campaign timing, audience targeting, and early onboarding experiences from top performing cohorts such as July to apply those learnings to future acquisitions.
* **Strengthen Long Term Loyalty:** Launch membership perks, personalized offers, and referral programs to boost customer lifetime value and reduce churn after the first transaction.

## Repository Contents
* `funnel_cohort_dataset.xlsx` : Raw dataset used for funnel and cohort modeling.
* `funnel_cohort_dashboard.pbix` : Interactive Power BI dashboard file containing the Funnel and Cohort visualizations.
* `funnel_cohort_analysis_report.pdf` : Presentation deck summarizing business cases, DAX formulas, dashboard visuals, and strategic insights.
