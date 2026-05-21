# Microsoft Purview DLP Alerts and Responses

## Overview

Microsoft Purview Data Loss Prevention (DLP) can generate alerts when sensitive information matches configured DLP policy conditions.

These alerts help organizations:
- Detect potential data leaks  
- Investigate incidents  
- Respond to risky behavior  
- Improve data protection policies  

---

# DLP Protection Actions

When content matches DLP policy conditions, Microsoft Purview can take various actions automatically.

---

## User Notifications

### Policy Tips
Display notifications directly to users.

Examples:
- Warning pop-ups  
- In-app notifications  

---

### Email Notifications
Send emails to:
- Users  
- Administrators  

Notifications can be customized.

---

# Sensitive Data Thresholds

Policies can trigger only when a defined amount of sensitive information is detected.

Example:
- 10 or more credit card numbers  

---

# Incident Reports and Alerts

DLP can:
- Send incident reports by email  
- Generate alerts when rules match  

---

# Restricting Access

DLP policies can:

- Restrict access to content  
- Encrypt content in Microsoft 365 locations  

---

## Override Options

Organizations can allow users to override policies.

Examples:
- User must provide a business justification  
- Access may still be logged and monitored  

---

# Data-at-Rest Protection

For stored content, DLP can:

- Lock sensitive files  
- Move files to quarantine folders  

---

# Teams Protection

For Microsoft Teams:
- Sensitive chat content can be blocked or hidden  

---

# Accessing DLP Alerts

Microsoft Purview Portal:

- Solutions → Data Loss Prevention → Alerts  

---

# Alert Retention

## Microsoft Purview Portal
- Displays alerts from the last 30 days  

---

## Microsoft Defender Portal
- Can retain alerts for up to 6 months  

---

# Filtering Alerts

Alerts can be filtered by:

- Time range  
- User  
- Alert status  
- Alert severity  

---

## Alert Status Options

| Status | Meaning |
|--------|---------|
| Active | Alert is open |
| Investigating | Investigation in progress |
| Resolved | Alert handled |
| Dismissed | Alert closed as non-issue |

---

## Severity Levels

- Low  
- Medium  
- High  

---

# Alert Information

Common alert details include:

- Alert name  
- Location  
- User  
- Severity  
- Status  

Columns can be customized to display additional information.

---

# DLP Alert Investigation Process

Microsoft Purview DLP alerts typically follow six stages.

---

## 1. Trigger

Policy conditions are detected.

Example:
- Sensitive information identified in a document  

---

## 2. Notify

Alert is generated and sent to dashboards or administrators.

---

## 3. Triage

Determine:
- Priority level  
- Whether it is a false positive  

Possible actions:
- End alert  
- Unblock user if appropriate  

---

## 4. Investigate

Collect evidence and determine:
- What happened  
- Why it happened  
- What actions occurred afterward  

---

## 5. Remediate

Possible remediation actions include:

- No further action  
- Monitor for future issues  
- Inform the user  
- Reset password  
- Disable account  
- Remove document access  
- Unshare content  
- Isolate device  
- Quarantine file  
- Delete email  

---

## 6. Tune Policies

Update DLP policies to improve:
- Accuracy  
- Effectiveness  
- Reduction of false positives  

---

# Benefits of DLP Alerts

- Detects risky data sharing  
- Supports incident response  
- Helps prevent data leaks  
- Improves compliance monitoring  

---

# Key Concepts

| Concept | Purpose |
|--------|---------|
| DLP Alert | Notification triggered by policy match |
| Policy Tip | Warning shown to users |
| Incident Report | Administrative notification |
| Quarantine | Isolate sensitive files |
| Triage | Review and prioritize alerts |
| Remediation | Respond to security incidents |

---

# Summary

Microsoft Purview DLP alerts help organizations identify and respond to potential data loss incidents.

Policies can:
- Notify users  
- Restrict or encrypt content  
- Generate alerts  
- Trigger remediation actions  

Administrators can investigate alerts, respond to incidents, and improve policies over time.

---

## One-Line Summary

> Microsoft Purview DLP alerts help detect, investigate, and respond to potential data loss incidents across Microsoft 365 environments.
