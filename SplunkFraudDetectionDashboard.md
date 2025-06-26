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
### 📋 ServiceNow Incident Tracking

| Ticket Status | Description | Link |
|---------------|-------------|------|
| **Original Ticket** | Initial incident creation and requirements (INC0001234) | [🎫 View ServiceNow Ticket](https://quinnran76.github.io/Cybersecurity-Portfolio/servicenow_ticket_index.html) |
| **Resolved Ticket** | Completed resolution with deliverables | [✅ View Resolved ServiceNow Ticket](https://quinnran76.github.io/Cybersecurity-Portfolio/servicenow_resolved_index.html) |

**Incident Details:**
- **Ticket ID:** INC0001234
- **Client:** Commonwealth Bank Fraud Team  
- **Priority:** High (2) - Critical fraud detection infrastructure
- **Status:** ✅ Resolved  
- **Resolution Time:** 7.5 hours (Same-day delivery)
- **Assigned Analyst:** Randal - Cybersecurity Data Analyst

## Dataset Analysis
**Source:** Commonwealth Bank transaction dataset (`prepared_data.csv` - 245KB)  
**Total Records Analyzed:** Complete customer transaction history  
**Fraud Cases Identified:** 92 confirmed fraudulent transactions

### Key Dataset Fields
- **Demographics:** Age groups (0-5), Gender (M/F)
- **Transaction Details:** Merchant IDs, Service categories, Transaction amounts
- **Temporal Data:** Step/month indicators for trend analysis
- **Risk Indicators:** Binary fraud flags (0 = legitimate, 1 = fraudulent)

## Dashboard Components
**Complete 11-Chart Analytics Suite:**

### Core Fraud Analytics
1. **Chart 1:** Transaction Count by Service Category
2. **Chart 2:** Fraudulent vs. Legitimate Payment Distribution
3. **Chart 3:** Customer Age Group Distribution Analysis
4. **Chart 4:** High-Risk Merchant Identification

### Demographic Risk Analysis
5. **Chart 5:** Fraudulent Transactions by Age (Tabular View)
6. **Chart 6:** Fraudulent Transactions by Age (Visual Chart)
7. **Chart 9:** Gender-Based Fraud Distribution Analysis
8. **Chart 10:** Female Customer Fraud Patterns by Category

### Advanced Pattern Detection
9. **Chart 7:** Fraud Distribution Across Service Categories
10. **Chart 8:** Temporal Fraud Patterns by Time Period
11. **Chart 11:** High-Risk Age Groups by Merchant Analysis

## Implementation & Setup
**Environment:** Splunk Enterprise on secure infrastructure  
**Deployment Process:**
1. **Infrastructure Setup:** Splunk Enterprise installation and configuration
2. **Data Integration:** CSV import using Splunk's "Add Data" functionality  
3. **Field Mapping:** Dynamic field recognition and categorization
4. **Dashboard Creation:** 11 custom visualization panels with search queries
5. **Export & Delivery:** PDF dashboard export for stakeholder distribution

### Technical Implementation
- **Platform:** Splunk Enterprise (Latest Version)
- **Data Processing:** Real-time CSV parsing and field extraction
- **Visualization:** Interactive charts with drill-down capabilities  
- **Export Format:** Executive-ready PDF dashboard reports
- **Security:** Secure data handling following banking compliance standards

## Key Analytical Findings
**Critical Risk Indicators Identified:**

### High-Risk Service Categories
- **Transportation Services:** Highest fraud concentration
- **Health Services:** Secondary risk category  
- **Food & Dining:** Significant fraud activity
- **Wellness & Beauty:** Emerging risk area

### Demographic Risk Patterns
- **Age Group 1 (19-25 years):** 38 fraud incidents - **HIGHEST RISK**
- **Age Group 2 (26-35 years):** 24 fraud incidents
- **Gender Analysis:** Female customers show 52 incidents vs. Male 40 incidents
- **Total Risk Population:** 92 confirmed fraud cases across all demographics

### Merchant Risk Assessment  
**High-Risk Merchants Flagged:**
- M348934600, M692898500, M1823072687 (Require enhanced monitoring)
- Geographic and temporal clustering identified
- Specific merchant-category combinations showing elevated risk

## Visual Documentation
![Commonwealth Bank Fraud Analytics](images/fraud-category.png)  
*Fraud distribution across service categories showing transportation as highest risk*

![Demographic Risk Analysis](images/fraud-age-merchant.png)  
*Age-based fraud patterns with merchant correlation analysis*

## Business Impact & Recommendations
**Immediate Value Delivered:**
- **Proactive Fraud Detection:** Real-time identification of high-risk transaction patterns
- **Resource Optimization:** Targeted investigation focus on highest-risk demographics  
- **Customer Protection:** Enhanced security for vulnerable customer segments
- **Operational Efficiency:** Data-driven fraud prevention replacing reactive approaches

**Strategic Recommendations:**
1. Enhanced monitoring for transportation service transactions
2. Specialized fraud prevention for 19-25 age demographic
3. Merchant-specific risk assessment protocols
4. Gender-aware fraud detection algorithms

---

## Quick Navigation

- [📁 Project Files](#project-files)
- [🎫 Original ServiceNow Ticket](https://quinnran76.github.io/Cybersecurity-Portfolio/servicenow_ticket_index.html) - View initial requirements
- [✅ Resolved ServiceNow Ticket](https://quinnran76.github.io/Cybersecurity-Portfolio/servicenow_resolved_index.html) - View completion details
- [📊 Dashboard Results](./fraud_detection_dashboard2-2024-08-06.pdf) - View exported dashboard

## Project Files

```
fraud-detection-project/
├── servicenow_form_template.html          # Original ServiceNow ticket
├── servicenow_ticket_resolved.html        # Resolved ServiceNow ticket  
├── fraud_detection_dashboard2-2024-08-06.pdf  # Dashboard export
├── prepared_data.csv                      # Analysis dataset
├── Task 1_Data analysis_Dashboard.pdf     # Project requirements
└── README.md                             # This file
```

---

## Contact Information

**Project Team:** Cybersecurity Team  
**Lead Analyst:** Randal - Cybersecurity Data Analyst  
**Client Contact:** Commonwealth Bank Fraud Team  

For questions or additional information, please refer to the ServiceNow tickets linked above.

---

*Last Updated: June 4, 2025*  
*Project Status: ✅ Completed & Delivered*
