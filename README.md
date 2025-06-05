# Randal Quinn – Cybersecurity Analyst Lab Portfolio

<p align="center">
  <img src="https://img.shields.io/badge/Splunk_Enterprise-008000?logo=splunk&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Configuration_Manager-FFA500?logo=microsoft&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Windows_Server_2022-0078D4?logo=windows&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/VMware_Workstation-607078?logo=vmware&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/PowerShell-012456?logo=powershell&logoColor=white&style=for-the-badge" />
</p>

This repository showcases my hands-on cybersecurity lab projects, incident response simulations, and Splunk analytics dashboards. The purpose is to demonstrate core competencies in enterprise security tools, data analysis, and threat response.

---

## 🔐 Projects Included

### 1. Active Directory + SCCM Lab
- Built a domain controller with Windows Server 2022
- Installed and configured SCCM (Configuration Manager) with SQL Server and SSRS
- Created OUs, GPOs, domain users, and deployed SCCM clients via GPO
- Extended AD Schema and monitored SCCM logs using CMTrace

📁 Folder: `/ActiveDirectory-SCCM/`

#### `/ActiveDirectory-SCCM/README.md`
```markdown
# Active Directory + SCCM Lab Setup

## Overview
This project simulates an enterprise deployment of Active Directory and SCCM on a virtual network.

## Key Components
- Windows Server 2022 Domain Controller
- Windows Server 2022 SCCM Server
- Windows 11 Workstation

## Setup Steps
1. Configure static IPs on each VM.
2. Install and configure Active Directory, DNS, DHCP.
3. Join all VMs to the domain.
4. Install SQL Server, SSRS, and SCCM.
5. Extend AD Schema and deploy clients.
6. Verify deployment via Configuration Manager Console.

## Screenshot Examples Below
![Logical Topology Diagram] ![AD OU Structure] ![AD Schema Extended]
![GPO Management]![DNS Manager] ![DHCP Scope] ![VM's Joined Domain]
![SCCM Console] ![SQL Server] ![SSRS] ![Deployment Verified] ![CMTRace Log Viewer]

## Tools Used
- VMware Workstation 17 Pro
- CMTrace Log Viewer
```
## Active Directory + SCCM Lab Screenshots
### Logical Topology Diagram
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/8a0096d6e7097a186cb0a4896476a8875061f02d/Diagrams/Screenshot%202025-06-03%20163246.png)

### AD OU Structure
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/734d74cd19a7e7e57d795a2808ff3971dd42b1c2/ActiveDirectory-SCCM/Screenshot%202025-05-26%20184750.png)

### AD Schema Extended
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/41cb09557db4884718b628ddbfe8f0ab33972c61/ActiveDirectory-SCCM/Screenshot%202025-06-03%20143000.png)

### GPO Management
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/6e90bd22bdb529e1fa32a2ebf749854a1a4f665e/ActiveDirectory-SCCM/Screenshot%202025-05-26%20190028.png)

### DNS Manager
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/5f85c18c34bc8a210704046ee584f25d62fbb2c3/ActiveDirectory-SCCM/Screenshot%202025-05-26%20185914.png)

### DHCP Scope
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/5f85c18c34bc8a210704046ee584f25d62fbb2c3/ActiveDirectory-SCCM/Screenshot%202025-05-26%20185636.png)

### VM's Joined to the Domain
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/e9c62845e2f2dd164a181d0937384b42f8f3ceed/ActiveDirectory-SCCM/Screenshot%202025-06-03%20152510.png)
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/e9c62845e2f2dd164a181d0937384b42f8f3ceed/ActiveDirectory-SCCM/Screenshot%202025-06-03%20152554.png)

### SCCM - Configuration Manager Console
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/f790e934d81da5bafaf04970a6e0c2f4ce0fdf05/ActiveDirectory-SCCM/Screenshot%202025-05-26%20191004.png)

### SQL Server
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/de6485b5246e06cd83c9c98635ba598c0a85ae57/ActiveDirectory-SCCM/Screenshot%202025-05-26%20191310.md.png)
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/de6485b5246e06cd83c9c98635ba598c0a85ae57/ActiveDirectory-SCCM/Screenshot%202025-05-26%20191350.md.png)

### SSRS
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/734d74cd19a7e7e57d795a2808ff3971dd42b1c2/ActiveDirectory-SCCM/Screenshot%202025-05-26%20191454.png)

### Deployment Verified
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/29cc1fd713b828d939022db7b9161a95f3583d7e/ActiveDirectory-SCCM/Screenshot%202025-05-26%20191210.png)
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/734d74cd19a7e7e57d795a2808ff3971dd42b1c2/ActiveDirectory-SCCM/Screenshot%202025-05-26%20193526.png)
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/734d74cd19a7e7e57d795a2808ff3971dd42b1c2/ActiveDirectory-SCCM/Screenshot%202025-05-26%20192823.png)
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/734d74cd19a7e7e57d795a2808ff3971dd42b1c2/ActiveDirectory-SCCM/Screenshot%202025-05-26%20192921.png)

### CMTrace Log Viewer
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/734d74cd19a7e7e57d795a2808ff3971dd42b1c2/ActiveDirectory-SCCM/Screenshot%202025-05-26%20191549.png)
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/734d74cd19a7e7e57d795a2808ff3971dd42b1c2/ActiveDirectory-SCCM/Screenshot%202025-05-26%20193722.png)





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
| **Original Ticket** | Initial incident creation and requirements (INC0001234) | [🎫 View Original Ticket](./https://quinnran76.github.io/Cybersecurity-Portfolio/docs/servicenow_form_template.html) |
| **Resolved Ticket** | Completed resolution with deliverables | [✅ View Resolved Ticket](./servicenow_ticket_resolved.html) |

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
- [🎫 Original ServiceNow Ticket](./servicenow_form_template.html) - View initial requirements
- [✅ Resolved ServiceNow Ticket](./servicenow_ticket_resolved.html) - View completion details
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




### 3. Incident Response Simulation
- Simulated email phishing attack targeting an HR department
- Drafted a full response plan including identification, containment, eradication, and recovery
- Suggested implementation of MFA, HIPS/IPS, and user awareness training

📁 Folder: `/IncidentResponse-Phishing/`

#### `/IncidentResponse-Phishing/README.md`
```markdown
# Incident Response Simulation – Phishing Attack

## Overview
This case study walks through a simulated phishing attack and details a complete IR response.

## Attack Scenario
- Phishing email from fake HR account
- Users submitted credentials and downloaded malware

## Response Steps
1. Identify impacted users and systems
2. Contain malware and disable accounts
3. Eradicate malware and patch vulnerabilities
4. Recover affected systems
5. Educate users and revise email security protocols

## Screenshot Examples
![Phishing Email Example](images/phishing-email.png)
![Incident Flowchart](images/incident-flow.png)

## Lessons Learned
- Importance of simulated phishing training
- Need for layered email filtering and MFA
```

### 4. Scripts and Automation (Optional/Future Additions)
- Collection of PowerShell or Bash scripts used in lab automation or data forwarding

📁 Folder: `/Scripts/`

#### `/Scripts/README.md`
```markdown
# Custom Scripts

This folder contains PowerShell and Bash scripts used during the cybersecurity lab deployments and automation.

## Contents
- `deploy-gpo.ps1` – Sample script to apply GPO policies
- `install-sysmon.ps1` – Automates Sysmon installation and config

## Screenshot Examples
![Sysmon Config Script](images/sysmon-script.png)

## Usage
Scripts are documented with comments. Please modify as needed for your lab environment.
```

---

## 🧰 Tools & Technologies Used
- Windows Server 2022
- SCCM Configuration Manager 2203 & 2303
- Splunk Enterprise + Universal Forwarder
- Ubuntu Server 24.04
- Group Policy, Sysmon, CMTrace
- VMware Workstation 17 Pro
- PowerShell, Bash

---

## 🔗 How to Use This Repository
- Each folder contains a `README.md` with setup steps and configuration screenshots
- Sample queries, JSON exports, and logs are included where applicable
- This repo serves both as a learning journal and a portfolio for employers and peers
