# Classification in Microsoft Purview

## Overview

Microsoft Purview provides multiple methods for classifying content and identifying sensitive information across Microsoft 365 environments.

Classification helps organizations:
- Protect sensitive data  
- Apply compliance controls  
- Automate governance processes  

---

# Methods of Classification

Microsoft Purview supports three primary classification methods:

1. Manual Classification  
2. Automated Pattern Matching  
3. Trainable Classifiers  

---

# 1. Manual Classification

Manual classification is performed directly by users.

### Characteristics
- Does not require Artificial Intelligence (AI)  
- Users apply labels manually  
- Flexible but prone to human error  

### Example
- A user manually marks a document as:
  - Confidential  
  - Highly Confidential  

---

# 2. Automated Pattern Matching

Automated classification uses rules and pattern matching to identify sensitive content.

---

## What Can Be Used for Detection?

### Keywords
- Specific words or phrases  

---

### Metadata Values
- File properties or document attributes  

---

### Sensitive Information
Examples:
- Banking information  
- Credit card numbers  
- Tax identifiers  

---

### Document Fingerprinting
Detects:
- Variations of templates  
- Known document patterns  

---

### Exact Data Match (EDM)
- Matches exact string values  
- Used for highly accurate identification  

---

## Use Cases

Automated pattern matching is commonly used for:

- Sensitivity labels  
- Retention labels  
- Retention policies  

---

# 3. Trainable Classifiers

Trainable classifiers use machine learning to identify content based on examples.

They can classify content by learning patterns from documents.

---

## Where to Access

Microsoft Purview:

- Information Protection → Classifiers → Trainable Classifiers  

---

# Pre-Trained Classifiers

Microsoft provides many ready-to-use classifiers.

---

## Common Categories

### Finance and Accounts
- Financial documents  
- Accounting records  

---

### Legal and Compliance
- Contracts  
- Intellectual property  
- Sensitive legal content  

---

### Human Resources (HR)
- Employee information  
- HR operations  

---

### Manufacturing and Environment
- Operational and industrial documents  

---

### IT and Security
- Technical and security-related content  

---

### Business and Corporate Documentation
- Organizational documents and communications  

---

# Supported File Types

Trainable classifiers support over 30 file types.

---

## Common Supported Formats

- PDF  
- Word documents  
- PowerPoint files  
- Excel spreadsheets  
- CSV files  
- Text files  
- Rich Text Format (.RTF)  
- Outlook messages (.MSG)  

---

# Supported Data Sources

Classifiers can analyze content stored in:

- SharePoint  
- Exchange  
- OneDrive  

---

# Custom Trainable Classifiers

Organizations can create custom classifiers tailored to their own content.

> At the time of recording, custom trainable classifiers supported English only.

---

## Training Requirements

### Positive Samples
Documents that belong to the category.

Requirements:
- Between 50 and 500 files  

---

### Negative Samples
Documents that do NOT belong to the category.

Requirements:
- Between 150 and 1500 files  

> Negative samples are typically three times the number of positive samples.

---

## Supported Training File Types

Includes:
- Word documents  
- Excel files  
- PowerPoint presentations  
- PDFs  
- Text files  
- Other supported formats  

---

# Training Timeline

### Prediction Model Creation
- Usually completed within 24 hours  

---

### Full Training Process
- Can take between 2 and 12 days  

---

# Sensitive Information Types (SITs)

Another important classification method is:
- Sensitive Information Types (SITs)

These identify:
- Credit card numbers  
- Passport numbers  
- Tax IDs  
- Medical information  

SITs are covered separately within Microsoft Purview.

---

# Key Concepts

| Method | Description |
|--------|-------------|
| Manual Classification | User-applied labels |
| Pattern Matching | Rule and keyword-based detection |
| Trainable Classifiers | AI/ML-based content recognition |
| Exact Data Match (EDM) | Exact string matching |
| Sensitive Information Types (SITs) | Detection of sensitive data patterns |

---

## One-Line Summary

> Microsoft Purview classifies data using manual labeling, automated pattern matching, and AI-powered trainable classifiers.
