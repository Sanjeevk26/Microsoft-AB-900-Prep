# Microsoft Purview Insider Risk Management

## Overview

Microsoft Purview Insider Risk Management helps organizations identify, prioritize, investigate, and respond to risky behavior performed by internal users.

It helps protect against:
- Data theft  
- Data leaks  
- Intellectual property theft  
- Regulatory compliance violations  
- Risky AI usage  
- Fraud and insider threats  

---

# Key Goals

Insider Risk Management is designed to:

- Detect risky insider behavior  
- Provide investigation tools  
- Support compliance requirements  
- Reduce accidental and malicious data exposure  

---

# Common Risk Scenarios

## Data Theft

Examples:
- Employees downloading sensitive files before leaving the company  
- Copying files to cloud storage or external devices  

---

## Data Leaks

Can occur through:
- Accidental oversharing  
- Malicious sharing of sensitive information  

---

## Confidentiality Violations

Includes:
- Unauthorized disclosures  
- Sharing protected information  

---

## Intellectual Property Theft

Protection against:
- Theft of proprietary business information  
- Unauthorized transfer of confidential assets  

---

## Financial and Regulatory Violations

Examples:
- Fraud  
- Insider trading  
- Regulatory breaches  

---

# Core Principles

Microsoft Purview Insider Risk Management focuses on:

- Transparency  
- Configurable policies  
- Integration with Microsoft security tools  
- Actionable investigation workflows  

---

# Data Sources Used

The solution analyzes signals from:

- Microsoft 365 Audit Logs  
- Exchange Online activity  
- Microsoft Entra activity/history  
- Microsoft 365 HR Data Connector  

---

## Human Resources Integration

The HR connector helps identify:
- Departing employees  
- Resignation dates  
- Termination dates  

---

# Accessing Insider Risk Management

Microsoft Purview Portal:

- https://purview.microsoft.com  

Navigate to:
- Solutions → Insider Risk Management  

---

# Recommendations Dashboard

Provides guidance in areas such as:

- Initial setup steps  
- Investigation improvements  
- Detection tuning  
- Integration with:
  - DLP  
  - Microsoft Defender XDR  

---

# Insider Risk Policies

Policies define:
- Risk indicators  
- Detection conditions  
- Response workflows  

---

## Policy Types

### Quick Policies
- Preconfigured templates  
- Faster deployment  

---

### Custom Policies
- Fully configurable  
- Tailored to organizational needs  

---

# Built-In Policy Templates

## 1. Data Theft by Departing Users

Detects:
- File downloads  
- Printing sensitive documents  
- Uploading files to cloud storage  

Supported cloud storage examples:
- Box  
- Dropbox  
- Google Drive  
- Amazon S3  
- Azure Storage  

Integrates with:
- HR Connector  
- Microsoft Entra account deletion events  

---

## 2. Data Leaks

Detects:
- Oversharing of sensitive information  
- Risky sharing behavior  

Can target:
- All users  
- Risky users  
- Priority users  

---

# Priority and Risky Users

Priority users can be configured manually.

Risky users may be identified using:
- HR connector signals  
- Communication Compliance policies  

---

# Communication and Behavior Signals

Monitors signals from:

- Exchange  
- Teams  
- Viva Engage  

---

## Risk Indicators Include

### Inappropriate Content
- Hate speech  
- Sexual language  
- Violent language  
- Self-harm references  
- Harassment or discrimination  

---

### Financial Compliance Risks
- Customer complaints  
- Money laundering  
- Regulatory collusion  
- Stock manipulation  
- Unauthorized disclosures  

---

### Sensitive Information Exposure
- Sharing protected or confidential information  

---

# User Reporting

Users can:
- Report Teams chat messages for review  

---

# Patient Data Misuse

Protects healthcare-related information.

Supports compliance requirements such as:
- HIPAA (Health Insurance Portability and Accountability Act)  
- HITECH Act  

Requires:
- Microsoft Healthcare Connector  

---

# Risky AI Usage

Monitors risky use of:
- Microsoft 365 Copilot  
- Microsoft Copilot  
- AI agents  

Examples:
- Sensitive prompts  
- Exposure of confidential information  

---

## Browser Extensions Required

Requires installation of:
- Microsoft Insider Risk Extension for Edge  
- Microsoft Purview Extension for Chrome  

---

# Risky Browser Usage

Scores browsing activity against:
- Organizational security policies  

---

# Security Policy Violations

Monitors violations using:
- Microsoft Defender for Endpoint  
- Endpoint integration for Insider Risk Management  

Can target:
- All users  
- Departing users  
- Risky users  
- Priority users  

---

# Alerts and Investigations

Policies can generate alerts based on:
- Severity  
- Risk indicators  

---

## Triage

Alerts are reviewed and prioritized.

Possible outcomes:
- False positive dismissal  
- Escalation for investigation  

---

# Cases and Investigations

If deeper investigation is needed:
- Create a case  

---

## Case Dashboard Features

Includes:
- User activity timeline  
- Content Explorer  
- Files and emails involved  
- Investigator notes  

---

# Response Actions

Organizations can respond with:

- Reminder notifications  
- User guidance  
- Retraining  
- Escalation or disciplinary actions  

---

# Reporting

Reports available include:

- Alerts  
- Analytics  
- Cases  
- User activity  
- Usage reports  

---

# Benefits

- Detects insider threats early  
- Helps prevent data theft and leaks  
- Supports compliance investigations  
- Integrates with Microsoft security ecosystem  

---

# Key Concepts

| Concept | Purpose |
|--------|---------|
| Insider Risk Management | Detect risky internal behavior |
| HR Connector | Identify departing or risky employees |
| Triage | Review and prioritize alerts |
| Cases | Investigate insider incidents |
| Risky AI Usage | Monitor unsafe AI interactions |
| Priority Users | High-risk or high-value users |

---

# Summary

Microsoft Purview Insider Risk Management helps organizations detect and investigate risky behavior from internal users.

It supports:
- Data theft prevention  
- Compliance monitoring  
- Risky AI usage detection  
- Insider threat investigations  

The solution integrates with Microsoft 365, Microsoft Defender, Microsoft Entra, HR systems, and other Microsoft Purview services.

---

## One-Line Summary

> Microsoft Purview Insider Risk Management detects and investigates risky internal behavior to help prevent data theft, leaks, compliance violations, and insider threats.
