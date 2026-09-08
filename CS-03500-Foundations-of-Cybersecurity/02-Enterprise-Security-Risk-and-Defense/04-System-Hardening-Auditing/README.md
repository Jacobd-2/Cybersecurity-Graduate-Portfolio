# System Hardening & Auditing

| **Project** | **Enterprise Security Risk & Defense**                                                                       |
| :---------- | :----------------------------------------------------------------------------------------------------------- |
| **Phase**   | System Hardening & Auditing                                                                                  |
| **Focus**   | Windows Security • Antivirus Management • Audit Logging • Event Analysis • System Hardening • Access Control |

## Project Overview

This phase evaluated and performed **Windows system security and auditing activities** within a controlled academic environment.

The assessment examined endpoint protection using **McAfee antivirus**, configured Windows audit logging to record failed authentication attempts, analyzed security events through **Event Viewer**, and evaluated system-hardening practices for reducing the attack surface.

During the assessment, the system's antivirus status and scheduled scans were reviewed. Windows audit logging was then configured to capture failed logon events, allowing security events to be monitored and investigated.

The assessment identified three failed logon attempts during the monitored period. Investigation determined that the events were associated with employee password errors rather than confirmed malicious activity. However, the events demonstrated the importance of continuous authentication monitoring and strong access controls.

---

# Project Objectives

* Verify the status of endpoint antivirus protection
* Review antivirus update status and scheduled scans
* Configure Windows audit logging
* Monitor failed authentication attempts
* Analyze Windows Security Event logs
* Identify and investigate potentially suspicious security events
* Interpret Windows Event ID 4625
* Evaluate authentication-related security risks
* Recommend Multi-Factor Authentication (MFA)
* Develop password-security recommendations
* Evaluate antivirus scanning schedules
* Examine system-hardening principles
* Identify methods for reducing the attack surface

---

# Endpoint Security Assessment

## 1. Antivirus Protection

The Windows 10 system was reviewed to determine the status of the installed **McAfee antivirus** software.

The antivirus application indicated that its most recent update had been completed on **October 21, 2024**, at 6:10 PM.

The system was also configured to perform scheduled antivirus scans every Sunday at 8:00 AM. The most recent scan had completed on October 20, 2024, without identifying a significant threat.

### Security Considerations

* Maintain current antivirus definitions
* Verify successful security updates
* Schedule regular antivirus scans
* Review scan results
* Quarantine detected threats
* Schedule scans during lower-usage periods
* Continuously monitor endpoint security

---

# Windows Audit Logging

## 2. Configuring Failed Logon Auditing

Windows **Local Group Policy Editor** was used to configure audit logging for failed authentication attempts.

The following policy path was used:

```text
Local Computer Policy
└── Computer Configuration
    └── Windows Settings
        └── Security Settings
            └── Local Policies
                └── Audit Policy
                    └── Audit logon events
```

The **Failure** option was enabled to record unsuccessful logon attempts.

This configuration allows failed authentication events to be recorded in the Windows Security event log and subsequently investigated through Event Viewer.

### Security Considerations

* Enable authentication auditing
* Record failed logon attempts
* Monitor authentication activity
* Review security event logs
* Investigate unusual authentication patterns
* Retain relevant security logs

---

# Security Event Analysis

## 3. Windows Event ID 4625

Windows **Event ID 4625** represents a failed account logon.

During the 24-hour monitoring period, three failed logon attempts were identified in the Windows Security event log.

The events were investigated to determine whether they represented potentially malicious authentication activity.

### Findings

The investigation determined that the failed attempts resulted from **employee password-entry errors** rather than confirmed malicious activity.

Although no malicious intent was identified, repeated failed authentication attempts remain a security concern because attackers can use stolen or guessed credentials to attempt unauthorized access.

### Security Considerations

* Monitor failed authentication events
* Investigate repeated failures
* Correlate authentication activity
* Identify unusual login patterns
* Monitor source systems and accounts
* Escalate suspicious authentication activity

---

# Authentication Security Recommendations

## 4. Multi-Factor Authentication

The assessment recommended implementing **Multi-Factor Authentication (MFA)** for employees to provide an additional layer of protection against unauthorized account access.

MFA can reduce the risk associated with compromised or stolen passwords by requiring an additional authentication factor.

### Security Considerations

* Require MFA for user accounts
* Prioritize privileged accounts
* Protect remote access
* Reduce reliance on passwords alone
* Review authentication policies regularly

---

## 5. Password Security

Employees were also advised to use **complex passwords** and protect their credentials from unauthorized disclosure.

Strong password practices can reduce the likelihood of successful credential-based attacks.

### Security Considerations

* Use strong passwords
* Avoid password reuse
* Protect credentials
* Do not share passwords
* Apply appropriate account-security policies
* Combine passwords with MFA

---

# Antivirus Monitoring Recommendations

## 6. Scheduled Security Scanning

The assessment recommended increasing antivirus scanning frequency to **daily scans**, preferably scheduled during off-peak hours.

More frequent scanning can provide additional opportunities to identify and quarantine malicious software while minimizing potential disruption to normal business operations.

### Security Considerations

* Schedule regular scans
* Monitor scan results
* Review detected threats
* Perform scans during lower-usage periods
* Maintain current antivirus definitions
* Investigate security alerts

---

# System Hardening

System hardening is a cybersecurity practice focused on **reducing vulnerabilities and minimizing an organization's attack surface**.

Hardening can involve disabling unnecessary services, removing unused applications, strengthening configurations, applying security updates, and enabling available security controls.

### Security Considerations

* Disable unnecessary services
* Remove unused applications
* Apply security updates
* Strengthen system configurations
* Restrict unnecessary privileges
* Enable built-in security controls
* Reduce the attack surface
* Continuously review system configurations

---

# Compliance & Security

System hardening can also support organizational security and compliance objectives by helping organizations establish stronger security configurations and reduce unnecessary exposure.

Maintaining appropriate security controls can help organizations demonstrate their commitment to protecting systems and information.

### Security Considerations

* Security policies
* Configuration management
* Vulnerability reduction
* Security standards
* Regulatory requirements
* Continuous security improvement

---

# Key Security Takeaways

The assessment demonstrated the importance of combining **endpoint protection, authentication monitoring, security logging, and system hardening** to strengthen an organization's security posture.

Key defensive priorities include:

* Current antivirus protection
* Regular security scanning
* Authentication auditing
* Security event monitoring
* Failed-logon investigation
* Multi-Factor Authentication
* Strong password practices
* System hardening
* Attack-surface reduction
* Continuous security monitoring

The analysis also demonstrated that not every failed authentication event represents a confirmed attack. Security teams must **investigate and contextualize security events** to distinguish normal user errors from potentially malicious activity.

---

# Skills Demonstrated

`Windows Security` `System Hardening` `Security Auditing` `Audit Logging` `Event Log Analysis` `Event Viewer` `Event ID 4625` `Endpoint Security` `Antivirus Management` `Authentication Monitoring` `MFA` `Password Security` `Access Control` `Threat Detection` `Security Monitoring` `Vulnerability Reduction`

---

# Frameworks & Methodologies

* **System Hardening**
* **Security Auditing**
* **Security Monitoring**
* **Access Control**
* **Defense in Depth**
* **Risk Mitigation**

---

# Security Concepts

* Windows Security
* Endpoint Security
* Antivirus Protection
* Audit Logging
* Authentication Monitoring
* Failed Logon Detection
* Windows Event ID 4625
* Event Viewer
* Multi-Factor Authentication
* Password Security
* System Hardening
* Attack Surface Reduction
* Configuration Management
* Vulnerability Reduction
* Security Monitoring

---

# Tools & Technologies

* **Windows 10**
* **McAfee Antivirus**
* **Local Group Policy Editor**
* **Windows Event Viewer**
* **Windows Security Event Logs**
* **Audit Policy**
* **Event ID 4625**

---

# Project Structure

```text
04-System-Hardening-Auditing/
├── README.md
└── system-hardening-auditing-report.pdf
```

---

# Portfolio Context

This phase was completed in a **controlled academic cybersecurity lab environment** to demonstrate endpoint security, Windows auditing, security-event analysis, and system-hardening concepts.

The exercise demonstrates the ability to **review endpoint protection, configure Windows audit policies, analyze authentication events, investigate failed logon activity, identify security risks, and develop recommendations for strengthening authentication and system security**.

The three failed logon events identified during the assessment were investigated and attributed to employee password-entry errors. No confirmed malicious activity was identified.

No unauthorized systems or production environments were accessed, compromised, or tested as part of this exercise.

## Disclaimer

This work was completed as an academic cybersecurity lab. The systems and security events described in this assessment were used for educational purposes and do not represent an actual production security assessment.
