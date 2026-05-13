# Sensitivity Labels in Microsoft Purview

## Overview

Sensitivity labels in Microsoft Purview are used to:

- Classify data  
- Protect sensitive content  
- Apply security and compliance controls  

Labels can be applied to documents, emails, meetings, teams, SharePoint sites, and more.

---

## What are Sensitivity Labels?

Sensitivity labels help organizations identify and protect sensitive information.

Examples of labels:
- No Sensitivity  
- Confidential  
- Highly Confidential  

Organizations can also create custom labels.

---

## Where Sensitivity Labels Can Be Applied

Sensitivity labels can protect:

- Documents  
- Emails  
- Teams meetings and chats  
- SharePoint sites  
- Microsoft 365 Groups  
- Power BI content  
- Microsoft 365 Copilot and Copilot Chat  
- Third-party applications  

---

## SharePoint Protection

When files stored in SharePoint are downloaded:
- Protection settings remain applied  
- Security persists outside the original location  

---

## eDiscovery Integration

Sensitivity labels can also be used in:
- eDiscovery investigations  
- Compliance and legal scenarios  

---

# Creating a Sensitivity Label

## Where to Create

Microsoft Purview Portal:

- Information Protection → Sensitivity Labels  
- Select:
  - Create a Label  

---

## Step 1: Label Details

Configure:

- Label Name  
- Display Name (visible to users)  
- Priority  
- Description for Users  
- Description for Admins  
- Label Color  

---

## Step 2: Define Scope

Choose what content the label applies to.

---

### Supported Scopes

#### Files and Assets
Includes:
- Microsoft 365  
- Microsoft Fabric  
- Power BI  
- Microsoft Azure  

---

#### Emails
Can:
- Encrypt emails  
- Apply "Do Not Forward" restrictions  

Restrictions can prevent:
- Forwarding  
- Printing  
- Copying  

Attachments inherit the same sensitivity label.

---

#### Teams Meetings and Chats
Supports protection for:
- Teams meetings  
- Meeting invites  
- Chats  

> Some advanced protections require Teams Premium.

---

#### Groups and Sites
Includes:
- Microsoft Teams  
- Microsoft 365 Groups  
- SharePoint Sites  
- Microsoft Loop workspaces  

---

#### Microsoft Purview Data Map
Can classify:
- Azure data sources  
- Amazon databases  
- Other mapped data assets  

---

# Protection Settings

Sensitivity labels can enforce protection policies.

---

## 1. Access Control

Control:
- Who can access content  
- What permissions users receive  

### Example Permissions
- Viewer  
- Restricted Viewer  
- Editor  
- Owner  
- Custom permissions  

Permissions can be assigned to:
- Users  
- Groups  

---

## 2. Content Marking

Can apply:
- Watermarks  
- Headers  
- Footers  

Supported on:
- Documents  
- Emails  
- Meeting invitations  

Text can be customized.

---

## 3. Automatic Labeling

Labels can be:

- Applied automatically  
- Recommended to users  

Based on:
- Content analysis  
- Sensitive Information Types (SITs)  
- Trainable classifiers  

---

## 4. Sharing Controls

For SharePoint and documents:
- Define sharing permissions  
- Configure:
  - View-only access  
  - Edit access  

---

## 5. Teams and Group Protection

Can configure:
- Access levels  
- External sharing controls  
- Conditional Access policies  
- Shared channel permissions  
- Discoverability of private teams  

---

# Publishing Labels

After creation, labels can be:

- Published to users and apps  
- Saved as drafts  

Published labels become available in:
- Word  
- Excel  
- PowerPoint  
- Outlook  
- SharePoint  
- Teams  
- Microsoft 365 Groups  

---

# Benefits of Sensitivity Labels

- Protect sensitive data  
- Support compliance requirements  
- Enable secure collaboration  
- Extend protection beyond Microsoft 365  
- Integrate with Microsoft Purview and eDiscovery  

---

# Key Concepts

| Concept | Purpose |
|--------|---------|
| Sensitivity Label | Classifies and protects content |
| Automatic Labeling | Applies labels based on conditions |
| Encryption | Restricts unauthorized access |
| Content Marking | Adds visual indicators like watermarks |
| Sharing Controls | Controls access and collaboration |

---

## One-Line Summary

> Sensitivity labels classify and protect sensitive content across Microsoft 365 using encryption, access control, and compliance policies.
