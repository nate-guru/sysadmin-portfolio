# Systems Administrator Portfolio

This repository documents my hands-on lab projects simulating a real-world Windows enterprise environment, with a focus on systems administration. All work is performed in an Azure-based virtual lab, using Windows Server 2022 and Windows 10 clients to build out core infrastructure services like Active Directory, DNS, Group Policy, and backup/recovery. PowerShell and troubleshooting are integrated throughout.

The goal of this portfolio is to demonstrate practical, job-ready skills that reflect the day-to-day responsibilities of a systems administrator.

---

## Projects

### [Project 1 – Active Directory Domain Setup](./Project-01_AD-DS-Setup)
Deployed a Windows Server 2022 VM in Azure and promoted it to a domain controller in a new forest (`guruwatte.lab`). Configured DNS and verified the environment. Includes a breakdown of key warnings and a real-world recovery from an RDP lockout caused by incorrect static IP configuration.

### Project 2 – User, Group, and OU Management *(Coming Soon)*
Will cover the creation of a realistic organizational unit structure, role-based security groups, and user accounts to simulate an IT-managed workforce. Will also include PowerShell automation for bulk account creation.

### Project 3 – Group Policy Implementation *(Planned)*
Will demonstrate how to enforce workstation policies across different departments using Group Policy Objects (GPOs), including security hardening, UX changes, and folder redirection.

---

## Goals

- Build a full-featured, enterprise-style Windows environment in Azure
- Showcase skills in server deployment, domain management, and security configuration
- Practice real-world troubleshooting and documentation
- Integrate PowerShell scripting as a long-term automation strategy
