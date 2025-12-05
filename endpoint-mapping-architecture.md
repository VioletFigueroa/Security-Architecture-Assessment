---
title: "Endpoint Mapping & Architecture"
date: 2025-11-22
layout: "single"
draft: false
tags: ["endpoint mapping", "architecture", "NIST", "compliance", "vulnerability assessment", "hardening"]
summary: "Comprehensive endpoint security assessment, NIST 800-53 control gap analysis, and secure architecture documentation."
---

## Executive Summary

This project provides a comprehensive assessment of the organization’s endpoint mapping and secure architecture. It identifies key vulnerabilities, evaluates compliance with regulatory standards, and outlines a phased strategy for implementing security improvements. The recommendations are grounded in the NIST SP 800-53 Revision 5 framework and aim to strengthen the confidentiality, integrity, and availability of information systems.

## Project Deliverables

- 📄 [Endpoint Mapping (XLSX)](/projects/endpoint-mapping-architecture/Project%2011%20Endpoint%20Mapping.xlsx)
- 📄 [Secure Architecture Report (DOCX)](/projects/endpoint-mapping-architecture/Secure%20Architecture%20Report.docx)
- 📄 [Secure Architecture Report (Markdown)](/projects/endpoint-mapping-architecture/Secure%20Architecture%20Report.md)

## Project Overview

A comprehensive security assessment of a 30-endpoint corporate network environment, evaluating security controls against NIST 800-53 framework requirements. This project demonstrates systematic security auditing, compliance gap analysis, and practical remediation planning.

### Business Context

A small technology company needed to assess their endpoint security posture to:

- Identify vulnerabilities in their network and endpoint configurations.
- Ensure compliance with NIST 800-53 standards.
- Develop a roadmap for remediation and long-term security improvements.

### Project Objectives

1. **Inventory & Assessment**: Comprehensive endpoint asset discovery.
2. **NIST 800-53 Mapping**: Control identification and current state analysis.
3. **Gap Analysis**: Identify missing or inadequate security controls.
4. **Risk Prioritization**: Categorize findings by severity and impact.

## Methodology

### Phase 1: Asset Inventory & Discovery

- User account configurations.
- Network configurations.
- Security tool deployment status.

**Inventory Results:**

```bash
Total Endpoints: 30
├── Windows 10 Pro: 15
├── Windows 11 Pro: 10
└── macOS (Various): 5

Patch Status:
├── Fully Patched: 12 (40%)
└── Missing Critical Patches: 18 (60%)
```bash

### Phase 2: NIST 800-53 Control Mapping

Selected NIST 800-53 Rev. 5 as the baseline framework, focusing on endpoint-relevant control families:

1. Identified applicable technical requirements.
2. Assessed current implementation state.
3. Documented evidence of compliance or gaps.
4. Assigned compliance rating (Implemented / Partial / Not Implemented).

### Phase 3: Gap Analysis

**Critical Findings by Control Family:**

#### Access Control (AC)

- **AC-2: Account Management**: Not Implemented.
- **AC-3: Access Enforcement**: Partial.
- **AC-7: Unsuccessful Logon Attempts**: Not Implemented.

#### Audit and Accountability (AU)

- **AU-2: Event Logging**: Not Implemented.
- **AU-6: Audit Review**: Not Implemented.

#### Configuration Management (CM)

- **CM-2: Baseline Configuration**: Partial.
- **CM-7: Least Functionality**: Not Implemented.

#### System and Information Integrity (SI)

- **SI-2: Flaw Remediation**: Partial.
- **SI-3: Malicious Code Protection**: Not Implemented.
- **SI-4: Information System Monitoring**: Not Implemented.

#### System and Communications Protection (SC)

- **SC-8: Transmission Confidentiality**: Not Implemented.
- **SC-12: Cryptographic Key Management**: Not Implemented.

### Phase 4: Risk Assessment & Prioritization

**Risk Matrix:**

| Priority | Control Gap               | Impact | Effort  | Timeline       |
|----------|---------------------------|--------|---------|----------------|
| 🔴 Critical | Endpoint malware protection | High   | Low     | Immediate      |
| 🔴 Critical | Patch management          | High   | Medium  | 0-30 days      |
| 🔴 Critical | Disk encryption           | High   | Medium  | 0-30 days      |
| 🟠 High    | Centralized logging (SIEM) | Medium | High    | 30-60 days     |
| 🟠 High    | Account management process | Medium | Low     | 30-60 days     |
| 🟠 High    | Access control enforcement | Medium | Medium  | 60-90 days     |
| 🟢 Medium  | Baseline configurations    | Medium | Medium  | 90-120 days    |
| 🟢 Medium  | Network monitoring         | Medium | High    | 90-120 days    |

## Implementation Strategy

### Phase 1: Immediate Actions (0–3 months)

- Implement network segmentation to separate public-facing systems, internal servers, and employee devices.
- Deploy multi-factor authentication for all privileged and remote access.
- Enforce strong password policies across the organization.
- Enhance endpoint protection with centralized patch management and full-disk encryption.
- Develop a formal incident response plan and establish basic SIEM capabilities.

### Phase 2: Intermediate Enhancements (3–9 months)

- Deploy endpoint detection and response (EDR) solutions.
- Conduct regular vulnerability assessments and automate backup processes.
- Strengthen cloud security by inventorying assets and implementing secure configuration baselines.
- Formalize vendor risk management procedures and initiate regular security awareness training.

### Phase 3: Long-Term Maturation (9–18 months)

- Implement advanced security controls such as data loss prevention (DLP) and network intrusion prevention systems (IPS).
- Conduct annual tabletop exercises to test incident response and disaster recovery plans.
- Establish a schedule for regular policy and control reviews.
- Invest in ongoing staff training and periodic third-party assessments.

## Key Learnings

- **Proactive Security Measures**: Early implementation of foundational controls significantly reduces risks.
- **Regulatory Compliance**: Adherence to standards like PCI DSS and GDPR builds customer trust and mitigates legal risks.
- **Continuous Improvement**: Regular assessments and updates ensure the security architecture remains effective and responsive.

## References

1. National Institute of Standards and Technology. (2020). Security and Privacy Controls for Information Systems and Organizations (NIST Special Publication 800-53, Revision 5). [https://doi.org/10.6028/NIST.SP.800-53r5](https://doi.org/10.6028/NIST.SP.800-53r5)
2. Payment Card Industry Security Standards Council. (2022). Payment Card Industry Data Security Standard: Requirements and Security Assessment Procedures (Version 4.0).
3. European Union. (2016). Regulation (EU) 2016/679 (General Data Protection Regulation).

[← Back to Projects](/projects/)
