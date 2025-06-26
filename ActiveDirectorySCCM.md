# Randal Quinn – Active Directory + SCCM Lab Portfolio

<p align="center">
  <img src="https://img.shields.io/badge/Windows_Server_2022-0078D4?logo=windows&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Configuration_Manager-FFA500?logo=microsoft&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/VMware_Workstation-607078?logo=vmware&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/PowerShell-012456?logo=powershell&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Splunk_Enterprise-008000?logo=splunk&logoColor=white&style=for-the-badge" />
</p>

This repository showcases my hands-on lab project to design and build the enterprise envionment foundation. The purpose is to expand this environment and demonstrate core competencies in enterprise security tools, data analysis, and threat response for later Security Analyst projects.

---

## 🔐 Project Includes

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
<img src="Diagrams/Screenshot%202025-06-03%20163246.png" alt="Logical Topology Diagram">

### AD OU Structure
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20184750.png" alt="AD OU Structure">

### AD Schema Extended
<img src="ActiveDirectory-SCCM/Screenshot%202025-06-03%20143000.png" alt="AD Schema Extended">

### GPO Management
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20190028.png" alt="GPO Management">

### DNS Manager
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20185914.png" alt="DNS Manager">

### DHCP Scope
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20185636.png" alt="DHCP Scope">

### VM's Joined to the Domain
<img src="ActiveDirectory-SCCM/Screenshot%202025-06-03%20152510.png" alt="VM Joined 1">
<img src="ActiveDirectory-SCCM/Screenshot%202025-06-03%20152554.png" alt="VM Joined 2">

### SCCM - Configuration Manager Console
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20191004.png" alt="SCCM Console">

### SQL Server
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20191310.md.png" alt="SQL Server 1">
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20191350.md.png" alt="SQL Server 2">

### SSRS
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20191454.png" alt="SSRS">

### Deployment Verified
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20191210.png" alt="Deployment Verified 1">
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20193526.png" alt="Deployment Verified 2">
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20192823.png" alt="Deployment Verified 3">
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20192921.png" alt="Deployment Verified 4">

### CMTrace Log Viewer
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20191549.png" alt="CMTrace Log Viewer 1">
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20193722.png" alt="CMTrace Log Viewer 2">


---
[← Back to Main README](SecurityEngineering_MyPracticalJourney.md)
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
