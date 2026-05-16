# Microsoft Purview Data Explorer

## Overview

Microsoft Purview Data Explorer helps organizations identify and explore sensitive information stored across Microsoft 365 services.

It provides visibility into:
- Sensitive Information Types (SITs)  
- Sensitivity labels  
- Retention labels  
- Trainable classifiers  

---

## Where to Access

Microsoft Purview Portal:

- Information Protection → Explorers → Data Explorer  

---

## What is Data Explorer?

Data Explorer provides a snapshot of content containing:

- Sensitive Information Types (SITs)  
- Sensitivity labels  
- Retention labels  
- Trainable classifiers  

It helps organizations understand where sensitive data exists across their environment.

---

# Sensitive Information Types (SITs)

Sensitive Information Types are predefined or custom patterns used to identify sensitive data.

---

## Categories of Sensitive Information

### 1. Personally Identifiable Information (PII)

Includes:
- Driver’s license numbers  
- Passport numbers  
- National identity numbers  
- Personal identification numbers  
- Tax identification numbers  
- Social security numbers  
- Physical addresses  

Supports:
- Global PII detection  
- Country-specific identifiers  

---

### 2. Financial Information

Includes:
- Bank account numbers  
- Credit card numbers  

> Financial information may be non-PII depending on context.

---

### 3. Authentication Secrets and Credentials

Includes:
- Password-related information  
- Authentication credentials  

---

### 4. Medical and Health Information

Includes:
- Medical conditions  
- Health-related identifiers  

---

### 5. Network and Security Information

Includes:
- IP addresses  
- SQL Server connection strings  

---

### 6. Location Information

Includes:
- Geographic and location-related data  

---

# Supported Data Sources

Data Explorer can identify sensitive information across:

- Exchange  
- OneDrive  
- Microsoft Teams  
- Microsoft Copilot  

---

## Important Note

The presence of a sensitive information type in the catalog does not necessarily mean your organization contains that specific data.

Example:
- “Indonesian Passport Number” may appear as a supported SIT even if no such data exists in your environment.

---

# Actions Available in Data Explorer

You can:

- Sort information  
- Filter results  
- Export data  
- Drill down into data sources  

---

# Drilling Down into Content

Selecting a data source opens the **Content Explorer**.

This allows administrators to:
- Explore matching files  
- Review content locations  
- Investigate sensitive data exposure  

---

# Required Permissions

To access Content Explorer, users need one of the following role groups:

- Content Explorer List Viewer  
- Content Explorer Content Viewer  

---

# Managing Permissions

Permissions can be configured in:

- Settings → Roles and Scopes → Role Groups  

Search for:
- “Content Explorer”  

Then:
- Edit the role group  
- Add required users  

---

# Benefits of Data Explorer

- Identifies locations of sensitive data  
- Improves compliance visibility  
- Supports governance and risk management  
- Helps investigate data exposure  

---

# Key Concepts

| Feature | Purpose |
|--------|---------|
| Data Explorer | View locations of sensitive content |
| Sensitive Information Types (SITs) | Detect sensitive data patterns |
| Content Explorer | Drill into matching files and content |
| Sensitivity Labels | Classify and protect data |
| Trainable Classifiers | AI-based classification |

---

# Summary

Microsoft Purview Data Explorer helps organizations identify and investigate sensitive information stored across Microsoft 365 services.

It provides visibility into:
- Sensitive Information Types  
- Sensitivity labels  
- Retention labels  
- Trainable classifiers  

With the correct permissions, administrators can drill into content locations and investigate files containing sensitive information.

---

## One-Line Summary

> Microsoft Purview Data Explorer helps identify, analyze, and investigate sensitive information across Microsoft 365 environments.
