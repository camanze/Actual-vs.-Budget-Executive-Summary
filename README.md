# Actual vs. Budget Executive Summary

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

3. **Measures and Calculations:**

   - **Total Sales Actual / Budget:** SUM of actuals and budget fields.
   - **Variance %:** DIVIDE([Actual] – [Budget], [Budget], 0).
   - **% of Budget:** DIVIDE([Actual], [Budget], 0).
   - **Dynamic Slicers:** Parameters for Year, Month, and Project ID drive all visuals via SELECTEDVALUE.
  
**DASHBOARD FEATURES**

1. **Interactive KPI Cards**

   - Display Income and Expense actuals, budget, variance, and budget attainment in a glance.
   - Conditional formatting (green/red) offers immediate visual cues.
  
2. **Time-Series Trend Analysis**

   - Clustered column charts compare Actual vs. Budget across historical periods.
   - Dynamic variance labels (▲/▼) highlight performance swings.
  
3. **Project-Level Breakout Tables**

   - Sortable table of projects with key metrics and in-cell bar visuals.
   - Drill-through capability: click any project to see detailed line-item breakdown.
  
4. **Drill-Down & Slicers**

   - Year, Month, and Project slicers filter every visual synchronously.
   - Drill-down on charts unveils monthly, weekly, or daily views without leaving the page.

Here is a snapshot of the dashboard;

![Actual Vs Budget Dashboard](https://github.com/user-attachments/assets/931aa6fb-54c4-4454-b7f5-d9d191e35986)

**ANALYSIS AND INSIGHTS**

•	**Variance Patterns:** Identify periods where actual income consistently outpaces budget, signaling optimistic forecasts or revenue spikes.

•	**Cost Control:** Track expense overruns in specific months or projects to trigger timely corrective actions.

•	**Project Performance:** Quickly spotlight underperforming projects (negative % of budget) and reallocate resources.

•	**Seasonality & Trends:** Use drill-down to uncover seasonality in income or expense lines, supporting improved forecasting.

To explore the interactive Power BI dashboards, [Click Here](https://app.powerbi.com/view?r=eyJrIjoiZjUxYjI1NDktMjA3OS00ZGU2LWEwODctZmY2ZmY4NzRlNmRlIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

**RECOMMENDATIONS**

1.	**Embed in Executive Workflow:** Schedule automatic dashboard refreshes and distribute via Power BI Service to key stakeholders.
2.	**Set Alerts:** Define data-driven alerts for when variances exceed predefined thresholds, enabling proactive management.
3.	**Deep-Dive Reports:** Build drill-through pages for detailed GL-code or department-level analysis.
4.	**Forecast Integration:** Incorporate forward-looking measures (forecast vs. budget vs. actual) to close the planning loop.
5.	**Training & Adoption:** Conduct workshops to ensure finance and project teams can leverage drill-down and export features effectively.

**CONCLUSION**

This Power BI Actual vs. Budget Executive Summary exemplifies how modern BI solutions can replace static reporting with interactive, self-service analytics. By unifying actuals, budgets, and variances in one dynamic canvas—with intuitive slicers and drill-through pathways—organizations gain a 360° view of financial health. The result is faster insight delivery, stronger governance, and a culture of data-driven decision-making that accelerates growth and operational excellence.






