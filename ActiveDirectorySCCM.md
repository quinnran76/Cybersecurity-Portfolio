# Randal Quinn – Active Directory + SCCM Lab Portfolio

<p align="center">
  <img src="https://img.shields.io/badge/Windows_Server_2022-0078D4?logo=windows&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Configuration_Manager-FFA500?logo=microsoft&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/VMware_Workstation-607078?logo=vmware&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/PowerShell-012456?logo=powershell&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Splunk_Enterprise-008000?logo=splunk&logoColor=white&style=for-the-badge" />
</p>

This repository showcases my hands-on lab project simulating an enterprise-level deployment of Active Directory and System Center Configuration Manager (SCCM) in a virtualized environment using VMware Workstation, designed as a foundational platform to demonstrate core competencies in enterprise security tools, data analysis, and threat response in future Security Analyst projects.


---

## Project Folder

`/ActiveDirectory-SCCM/`

## Overview

The lab environment includes:

- A Domain Controller running Windows Server 2022 with Active Directory, DNS, and DHCP
- A separate SCCM Server with SQL Server and SSRS installed
- A Windows 11 workstation joined to the domain

## Tools and Technologies

- VMware Workstation 17 Pro  
- Windows Server 2022  
- Windows 11  
- SQL Server + SSRS  
- Microsoft Endpoint Configuration Manager (SCCM)  
- CMTrace Log Viewer  

## Setup Steps

1. [Configure static IP addresses on all virtual machines](#logical-topology-diagram)
2. [Install and configure Active Directory, DNS, and DHCP roles](#dns-configuration)
3. [Join all VMs to the domain](#domain-membership-verification)
4. [Install SQL Server, SSRS, and SCCM](#sql-server-and-ssrs-interface)
5. [Extend the Active Directory schema to support SCCM](#active-directory-schema-extension)
6. [Create OUs, GPOs, and domain users](#active-directory-ou-structure)
7. [Deploy SCCM clients using Group Policy](#gpo-management)
8. [Verify client deployment using SCCM Console and CMTrace](#deployment-verification)

## Screenshot Examples

### Logical Topology Diagram
<img src="Diagrams/Screenshot%202025-06-03%20163246.png" alt="Logical Topology Diagram">

### Active Directory OU Structure
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20184750.png" alt="AD OU Structure">

### Active Directory Schema Extension
<img src="ActiveDirectory-SCCM/Screenshot%202025-06-03%20143000.png" alt="AD Schema Extended">

### GPO Management
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20190028.png" alt="GPO Management">

### DNS Configuration
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20185914.png" alt="DNS Manager">

### DHCP Scope Settings
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20185636.png" alt="DHCP Scope">

### Domain Membership Verification
<img src="ActiveDirectory-SCCM/Screenshot%202025-06-03%20152510.png" alt="VM Joined 1">
<img src="ActiveDirectory-SCCM/Screenshot%202025-06-03%20152554.png" alt="VM Joined 2">

### SCCM Console View
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20191004.png" alt="SCCM Console">

### SQL Server and SSRS Interface
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20191310.md.png" alt="SQL Server 1">
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20191350.md.png" alt="SQL Server 2">
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20191454.png" alt="SSRS">

### Deployment Verification
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20191210.png" alt="Deployment Verified 1">
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20193526.png" alt="Deployment Verified 2">
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20192823.png" alt="Deployment Verified 3">
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20192921.png" alt="Deployment Verified 4">

### CMTrace Log Output
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20191549.png" alt="CMTrace Log Viewer 1">
<img src="ActiveDirectory-SCCM/Screenshot%202025-05-26%20193722.png" alt="CMTrace Log Viewer 2">

> Screenshots are stored in the `/ActiveDirectory-

---
[← Back to Main README](README.md)
---

## Key Accomplishments

- Extended the Active Directory schema for SCCM integration  
- Used GPO to deploy SCCM clients across domain-joined machines  
- Verified SCCM functionality through logs, reports, and console access  
- Created a modular and scalable lab for enterprise systems testing

---

## 🔗 How to Use This Repository
- Each folder contains a `README.md` with setup steps and configuration screenshots
- Sample queries, JSON exports, and logs are included where applicable
- This repo serves both as a learning journal and a portfolio for employers and peers
