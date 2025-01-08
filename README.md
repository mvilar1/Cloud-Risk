# Azure Infrastructure Setup and Risk Assessment Project

## Overview
This project demonstrates the deployment of a secure Azure-based infrastructure, risk assessment using industry-standard frameworks (**NIST 800-30**, **ISO 27001**), and manual resource configuration.

The infrastructure includes an Azure VM hosting the OWASP Juice Shop application and a detailed risk assessment identifying vulnerabilities and proposing mitigation strategies.

## Objectives
- Deploy Azure infrastructure manually.
- Perform a detailed risk assessment using tools like **OWASP ZAP** and **Nessus Essentials**.
- Align the assessment process with **NIST 800-30** and **ISO 27001** standards.

## Tools and Frameworks
- **Frameworks**: NIST 800-30, ISO 27001.
- **Tools**:
  - OWASP ZAP (Application Vulnerability Scanning).
  - Nessus Essentials (Network and VM Vulnerability Scanning).
  - Azure Security Center (Cloud-Native Recommendations).

## Infrastructure
The Azure environment includes:
- An Azure VM hosting the OWASP Juice Shop application.
- Network Security Groups (NSG) configured to allow HTTP traffic (port 3000) and secure RDP access (port 3389).
- Azure Blob Storage for application data (optional).


## Risk Assessment Process
1. **Manual Infrastructure Setup**:
   - Created an Azure VM and configured the Network Security Group (NSG) for access control.
   - OWASP Juice Shop was deployed as a test application.
2. **Vulnerability Scanning**:
   - Used OWASP ZAP to scan the Juice Shop application for vulnerabilities like SQL Injection.
   - Nessus Essentials was used to identify VM misconfigurations and open ports.
3. **Risk Evaluation**:
   - Assessed risks using a likelihood-impact matrix.
4. **Mitigation**:
   - Manually applied mitigations, such as closing unused ports and restricting RDP access.
