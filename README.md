# DFS-Ranks-Automobile-Insurance-Complaints

## Automobile Insurance Complaints & Premium Trend Analysis

This project analyzes New York State automobile insurance complaint data sourced from DFS (Department of Financial Services). The goal is to understand complaint patterns, trends over time, premium movements, and overall insurer performance.

The final deliverables include:
✔ Complaint diagnostics
✔ Premium trend analysis & factors
✔ Company-wise comparison dashboard (Top 5 insurers)
✔ Executive summary + insights

## Insurance companies receive customer complaints related to:

Claim payment delays

Policy non-renewals

Question-of-fact disputes

Withdrawn or not-upheld cases

DFS ranks companies based on complaints per million dollars of written premiums, where:

Low ratios → Better service quality

High ratios → Higher complaint burden

This project analyzes multi-year complaint and premium data to identify:

Complaint frequency & distribution

Complaint trends by year

Premium progress over time

Company performance vs competitors

Improvement opportunities for key companies

## Dataset Description
Column Name	Meaning
NAIC	National Insurance Identifier
Company_Name	Insurance provider
Ratio	Upheld complaints / Avg. premiums
Upheld_Complaints	Complaints validated by DFS
Question_of_Fact_Complaints	Disputed cases
Not_Upheld_Complaints	Withdrawn / Rejected
Total_Complaints	Sum of all complaints
Premiums_Written	Premiums written in NY (Millions USD)
Ranking	DFS complaint-ratio rank
Filing_Year	Year complaint was closed

# 1. Complaint Diagnostics
a. Frequency of Complaint Types

Across all companies and years:

Not-Upheld Complaints typically form the largest share, showing many disputes do not result in validated issues.

Question-of-Fact Complaints appear moderate in volume, indicating frequent disputes that require DFS review.

Upheld Complaints are generally the smallest portion, which reflects:

Either insurers genuinely resolve most issues

Or customers withdraw many complaints

b. Complaint Trends Over the Years

Complaint trends generally follow patterns such as:

Fluctuations tied to industry events, e.g., regulatory changes or disaster periods.

Gradual decline or increase depending on consumer sentiment and claim severity.

Certain companies show repeated high complaints, affecting their ranking position.

Companies with consistently improving trends appear more customer-centric.

# 2. Premium Trend Analysis
a. Premium Growth Over Time

Premiums often show:

Upward movement driven by inflation, rising repair costs, fraud/litigation exposure.

Sudden spikes indicating:

Regulatory rate approvals

Market exits by competitors

Increased claims frequency

b. Causes Behind Premium Changes

Typical causes include:

Higher claims severity → more payouts, increased premium needs

Economic conditions → inflation in repair & healthcare costs

Shift in customer base → urban markets vs rural

Regulatory actions → rate caps or approvals

c. Expected Future Trend (based on historical patterning)

If premiums have risen steadily year after year, future premiums may also grow unless:

New competitors enter

Customer claims reduce

Regulations restrict premium hikes

# 3. Comparison Dashboard (5-10-Company View)

The Power BI dashboard includes:

Metrics Compared:

Total Complaints

Premium Volume

Complaint Ratios

Year-wise complaint trend

Year-wise premium growth

Rank movement

Insights from the 5-Company Comparison:

Companies with higher premium bases often show lower complaint ratios, indicating better complaint absorption.

Smaller insurers frequently show higher ratios despite low absolute complaints, due to low premium volume.

Some companies consistently rank high, implying:

Better policies

Faster claim settlement process

Strong customer service

## Key Insights 
Complaint Patterns

Not-upheld complaints dominate the dataset.

Upheld complaints are few, indicating:

Many disputes lack evidence

Companies are able to justify decisions

Certain insurers show recurring spikes, needing systemic review.

Premium Dynamics

Premiums trend upward in most years.

Year-on-year fluctuations correlate with:

Claim severity

Natural disasters

Regulatory approvals

Company Performance

High-ranked companies (Rank 1–5) show:

Low upheld complaints

Strong premium bases

Low-ranked companies suffer from:

High ratios

Excess upheld complaints

Inefficiencies in settlement workflow
