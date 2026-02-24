# Credit Risk Assessment Dashboard using Power BI

## Overview

This project focuses on analyzing borrower loan default risk using financial and demographic data.
The dashboard identifies high-risk customer segments and evaluates financial exposure to assist in data-driven lending decisions.

The objective of this analysis is to move beyond descriptive loan distribution metrics and provide actionable insights into:

- Probability of Default (PD)
- Exposure at Default (EAD)
- Debt-to-Income Risk
- Employment Stability Risk
- Credit Score-based Default Trends
- Time-based Lending Risk (Vintage Analysis)

---

## Dataset Features

The dataset contains borrower-level loan application details including:

- Age
- Income
- Loan Amount
- Credit Score
- Debt-to-Income Ratio (DTI)
- Employment Type
- Months Employed
- Loan Term
- Interest Rate
- Number of Credit Lines
- Has Mortgage
- Has Co-Signer
- Loan Purpose
- Loan Issue Date
- Default Status

---

## Key Risk Metrics Calculated

| Metric | Description |
|--------|-------------|
| Default Rate | Percentage of loans that resulted in default |
| High DTI Default Rate | Default rate for borrowers with DTI > 0.4 |
| Exposure at Default (EAD) | Total loan amount at risk due to default |
| Average Interest (Defaulted) | Avg interest charged to defaulted borrowers |
| Employment Stability Risk | Risk based on employment duration |
| High LGD Proxy | Borrowers with no mortgage and no co-signer |

---

## Dashboard Insights

The dashboard helps answer:

- Which credit score groups are more likely to default?
- Do borrowers with high DTI pose greater risk?
- Does having a co-signer reduce default probability?
- Which loan purposes contribute to higher financial exposure?
- Are unstable employment conditions linked to defaults?
- Is interest rate pricing aligned with borrower risk?
- Which lending periods showed increased default trends?

---

## Visualizations Included

- Default Rate by Credit Score Band
- Default Rate by DTI Bucket
- Default Rate by Employment Stability
- Default Rate by Loan Purpose
- Defaults by Mortgage Availability
- Default Rate by Co-Signer Presence
- Interest Rate vs Credit Score (Risk Pricing Check)
- Exposure at Default (EAD) by Loan Purpose
- Default Rate by Loan Year
- EAD Trend by Loan Year

---

## Tools Used

- Power BI
- DAX
- Data Modeling
- Risk Segmentation Techniques

---

## Business Use Case

This dashboard can support:

- Credit Risk Teams
- Loan Approval Decision Making
- Lending Policy Evaluation
- Financial Risk Monitoring
- Portfolio Exposure Analysis

---

## Outcome

Provides a risk-driven perspective on lending by identifying borrower segments that contribute to higher probability of default and financial exposure, enabling better credit decision strategies.
