# Zero Trust Methodology

## Overview

Zero Trust is a modern security approach summarized by the principle:

> **“Never trust, always verify.”**

It assumes that threats can exist both inside and outside the network, so every access request must be validated.

---

## Core Principles of Zero Trust

### 1. Verify Explicitly
- Always authenticate and authorize every request  
- Evaluate:
  - User identity  
  - Location  
  - Device health  
  - Data classification  
  - Risk signals  
- Example: Multi-Factor Authentication (MFA)

---

### 2. Least Privilege Access
- Provide only minimum access required  
- Access is:
  - Just-In-Time (JIT) → only when needed  
  - Just-Enough (JEA) → only required permissions  
- Reduces attack surface  

---

### 3. Assume Breach
- Always assume the system is already compromised  
- Focus on:
  - Minimizing damage (blast radius)  
  - Preventing lateral movement  
  - Continuous monitoring and analytics  
  - Encryption of data and traffic  

---

## Why Implement Zero Trust?

- Enables work from anywhere  
- Supports cloud and hybrid environments  
- Improves security posture  

### Provides:
- Identity verification  
- Controlled access to apps/data  
- Automated threat detection & response  

---

## Traditional vs Zero Trust Model

| Traditional Model        | Zero Trust Model            |
|-------------------------|----------------------------|
| Trust inside network    | Trust nothing by default   |
| Perimeter-based security| Identity-based security    |
| Limited visibility      | Full visibility & analytics|
| High breach risk        | Minimized risk             |

> According to the Microsoft Zero Trust model, modern environments no longer rely on physical boundaries but extend security to every access point.

---

## Six Foundational Elements

Zero Trust is built across six key pillars:

### 1. Identities
- Users, services, devices  
- Use:
  - MFA  
  - Conditional access  
  - Passwordless authentication  

---

### 2. Devices
- Laptops, mobiles, IoT devices  
- Ensure:
  - Device compliance  
  - Registered devices only  
  - Device health checks  

---

### 3. Applications (Apps)
- SaaS and on-prem apps  

**Controls:**
- Single Sign-On (SSO)  
- Continuous verification  
- Monitoring abnormal behavior  

---

### 4. Infrastructure
- Servers, VMs, containers  

**Features:**
- Just-In-Time access  
- Workload monitoring  
- Granular access control  

---

### 5. Network
- Move from:
  - Flat networks → Micro-segmentation  

**Ensure:**
- Encrypted traffic  
- Limited lateral movement  

---

### 6. Data
- Core asset to protect  

**Apply:**
- Classification & labeling  
- Encryption  
- Access policies  

---

## Key Security Capabilities

- Strong Authentication (MFA)  
- Policy-Based Access Control  
- Micro-Segmentation  
- Automation & AI-driven threat detection  
- Data Classification & Protection  

---
