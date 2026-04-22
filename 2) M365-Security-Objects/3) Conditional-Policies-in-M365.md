# Conditional Access Policies in Microsoft Entra

## Overview

Conditional Access is a key security feature in Microsoft Entra that helps control access to resources based on defined conditions.

It is part of the authentication process and ensures that users must meet specific requirements before accessing applications or data.

---

## What is Conditional Access?

Conditional Access evaluates signals and enforces policies after initial authentication (e.g., username and password).

It follows a simple logic:

> If conditions are met → then allow or restrict access

---

## Where to Configure

- Microsoft Entra Admin Center  
  - Identity → Protection → Conditional Access  

- Azure Portal  
  - Search for "Conditional Access"  

---

## How Conditional Access Works

1. User signs in (first-factor authentication)  
2. System evaluates signals (user, device, location, risk, etc.)  
3. Policy is applied  
4. Access decision is enforced  

---

## Policy Configuration Components

### 1. Users and Groups
- Apply policy to:
  - Specific users  
  - Groups  
  - External users  

---

### 2. Target Resources
- Define which resources are protected:
  - Applications  
  - Services  
- Example:
  - Apply stricter controls for admin portals  

---

### 3. Network / Location
- Based on:
  - IP address  
  - Country/region  
  - Named locations  

#### Examples:
- Allow access only from office locations  
- Block access from unknown regions  

---

### 4. Conditions

#### User Risk
- Risk level of the user:
  - Low  
  - Medium  
  - High  

---

#### Sign-in Risk
- Probability that a login is compromised:
  - Low  
  - Medium  
  - High  

> Requires Microsoft Entra ID P2 (risk-based conditional access)

---

#### Device Platforms
- Apply policies based on OS:
  - Windows  
  - macOS  
  - Linux  
  - iOS  
  - Android  

---

#### Client Apps
- Browser  
- Mobile apps  
- Desktop applications  
- Legacy authentication clients  

---

#### Additional Signals
- Microsoft Defender for Cloud Apps  
- Session-based monitoring and controls  

---

## Access Controls (Decisions)

When conditions are met, actions can include:

### 1. Grant Access
With additional requirements:
- Require Multi-Factor Authentication (MFA)  
- Require passwordless authentication  
- Require phishing-resistant MFA  
- Require compliant or approved device  
- Require approved client app  
- Require Intune app protection policy  
- Force password change  

---

### 2. Block Access
- Completely deny access if conditions are not met  

---

### 3. Limited / Conditional Access
- Reduce access during session  
- Enforce session controls  

---

### 4. Risk-Based Actions
- Revoke session  
- Force password reset  
- Require risk remediation  

---

## Licensing Requirements

- Conditional Access requires a **paid Microsoft Entra plan**  
- Risk-based Conditional Access requires:
  - **Microsoft Entra ID P2**  

---

## Use Cases

- Require MFA for admin access  
- Allow access only from trusted locations  
- Restrict access to compliant devices  
- Block risky sign-ins  
- Protect sensitive applications  

---

## Policy States

A Conditional Access policy can be:

- **On (Enabled)** → Actively enforced  
- **Report-only** → Simulates impact without enforcing  
- **Off (Disabled)** → Not applied  

---

## Best Practices

- Start with report-only mode before enforcing  
- Apply least privilege principles  
- Use MFA for high-risk access  
- Combine multiple signals (user, device, location)  
- Regularly review and update policies
  
---

## One-Line Summary

> Conditional Access evaluates conditions during sign-in and enforces security policies to control access to resources.
