# Healthcare-Claims-And-Financial-Performance-Analysis
Analysis of a healthcare insurance claims dataset using Excel, SQL, and Power BI to identify high-cost procedures, diagnoses, claim types, and members, uncover spending patterns, and recommend data-driven strategies for better claims-cost management.
### Project Overview
Healthcare insurance companies must balance the cost of providing quality care with the revenue received from premiums. When claims spending rises, identifying what drives that spending becomes essential for controlling costs and maintaining financial sustainability.

In this project, I analyzed a synthetic healthcare claims dataset containing member demographics, claim types, diagnosis codes (ICD), procedure codes (CPT), billed amounts, paid amounts, plan types, and claim dates.

The objective was to understand where healthcare spending was concentrated, identify high-cost claims patterns, and provide actionable recommendations to support better financial and claims management.
Using Excel for initial data inspection, SQL for data cleaning, and Power BI for visualization, I developed a dashboard that enables stakeholders to explore claim costs by procedure, diagnosis, member, claim type, and insurance plan.
### Problem Statement
The healthcare insurance company is experiencing financial pressure and needs a clearer understanding of the factors driving its claims expenditure.

Although the company processes multiple types of claims, it is unclear which procedures, diagnoses, members, and service categories contribute most to the total amount paid. The company also needs to understand the relationship between billed amounts and paid amounts to identify areas that may require further investigation.

The analysis aims to support evidence-based decisions around claims auditing, high-cost case management, reimbursement reviews, and financial performance monitoring.
### Data Source:
Secondary Dataset
### Tool: 
Excel, SQL and Power BI
### Data Cleaning
- Initial loading and Data Inspection in Excel:
I opened the dataset in Microsoft Excel to review its structure and understand the information available before performing the analysis.

- Data Cleaning and Preparation in SQL:
I used SQL to clean and prepare the dataset for analysis. The preparation process focused on ensuring that fields were consistently formatted and suitable for aggregation. Relevant checks included reviewing missing values and duplicate records, validating numeric and date fields, standardizing categorical values, and checking for unusual billed or paid amounts.

- Data Visualization in Power BI
I imported the cleaned dataset into Power BI and developed an interactive dashboard to communicate the results to business stakeholders.
The dashboard includes key performance indicators for total members, total claims, total paid amount, total billed amount, average paid per claim, and overall paid ratio.
I also created visualizations to examine the top CPT codes by total paid amount, the top ICD codes by total paid amount, member costs by claim type, and average paid amounts by procedure code.
Filters for claim type, plan type, and claim date allow users to explore the data across different categories and time periods.
The resulting dashboard provides a consolidated view of healthcare claims spending and highlights areas requiring further financial or operational investigation.
### Key Findings and Results
### Findings 1: The company processed $1.55milion in paid claims 
The difference between the billed and paid amounts is approximately $511,420. This represents the gap between what was billed and what was paid. It should not automatically be classified as unpaid claims or financial loss, because contractual adjustments, benefit structures, member cost-sharing, and other payment arrangements may explain part of the difference.
- Why it matters: The size of the claims expenditure makes it important to understand which services and member groups account for the largest share of payments. However, determining whether the company is genuinely operating at a loss requires additional information about premium revenue and other expenses.
### Finding 2: A small number of CPT codes account for substantial spending
These first four procedure codes account for approximately $683,773, or 44.1% of the overall paid claims amount. The two highest-ranked procedure codes alone represent approximately $446,526 in paid claims.
- Why it matters: Spending is concentrated in a limited group of procedure codes. This makes those codes a practical starting point for a deeper review of service frequency, average cost per claim, provider pricing, and claims accuracy.
The concentration does not necessarily mean that these procedures are inappropriate or overpriced. They may reflect expensive but medically necessary services or a high volume of legitimate claims.
### Finding 3:  Certain diagnosis codes are associated with higher expenditure
The four leading diagnosis codes represent approximately $657,913 in paid claims
- Why it matters: Diagnosis-level analysis can reveal where treatment-related expenditure is concentrated. However, total spending alone cannot establish whether a diagnosis is expensive because it occurs frequently, requires more intensive treatment, or is associated with higher costs per claim.
### Finding 4: Paid-to-billed ratios vary across claim types
Laboratory and pharmacy claims have the highest displayed paid ratios, while inpatient claims have the lowest.
- Why it matters: The difference suggests that the relationship between billed and paid amounts varies by service category.
A lower paid ratio does not automatically indicate better cost control, and a higher ratio does not necessarily indicate overspending. Differences may be driven by negotiated reimbursement rates, deductibles, benefit limits, claim adjustments, or other payment rules.
The business should review billed amounts, paid amounts, adjustments, and denials by claim type before concluding why these differences exist.
### Finding 5: Some procedure codes have high average paid amounts per claim
Some CPT codes have a higher average paid amount per claim, meaning the insurer spends more on each claim involving those procedures.
- Why it matters: A procedure may not have the highest total spending simply because it occurs less often. Looking at the average paid per claim helps identify procedures that are expensive each time they are billed, even if they do not account for the largest share of overall spending.
### Finding 6: Member-level spending deserves closer monitoring
This suggests that some members account for greater spending than others, with member IDs 6, 32, and 58 among the highest-cost members shown.
- Why it matters: A small number of high-cost members can materially affect claims expenditure. However, high spending may be associated with complex medical needs or necessary treatment and should not automatically be interpreted as inappropriate utilization.
The company should examine individual claim histories, recurring service patterns, diagnosis mix, and potentially avoidable hospital utilization to understand the reasons behind higher costs.
### Practical Recommendations
- Review the top CPT codes for unusual payments, pricing issues, and potential claim errors.
- Analyze claim frequency and treatment costs to identify opportunities for more efficient care.
- Investigate recurring admissions and emergency visits to identify potentially avoidable expenses.
- Examine paid-to-billed ratios across claim types to identify discrepancies and understand reimbursement patterns.
- Track profitability: Combine claims data with premium revenue and operating expenses to determine the actual causes of financial losses.
### Conclusion
The analysis shows that healthcare expenditure is concentrated in particular procedure codes, diagnosis codes, and member-level claim patterns. It also reveals differences in paid-to-billed ratios across service categories and highlights procedures with high average paid amounts.

These findings provide a focused starting point for investigating the sources of claims expenditure. They do not, by themselves, establish that the highlighted claims are inappropriate or explain the company's overall financial losses.
The next step is to combine claims analysis with reimbursement, utilization, provider, premium, and operating-cost data. This will help the business move from identifying where it spends the most money to understanding why those costs occur and which interventions are most likely to improve financial performance while preserving appropriate patient care.


