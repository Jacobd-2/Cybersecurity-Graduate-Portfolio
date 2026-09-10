# Privilege Escalation

| **Training Area**  | Hack The Box Academy                                                                             |
| :----------------- | :----------------------------------------------------------------------------------------------- |
| **Focus**          | Linux Security • Windows Security • Privilege Escalation • System Enumeration                    |
| **Primary Skills** | System Enumeration • Permission Analysis • Misconfiguration Identification • Security Assessment |

## Overview

This section documents privilege-escalation concepts and system-security assessment skills developed through Hack The Box Academy hands-on training.

The training focused on understanding how attackers may identify weaknesses in operating-system configurations, permissions, services, and access controls that could allow movement from a lower-privileged account to a higher level of access.

Training covered both **Linux and Windows environments**, providing practical exposure to operating-system enumeration, permission analysis, security misconfigurations, and privilege-escalation methodologies within authorized laboratory environments.

## Completed Training

The following Hack The Box Academy modules contributed to this training area:

* **Linux Privilege Escalation**
* **Windows Privilege Escalation**

These modules build upon the exploitation and system-access concepts documented in the previous sections of this portfolio.

## Key Skills Developed

### System Enumeration

* Enumerating operating-system environments
* Identifying users and groups
* Reviewing permissions and access controls
* Identifying running processes and services
* Examining system configurations
* Identifying potentially exploitable misconfigurations
* Assessing available privileges

### Linux Privilege Escalation

Training included concepts related to:

* Linux user and group permissions
* File and directory permissions
* SUID and SGID concepts
* Scheduled tasks and jobs
* Running services
* Environment configuration
* Credential and configuration exposure
* Identifying misconfigured privileges
* Assessing potential escalation paths

### Windows Privilege Escalation

Training included concepts related to:

* Windows users and groups
* File and directory permissions
* Windows services
* Registry configuration
* Scheduled tasks
* Privilege assignments
* System configuration weaknesses
* Credential exposure
* Identifying potential escalation paths

## Privilege Escalation Assessment Workflow

```text id="8e2kqf"
Initial Access
      ↓
System Enumeration
      ↓
User & Group Identification
      ↓
Permission Analysis
      ↓
Service & Process Analysis
      ↓
Configuration Review
      ↓
Misconfiguration Identification
      ↓
Privilege Escalation Validation
      ↓
Impact Assessment
      ↓
Remediation
```

## Tools & Technologies

Training included practical exposure to concepts and tools associated with:

* Linux command-line tools
* Windows command-line tools
* File and directory permissions
* User and group enumeration
* Process and service enumeration
* Scheduled tasks
* System configuration analysis
* Access-control analysis
* Operating-system security assessment

## Security Applications

Privilege-escalation knowledge supports both offensive and defensive cybersecurity activities.

### Offensive Security

* Identifying privilege-escalation opportunities
* Analyzing operating-system configurations
* Reviewing permissions and access controls
* Identifying vulnerable services and configurations
* Evaluating potential escalation paths
* Assessing the security impact of excessive privileges

### Defensive Security

Understanding privilege escalation helps security professionals:

* Identify excessive user privileges
* Strengthen operating-system configurations
* Apply least-privilege principles
* Harden services and scheduled tasks
* Review file and directory permissions
* Reduce credential exposure
* Detect suspicious privilege changes
* Improve endpoint monitoring and incident response

## Windows & Linux Security Comparison

| **Area**                | **Linux**                    | **Windows**                     |
| :---------------------- | :--------------------------- | :------------------------------ |
| **Identity**            | Users & Groups               | Users, Groups & Domain Accounts |
| **Permissions**         | File & Directory Permissions | NTFS & Share Permissions        |
| **Services**            | System Services              | Windows Services                |
| **Scheduled Execution** | Cron & Scheduled Jobs        | Task Scheduler                  |
| **Configuration**       | System Configuration Files   | Registry & System Configuration |
| **Security Principle**  | Least Privilege              | Least Privilege                 |
| **Assessment Goal**     | Identify escalation paths    | Identify escalation paths       |

## Portfolio Connection

The privilege-escalation skills developed through this training build upon and complement other sections of this portfolio:

* **01-Penetration-Testing** — Penetration-testing methodology
* **02-Network-Enumeration** — Network and service enumeration
* **03-Web-Application-Security** — Application vulnerability assessment
* **04-Exploitation** — Exploitation and payload concepts
* **06-Active-Directory** — Windows and domain security
* **07-Network-Pivoting** — Network movement and access

These areas demonstrate progression from **reconnaissance and enumeration through exploitation, privilege escalation, Active Directory assessment, and network access**.

## Training Evidence

The complete Hack The Box Academy transcript provides supporting documentation of completed training and learning progress.

**HTB Academy Transcript:** [View Training Transcript](../HTB-Academy-Transcript.pdf)

## Disclaimer

All Hack The Box Academy activities were completed for authorized educational and training purposes within the Hack The Box environment.

No unauthorized systems or networks were targeted.

This repository does not contain proprietary Hack The Box course material, solutions, flags, credentials, or other restricted content. Portfolio documentation focuses on skills, concepts, tools, and personal learning outcomes.
