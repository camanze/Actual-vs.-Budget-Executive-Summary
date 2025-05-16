# Actual-vs.-Budget-Executive-Summary

**INTRODUCTION**

In an era where rapid, data-driven decisions separate leaders from followers, financial teams need more than static tables and slide decks. This project delivers a dynamic Actual vs. Budget Executive Summary built in Power BI, designed to empower executives with real-time insights into income and expenses across projects, periods, and granular dimensions. Leveraging interactive slicers, drill-down, and drill-through functionality, the dashboard transforms raw ledger data into a strategic tool for monitoring performance, diagnosing variances, and driving continuous improvement.

**PROJECT OVERVIEW**

- **Objective:** Create an executive summary that compares Actual vs. Budget figures for both Income and Expenses, highlights variances, and enables deep exploration without overwhelming users.

- **Scope:** Financial data spanning multiple years, months, and project IDs, covering both revenue streams and cost centers.

- **Key Deliverables:**

 1. **KPI Cards** - showing actual values, budget targets, variance percentages, and percentage-of-budget gauges.

 2. **Trend Charts** - plotting Actual vs. Budget over time with conditional variance markers.

 3. **Tabular Breakouts** - listing top projects sorted by variance and percentage-of-budget, with in-line bar indicators.

**DATA AND METHODOLOGY**

1. **Source:** The dataset used for this project was generated using AI (ChatGPT), and is a simple sample dataset tailored for the purpose of the project. You can generate yours, or use the copy available in this repository.

2. **Data Preparation:**

   -  Imported transactional and budget tables via Power Query.
   -  Created a Date dimension table, marked as a date table for time intelligence.
   -  Built relationships between Projects, Actuals, and Budgets tables.
   -  Ensured clean, consistent data by standardizing currency, handling missing values, and validating project IDs.
