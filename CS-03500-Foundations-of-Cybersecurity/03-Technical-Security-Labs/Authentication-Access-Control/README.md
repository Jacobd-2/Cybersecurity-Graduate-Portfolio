# Authentication & Access Control

| **Lab**     | **Applying User Authentication and Access Controls (4e)**                                    |
| :---------- | :------------------------------------------------------------------------------------------- |
| **Type**    | Hands-On Identity & Access Control Lab                                                       |
| **Focus**   | User Authentication • Active Directory • Security Groups • File Permissions • Access Control |

## Lab Overview

This hands-on lab focused on implementing **user authentication and access controls** within a Windows-based environment.

The lab was completed using *Fundamentals of Information Systems Security, Fourth Edition* and provided practical experience with **Active Directory Users and Computers, user accounts, security groups, folder permissions, and access-control configuration**.

The lab demonstrated how organizations can control access to resources by assigning users to appropriate security groups and configuring permissions on protected folders.

**Time on Task:** 20 hours
**Completion:** 100%

---

# Lab Objectives

The primary objectives of this lab were to:

1. Create user accounts within Active Directory.
2. Create and configure security groups.
3. Organize users according to access requirements.
4. Create folders requiring controlled access.
5. Configure security permissions for protected resources.
6. Apply authentication and authorization concepts.
7. Verify appropriate access to protected resources.
8. Document the implemented access controls.

---

# 1. Create Users & Security Groups

The first part of the lab involved creating users and security groups using **Active Directory Users and Computers**.

### Technology

```text id="k7q3cz"
Active Directory Users and Computers
```

### Activities

* Created user accounts
* Created security groups
* Added users to appropriate groups
* Organized accounts according to access requirements
* Verified newly created users and groups

### Security Objective

Security groups allow administrators to manage access to resources based on defined roles and responsibilities rather than assigning permissions individually to every user.

---

# 2. Active Directory User Management

Active Directory was used to manage identities within the lab environment.

### Areas Addressed

* User account creation
* Identity management
* Security group membership
* Account organization
* Authentication

### Security Consideration

Centralized identity management allows organizations to consistently apply authentication and authorization policies across users and protected resources.

---

# 3. Create Folders & Configure Security Permissions

The second part of the lab involved creating folders and configuring security permissions.

### Activities

* Created protected folders
* Configured folder security permissions
* Assigned permissions through security groups
* Applied access-control principles
* Evaluated authorized access to resources

### Security Objective

File-system permissions help ensure that users can access only the resources required for their assigned responsibilities.

---

# 4. Authentication & Authorization

The lab demonstrated the distinction between **authentication** and **authorization**.

### Authentication

Authentication determines **who a user is**.

In the lab environment, user accounts created through Active Directory provided identities that could be authenticated when accessing the Windows environment.

### Authorization

Authorization determines **what an authenticated user is allowed to access**.

Security groups and folder permissions were used to control access to protected resources.

```text id="u8j2nc"
User
  ↓
Authentication
  ↓
Authenticated Identity
  ↓
Security Group
  ↓
Folder Permissions
  ↓
Authorized Resource Access
```

---

# 5. Group-Based Access Control

Security groups were used to support centralized access management.

Instead of assigning permissions individually to each user, permissions can be associated with groups and users can be assigned to the appropriate groups.

### Security Benefits

* Simplifies permission management
* Supports role-based access
* Reduces administrative overhead
* Helps maintain consistent access policies
* Supports the principle of least privilege

---

# 6. Access Control & Least Privilege

The lab demonstrated the importance of limiting access to resources based on business and security requirements.

### Least-Privilege Principle

Users should receive only the permissions necessary to perform their authorized responsibilities.

Applying least privilege can reduce the potential impact of:

* Compromised accounts
* Insider threats
* Unauthorized access
* Accidental data modification
* Credential theft

---

# Hands-On Evidence

The completed lab included evidence demonstrating the configured Active Directory environment.

### Primary Evidence

**Active Directory Users and Computers**

The required screen capture demonstrated the newly created:

* User accounts
* Security groups

Additional screenshots from the completed lab can be stored in the `screenshots/` directory.

---

# Access-Control Assessment

| **Control Area**   | **Implementation**           | **Security Purpose**            |
| :----------------- | :--------------------------- | :------------------------------ |
| User Accounts      | Active Directory             | Centralized identity management |
| Security Groups    | Active Directory             | Group-based access management   |
| Folder Permissions | Windows Security Permissions | Resource protection             |
| Authentication     | User accounts                | Verify user identity            |
| Authorization      | Group and folder permissions | Control resource access         |
| Least Privilege    | Permission assignment        | Limit unnecessary access        |

---

# Key Security Takeaways

* Authentication verifies a user's identity.
* Authorization determines what resources an authenticated user can access.
* Active Directory provides centralized identity and access management.
* Security groups simplify permission administration.
* Folder permissions help protect sensitive resources.
* Group-based access control supports consistent security policies.
* Least privilege reduces unnecessary access and limits potential security impact.
* Access controls should be regularly reviewed as user responsibilities change.

---

# Skills Demonstrated

`Active Directory`

`User Account Management`

`Security Group Management`

`Authentication`

`Authorization`

`Access Control`

`File Permissions`

`Least Privilege`

`Windows Security`

`Identity Management`

---

# Tools & Technologies

* Windows Server
* Active Directory
* Active Directory Users and Computers
* Windows Security Permissions
* Security Groups
* User Accounts
* File-System Permissions

---

# Security Concepts

* Authentication
* Authorization
* Identity & Access Management
* Access Control
* Least Privilege
* Security Groups
* User Management
* File-System Security
* Resource Protection
* Role-Based Access
* Account Management
* Privilege Management

---

# Project Structure

```text id="w4e7pa"
Authentication-Access-Control/
├── README.md
├── screenshots/
├── configuration/
├── analysis/
└── report.pdf
```

### Recommended Artifact Organization

**screenshots/**
Store screenshots demonstrating Active Directory users, security groups, folder permissions, and access-control configuration.

**configuration/**
Store sanitized configuration documentation or permission matrices.

**analysis/**
Store supporting notes and access-control analysis.

**report.pdf**
Store the completed authentication and access-control lab report.

---

# Portfolio Context

This lab was completed as part of hands-on cybersecurity coursework using a controlled Windows and Active Directory environment.

The lab demonstrates practical experience with **identity management, Active Directory, authentication, authorization, security groups, file permissions, and access-control principles**.

These skills are directly relevant to enterprise security environments where administrators and security professionals must ensure that users have appropriate access to organizational resources.

## Disclaimer

This lab was performed within an authorized educational environment.

No unauthorized accounts, systems, networks, or production resources were accessed or modified.
