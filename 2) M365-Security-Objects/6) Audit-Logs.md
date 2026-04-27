# Audit Logs and Sign-In Logs in Microsoft Entra

## Overview

Microsoft Entra provides tools to review **user activity** and **administrative actions** through logs. These logs help monitor security, investigate issues, and maintain compliance.

The primary tools are:
- Sign-in Logs  
- Audit Logs  

Both are available in the Microsoft Entra Admin Center.

---

## Where to Access

- Microsoft Entra Admin Center  
  - Entra ID → Monitoring and Health  

---

## Sign-In Logs

Sign-in logs track authentication activity for:

- Users  
- Service principals  
- Managed identities  

---

### Key Information Available

- **Date and Time**
  - Format: `YYYY-MM-DDTHH:MM:SSZ`  
  - "Z" indicates UTC (Zulu / GMT time)  

- **Request ID**
- **User Principal Name (UPN)**
- **Application used**
- **Sign-in status** (Success / Failure)
- **IP address and location**
- **Resource accessed**
- **Conditional Access status**

---

### Use Cases

- Identify:
  - Successful vs failed sign-ins  
  - Application usage trends  
  - Suspicious login attempts  
- Answer questions such as:
  - How many users accessed a specific application?  
  - How many failed login attempts occurred?  
  - Which services or applications were accessed?  

---

## Audit Logs

Audit logs track **configuration changes** and administrative activities.

---

### Key Information Available

- **Date and Time**
- **Service**
- **Category**
- **Activity performed**
- **Status and reason**

---

### Use Cases

- Track changes such as:
  - User creation or deletion  
  - Password changes  
  - Device updates  
  - Group modifications  
  - Role or permission updates  
  - Application or service principal changes  

- Answer questions such as:
  - Who changed user or group settings?  
  - What licenses were assigned or modified?  
  - Were group owners changed?  

---

## Exporting Logs

Logs can be exported for further analysis:

- CSV (Comma Separated Values)  
- JSON format  

---

## Filtering and Customization

You can customize logs by:

- Filtering by:
  - Date range  
  - User  
  - Application  
- Switching time format:
  - UTC (default)  
  - Local time  
- Adjusting view based on requirements  

---

## Benefits

- Improves visibility into user and admin activity  
- Helps detect suspicious behavior  
- Supports troubleshooting and investigations  
- Assists in compliance and auditing  

---

## Best Practices

- Regularly review sign-in and audit logs  
- Monitor failed login attempts  
- Investigate unusual access patterns  
- Export logs for deeper analysis when needed  

---

## Summary

- Sign-in logs track authentication activity  
- Audit logs track configuration and administrative changes  
- Both are essential for monitoring, security, and troubleshooting  

---

## One-Line Summary

> Use sign-in logs for tracking access activity and audit logs for monitoring administrative and configuration changes in Microsoft Entra.
