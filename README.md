# Gap Analysis of Vendor Privacy and Security Policy

## Overview
This repository documents the project to perform a gap analysis on Best Buy's Information Security Policy. The objective was to ensure alignment with PCI DSS 4.0 requirements.
## Key Highlights
- Framework: PCI DSS 4.0
- Scope: Access control, data protection, incident response, and third-party management
- Tools: Google Docs

## Key Findings
### **Compliant Controls**
- **Data Retention**: Data rendered unrecoverable (Requirement 9.4.6).
- **Third-Party Audits**: TPSPs reviewed annually (Requirement 12.8.4).
- **Encryption**:
  - In-Transit: TLS 1.2 secure (Requirement 4.2.1).
  - At Rest: 128-bit key strength (Requirement 3.5).
- **Incident Response**: IR plan reviewed annually (Requirements 12.10.1, 12.10.2).

### **Non-Compliant Controls**
- **Vulnerability Scanning**: Internal and external scans not conducted quarterly (Requirements 11.3.1, 11.3.2).
- **Patching**: Critical patches not implemented within 30 days (Requirement 6.3.3).
- **Weak Protocols**: Weak protocols not fully mitigated (Requirement 1.2.6).

### **Detailed Gap Table**

| **Requirement**    | **Control**                          | **Status**      | **Comments**                                       |
|---------------------|--------------------------------------|-----------------|---------------------------------------------------|
| 6.3.3              | Critical Patching                   | Non-Compliant   | Patches not implemented within 30 days.          |
| 11.3.1, 11.3.2     | Vulnerability Scans (Internal/Ext.) | Non-Compliant   | Not conducted quarterly.                         |
| 1.2.6              | Weak Protocol Mitigation            | Non-Compliant   | Weak protocols require additional mitigation.    |



## Quick Links
- [Methodology](docs/Methodology.md)
- [Findings](docs/Findings.md)
- [Action Plan](docs/Action_Plan.md)
- [Lessons Learned](docs/Lessons_Learned.md)
