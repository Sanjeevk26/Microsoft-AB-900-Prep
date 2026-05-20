# Microsoft Purview Data Loss Prevention (DLP)

## Overview

Microsoft Purview Data Loss Prevention (DLP) helps organizations prevent users from sharing sensitive information with unauthorized people.

DLP protects:
- Data at rest  
- Data in motion  
- Data in use  

It integrates closely with Microsoft Purview Information Protection for classification and labeling.

---

# What is Sensitive Data?

Sensitive data can include:

- Financial information  
  - Credit card numbers  
  - Bank account numbers  

- Proprietary business data  

- Medical and health records  

- Social security numbers and other personal identifiers  

---

# Supported Services and Platforms

Microsoft Purview DLP works across:

---

## Microsoft 365 Services

- Exchange  
- SharePoint  
- OneDrive  
- Microsoft Teams  

---

## Office Applications

- Word  
- Excel  
- PowerPoint  

---

## Endpoints

- Windows 10  
- Windows 11  
- macOS  

---

## Additional Locations

- Non-Microsoft cloud applications  
- On-premises file shares  
- On-premises SharePoint  
- Microsoft Fabric  
- Power BI workspaces  
- Microsoft 365 Copilot  

---

# Accessing DLP

Microsoft Purview Portal:

- https://purview.microsoft.com  

Navigate to:
- Solutions → Data Loss Prevention (DLP)

---

# DLP Policies

DLP policies identify sensitive information and apply protection rules to prevent data exposure.

---

# Creating a DLP Policy

## Step 1: Choose Protection Type

Options include:
- Enterprise applications and devices  
- Inline web traffic using Microsoft Edge for Business  

---

## Step 2: Select a Category

Built-in policy templates include:

### Financial Data
Country-specific templates such as:
- Australia  
- Canada  
- France  
- Germany  
- Israel  
- Japan  
- Saudi Arabia  
- United Kingdom  
- United States  

---

### Medical and Health Information

Includes templates for:
- Australia  
- Canada  
- United Kingdom  
- United States  

---

### Privacy Regulations

Includes:
- GDPR (General Data Protection Regulation)  
- Country-specific privacy policies  

---

## Example

A policy may protect:
- Japanese bank account numbers  
- Credit card numbers  

---

# Step 3: Configure Policy Details

Define:
- Policy name  
- Optional description  

---

# Step 4: Assign Administrative Units

Policies can target:
- Specific users  
- Specific groups  

> Requires Microsoft 365 E5 licensing.

Without E5:
- Policy applies to all users and groups.

---

# Step 5: Choose Locations

Apply the policy to:

- Exchange email  
- SharePoint sites  
- OneDrive accounts  
- Teams chats and channels  
- Devices  
- On-premises repositories  
- Microsoft Fabric  
- Power BI workspaces  
- Managed cloud apps  

---

# Step 6: Define Policy Settings

Options include:

- Use predefined templates  
- Create advanced custom DLP rules  

---

# Configuring Sensitive Information

You can:
- Add or remove sensitive information types  
- Adjust confidence levels for detections  

Example:
- Increase confidence threshold before identifying a Japanese bank account number  

---

# Protection Actions

Policies can:
- Block sharing  
- Restrict access  
- Generate alerts  
- Notify users  

Additional protection settings are configured in advanced DLP rules.

---

# Policy Modes

DLP policies support three modes:

| Mode | Description |
|------|-------------|
| Simulation Mode | Test policy impact without enforcement |
| Enabled | Actively enforce the policy |
| Disabled / Draft | Policy exists but is not enforced |

---

# Simulation Mode

Simulation mode helps evaluate policy behavior before enforcement.

---

## What Simulation Shows

- Scan status  
- Number of items scanned  
- Number of matches found  
- Matched files and locations  
- Alerts generated  

---

## Example Results

Simulation can identify:
- Sensitive financial information in SharePoint  
- Credit card numbers in OneDrive files  

---

# Alerts

DLP can generate alerts when:
- Sensitive information is detected  
- Policy conditions are triggered  

Alerts help administrators investigate potential data exposure.

---

# Synchronization Time

Policy synchronization may take:
- Between 2 and 24 hours  

---

# Benefits of DLP

- Prevents accidental data sharing  
- Protects sensitive information  
- Supports regulatory compliance  
- Extends protection across Microsoft 365 and endpoints  

---

# Key Concepts

| Concept | Purpose |
|--------|---------|
| DLP Policy | Protect sensitive information |
| Simulation Mode | Test policies before enforcement |
| Sensitive Information Types | Detect regulated or sensitive data |
| Alerts | Notify administrators of policy matches |
| Protection Actions | Block or restrict risky activities |

---

# Summary

Microsoft Purview Data Loss Prevention helps organizations detect and protect sensitive information across Microsoft 365 services, endpoints, cloud apps, and collaboration platforms.

Policies can identify sensitive data, apply protection rules, generate alerts, and prevent unauthorized sharing.

---

## One-Line Summary

> Microsoft Purview DLP protects sensitive data by detecting, monitoring, and preventing unauthorized sharing across Microsoft 365 and connected environments.
