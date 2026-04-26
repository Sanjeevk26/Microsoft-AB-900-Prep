# Identity Secure Score in Microsoft Entra

## Overview

Identity Secure Score is a metric in Microsoft Entra that measures how well your organization’s identity security aligns with Microsoft’s recommended best practices.

- Score range: **0% to 100%**
- **100%** → All recommendations followed  
- **0%** → No recommendations implemented  

There is no mandatory minimum score. The goal is to evaluate and apply recommendations that are relevant to your organization.

---

## Availability

- Available to **all customers** (free and paid)  
- Some recommendations require **paid licenses** to implement  

---

## Refresh Frequency

- Updated every **24 hours**

---

## Where to Access

- Microsoft Entra Admin Center  
  - Entra ID → Identity Secure Score  

---

## Understanding the Score

The Identity Secure Score is based on implemented recommendations.

### Example Metrics Displayed:
- Current score percentage  
- Recommendations list  
- Priority levels:
  - High  
  - Medium  
  - Low  

---

## Recommendation Details

Each recommendation includes:

- **Priority level** (High / Medium / Low)  
- **Required license** (if applicable)  
- **Secure score points** (impact on score)  
- **Impacted resource type**  
- **Status**:
  - Active  
  - Completed  
- **Last updated date**  

---

## Types of Recommendations

You can filter recommendations by:

- Security best practices  
- Microsoft Defender for Identity  

---

## Viewing Recommendation Details

Selecting a recommendation provides:

- **Description**  
- **Current status**  
- **Business value**  
- **Action plan** (how to implement)  
- **User impact**  

### Example Recommendation:
**Do not expire passwords**

- Frequent password changes can lead to weaker passwords  
- Users may reuse or simplify passwords  

---

## Managing Recommendations

You can mark recommendations as:

- **Active**  
- **Dismissed**  
- **Postponed**  

> Completing recommendations increases your secure score.

---

## Common Recommendations

- Maintain **more than one Global Administrator**  
- Disable **password expiration policies**  
- Enable **Self-Service Password Reset (SSPR)**  
- Enforce **Multi-Factor Authentication (MFA)**  
- Use **least privilege roles** instead of Global Admin  

---

## Identity Secure Score vs Microsoft Secure Score

| Feature | Identity Secure Score | Microsoft Secure Score |
|--------|----------------------|------------------------|
| Scope | Identity security only | Broader (identity, data, apps) |
| Location | Entra Admin Center | Microsoft Defender |
| Focus | Identity best practices | Overall security posture |

---

## Benefits

- Helps identify security gaps  
- Provides actionable recommendations  
- Improves overall identity security posture  
- Tracks progress over time  

---

## Best Practices

- Focus on **high-priority recommendations first**  
- Implement changes based on **business needs**  
- Regularly review score and updates  
- Avoid unnecessary configurations just to increase score  

---

## Summary

- Identity Secure Score measures alignment with Microsoft security best practices  
- It is updated daily and provides actionable recommendations  
- Organizations should use it as a **guidance tool**, not a strict target  

---

## One-Line Summary

> Identity Secure Score indicates how closely your identity security aligns with Microsoft’s recommended best practices.
