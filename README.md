# Consumer-Financial-Complaints-Analytics-CFCA-Project
A Power BI project analyzing over 60K consumer financial complaints to uncover key trends in response times, complaint types, and company performance. The dashboard highlights issues driving customer dissatisfaction and provides insights to help improve service efficiency and trust in the finance sector.
📊 Consumer Financial Complaints Analytics (CFCA) Project

Project Overview

This project was developed as a submission for the Onyx Data DNA Challenge, focusing on the Consumer Financial Protection Bureau (CFPB) dataset. The goal was to step into the role of a Data Analyst at the CFPB to identify critical patterns in consumer complaints, assess company accountability, and highlight areas of concern for regulatory action.

The analysis is presented in a dynamic, three-page Power BI report designed to guide regulators and provide transparency to consumers.

🎯 Key Questions Addressed

The report is structured to answer the core analytical questions posed by the CFPB brief:

When do complaints rise or fall over time? Which products generate the most complaints?
Which states and regions are hotspots? What are the biggest underlying causes of complaints?
How fast and timely are company responses? Which companies show the highest complaint rates relative to market share?
Do submission channels differ in response speed or outcomes? Do company traits (size tier, enforcement history) correlate with outcomes?

🛠️ Data & Methodology
The primary dataset consists of merged Consumer Financial Complaints data, including details on submission, company response, product, issue, and geographic information.

Technology Stack
Data Modeling/Analysis: Power BI (DAX)
Visualization: Power BI
Data Preparation: Assumed transformation and combination of fact/dimension tables into a primary Complaint Fact Table.

🔎 Report Page Breakdown & Key Insights

The Power BI report is divided into three distinct pages, each focusing on a different analytical layer:

Page 1: Overview & Trends

Focus: High-level KPIs and macro-environmental trends.
![CFCA Project_page-0001](https://github.com/user-attachments/assets/ae6ee928-3e50-4e54-91d9-41d7516006f2)


Total Complaints: 62,516 (vs. LY $\triangle 28.3\%$)

Temporal Trend: Complaint volume exhibits a consistent seasonal pattern, with an annual peak observed around June/July.

Top Products: Checking or savings account and Credit card or prepaid card are the primary volume drivers.

Underlying Issues: The biggest underlying cause is 'Managing an account' (over 15k complaints).

Page 2: Company & Response Analysis

Focus: Benchmarking company performance and assessing operational risk.
![CFCA Project_page-0002](https://github.com/user-attachments/assets/b3992f46-64de-4783-a251-2a8d2b3e218d)


Outlier Identification: Company COMP-0342 is flagged for the Most Complaints and has a Complaint Rate (per 1% Share) that is significantly high.

Submission Channels: The analysis reveals a stark contrast: Web submissions account for the largest volume but may be associated with longer response times compared to channels like Referral.

Response Effectiveness: The performance summary table clearly contrasts % Timely Responses with % Closed with Monetary Relief, identifying companies that prioritize speed over substantive resolution (e.g., high timeliness, low monetary relief rate).

Page 3: Complaint Response and Product Insights

Focus: Deep dive into product-specific severity and geographic/seasonal volatility.
![CFCA Project_page-0003](https://github.com/user-attachments/assets/d5ce4463-882b-437c-8d2e-f1488114f6e4)

Severity by Product: The Mortgage product, despite having lower raw volume than Checking accounts, exhibits an average response time of 15.19 days and an Average Reputation Score of 75.45, suggesting that high-impact issues in this category are resolved slowly.

Response Outcomes: The majority of responses are 'Closed with explanation' (41k), indicating that most cases do not result in monetary relief but rather a detailed communication from the company.

Regional Hotspots (Seasonal): A matrix analysis highlights that the Middle Atlantic and South Atlantic regions consistently drive the highest complaint volumes, with peak activity observed across the summer months.

[View the Report on Power BI](https://app.powerbi.com/groups/me/reports/32f1aaf2-3e5b-4151-8a36-7e8555010eb0/c65e9cf42b5bd7aa23a8?experience=power-bi)



Final note: The analysis provided within the report addresses the CFPB's mandate to strengthen consumer protection policies by identifying specific corporate and regional risks.
