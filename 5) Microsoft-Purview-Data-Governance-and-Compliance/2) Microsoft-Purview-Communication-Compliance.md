# Microsoft Purview Communication Compliance

## Overview

Microsoft Purview Communication Compliance helps organizations detect, investigate, and respond to potentially inappropriate or risky communications across Microsoft 365 and connected platforms.

It supports:
- Regulatory compliance monitoring  
- Enforcement of corporate communication policies  
- Detection of risky or inappropriate behavior  
- Monitoring of AI-generated interactions  

---

# Supported Communication Sources

Communication Compliance can monitor content from:

- Microsoft Teams  
- Exchange Online (Emails)  
- Microsoft 365 Copilot  
- Microsoft Copilot Chat  
- Viva Engage  
- Third-party communication platforms  

---

# AI and Copilot Integration

Communication Compliance can also analyze:
- Microsoft 365 Copilot interactions  
- AI-generated prompts and responses  
- Communications through AI applications integrated using:
  - Microsoft Entra  
  - Microsoft Purview Data Map connectors  

---

# Accessing Communication Compliance

Microsoft Purview Portal:

- https://purview.microsoft.com  

Navigate to:
- Solutions → Communication Compliance  

---

# Initial Setup Requirements

Before creating policies, administrators should:

- Assign Communication Compliance permissions  
- Enable auditing  
- Optionally configure:
  - Distribution groups  
  - Microsoft 365 groups  
  - Mail-enabled security groups  

---

# Communication Compliance Policies

Policies are used to monitor communications for specific risks or violations.

---

# Built-In Policy Templates

## 1. Inappropriate Text Detection

Detects:
- Abusive language  
- Offensive language  
- Harassment or toxic communication  

---

## 2. Inappropriate Images

Detects:
- Adult or explicit images  
- Inappropriate visual content  

---

## 3. Sensitive Information Types (SITs)

Detects:
- Credit card numbers  
- Passport numbers  
- Tax IDs  
- Other sensitive information  

---

## 4. Financial Regulatory Compliance

Monitors communications for:
- Financial compliance terms  
- Regulatory violations  
- Industry-specific financial language  

---

## 5. Conflict of Interest Detection

Detects:
- Suspicious interactions between users or groups  
- Potential conflicts of interest  

---

## 6. Microsoft Copilot Interaction Monitoring

Monitors:
- Copilot prompts  
- AI-generated responses  
- Risky or inappropriate AI interactions  

---

## 7. Custom Policies

Organizations can create custom compliance policies tailored to specific business requirements.

---

# User-Reported Messages

Communication Compliance can also review:
- User-reported Teams messages  

Supported message types:
- Channel chats  
- Group chats  
- Private chats  

---

# Alerts and Investigations

When policy violations are detected, alerts are generated for investigation.

---

# Alert Investigation Features

Administrators can:

- Review flagged messages  
- View conversation summaries  
- Access detailed message views  
- Review user activity history  
- Review past remediation actions  

---

# Alert Resolution Actions

Alerts can be resolved using actions such as:

- Marking alerts as:
  - Compliant  
  - Non-compliant  
  - Questionable  
  - Custom-tagged  

- Sending notices to users  
- Opening investigation cases  

---

# Escalation and eDiscovery

Alerts can be escalated to:
- Other reviewers  
- Microsoft Purview eDiscovery investigations  

---

# Reporting and Analytics

Communication Compliance provides reports such as:

- Recent policy matches  
- Users with the highest number of policy matches  
- Detailed compliance and investigation reports  

---

# Benefits

- Detects risky or inappropriate communications  
- Supports regulatory compliance  
- Helps investigate insider risks  
- Monitors AI and Copilot interactions  
- Provides centralized investigation workflows  

---

# Key Concepts

| Concept | Purpose |
|--------|---------|
| Communication Compliance | Monitor risky communications |
| Policy Templates | Predefined monitoring policies |
| Alerts | Notifications of policy violations |
| SITs | Sensitive Information Types |
| eDiscovery Integration | Escalate investigations |
| Copilot Monitoring | Detect risky AI interactions |

---

# Summary

Microsoft Purview Communication Compliance helps organizations monitor communications across Microsoft 365 and connected platforms for inappropriate content, sensitive information exposure, regulatory violations, and risky AI interactions.

It provides:
- Policy-based monitoring  
- Alert investigation workflows  
- Reporting and analytics  
- Integration with Microsoft Purview and eDiscovery  

---

## One-Line Summary

> Microsoft Purview Communication Compliance helps organizations detect, investigate, and manage risky or inappropriate communications across Microsoft 365 and AI-powered platforms.
