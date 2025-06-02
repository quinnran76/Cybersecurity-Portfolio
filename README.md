# Randal Quinn – Cybersecurity Analyst Lab Portfolio

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

## Screenshot Examples
![AD OU Structure](images/ad-ou-structure.png)
![SCCM Console](images/sccm-console.png)


## Tools Used
- VMware Workstation 17 Pro
- CMTrace Log Viewer
```
