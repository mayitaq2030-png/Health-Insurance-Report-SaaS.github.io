# Insurance Portfolio Optimization & Retention Strategy

### Executive Summary:

<p align ="justify"> This project presents a comprehensive analysis of a 100-policy insurance portfolio in the U.S. market, covering Life, Auto, SME (Small and Medium Enterprises), Home, and Travel lines of business. The analysis revealed a collection efficiency of 85.1% and a cancellation (churn) rate of 35%. Through an interactive dashboard, a total of $10,870 USD in revenue leakage was identified. Consequently, a strategic roadmap was designed to mitigate default risks and improve operational quality in policy issuance. </p>

### Business Problem:

<p align="justify"> The company faced three critical challenges:

Revenue Leakage: A significant gap between written and collected premiums, negatively impacting liquidity.

High Churn Rate: 35% of policies are lost prematurely, primarily within the Retail segment.

Operational Inefficiency: A high volume of cancellations categorized under "Issuance Error," indicating internal underwriting process failures rather than just market-driven factors. </p>

#### Order completion for chart 

<img width="517" height="535" alt="image" src="https://github.com/user-attachments/assets/9cc45cdd-1029-4300-b6ba-290f936829bf" />


### Methodology: 

This analysis followed the Data Analytics Lifecycle process:

Extraction and Cleaning: Processing raw data (CSV) ensuring the integrity of dates, amounts, and policy categories.

Exploratory Data Analysis (EDA): Identifying behavioral patterns by region (Northeast, West, South, Midwest) and payment frequency.

Critical KPI Calculation: Defining metrics such as Collection Efficiency, Churn Rate, and Written vs. Collected Premium.

Data Visualization: Creating an executive dashboard in React/Tailwind with a "Data Storytelling" approach to facilitate high-level decision-making.

### Skills:

<p align="justify">
Data Analysis: Data cleaning, CSV/Excel manipulation, and descriptive statistical analysis.

Advanced Visualization: Designing interactive dashboards (Power BI Style) using React and Recharts.

Insurance Domain Knowledge: Proficiency in policy management (Underwriting, Lines of Business, Customer Lifecycle).

Strategic Thinking: Translating technical metrics into business recommendations (Risk & Opportunity Matrix).

</p>


### Results & Business Recommendations:

[Dashborad Executive Analytics ](https://gemini.google.com/share/f222cb950cac)

[Dashborad Insurance Portfolio Intelligence](https://gemini.google.com/share/daab9259b0f4)

<img width="1324" height="539" alt="image" src="https://github.com/user-attachments/assets/9df0c1ae-fba7-45a9-8dc5-69b2a5003fe7" />

<p align="justify">
SME Segment as an Anchor: Small and Medium Enterprises were identified as having a projected renewal rate of 92%, making it the most stable segment for expansion.

Periodicity Risk: Findings showed that monthly payments directly correlate with defaults. Recommendation: Incentivize annual payments through a 5-8% discount to reduce credit risk.

Operational Optimization: 15% of cancellations are due to issuance errors. Action: Immediate audit of agent onboarding processes in the South region.
</p>

### Next Steps:

Predictive Modeling: Implement a Machine Learning model (e.g., Random Forest) to predict churn before a cancellation occurs.

Collection Automation: Integrate an automated reminder system (SMS/Email) based on the specific due dates identified in the analysis.

Regional Deep Dive: Conduct a loss ratio analysis by city to adjust technical rates in high-exposure areas.
