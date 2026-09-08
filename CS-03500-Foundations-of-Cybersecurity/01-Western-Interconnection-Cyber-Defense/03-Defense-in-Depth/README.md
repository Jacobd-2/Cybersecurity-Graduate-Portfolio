# Defense in Depth

**Project:** Western Interconnection Cyber Defense
**Course:** CS 03500 — Foundations of Cybersecurity
**Project Phase:** Defense in Depth
**Project Type:** Academic Cybersecurity Simulation

## Overview

This phase evaluated defense-in-depth strategies for protecting the Western Interconnection power grid against cyber threats.

The assessment examined vulnerabilities within network and endpoint security layers, evaluated the application of the NSA's defense-in-depth strategy across people, technology, and operations, and identified encryption as an additional layer for protecting communications between critical grid components.

## Key Security Risks

### 1. Network Security – Segmentation

Network segmentation divides an environment into smaller sections, allowing security policies and controls to be applied to different network segments.

Insufficient segmentation within power-grid environments can allow an attacker who compromises one portion of the network to move toward critical operational systems.

The assessment examined attacks against Ukraine's power grid as an example of the importance of separating information technology (IT) and operational technology (OT) environments.

**Security considerations:**

* Separate IT and OT environments
* Restrict communication between network segments
* Apply security controls based on network function
* Limit lateral movement
* Monitor traffic between critical segments

### 2. Endpoint Security – Patch Management

Patch management helps protect endpoint operating systems and applications against known vulnerabilities.

Unpatched systems can provide attackers with opportunities to gain unauthorized access or execute malicious code. The WannaCry ransomware incident was examined as an example of how attackers can exploit vulnerable, unpatched Windows systems.

**Security considerations:**

* Maintain current security updates
* Monitor for known vulnerabilities
* Establish regular patching procedures
* Prioritize critical vulnerabilities
* Verify successful patch deployment

## NSA Defense-in-Depth Strategy

The assessment examined defense in depth across three areas: **people, technology, and operations**.

### 1. People – Access Control

Role-Based Access Control (RBAC) can restrict users to the systems and resources required for their responsibilities.

Multi-Factor Authentication (MFA) can provide an additional authentication layer for access to critical systems such as SCADA environments.

**Security considerations:**

* Role-based access
* Least-privilege permissions
* Multi-Factor Authentication
* Strong authentication policies
* Regular access reviews

### 2. Technology – Intrusion Detection and Prevention

Intrusion Detection and Prevention Systems (IDPS) can monitor network activity for suspicious behavior and help detect or prevent malicious activity.

For a power-grid environment, IDPS capabilities can provide early warning of potential attacks and support rapid defensive response.

**Security considerations:**

* Network activity monitoring
* Threat detection
* Prevention of malicious activity
* Security alerts
* Rapid incident response

### 3. Operations – Data Recovery

Data recovery supports cyber resilience by helping organizations restore critical systems and information following a security incident.

For critical infrastructure, effective recovery capabilities can reduce operational downtime and support continuity following a cyberattack or system disruption.

**Security considerations:**

* Regular backups
* Recovery procedures
* Business continuity
* Disaster recovery planning
* Testing recovery processes

## Cryptographic Protection

The assessment examined the **Advanced Encryption Standard (AES)** as an additional security layer for protecting communications between critical grid components.

AES is a symmetric encryption algorithm that can be used to protect sensitive information while it is transmitted between systems.

For example, AES-256 could be used to protect communications between substations and control centers, helping maintain the confidentiality and integrity of critical information.

**Security considerations:**

* Encryption of sensitive communications
* Protection against data interception
* Confidentiality of information
* Integrity of transmitted information
* Secure communication between critical components

## Key Security Takeaways

The assessment demonstrated that protecting critical infrastructure requires multiple complementary security layers rather than relying on a single security control.

Key defensive priorities include:

* Network segmentation
* IT/OT separation
* Patch management
* Role-Based Access Control
* Multi-Factor Authentication
* Intrusion Detection and Prevention
* Data recovery
* Encryption
* Continuous monitoring
* Cyber resilience

Implementing these controls across people, technology, and operational processes can help reduce the likelihood and potential impact of attacks against critical infrastructure.

## Skills Demonstrated

* Defense in Depth
* Network Segmentation
* IT/OT Security
* Endpoint Security
* Patch Management
* Access Control
* Multi-Factor Authentication
* Intrusion Detection and Prevention
* Data Recovery
* Cyber Resilience
* Cryptography
* AES Encryption
* Critical Infrastructure Security
* Risk Analysis

## Evidence

**Primary Deliverable:**
[Defense in Depth Report](./defense-in-depth-report.pdf)

## Disclaimer

This work was completed as an academic cybersecurity simulation. No real-world critical infrastructure systems were targeted, accessed, or tested.
