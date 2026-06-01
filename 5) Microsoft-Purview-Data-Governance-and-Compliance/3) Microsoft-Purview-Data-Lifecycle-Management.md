# Microsoft Purview Data Lifecycle Management

## Overview

Microsoft Purview Data Lifecycle Management, previously known as Microsoft Information Governance, helps organizations manage how long data is retained and when it should be deleted.

It supports:
- Retention policies  
- Retention labels  
- Records management  
- Regulatory and legal retention requirements  

The solution works across Microsoft 365 services such as:
- Exchange  
- SharePoint  
- OneDrive  
- Microsoft Teams  
- Viva Engage  
- Microsoft Copilot experiences  

---

# Key Components

Microsoft Purview Data Lifecycle Management includes:

1. Retention Policies  
2. Retention Labels  
3. Priority Cleanup  
4. Records Management  

---

# Retention Policies

Retention policies automatically retain or delete content based on defined rules.

---

## Purpose

Retention policies help organizations:
- Meet legal requirements  
- Support compliance regulations  
- Preserve data for eDiscovery  
- Automatically remove outdated data  

---

# Accessing Data Lifecycle Management

Microsoft Purview Portal:

- https://purview.microsoft.com  

Navigate to:
- Solutions → Data Lifecycle Management  

---

# Creating a Retention Policy

## Step 1: Create a New Policy

Go to:
- Policies → New Retention Policy  

---

## Step 2: Administrative Units

If licensed appropriately, you can:
- Add or remove admin units  

---

## Step 3: Choose Scope Type

### Adaptive Scope
Automatically applies retention settings using intelligent targeting.

Requires:
- Microsoft 365 E5 or similar licensing  

---

### Static Scope
Manually select locations and users.

---

# Supported Locations

Retention policies can apply to:

- Exchange mailboxes  
- Public folders  
- SharePoint sites  
- OneDrive accounts  
- Microsoft 365 Groups  
- Teams chats and channel messages  
- Viva Engage messages  
- Microsoft Copilot experiences  
- Enterprise AI applications  

---

# Retention Actions

Policies can:

- Retain content  
- Delete content automatically  
- Retain content forever  

---

## Retain Content

Retained content:
- Cannot be permanently deleted  
- Remains available for eDiscovery  

Retention duration examples:
- 5 years  
- 7 years  
- 10 years  
- Custom duration  

Retention can be based on:
- Creation date  
- Last modified date  

---

## Delete Content Automatically

Content can be automatically deleted after reaching a specific age.

Example:
- Delete documents after 5 years  

> Items may still be deleted earlier by users unless protected by retention.

---

## Retain Forever

Content remains preserved indefinitely, even if users attempt deletion.

---

# Retention Labels

Retention labels provide item-level retention management.

Used for:
- Exceptions to retention policies  
- Specific regulatory or legal requirements  

---

# Creating a Retention Label

Retention labels can include:

- Label name  
- Admin description  
- User description  

---

# Retention Label Actions

Retention labels can:

- Retain items for a specified period  
- Retain forever  
- Delete items automatically  
- Trigger disposition reviews  
- Change labels automatically  
- Trigger Power Automate flows  
- Deactivate retention settings  

---

# Applying Retention Labels

Labels can be applied:

- Manually by users  
- Automatically based on conditions  

Supported locations:
- Outlook  
- OneDrive  
- SharePoint  
- Microsoft 365 Groups  

---

# SharePoint Integration

Retention labels can also apply to:

- Document libraries  
- Folders  
- Document sets  

---

# Records Management

With Records Management licensing, enhanced retention labels become available.

---

## Types of Records

### Standard Retention Label
- Allows editing and deleting  

---

### Record (Locked)
- Prevents deletion  
- Prevents major edits  
- May allow renaming or metadata updates  

---

### Record (Unlocked)
- Allows editing  
- Prevents deletion  

---

### Regulatory Record
Most restrictive option:
- Blocks editing  
- Blocks deletion  
- Prevents moving items  
- Prevents label changes or removal  

---

# Priority Cleanup

Priority Cleanup permanently deletes sensitive data when required.

Use cases:
- Data privacy requests  
- Removal of leaked data  
- Regulatory deletion requests  

---

## Important Note

Items marked as:
- Regulatory Records  

cannot be deleted through Priority Cleanup.

---

# Retention Conflict Resolution

Multiple retention policies or labels may apply to the same item.

Microsoft Purview resolves conflicts using precedence rules.

---

# Retention Precedence Rules

## Rule 1: Retention Wins Over Deletion

If both retention and deletion apply:
- Retention takes priority  

---

## Rule 2: Longest Retention Wins

If multiple retention settings exist:
- The item is retained for the longest duration  

Example:
- Policy retains until 2032  
- Label retains until 2035  
- Final retention = 2035  

---

## Rule 3: Labels Override Policies

If both retention labels and retention policies exist:
- Retention labels take precedence  

---

## Rule 4: Specific Policies Override Broad Policies

More targeted policies take priority over general policies.

Example:
- User-specific policy overrides organization-wide policy  

---

## Rule 5: Earliest Deletion Wins

If only deletion actions remain:
- Earliest deletion date takes precedence  

---

# Benefits

- Automates retention and deletion processes  
- Supports compliance and legal requirements  
- Protects records and sensitive data  
- Integrates with eDiscovery and Microsoft 365 services  

---

# Key Concepts

| Concept | Purpose |
|--------|---------|
| Retention Policy | Automatically retain or delete content |
| Retention Label | Item-level retention management |
| Adaptive Scope | Dynamic targeting using intelligent rules |
| Regulatory Record | Most restrictive records protection |
| Priority Cleanup | Permanently remove sensitive data |
| Disposition Review | Manual review before deletion |

---

# Summary

Microsoft Purview Data Lifecycle Management helps organizations manage data retention, deletion, and records governance across Microsoft 365 services.

Using retention policies and retention labels, organizations can:
- Preserve important information  
- Automatically remove outdated content  
- Meet legal and compliance requirements  
- Protect sensitive records  

---

## One-Line Summary

> Microsoft Purview Data Lifecycle Management automates retention, deletion, and records governance across Microsoft 365 environments using retention policies and labels.
