# Troubleshooting Sign-In Issues in Microsoft Entra

## Overview

Microsoft Entra provides tools to detect and troubleshoot **risky sign-in behaviors**. These tools help identify potential security threats and enforce appropriate actions such as blocking access or requiring additional verification.

---

## Risky Sign-In Behavior

Risky behavior refers to sign-in activity that appears suspicious or abnormal.

### Common Examples:

- **Leaked credentials**
  - User credentials exposed publicly or compromised  

- **Impossible travel**
  - Sign-ins from two distant locations within a short time  

- **Unfamiliar locations**
  - Login attempts from new or unexpected geographic locations  

- **Anonymous or suspicious IP addresses**
  - Sign-ins from anonymized or high-risk networks  

- **Infected or non-compliant devices**
  - Devices that do not meet security policies  

---

## Required Licensing

To use advanced risk detection and policies:

- Microsoft Entra ID **P2** is required  
- Also included in:
  - Microsoft 365 E5  
  - Enterprise Mobility + Security E5  

---

## Tools for Troubleshooting Sign-In Issues

### 1. Conditional Access Policies

- Used to enforce security based on conditions  
- Can:
  - Block access  
  - Require Multi-Factor Authentication (MFA)  
  - Restrict access based on risk  

> Risk-based Conditional Access requires Entra ID P2

---

### 2. Multi-Factor Authentication (MFA)

- Adds additional verification during sign-in  
- Can be enforced via:
  - MFA registration policies  

#### Options:
- Apply to all users  
- Exclude specific users or groups  

---

### 3. Identity Protection Dashboard

Located in Microsoft Entra Admin Center:

- Identity → Protection  

Provides visibility into risks and security events.

---

## Risk Reports

The Identity Protection dashboard includes several reports:

### Risky Users
- Users flagged as potentially compromised  
- Actions:
  - Confirm compromise  
  - Mark as safe  
  - Reset password  
  - Block user  

---

### Risky Sign-Ins
- Suspicious login attempts  
- Actions:
  - Investigate sign-in  
  - Configure trusted IPs  

---

### Risk Detections
- Detailed list of detected threats  

---

### Risky Workload Identities
- Risks related to applications and services  

---

## Risk Evaluation

Microsoft evaluates risk using global intelligence and signals.

### Sources of Signals:
- Microsoft Entra ID  
- Active Directory  
- Microsoft accounts  
- Other Microsoft services  

---

### Common Detection Signals:

- Anonymous IP address activity  
- Leaked credentials  
- Suspicious login patterns  
- Unusual user behavior  

---

## Advanced Risk Detection (P2 Features)

With Microsoft Entra ID P2, additional risk detections include:

- **Impossible travel**
- **Password spray attacks**
- **Unfamiliar sign-in properties**
  - New IP address  
  - Unknown device or browser  
- **Malicious IP activity**
- **Mass access to sensitive files**
- **Suspicious email forwarding rules**
- **MFA denial reported as suspicious**

---

## Actions Based on Risk

Based on detected risk, organizations can:

- Block sign-in attempts  
- Require MFA  
- Reset user passwords  
- Revoke sessions  
- Restrict access  

---

## Trusted IPs

- Define known safe IP ranges  
- Reduce false positives  
- Improve user experience  

---

## Best Practices

- Use Conditional Access for risk-based control  
- Enforce MFA for all users  
- Monitor Identity Protection reports regularly  
- Configure trusted locations carefully  
- Respond quickly to detected risks  

---

## One-Line Summary

> Microsoft Entra uses risk signals and security tools like Conditional Access and MFA to detect and respond to suspicious sign-in activity.
