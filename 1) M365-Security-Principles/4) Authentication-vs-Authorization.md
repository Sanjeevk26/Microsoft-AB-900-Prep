# Authentication vs Authorization (Microsoft Entra)

## Overview

This section explains how users securely access systems using **authentication** and **authorization**, along with modern security practices in **Microsoft Entra**.

---

## Authentication

### What is Authentication?
Authentication is the process of **verifying who you are**.

> Example: Logging into Microsoft Entra using a username and password.

---

### Why Authentication Alone is Not Enough
- Username and password can be:
  - Stolen  
  - Guessed  
  - Reused  

---

### Multi-Factor Authentication (MFA)

MFA adds additional layers of security by requiring multiple forms of verification.

#### Types of Authentication Factors:
1. **Something you know**
   - Password  
2. **Something you have**
   - Mobile phone / Authenticator app  
3. **Something you are**
   - Biometrics (face, fingerprint)  

---

### Example of MFA Flow
- Enter username and password  
- Enter number shown on screen via Authenticator app  
- Verify identity using face recognition  

---

## Microsoft Entra ID

- Microsoft’s **identity provider**
- Handles authentication for:
  - Azure  
  - Microsoft 365  
  - Other Microsoft services  

---

## Authorization

### What is Authorization?
Authorization determines **what you are allowed to do** after authentication.

- Access to:
  - Services  
  - Data (read/write)  
  - Actions within systems  

---

### Example
- A **Global Administrator** can:
  - Access all services  
  - Manage users and permissions  

---

## Role-Based Access Control (RBAC)

RBAC assigns permissions using **roles**.

### Common Roles:

| Role        | Permissions |
|-------------|------------|
| **Owner**   | Full control (all actions) |
| **Contributor** | Can create/manage resources but cannot assign roles |
| **Reader**  | Read-only access |

---

### Key Concept:
- Roles = Collection of permissions  
- Assigned to users via RBAC  

---

## Authentication Methods in Microsoft Entra

### 1. Password-Based Authentication
- Username + password  
- Least secure when used alone  

---

### 2. Multi-Factor Authentication (MFA)
- Adds extra verification layers  
- Strongly recommended  

---

### 3. Microsoft Authenticator

#### Methods:
- Push notification (approve request + number match)  
- One-Time Passwords (OTP)  

---

### 4. Passwordless Authentication (Most Secure)

#### Options:
- Phone sign-in (PIN + biometric)  
- Windows Hello (face recognition / fingerprint)  
- FIDO2 security keys (physical devices)  
- Certificates  

---

### 5. Other Methods
- SMS (text message)  
- Voice call  
- App passwords (legacy apps)  
- Security questions (for password reset)  

---

## Self-Service Password Reset (SSPR)

- Allows users to reset passwords without admin help  
- Uses:
  - Email  
  - Security questions  
  - Phone verification  

---

## Password Security Best Practices

### Old Practice (Not Recommended)
- Frequent password changes (every 14–90 days)

### Problems:
- Weak patterns (e.g., password1 → password2)  
- Reused passwords  
- Written down passwords  

---

### Modern Best Practice
- Use:
  - MFA  
  - Passwordless authentication  
  - Strong, unique passwords  

---

## Security Risks of Weak Authentication

- Credential theft  
- Unauthorized access  
- Data breaches  
- System misuse  

---

- **Authentication** = Proving identity  
- **Authorization** = Defining access permissions  
- **RBAC** = Controls access via roles  
- **MFA & Passwordless** = Strongest security approaches  

> **Authentication = Who you are | Authorization = What you can do**
