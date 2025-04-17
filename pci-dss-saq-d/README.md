# PCI-DSS SAQ-D Compliance Guide

This section provides a structured overview of key requirements in the PCI-DSS Self-Assessment Questionnaire D (SAQ-D), one of the most comprehensive compliance tools for organizations that process, store, or transmit cardholder data. Originally written as part of a graduate cybersecurity course, this guide has been reformatted to serve as a practical reference for implementing secure payment practices.

---

## Overview

**Objective:**  
To break down critical controls within Sections 3, 8, 9, and 10 of the PCI-DSS SAQ-D and offer actionable strategies for compliance.

**Focus Areas:**
- Encryption & key management for stored cardholder data
- Identification and authentication controls (e.g., MFA, user IDs)
- Physical access controls and audit readiness
- Logging and monitoring of sensitive system access

---

## Section Breakdown

### Section 3: Safeguarding Stored Cardholder Data
- Use of encryption, truncation, or tokenization
- Key management best practices
- Data retention policies and risk assessments

### Section 8: Access Control via Identification & Authentication
- Unique user identification
- Two-factor authentication (2FA)
- Password policy enforcement
- Role-Based Access Control (RBAC) principles

### Section 9: Physical Access Control
- Controlled access to backup media and data centers
- Surveillance and visitor logging procedures
- Employee access protocols and physical audits

### Section 10: Monitoring & Tracking Access
- Security Information and Event Management (SIEM)
- Audit log retention and review policies
- Alerting and anomaly detection mechanisms

---

## Tools & Practices Discussed

- AES-256 Encryption and secure key storage
- Multi-Factor Authentication implementation (e.g., Google Authenticator, Duo)
- Log review automation via SIEM tools (e.g., Splunk, ELK)
- Access governance and audit trail maintenance

---

## Document

You can view the original paper (academic version) here:  
 [`PCI-DSS SAQ-D Compliance- A Section-by-Section Guide to Secure Payment Practices.pdf`](./PCI-DSS SAQ-D Compliance- A Section-by-Section Guide to Secure Payment Practices.pdf)

---

## Author

**Nelson Morales**  
Cybersecurity Graduate Student @ Purdue University Global  
Software Engineer Apprentice | [LinkedIn](https://www.linkedin.com/in/nelson-cyberdev/) | [GitHub](https://github.com/Sonofneli7)

---

> This document is educational in nature and based on PCI-DSS documentation as of 2024. Always refer to the official [PCI Security Standards Council](https://www.pcisecuritystandards.org) site for the latest requirements.
