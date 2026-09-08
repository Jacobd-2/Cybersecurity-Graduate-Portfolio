# Threat Analysis & Cyber Kill Chain

**Project:** Western Interconnection Cyber Defense
**Course:** CS 03500 — Foundations of Cybersecurity
**Project Phase:** Threat Analysis & Cyber Kill Chain
**Project Type:** Academic Cybersecurity Simulation

## Overview

This phase analyzed a simulated cyberattack against the Western Interconnection power grid. The assessment focused on identifying a malware threat capable of affecting Supervisory Control and Data Acquisition (SCADA) and Industrial Control System (ICS) environments.

The analysis used **BlackEnergy** as the malware example and applied the Cyber Kill Chain and Adversary Model to examine how an attack could progress from initial reconnaissance through actions on objectives.

## Malware Threat: BlackEnergy

BlackEnergy was examined as a potential threat to power-grid environments because of its association with attacks involving industrial control systems and critical infrastructure.

The assessment considered potential infection vectors including:

* Phishing
* Malicious downloads
* Exploitation of software vulnerabilities
* Weak security configurations

Potential impacts examined included disruption of operational systems, manipulation of control commands, equipment disruption, and denial-of-service activity.

## Cyber Kill Chain Analysis

The attack scenario was mapped across seven stages:

| Stage                     | Analysis                                                                                                       |
| ------------------------- | -------------------------------------------------------------------------------------------------------------- |
| **Reconnaissance**        | Identify information about the target infrastructure, vulnerabilities, and potential entry points.             |
| **Weaponization**         | Develop or prepare a malicious payload for the intended target.                                                |
| **Delivery**              | Deliver the malware through methods such as phishing, malicious downloads, or exploitation of vulnerabilities. |
| **Exploitation**          | Exploit a vulnerability or weakness to execute malicious activity.                                             |
| **Installation**          | Establish the malware on a target system or related infrastructure.                                            |
| **Command & Control**     | Establish communication with attacker-controlled infrastructure to receive instructions.                       |
| **Actions on Objectives** | Execute the attacker's intended objectives, potentially disrupting operations or manipulating system activity. |

## Defensive Strategies

The assessment identified several defensive measures that could help prevent, detect, or limit the impact of a BlackEnergy-style attack:

### Monitor and Respond

Continuously monitor network activity and respond rapidly to suspicious behavior or potential intrusions.

### Secure Remote Access

Protect remote-access pathways to control systems and eliminate unnecessary or unauthorized access points.

### Manage Authentication

Implement strong authentication controls, including strong password requirements and Multi-Factor Authentication (MFA) where appropriate.

### Network Segmentation

Segment operational technology and other critical network environments to limit lateral movement and contain potential compromises.

### Patch and Configuration Management

Maintain supported systems, apply security updates, and ensure systems are securely configured to reduce exploitable weaknesses.

### Application Whitelisting

Restrict execution to authorized applications to help prevent unauthorized or malicious software from running.

## Adversary Model

The project also evaluated the simulated threat using an adversary model consisting of capabilities, resources, intent, motivation, access, and risk aversion.

| Element           | Assessment                                                                            |
| ----------------- | ------------------------------------------------------------------------------------- |
| **Capabilities**  | Ability to exploit weaknesses in SCADA/ICS environments                               |
| **Resources**     | Skilled personnel and access to advanced technical capabilities                       |
| **Intent**        | Potential disruption of critical infrastructure for strategic or political objectives |
| **Motivation**    | Potential geopolitical or financial objectives                                        |
| **Access**        | Potential use of social engineering and exploitation of vulnerabilities               |
| **Risk Aversion** | Assessed as moderate based on potential objectives and consequences                   |

## Key Security Takeaways

The analysis demonstrated how an attacker could progress through multiple stages of a cyberattack against a critical infrastructure environment.

Key defensive priorities include:

* Early detection and continuous monitoring
* Strong authentication and access controls
* Secure remote access
* Network segmentation
* Vulnerability and patch management
* Secure system configuration
* Application control
* Rapid incident response

A layered defensive strategy can reduce the likelihood that an attacker will successfully progress through the entire attack chain.

## Skills Demonstrated

* Threat Analysis
* Threat Modeling
* Malware Analysis
* Cyber Kill Chain
* Adversary Modeling
* SCADA / ICS Security
* Critical Infrastructure Security
* Vulnerability Assessment
* Network Segmentation
* Authentication and Access Control
* Security Monitoring
* Incident Response
* Risk Analysis

## Evidence

**Primary Deliverable:**
[Threat Analysis & Cyber Kill Chain Report](./threat-analysis-cyber-kill-chain-report.pdf)

## References

* Kaspersky — BlackEnergy threat research
* Chapple & Seidl — *Cyberwarfare: Information Operations in a Connected World*
* CISA / ICS-CERT — *Seven Strategies to Defend ICSs*
* Mullins — *The Cold War: Then and Now*

## Disclaimer

This work was completed as an academic cybersecurity simulation. No real-world critical infrastructure systems were targeted, accessed, or tested.
