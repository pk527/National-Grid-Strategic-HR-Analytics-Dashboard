# 🌐 National Grid Strategic & HR Analytics Dashboard

## 📌 Project Overview

The **National Grid Strategic & HR Analytics Dashboard** is an interactive Power BI solution built to empower executive decision-making across workforce management, strategic alignment, and operational cost efficiency. This system supports National Grid’s leadership by integrating real-time workforce metrics, financial productivity insights, competitive benchmarking, and predictive analytics.

---

## 🖼️ Dashboard Snapshot

<img width="1280" alt="Screenshot 2025-07-21 001023" src="https://github.com/user-attachments/assets/a0fe062f-4e73-4f45-833f-a92574f02d26">

---

## 🧭 Key Features

### 1. Executive Performance Metrics
- **Revenue Impact on Workforce Productivity**
- **Net Profit Impact from Workforce Dynamics**
- **Turnover Impact on Output**
- KPIs are tracked over time with visual trend indicators and goal variance arrows.

### 2. Competitive HR Benchmarking
- High-performer retention trends compared across **E.ON**, **EDF**, **SSE**, and **National Grid**
- Performance rating vs. retention rate helps identify top talent leakage and organizational risk

### 3. Departmental Insights
- **Salary Benchmark Gaps** across functions (IT, HR, Finance, Legal, etc.)
- Visual block chart to highlight departments below/above market average

### 4. Cost Efficiency by Role Level
- Yearly trend comparison (2021–2023) of **Labor Cost Efficiency** for roles: Mid, Lead, Manager, Junior, and Senior
- Visualizes changes in productivity and cost dynamics per grade

### 5. Training Investment by Gender
- Line chart showing **training hours by gender** (Female, Male, Non-Binary)
- Supports DEI evaluation in learning & development budgets

---

## 🧰 Data Sources & Transformations

### Data Sources:
- Simulated internal HRMS & finance data (Excel)
- External competitor data (e.g., from industry reports)

### Transformations via Power Query:
- Merging salary and role efficiency data
- Creating performance groups by quartiles
- Normalizing turnover, training hours, and financial impact fields

### Key DAX Measures:
- `Turnover Impact on Output`
- `High Performer Retention %`
- `Labor Cost Efficiency`
- `Training Investment per Headcount`

---

## 📊 KPIs Summary

| Metric                               | Description                                             |
|--------------------------------------|---------------------------------------------------------|
| Revenue Impact on Productivity       | Revenue loss/gain attributable to workforce turnover    |
| Labor Cost Efficiency                | Cost-to-output ratio by job grade                       |
| High Performer Retention             | % of top talent retained per performance group          |
| Salary Benchmark Index               | Internal salary vs. market average                      |
| Training Investment by Gender        | Breakdown of L&D allocation by gender identity          |



---


## 🧑‍🏫 How to Use the Dashboard

| Feature                             | Interaction Method                                      |
|-------------------------------------|----------------------------------------------------------|
| Change City/Location                | Click buttons on left panel (e.g., Birmingham, London)   |
| View Departmental Salary Gaps       | Hover over treemap blocks                               |
| Monitor Retention by Competitor     | Use dropdown or scroll through scatter plots             |
| Simulate Turnover Impact            | Watch how revenue/profit indicators react to spikes      |
| Evaluate Cost Efficiency by Grade   | Compare 2021–2023 bars in grouped column chart           |
| Review DEI in Training Investment   | Analyze color-coded line chart by gender                 |

---


## 🧩 Troubleshooting

| Issue                         | Solution                                                |
|-------------------------------|----------------------------------------------------------|
| Data not loading              | Reconnect Excel files in Power Query Editor             |
| Blank visual or slicer error  | Reset filters and reapply visuals                       |
| Performance slow              | Disable auto-page refresh or simplify visuals           |
| Forecast not showing          | Ensure consistent time-series data with no missing dates|

---



