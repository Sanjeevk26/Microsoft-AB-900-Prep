# App Registrations and Enterprise Applications in Microsoft Entra

## Overview

Microsoft Entra provides two key concepts for managing application access and identity:

- App Registrations  
- Enterprise Applications  

These are used to enable applications to authenticate and securely access resources.

---

## App Registrations

### What are App Registrations?

App registrations are used to **define an application** and establish trust between the application and Microsoft Entra ID.

> The application trusts Microsoft Entra ID for authentication.

---

### Where to Access

- Microsoft Entra Admin Center  
  - Entra ID → App Registrations  

- Azure Portal  
  - Search for "App Registrations"  

---

### Creating an App Registration

When creating a new app registration, you configure:

- **Application Name**  
- **Supported Account Types**:
  - Single tenant (your organization only)  
  - Multi-tenant (any organization)  
  - Multi-tenant + personal Microsoft accounts  
  - Personal Microsoft accounts only  

- **Redirect URI (Optional)**  
  - URL where authentication responses are sent  
  - Used in web and client applications  

---

### Key Configuration Options

#### Certificates and Secrets
- Used for authentication  
- Includes:
  - Client secrets (password-like credentials)  
  - Certificates  

---

#### API Permissions
- Defines what resources the app can access  
- Example:
  - Microsoft Graph  
  - Microsoft 365 services  

---

## Enterprise Applications

### What are Enterprise Applications?

Enterprise applications represent the **actual instance of an application** within a Microsoft Entra tenant.

- They are based on app registrations  
- Created automatically when an app registration is created  

---

### Key Concept

| Concept | Meaning |
|--------|--------|
| App Registration | Defines the application |
| Enterprise Application | Instance of the application in a tenant |

---

### Service Principal

- Enterprise applications are also known as **service principals**  
- A service principal is:
  - A security identity for an application  
  - Used to authenticate and access resources  

---

## Managing Enterprise Applications

### Where to Access

- Microsoft Entra Admin Center  
  - Entra ID → Enterprise Applications  

---

### Key Capabilities

- Assign users and groups  
- Configure Single Sign-On (SSO)  
- Apply Conditional Access policies  
- Manage permissions and access  

---

### Importing Applications

- Go to:
  - Enterprise Applications → New Application  
- Add applications from:
  - Microsoft Entra Application Gallery  
  - Custom integrations  

---

## Relationship Between App Registrations and Enterprise Apps

- App Registration:
  - Defines the application globally  
- Enterprise Application:
  - Represents the app within a specific tenant  
  - Handles authentication and access control  

---

## Use Cases

- Integrating custom applications with Microsoft Entra  
- Enabling secure authentication for apps  
- Managing application access across users and groups  
- Applying security policies to applications  

---

## Summary

- App registrations define how an application integrates with Microsoft Entra  
- Enterprise applications are the tenant-specific instances of those apps  
- Service principals enable secure authentication and access  

---

## One-Line Summary

> App registrations define an application, while enterprise applications (service principals) represent and manage that application within a tenant.
