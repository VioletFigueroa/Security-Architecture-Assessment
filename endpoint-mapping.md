title: "Endpoint Security Mapping & NIST 800-53 Gap Analysis"
date: 2025-07-10
layout: "single"
draft: false
tags: ["NIST", "compliance", "endpoint security", "vulnerability assessment", "hardening"]
summary: "Comprehensive endpoint security assessment and NIST 800-53 control gap analysis with remediation roadmap."
weight: 4

# Endpoint Security Mapping & NIST 800-53 Gap Analysis

## Project Overview

A comprehensive security assessment of a 30-endpoint corporate network environment, evaluating security controls against NIST 800-53 framework requirements. This project demonstrates systematic security auditing, compliance gap analysis, and practical remediation planning.

### Business Context

A small technology company needed to assess their endpoint security posture to:

**Environment:**

## Project Objectives

1. **Inventory & Assessment** - Comprehensive endpoint asset discovery
2. **NIST 800-53 Mapping** - Control identification and current state analysis
3. **Gap Analysis** - Identify missing or inadequate security controls
4. **Risk Prioritization** - Categorize findings by severity and impact

## Methodology

### Phase 1: Asset Inventory & Discovery

- User account configurations
- Network configurations
- Security tool deployment status

**Tools Used:**

**Inventory Results:**

```
Total Endpoints: 30
├── Windows 10 Pro: 15
├── Windows 11 Pro: 10
└── macOS (Various): 5

Patch Status:
├── Fully Patched: 12 (40%)
├── Missing Critical Patches: 18 (60%)

```text

### Phase 2: NIST 800-53 Control Mapping

**Framework Selection:**
Selected NIST 800-53 Rev. 5 as the baseline framework, focusing on endpoint-relevant control families:

**Control Assessment Process:**

For each relevant control:

1. Identified applicable technical requirements
2. Assessed current implementation state
3. Documented evidence of compliance or gaps
4. Assigned compliance rating (Implemented / Partial / Not Implemented)

### Phase 3: Gap Analysis

**Critical Findings by Control Family:**

#### Access Control (AC)

❌ **AC-2: Account Management**

⚠️ **AC-3: Access Enforcement**

❌ **AC-7: Unsuccessful Logon Attempts**

#### Audit and Accountability (AU)

❌ **AU-2: Event Logging**

❌ **AU-6: Audit Review**

#### Configuration Management (CM)

⚠️ **CM-2: Baseline Configuration**

❌ **CM-7: Least Functionality**

#### System and Information Integrity (SI)

⚠️ **SI-2: Flaw Remediation**

❌ **SI-3: Malicious Code Protection**

❌ **SI-4: Information System Monitoring**

#### System and Communications Protection (SC)

❌ **SC-8: Transmission Confidentiality**

❌ **SC-12: Cryptographic Key Management**

### Phase 4: Risk Assessment & Prioritization

**Risk Matrix:**

| Priority | Control Gap | Impact | Effort | Timeline |
|----------|-------------|--------|--------|----------|
| 🔴 Critical | Endpoint malware protection | High | Low | Immediate |
| 🔴 Critical | Patch management | High | Medium | 0-30 days |
| 🔴 Critical | Disk encryption | High | Medium | 0-30 days |
| 🟡 High | Centralized logging (SIEM) | Medium | High | 30-60 days |
| 🟡 High | Account management process | Medium | Low | 30-60 days |
| 🟡 High | Access control enforcement | Medium | Medium | 60-90 days |
| 🟢 Medium | Baseline configurations | Medium | Medium | 90-120 days |
| 🟢 Medium | Network monitoring | Medium | High | 90-120 days |

## Remediation Roadmap

### Phase 1: Critical Controls (0-30 Days)

**1. Endpoint Protection Deployment**

**2. Patch Management Program**

**3. Full Disk Encryption**

### Phase 2: High Priority Controls (30-90 Days)

**4. Centralized Log Management**

**5. Access Control Hardening**

**6. Baseline Security Configurations**

### Phase 3: Medium Priority Controls (90-180 Days)

**7. Network Monitoring & EDR Enhancement**

**8. Vulnerability Management Program**

**9. Security Awareness & Documentation**

## Technologies & Tools Used

### Assessment Tools

### Recommended Solutions

## Project Outcomes

### Measurable Results

✅ **Complete asset inventory** - 30 endpoints documented with detailed configurations
✅ **75+ NIST 800-53 controls assessed** - Comprehensive gap analysis completed
✅ **18 critical/high priority gaps identified** - Risk-prioritized remediation roadmap
✅ **100% malware protection deployment** - EDR implemented across all endpoints
✅ **60% → 100% patch compliance** - Automated patch management established
✅ **Disk encryption deployed** - BitLocker/FileVault on all devices
✅ **SIEM implementation** - Centralized logging and monitoring operational

### Professional Skills Demonstrated

## Key Learnings

### Framework Value

**NIST 800-53 Provides Structure:**
The framework gave systematic structure to what could have been an overwhelming assessment. Breaking security into control families made the audit manageable and ensured comprehensive coverage.

**Compliance Drives Security:**
While initially approached as a compliance requirement, the NIST framework actually identified real security gaps that posed genuine risk to the organization.

### Practical Implementation

**Prioritization is Essential:**
Not everything can be fixed immediately. Risk-based prioritization ensured critical controls were implemented first while maintaining momentum for longer-term improvements.

**Balance Security and Usability:**
Security controls must be practical for users. Overly restrictive policies led to workarounds that actually decreased security. Finding the right balance required user feedback and iterative adjustments.

**Automation is Key:**
Manually managing 30 endpoints was unsustainable. Automated patch management, configuration enforcement, and centralized monitoring were essential for long-term success.

### Career Impact

This project demonstrated ability to:

These skills directly contributed to securing cybersecurity analyst roles focused on compliance and endpoint security.

## Full Report

📄 [**Read the complete endpoint security assessment report (Google Drive)**](https://drive.google.com/file/d/your-endpoint-mapping-report-id/view)

*Report includes: Executive summary, complete asset inventory, NIST 800-53 control assessment matrix, detailed gap analysis, risk prioritization matrix, phased remediation roadmap, implementation guides, and ongoing maintenance procedures.*

**Related Skills:** NIST 800-53, Endpoint Security, Compliance Auditing, Vulnerability Management, Security Hardening, Risk Assessment

[← Back to Projects](/projects/)
