# Microsoft Entra: Users and Groups

## Overview

In Microsoft 365, **Microsoft Entra ID** is used to manage security objects such as **users and groups**. These are fundamental for controlling access, permissions, and collaboration within an organization.

Users and groups can be managed via:
- Microsoft Entra Admin Center: https://entra.microsoft.com  
- Azure Portal: https://portal.azure.com  

---

## Users in Microsoft Entra

Users represent individuals or entities that need access to resources.

### User Creation

When creating a user, you define:
- User Principal Name (UPN) → `user@domain`
- Display name  
- Password (manual or auto-generated)  

Additional properties include:
- First name / Last name  
- Job information  
- Contact details  
- User type  

---

## Types of Users

### 1. Internal Users
Users who belong to the organization.

#### Member
- Typically employees or internal staff  
- Full access based on assigned roles  

#### Guest (Internal)
- Limited access  
- Can:
  - Manage their profile  
  - Change password  
  - View limited group information  
- Cannot:
  - View full directory  
  - Access all users/groups  

---

### 2. External Users
- Users from outside the organization  
- Authenticate using their own Entra tenant  
- Commonly added as **Guests**  

#### Requirements:
- Need **Guest Inviter role** to invite  
- Used for collaboration (partners, vendors)  

---

## Roles and Permissions

- Roles define **what actions a user can perform**  
- Example roles:
  - Global Administrator  
  - User Administrator  
  - Reader  

To assign roles, you need:
- **Privileged Role Administrator** role  

> Roles are collections of permissions applied to users or groups.

---

## Groups in Microsoft Entra

Groups are used to manage permissions **at scale**.

Instead of assigning permissions to individual users:
- Assign permissions to a group  
- Add users to the group  

### Benefits:
- Easier management  
- Immediate permission updates  
- Scalable for large organizations  

---

## Types of Groups

### 1. Security Groups
Used for:
- Access control to applications and resources  
- License assignment  

#### Members can include:
- Users  
- Devices  
- Other groups (nested groups)  
- Service principals (applications)  

---

### 2. Microsoft 365 Groups
Used for:
- Collaboration  

#### Provides:
- Shared mailbox  
- Calendar  
- Files  
- SharePoint site  

#### Members:
- Users  
- Service principals  
- External users supported  

---

## Membership Types

### Assigned Membership
- Manually add/remove users  
- Fixed membership  

---

### Dynamic Membership
- Membership based on rules  

#### Example:
- Users located in a specific country  
- Devices meeting certain conditions  

> Membership updates automatically when conditions change.

---

## Group Roles and Licensing

- Groups can be assigned **Microsoft Entra roles**  
- Requires at least:
  - **Microsoft Entra P1 license**  

---

## Group Owners

### Responsibilities:
- Add/remove members  
- Assign/remove other owners  
- Manage group settings  

### Best Practice:
- Have **at least two owners per group**

#### Why?
- Prevent loss of control if one owner leaves  
- Ensures continuity of management  

---

## Key Concepts

- Users:
  - Internal or External  
  - Member or Guest  

- Groups:
  - Security or Microsoft 365  
  - Assigned or Dynamic membership  

- Roles:
  - Define permissions  
  - Applied via RBAC  

---

## Summary

- Microsoft Entra uses users and groups to manage access  
- Groups simplify permission management at scale  
- Dynamic groups automate membership  
- Always follow best practices such as assigning multiple owners  

---

## One-Line Summary

> Use users for identity and groups for scalable access management in Microsoft Entra.
