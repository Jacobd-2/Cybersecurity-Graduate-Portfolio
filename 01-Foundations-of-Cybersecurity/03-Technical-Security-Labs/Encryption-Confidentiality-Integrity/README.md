# Encryption, Confidentiality & Integrity

| **Lab**     | **Using Encryption to Enhance Confidentiality and Integrity (4e)**                  |
| :---------- | :---------------------------------------------------------------------------------- |
| **Type**    | Hands-On Cryptography & Information Security Lab                                    |
| **Focus**   | Encryption • Asymmetric Cryptography • Key Management • Confidentiality • Integrity |

## Lab Overview

This hands-on lab focused on applying **encryption and cryptographic concepts to enhance information confidentiality and integrity**.

The lab was completed using *Fundamentals of Information Systems Security, Fourth Edition* and provided practical experience with **asymmetric encryption, cryptographic key pairs, key exchange, and key fingerprints**.

A key component of the lab involved creating and exchanging an **asymmetric encryption key pair** and verifying the associated key fingerprint.

**Time on Task:** 5 hours, 36 minutes
**Completion:** 100%

---

# Lab Objectives

The primary objectives of this lab were to:

1. Create an asymmetric encryption key pair.
2. Exchange cryptographic keys.
3. Examine key-pair information.
4. Verify a cryptographic key fingerprint.
5. Understand the role of public and private keys.
6. Apply encryption concepts to confidentiality.
7. Understand how cryptographic mechanisms support data integrity.
8. Document cryptographic configuration and verification evidence.

---

# 1. Create an Asymmetric Encryption Key Pair

The first hands-on component involved creating an asymmetric encryption key pair.

An asymmetric cryptographic system uses two mathematically related keys:

* **Public key** — can be distributed to other users or systems.
* **Private key** — must remain protected by its owner.

```text id="h5y0az"
             Key Pair
                │
       ┌────────┴────────┐
       ↓                 ↓
 Public Key        Private Key
       │                 │
 Distributed        Protected
       │                 │
       └───────┬─────────┘
               ↓
       Cryptographic
          Operations
```

### Security Objective

Separating public and private keys allows users to securely exchange information without directly sharing a private encryption key.

---

# 2. Exchange Asymmetric Encryption Keys

The lab included the exchange of asymmetric encryption keys.

### Security Concepts

Public keys can be shared with other parties while private keys remain under the control of their respective owners.

This model supports secure communications and can be used for:

* Encryption
* Decryption
* Digital signatures
* Identity verification
* Secure key exchange

### Security Objective

Key exchange allows communicating parties to establish cryptographic trust without exposing private keys.

---

# 3. Verify Key Fingerprint

The lab required a screen capture showing the **fingerprint for the generated key pair**.

A cryptographic fingerprint provides a compact representation of a key that can be used to help verify that the correct key is being used.

### Evidence

**Key-Pair Fingerprint**

The lab documentation includes evidence of the generated key-pair fingerprint.

The fingerprint should be treated as verification metadata rather than a replacement for protecting the associated private key.

---

# 4. Confidentiality

Encryption supports **confidentiality** by preventing unauthorized parties from understanding protected information.

In an asymmetric encryption model:

```text id="m5t8qk"
Sender
  │
  │ Encrypt
  ↓
Recipient's Public Key
  │
  ↓
Encrypted Data
  │
  ↓
Recipient
  │
  │ Decrypt
  ↓
Recipient's Private Key
  │
  ↓
Original Data
```

### Security Objective

Only the intended recipient possessing the appropriate private key should be able to decrypt information protected with their public key.

---

# 5. Integrity

Cryptographic mechanisms can also help verify that information has not been modified.

Integrity mechanisms may include:

* Cryptographic hashes
* Digital signatures
* Message authentication mechanisms
* Key verification

A cryptographic fingerprint can assist with verifying that a known cryptographic key corresponds to the expected key identity.

### Security Objective

Integrity controls help detect unauthorized modification or substitution of information and cryptographic keys.

---

# 6. Key Management

Effective encryption depends on properly managing cryptographic keys.

### Key Management Considerations

* Protect private keys
* Safely distribute public keys
* Verify key identities
* Monitor key ownership
* Replace compromised keys
* Maintain appropriate access controls
* Protect key storage

### Security Consideration

Compromise of a private key can undermine the security of information protected using that key.

---

# Hands-On Evidence

The completed lab included evidence of asymmetric cryptographic key creation and verification.

### Primary Evidence

**Key-Pair Fingerprint**

A screen capture was created showing the fingerprint associated with the generated asymmetric encryption key pair.

Additional screenshots and supporting evidence should be stored in the `screenshots/` directory.

---

# Security Assessment

| **Security Property** | **Cryptographic Mechanism**   | **Security Purpose**                             |
| :-------------------- | :---------------------------- | :----------------------------------------------- |
| Confidentiality       | Encryption                    | Protect information from unauthorized disclosure |
| Integrity             | Cryptographic verification    | Detect unauthorized modification                 |
| Authentication        | Key verification / signatures | Establish cryptographic identity                 |
| Key Security          | Private-key protection        | Prevent unauthorized cryptographic operations    |

---

# Key Security Takeaways

* Asymmetric cryptography uses public and private keys.
* Public keys can be distributed while private keys must remain protected.
* Key exchange supports secure communications between parties.
* Key fingerprints can help verify cryptographic key identity.
* Encryption provides an important mechanism for protecting confidentiality.
* Cryptographic integrity mechanisms can help detect unauthorized modification.
* Strong key management is essential to maintaining the security of cryptographic systems.

---

# Skills Demonstrated

`Asymmetric Cryptography`

`Encryption`

`Key Pair Generation`

`Key Exchange`

`Key Fingerprint Verification`

`Cryptographic Key Management`

`Confidentiality`

`Integrity`

`Information Security`

---

# Tools & Technologies

* Asymmetric encryption
* Cryptographic key pairs
* Public keys
* Private keys
* Key fingerprints
* Encryption technologies
* Cryptographic verification

---

# Security Concepts

* Cryptography
* Asymmetric Encryption
* Public-Key Cryptography
* Public Keys
* Private Keys
* Key Exchange
* Key Management
* Key Fingerprints
* Confidentiality
* Integrity
* Authentication
* Digital Signatures
* Data Protection

---

# Project Structure

```text id="a8w4kc"
Encryption-Confidentiality-Integrity/
├── README.md
└── Encryption-Confidentiality-Integrity-report.pdf
```

### Recommended Artifact Organization

**screenshots/**
Store screenshots demonstrating key creation, key exchange, fingerprints, and other important lab evidence.

**keys/**
Do **not** upload private keys or other sensitive cryptographic material. If documentation is required, use sanitized or non-sensitive examples.

**analysis/**
Store supporting cryptography notes and analysis.

**report.pdf**
Store the completed encryption lab report.

---

# Portfolio Context

This lab was completed as part of hands-on cybersecurity coursework using a controlled educational environment.

The lab demonstrates practical understanding of **asymmetric cryptography, key management, confidentiality, integrity, and cryptographic verification**.

These concepts provide foundational knowledge for securing communications, protecting sensitive information, and implementing enterprise security controls.

## Disclaimer

This lab was performed within an authorized educational environment.

No unauthorized systems, accounts, cryptographic keys, or production environments were accessed or compromised.

**Sensitive cryptographic material, including private keys, should never be uploaded to a public GitHub repository.**
