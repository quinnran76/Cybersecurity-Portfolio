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
![SCCM Console]

## Tools Used
- VMware Workstation 17 Pro
- CMTrace Log Viewer
```
## Active Directory + SCCM Lab Screenshots
### Logical Topology Diagram
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/012c23112d77238c84fac03b6f61fab1aa347949/Diagrams/Screenshot%202025-06-02%20172826.png)

### AD OU Structure
![image alt](https://github.com/quinnran76/Cybersecurity-Portfolio/blob/734d74cd19a7e7e57d795a2808ff3971dd42b1c2/ActiveDirectory-SCCM/Screenshot%202025-05-26%20184750.png)

### AD Schema Extended
![image alt](

### 2. Splunk Fraud Detection Dashboard
- Used Splunk Enterprise on Ubuntu to ingest and visualize financial transaction data
- Created indexes and dashboards to identify fraud by age, gender, merchant, and category
- Used Splunk's “Interesting Fields” to create filters for detecting anomalies

📁 Folder: `/Splunk-Dashboard/`

#### `/Splunk-Dashboard/README.md`
```markdown
# Splunk Fraud Detection Dashboard

## Overview
This project uses Splunk Enterprise to visualize financial fraud patterns across customer demographics and transaction details.

## Dataset Fields
- Age, Gender, Merchant, Category, Amount, Fraud Flag

## Dashboard Charts
- Fraud Count by Category
- Fraud Trends by Age, Gender, Merchant
- Top 5 Merchants by Fraud Reports

## Setup
1. Install Splunk on Ubuntu Server 24.04.
2. Import CSV data using "Add Data" in Splunk.
3. Use "Interesting Fields" for dynamic filters.
4. Create dashboard panels using search queries.

## Screenshot Examples
![Fraud by Category](images/fraud-category.png)
![Fraud by Age and Merchant](images/fraud-age-merchant.png)
```

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
