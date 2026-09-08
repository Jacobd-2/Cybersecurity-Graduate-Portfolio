# Packet Capture & Traffic Analysis

| **Lab**     | **Performing Packet Capture and Traffic Analysis (4e)**                                |
| :---------- | :------------------------------------------------------------------------------------- |
| **Type**    | Hands-On Network Security Lab                                                          |
| **Focus**   | Packet Capture • Wireshark • Network Traffic Analysis • FTP • SFTP • Protocol Analysis |

## Lab Overview

This hands-on lab focused on capturing, inspecting, and analyzing network traffic using **Wireshark**.

The lab was completed using *Fundamentals of Information Systems Security, Fourth Edition* and provided practical experience analyzing network communications and file-transfer protocols.

A key component of the lab involved generating and analyzing **FTP and SFTP file-transfer traffic**, allowing packet-level examination of network communications and the differences between unencrypted and encrypted file-transfer protocols.

**Time on Task:** 5 hours, 27 minutes
**Completion:** 100%

---

# Lab Objectives

The primary objectives of this lab were to:

1. Configure Wireshark for network traffic analysis.
2. Generate controlled network traffic for analysis.
3. Capture network packets associated with file transfers.
4. Analyze captured traffic using Wireshark.
5. Examine FTP traffic.
6. Examine SFTP traffic.
7. Identify relevant network protocols and communications.
8. Interpret packet-level information.
9. Compare security characteristics of different file-transfer protocols.
10. Document network-analysis results.

---

# 1. Configure Wireshark & Generate Network Traffic

The first part of the lab involved configuring Wireshark and generating controlled network traffic for subsequent analysis.

### Activities

* Configured Wireshark for packet capture
* Generated network traffic
* Performed FTP file transfers
* Performed SFTP file transfers
* Captured the resulting network communications
* Verified successful file transfers

### Security Focus

Generating known network activity provides a controlled baseline for examining how application protocols appear at the packet level.

---

# 2. FTP Traffic Analysis

FTP traffic was captured and analyzed using Wireshark.

### Analysis Areas

* FTP protocol traffic
* Client/server communications
* File-transfer activity
* Network packets associated with FTP
* Source and destination information
* Protocol behavior

### Security Consideration

FTP does not provide the same level of protection for communications as encrypted file-transfer protocols. Network traffic analysis can therefore provide visibility into information transmitted through FTP connections.

---

# 3. SFTP Traffic Analysis

SFTP traffic was also generated and analyzed using Wireshark.

### Analysis Areas

* SFTP communications
* Client/server traffic
* Encrypted network sessions
* Source and destination information
* Packet-level protocol behavior

### Security Consideration

SFTP operates through an encrypted SSH connection, providing stronger protection for file transfers than traditional FTP.

---

# 4. Wireshark Packet Analysis

Wireshark was used to inspect captured packets and investigate network communications.

### Analysis Activities

* Examined captured packets
* Identified protocols
* Reviewed packet details
* Investigated source and destination hosts
* Examined communication sessions
* Applied Wireshark analysis techniques
* Compared FTP and SFTP traffic

---

# 5. FTP vs. SFTP Security Comparison

| **Characteristic** | **FTP**                                         | **SFTP**                          |
| :----------------- | :---------------------------------------------- | :-------------------------------- |
| Encryption         | Limited / None by default                       | Encrypted through SSH             |
| Traffic Visibility | Greater visibility into transmitted information | Payload protected by encryption   |
| Security           | Lower                                           | Higher                            |
| Primary Use        | File transfer                                   | Secure file transfer              |
| Security Risk      | Sensitive information may be exposed            | Provides stronger confidentiality |

### Security Takeaway

The lab demonstrated the importance of selecting secure network protocols when transferring sensitive information.

Using encrypted protocols helps protect data from unauthorized interception during transmission.

---

# Hands-On Evidence

The lab included evidence demonstrating successful FTP and SFTP file transfers.

### Evidence

* Successful FTP file transfer
* Successful SFTP file transfer
* Wireshark packet captures
* Network traffic analysis

Screenshots and supporting evidence from the completed lab should be stored in the lab's `screenshots/` directory.

---

# Key Security Takeaways

* Packet capture provides visibility into network communications.
* Wireshark can be used to inspect and analyze network protocols.
* FTP and SFTP provide an important example of differences between traditional and encrypted file-transfer protocols.
* Network traffic analysis can support security investigations and troubleshooting.
* Encrypted protocols are important for protecting sensitive information in transit.
* Understanding normal network traffic helps security professionals identify abnormal activity.

---

# Skills Demonstrated

`Wireshark`

`Packet Capture`

`Network Traffic Analysis`

`Packet Analysis`

`Protocol Analysis`

`FTP`

`SFTP`

`Network Security`

`Network Forensics`

`Security Analysis`

---

# Tools & Technologies

* Wireshark
* Network packet capture
* FTP
* SFTP
* SSH
* Network protocols
* Packet analysis techniques

---

# Security Concepts

* Packet Capture
* Network Traffic Analysis
* Network Forensics
* Protocol Analysis
* FTP
* SFTP
* SSH
* Encryption
* Confidentiality
* Data in Transit
* Client-Server Communication
* Network Security

---

# Project Structure

```text
Packet-Capture-Traffic-Analysis/
├── README.md
├── screenshots/
├── packet-captures/
├── analysis/
└── report.pdf
```

### Recommended Artifact Organization

**screenshots/**
Screenshots demonstrating Wireshark configuration, FTP/SFTP transfers, and important packet-analysis findings.

**packet-captures/**
Authorized lab PCAP files, if redistribution is permitted.

**analysis/**
Supporting notes, Wireshark filters, observations, and analysis results.

**report.pdf**
The completed 10-page lab report.

---

# Portfolio Context

This lab was completed as part of hands-on cybersecurity coursework and demonstrates practical experience with **packet capture, Wireshark, network traffic analysis, and secure file-transfer protocols**.

The lab provides technical evidence supporting foundational skills in **network security and network forensics**.

## Disclaimer

This lab was performed within an authorized educational environment.

No unauthorized systems, networks, communications, or production environments were targeted or monitored.
