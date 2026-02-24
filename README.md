# Data Governance Risk Analysis (Power BI)
This project presents an end-to-end Data Governance Analysis designed to evaluate enterprise data trust, compliance exposure, and remediation effectiveness through an executive-focused Power BI dashboard.
The goal was simple:
Turn complex governance metrics into clear, decision ready insights.

## Report Structure
### 1. Executive Overview
A high level snapshot of organizational data trust, financial exposure, critical data coverage, and compliance distribution.
This page answers the question: Where do we stand today?

### 2. Data Quality & Stewardship
A deeper dive into field-level quality metrics including accuracy, completeness, ownership distribution, and stewardship workload.
This page answers the question: Why does risk exist?

### 3. Risk, Audit & Remediation
An operational view of audit recency, open issues, remediation cost, and regulatory exposure.
This page answers the question: Are we fixing issues effectively?

Users can toggle between:
Latest Audit and Previous Audit for all pages.

## Key KPIs Included
- Data Trust Index
- Financial Exposure
- Total Fines
- Remediation Cost
- Critical Data Element Coverage
- Non-Compliant Fields
- Average Days Since Last Audit
- Open Issues
- Average Fields per Owner
- Average Completeness Score
- Average Accuracy Score

## Tools Used
- Power BI
- DAX (for dynamic metrics & RAG logic)
- Data modeling & governance scoring framework

## Methodology: Data Trust Index Framework
The Data Trust Index (DTI) is a composite governance score designed to provide a single, normalized view of enterprise data reliability.
Rather than relying on one metric, the index combines quality performance, compliance posture, and governance risk exposure into a structured scoring model.

### Conceptual Formula
The index is calculated using a weighted model:

``` Data Trust Index =
(Data Quality Score × W₁)
+ (Compliance Score × W₂)
− (Risk Exposure Score × W₃)

