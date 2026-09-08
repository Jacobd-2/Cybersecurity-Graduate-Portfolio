# Security Monitoring & Logging

| **Lab**     | **Implementing Security Monitoring and Logging (4e)**                                                |
| :---------- | :--------------------------------------------------------------------------------------------------- |
| **Type**    | Hands-On Security Monitoring Lab                                                                     |
| **Focus**   | Security Monitoring • Windows Logging • Failed Logon Detection • Snort • Network Activity Monitoring |

## Lab Overview

This hands-on lab focused on implementing **security monitoring and logging** across Windows systems and network environments.

The lab was completed using *Fundamentals of Information Systems Security, Fourth Edition* and provided practical experience identifying **failed logon attempts on Windows systems** and monitoring **network activity with Snort**.

The exercise demonstrated how security logs and network monitoring technologies can provide visibility into authentication activity and network behavior.

**Time on Task:** 7 hours, 3 minutes
**Completion:** 91%

---

# Lab Objectives

The primary objectives of this lab were to:

1. Identify failed logon attempts on Windows systems.
2. Examine Windows security event information.
3. Investigate authentication-related security events.
4. Monitor network activity using Snort.
5. Apply security monitoring and logging concepts.
6. Understand the importance of endpoint security visibility.
7. Understand the role of network monitoring in security operations.
8. Document technical evidence from security-monitoring activities.

---

# 1. Identify Failed Logon Attempts on Windows Systems

The first part of the lab focused on identifying **failed logon attempts on Windows systems**.

The exercise was performed on the **vWorkstation** and involved examining Windows security event information associated with authentication activity.

### Security Concept

Failed logon attempts can provide valuable information when investigating authentication activity.

Repeated or unusual authentication failures may indicate potential unauthorized-access attempts, credential attacks, or other security events requiring further investigation.

### Security Objective

The exercise demonstrated how Windows security events can be used to monitor and investigate authentication activity.

---

# 2. Windows Security Event Monitoring

The lab required examination of security-event information on the Windows **vWorkstation**.

The exercise provided hands-on experience working with the **Security Event Properties** interface.

### Evidence

The lab required a screen capture showing the **Security Event Properties** dialog box on the vWorkstation.

This demonstrated the ability to access and examine Windows security-event information during a monitoring investigation.

### Monitoring Workflow

```text
Windows System
      ↓
Authentication Activity
      ↓
Security Events
      ↓
Event Properties
      ↓
Security Analysis
      ↓
Investigation
```

---

# 3. Monitor Network Activity with Snort

The second part of the lab focused on monitoring **network activity using Snort**.

Snort is a network security monitoring technology that can be used to inspect network traffic and identify activity that may require security investigation.

### Security Objective

The exercise demonstrated how network monitoring can complement endpoint security logging by providing visibility into network activity.

### Monitoring Flow

```text
Network Traffic
      ↓
     Snort
      ↓
Traffic Monitoring
      ↓
Security Events
      ↓
Analysis
      ↓
Investigation
```

---

# 4. Endpoint and Network Security Monitoring

The lab demonstrated two important sources of security visibility:

| **Monitoring Area** | **Technology**          | **Security Purpose**            |
| ------------------- | ----------------------- | ------------------------------- |
| Windows Endpoint    | Windows Security Events | Monitor authentication activity |
| Network             | Snort                   | Monitor network activity        |

Combining endpoint and network monitoring can provide a broader view of activity within an information system.

Endpoint logs can provide information about authentication events, while network monitoring can provide visibility into traffic and network behavior.

---

# 5. Security Monitoring & Logging

Effective security monitoring depends on collecting and analyzing relevant security information.

### Security Monitoring Process

```text
Security Events
      ↓
     Logging
      ↓
   Monitoring
      ↓
     Analysis
      ↓
Threat Identification
      ↓
 Investigation
      ↓
Security Response
```

Security monitoring technologies help security teams identify events that may require additional analysis or response.

---

# 6. Security Operations Considerations

Security monitoring is an important component of defensive cybersecurity and security operations.

Monitoring authentication events can help identify potentially suspicious login activity, while network monitoring can provide additional visibility into activity occurring across the environment.

### Key Considerations

* Monitor authentication activity.
* Review security events.
* Investigate unusual activity.
* Monitor network traffic.
* Correlate information from multiple security sources.
* Maintain appropriate security logging.
* Use monitoring data to support incident investigation.

---

# Hands-On Evidence

The completed lab included hands-on evidence demonstrating the security-monitoring activities.

### Primary Evidence

**Security Event Properties Dialog Box**

The required screen capture documented the Security Event Properties dialog box on the vWorkstation.

### Network Monitoring

The lab also included hands-on activity involving **network monitoring with Snort**.

Additional screenshots from the completed lab should be stored in the `screenshots/` directory.

---

# Key Security Takeaways

* Windows security events provide valuable visibility into authentication activity.
* Failed logon attempts can serve as indicators for additional investigation.
* Security event properties can provide information useful during security analysis.
* Network monitoring provides visibility beyond individual endpoints.
* Snort can be used for network security monitoring.
* Endpoint and network monitoring provide complementary sources of security information.
* Effective logging supports security investigations and incident response.
* Security monitoring is an important component of defensive security operations.

---

# Skills Demonstrated

`Security Monitoring`

`Security Logging`

`Windows Event Analysis`

`Failed Logon Detection`

`Authentication Monitoring`

`Network Activity Monitoring`

`Snort`

`Intrusion Detection Concepts`

`Security Event Analysis`

`Defensive Security`

`Security Operations`

`Technical Documentation`

---

# Tools & Technologies

* Windows Security Event Monitoring
* Windows Event Logging
* Snort
* Network Monitoring
* Security Event Analysis
* Network Security Monitoring

---

# Security Concepts

* Security Monitoring
* Security Logging
* Authentication Monitoring
* Failed Logon Detection
* Windows Security Events
* Network Monitoring
* Intrusion Detection
* Security Event Analysis
* Endpoint Monitoring
* Network Security
* Defensive Security
* Security Operations
* Incident Investigation

---

# Project Structure

```text
Security-Monitoring-Logging/
├── README.md
└── Security-Monitoring-Logging-report.pdf
```

### Recommended Artifact Organization

**screenshots/**
Store the Security Event Properties screenshot and other relevant evidence from the lab.

**logs/**
Store sanitized security-log examples or exported event information when appropriate.

**snort/**
Store Snort-related lab configurations or artifacts that are safe to publish.

**analysis/**
Store supporting notes, monitoring analysis, and security observations.

**report.pdf**
Store the completed security monitoring and logging report.

---

# Portfolio Context

This lab was completed as part of hands-on cybersecurity coursework using a controlled educational environment.

The lab demonstrates practical experience with **security monitoring, Windows security events, failed logon analysis, network activity monitoring, Snort, and defensive security operations**.

The exercise complements the portfolio's other technical security labs by demonstrating the ability to monitor both **endpoint and network activity** as part of a layered security-monitoring strategy.

## Disclaimer

This lab was performed within an authorized educational environment.

All security-monitoring activities were conducted for educational purposes within the controlled laboratory environment. No unauthorized systems, accounts, networks, or production environments were targeted.
