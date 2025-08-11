**I. Introduction**
__________________
**1. Introduction to dataset**

This project is an HR workforce dashboard built from an employee-level dataset and aggregated HR metrics. Key fields and views included in the dataset and dashboard:

- Employee roster table with: EmployeeName, Salary, Tenure (years), Position, Absence Rate, Satisfaction Score, Recruitment Source, Gender, Marital Status, Performance, Retention Risk, Ethnicity, Employment Status.

- Executive summary KPIs: Total Employees (299), Total Salary Expenses (~$21.47M), Overall Turnover Rate (34.78%), Avg. Tenure (12.31 years), Absence Rate (0.23%), Satisfaction Score (3.89), Average Age (46.5).

- Distributions & breakdowns: Age bands, Gender split (Female 56.67% / Male 43.33%), Turnover by Department (Production 40.69%, Admin 30%, Software Eng 30%, IT/IS 21.74%, Sales 16.13%), Departure reasons (top: “Another position”, “Unhappy”, “More money”, “Career change”), Top recruitment sources (Indeed 82, LinkedIn 74, Google Search 49, Employee Referral 31...).

- Department-level metrics: Salary expenses, headcount, tenure, turnover rate, absence, satisfaction and engagement scores (shown in the Workforce Metrics table).

The dataset supports both high-level monitoring (KPIs, department comparisons) and detailed people-level analysis (identify at-risk employees, see recruitment source and performance).

**2. Business questions**

From this dashboard, the main stakeholder questions are:

1. Which departments are losing the most people and why? (High-level: turnover rates by department; detailed: departure reasons and profiles.)

2. What are the cost and people implications of turnover (salary spend, headcount concentration)?

3. Which recruitment channels deliver the best hires (quality/retention/cost)?

4. Who is at retention risk and what interventions will keep critical talent?

5. Are satisfaction and engagement driving turnover (and where should we invest to improve them)?

6. Is the workforce aging or concentrated in roles that need succession planning?

7. Which quick actions will reduce voluntary attrition in high-risk groups?

**II. Visualization**
________________________
**1. Workforce Database**

<img width="1319" height="726" alt="image" src="https://github.com/user-attachments/assets/03994634-e0e3-48a0-9dc9-44a81fec2521" />


**2. Excutive Summary**

<img width="1322" height="735" alt="image" src="https://github.com/user-attachments/assets/af46258d-d9d4-44a7-90d1-0ddb8fc581d1" />

**III. Insights**
_____________________
**1. High overall turnover concentrated in Production**

Overall turnover($12.53M). This makes Production turnover the most material people + cost risk.

**2. Top exit drivers are external opportunity & compensation**

Most frequent departure reasons: Another position, Unhappy, More money, Career change. This suggests many departures are voluntary and driven by pay and/or job satisfaction/opportunity.

**3. Satisfaction varies by department and aligns with turnover.**

Department satisfaction scores (examples from table): Production 3.86, IT/IS 3.96, Sales 4.03, Software Eng 4.10, Admin Offices 3.60, Exec Office 3.00. Higher-turnover departments (Production, Admin) show lower or mid satisfaction—indicating correlation between satisfaction and attrition.

**4. Recruitment mix skews toward job boards; referrals underused**

Top sources: Indeed (82), LinkedIn (74), Google Search (49), Employee Referrals (31). Referral hires are relatively low compared with boards despite referrals often yielding better retention—opportunity to improve hire quality via referrals.

**5. Workforce is relatively long-tenured but aging.**

Avg tenure ~12.31 years and average age 46.5—organization has many long-serving employees. This is positive for knowledge continuity but increases near-term risk of retirement and the need for succession planning.

**6. Salary concentration implies exposure to Production shocks.**

Production accounts for the lion’s share of salary expense. Any retention or productivity issues in Production carry large financial impact.|

**III. Recommendations**
__________________________

**Immediate / Quick wins (0–3 months)**

*1. Launch targeted retention interviews in Production.*

Run short structured stay interviews with a representative sample of Production employees to validate drivers (pay, hours, manager issues, career path). Use standardized templates and log responses for analytics.

*2. Stabilize high-risk employees with “rapid” interventions.*

For employees flagged as High retention risk + performing adequately, offer focused measures: retention bonus for critical roles, flexible scheduling, or rapid career pathway mapping.

*3. Standardize exit interviews and centralize reasons.*

Make exit reasons mandatory and coded consistently so trends (e.g., pay, management, hours) can be tracked monthly.

*4. Boost employee referral program.*

Incentivize referrals (short-term bonus + recognition) and promote success stories—aim to increase % of hires from referrals within 6 months.

**Medium term (3–9 months)**

*5. Compensation benchmarking & targeted pay adjustments.*

Benchmark key Production roles vs. market. Where “more money” is a common reason for leaving, prioritize market-competitive adjustments for high-turnover / hard-to-replace roles.

*6. Career pathing & upskilling in high-turnover areas.*

Create clear ladders for Production roles (e.g., multi-skilling, team lead programs) and short training tracks. Visible progression often reduces turnover driven by “no career growth”.

*7. Manager training in frontline leadership.*

Deliver solid frontline manager coaching (feedback, recognition, dispute resolution). Many “unhappy” exits relate to people management rather than compensation.

*8. Refine recruiting funnel & source ROI analysis.*

Track hires by source for 12-month retention, cost-per-hire, time-to-fill, and performance. Reallocate budget toward top-performing channels (and referrals).

**Long term (>9 months)**

*9. Predictive attrition model & dashboard alerts.*

Build a model using satisfaction, tenure, recent pay changes, performance, retention risk, absence rate to predict voluntary attrition and generate alerts for high-probability leavers.

*10. Succession & knowledge-transfer plan for aging workforce.*

Identify critical roles with older incumbents (avg age 46.5; many long tenure). Create mentoring, documentation, and planned replacements.

*11. Optimize workforce cost structure.*

With Production absorbing ~60% of salary spend, evaluate opportunities: process improvements, automation, multi-skilling, or shift design to reduce overtime and reliance on external hires.
