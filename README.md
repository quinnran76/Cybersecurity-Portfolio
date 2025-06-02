# Randal Quinn – Cybersecurity Analyst Lab Portfolio

![Security+](https://img.shields.io/badge/CompTIA-Security%2B-informational?style=flat&logo=compTIA&logoColor=white&color=orange)
![Splunk](https://img.shields.io/badge/Splunk-User-blue?style=flat&logo=splunk&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-Scripting-blue?style=flat&logo=powershell)
![Windows Server](https://img.shields.io/badge/Windows%20Server-2022-informational?style=flat&logo=windows&logoColor=white&color=blue)
![Ubuntu](https://img.shields.io/badge/Linux-Ubuntu-informational?style=flat&logo=ubuntu&logoColor=white&color=orange)
![VMware](https://img.shields.io/badge/VMware-Workstation-59666C?style=flat&logo=vmware&logoColor=white)
![Azure AD](https://img.shields.io/badge/Microsoft-Azure%20AD-blue?style=flat&logo=microsoft-azure&logoColor=white)
![OKTA](https://img.shields.io/badge/OKTA-MFA-blue?style=flat&logo=okta&logoColor=white)
![Intune](https://img.shields.io/badge/Microsoft-Intune-blue?style=flat&logo=microsoft&logoColor=white)
![SCCM](https://img.shields.io/badge/SCCM-ConfigMgr-blue?style=flat&logo=microsoft&logoColor=white)
![ServiceNow](https://img.shields.io/badge/ServiceNow-Ticketing-lightgrey?style=flat&logo=servicenow&logoColor=white)


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
