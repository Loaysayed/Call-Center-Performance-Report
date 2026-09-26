# 📊 Call Center Performance Report

An end-to-end Power BI report designed to analyze call center performance, service quality, and agent efficiency.

The project focuses on monitoring key service KPIs, identifying performance drivers, analyzing month-over-month trends, and simulating staffing scenarios using What-If Analysis.

---

## 🎯 Project Objective

The objective of this project is to evaluate call center performance and identify the key factors affecting service quality and operational efficiency.

The analysis focuses on:

- Monitoring key call center KPIs
- Analyzing month-over-month performance trends
- Identifying the root causes behind performance changes
- Evaluating agent and project-level performance
- Simulating staffing scenarios using What-If Analysis

---

## 🛠️ Tools & Technologies

- Power BI
- DAX
- Power Query
- Data Modeling
- What-If Analysis
- Interactive Data Visualization

---

## 📈 Key KPIs

The report monitors several call center performance indicators, including:

- ASA (Average Speed of Answer)
- Abandon Rate
- Forecasted Calls Accuracy
- Handled Calls
- Total Calls
- Agent Performance

---

## 🔍 Analysis Performed

### 1. KPI & Trend Analysis

Developed dynamic DAX measures to monitor service performance and analyze month-over-month changes.

### 2. Root Cause Analysis

Investigated changes in call center performance by analyzing performance across projects and individual agents.

### 3. What-If Analysis

Developed a staffing simulation model to evaluate how changes in agent count could impact:

- ASA
- Abandon Rate

### 4. Interactive Analysis

Created interactive tooltips and insights-driven visualizations to allow users to explore performance across different dimensions.

---

## 💡 Key Insights

A noticeable decline in call center performance was identified during March.

- ASA increased by 149.4%
- Forecasted Calls Accuracy decreased by 57.8%

Further root cause analysis showed that underperformance in Project B and a subset of agents were major contributors to the decline in key service KPIs.

Project B experienced a 228.4% increase in ASA compared with the previous period.

---

## 📊 Dashboard Preview

### Overview

![Call Center Dashboard](screenshots/overview.png)

### Root Cause Analysis

![Root Cause Analysis](screenshots/root-cause-analysis.png)

### What-If Analysis

![What-If Analysis](screenshots/what-if-analysis.png)

---

## 📂 Repository Structure

```text
dashboard/       → Power BI report
data/            → Dataset information
screenshots/     → Dashboard screenshots
docs/            → Additional project documentation
