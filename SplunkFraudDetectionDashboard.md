### 2. Splunk Fraud Detection Dashboard
- Used Splunk Enterprise on Ubuntu to ingest and visualize financial transaction data
- Created indexes and dashboards to identify fraud by age, gender, merchant, and category
- Used Splunk's “Interesting Fields” to create filters for detecting anomalies

📁 Folder: `/Splunk-Dashboard/`

#### `/Splunk-Dashboard/README.md`
```markdown
# Splunk Fraud Detection Dashboard

## Overview
This project was developed as part of Commonwealth Bank's cybersecurity initiative to combat financial
fraud through advanced data analytics and visualization. Using Splunk Enterprise, I created a comprehensive
fraud detection dashboard that analyzes transaction patterns across customer demographics, merchant categories,
and temporal data to identify high-risk fraud indicators and enhance the bank's fraud prevention capabilities.

**Project managed through ServiceNow Incident Management System**
```
# Splunk Fraud Detection Dashboard

## Overview
A comprehensive fraud detection dashboard built with Splunk Enterprise to analyze Commonwealth Bank transaction data and identify fraudulent patterns across customer demographics and transaction categories.

**Project Status:** ✅ Completed & Delivered  
**Total Fraud Cases Identified:** 92 fraudulent transactions

## ServiceNow Tracking

| Status | Description | Link |
|--------|-------------|------|
| **Original Ticket** | Initial requirements (INC0001234) | [🎫 View ServiceNow Ticket](https://quinnran76.github.io/Cybersecurity-Portfolio/servicenow_ticket_index.html) |
| **Resolved Ticket** | Completed deliverables | [✅ View Resolved ServiceNow Ticket](https://quinnran76.github.io/Cybersecurity-Portfolio/servicenow_resolved_index.html) |

## Dataset Summary
- **Source:** Commonwealth Bank transaction data (`prepared_data.csv`)
- **Records Analyzed:** Complete customer transaction history
- **Analysis Period:** 4 months (May - August)
- **Demographics:** Age groups 0-5, Gender (M/F)
- **Transaction Data:** Merchant IDs, categories, amounts, fraud indicators

## Dashboard Results

### Key Findings

**Highest Risk Categories:**
- Transportation Services (highest fraud concentration)
- Health Services
- Food & Dining
- Wellness & Beauty

**High-Risk Demographics:**
- **Age Group 1 (19-25 years):** 38 fraud incidents - HIGHEST RISK
- **Age Group 2 (26-35 years):** 24 fraud incidents
- **Gender:** Female customers (52 incidents) vs Male (40 incidents)

**High-Risk Merchants:**
- M348934600
- M692898500  
- M1823072687

### Dashboard Components (11 Charts)

1. **Transaction Count by Service Category**
2. **Fraudulent vs. Legitimate Payment Distribution**
3. **Customer Age Group Distribution Analysis**
4. **High-Risk Merchant Identification**
5. **Fraudulent Transactions by Age (Table)**
6. **Fraudulent Transactions by Age (Chart)**
7. **Fraud Distribution Across Service Categories**
8. **Temporal Fraud Patterns by Time Period**
9. **Gender-Based Fraud Distribution**
10. **Female Customer Fraud Patterns by Category**
11. **High-Risk Age Groups by Merchant Analysis**

## Technical Implementation
- **Platform:** Splunk Enterprise on Ubuntu
- **Data Processing:** CSV import with dynamic field recognition
- **Visualization:** 11 interactive dashboard panels
- **Export:** PDF dashboard reports for stakeholders

## Business Impact
- **Proactive Fraud Detection:** Real-time pattern identification
- **Resource Optimization:** Targeted investigation on high-risk segments
- **Customer Protection:** Enhanced security for vulnerable demographics
- **Operational Efficiency:** Data-driven fraud prevention

## Recommendations
1. Enhanced monitoring for transportation service transactions
2. Specialized fraud prevention for 19-25 age demographic
3. Merchant-specific risk assessment protocols
4. Gender-aware fraud detection algorithms

## Project Files
- [📊 Dashboard Results](./fraud_detection_dashboard2-2024-08-06.pdf) - Exported dashboard
- `prepared_data.csv` - Analysis dataset
- `Task 1_Data analysis_Dashboard.pdf` - Project requirements

---

**Lead Analyst:** Randal - Cybersecurity Data Analyst  
**Client:** Commonwealth Bank Fraud Team  
**Resolution Time:** 7.5 hours (Same-day delivery)
---

## Contact Information

**Project Team:** Cybersecurity Team  
**Lead Analyst:** Randal - Cybersecurity Data Analyst  
**Client Contact:** Commonwealth Bank Fraud Team  

For questions or additional information, please refer to the ServiceNow tickets linked above.

---

*Last Updated: June 4, 2025*  
*Project Status: ✅ Completed & Delivered*
