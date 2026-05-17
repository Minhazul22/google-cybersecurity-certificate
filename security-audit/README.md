# Security Audit — Botium Toys

## Overview

This project is an internal security audit conducted for **Botium Toys**, a fictional small U.S. business used as a case study in the Google Cybersecurity Certificate program.

The goal was to assess the company's existing security posture, identify gaps in controls and compliance, and provide recommendations to reduce risk.

---

## Scenario

Botium Toys is a growing toy retailer with both a physical storefront and an online presence serving U.S. and international customers. The IT manager initiated an internal audit due to concerns about:

- Inadequate asset management
- Lack of proper security controls
- Potential non-compliance with U.S. and international regulations (PCI DSS, GDPR, SOC)

---

## What I Did

- Reviewed the company's scope, goals, and risk assessment report
- Analyzed existing assets managed by the IT department
- Used the NIST Cybersecurity Framework (NIST CSF) as a reference
- Completed a controls and compliance checklist evaluating:
  - Administrative/Managerial controls
  - Technical controls
  - Physical/Operational controls
  - PCI DSS compliance
  - GDPR compliance
  - SOC type 1 & 2 compliance
- Provided recommendations to the IT manager prioritized by risk level

---

## Key Findings

| Area | Status |
|------|--------|
| Firewall | ✅ In place |
| Antivirus software | ✅ In place |
| Physical security (locks, CCTV, fire detection) | ✅ In place |
| Encryption | ❌ Not implemented |
| Least privilege & separation of duties | ❌ Not implemented |
| Intrusion detection system (IDS) | ❌ Not implemented |
| Disaster recovery & backups | ❌ Not implemented |
| Password management system | ❌ Not implemented |
| PCI DSS compliance | ❌ Non-compliant |
| GDPR compliance | ⚠️ Partially compliant |
| SOC compliance | ⚠️ Partially compliant |

**Risk score: 8/10** (high)

---

## Top Recommendations

1. Implement **least privilege** and **separation of duties** to restrict data access
2. Deploy **encryption** to protect cardholder data and PII
3. Set up **data backups** and a **disaster recovery plan**
4. Install an **intrusion detection system (IDS)**
5. Strengthen **password policies** and deploy a **password management system**
6. Conduct a full **asset classification and inventory**

---

## Files

| File | Description |
|------|-------------|
| `Controls-and-compliance-checklist-completed.docx` | Completed audit checklist with Yes/No answers and recommendations |

---

## Skills Demonstrated

- Security auditing
- Risk assessment
- NIST Cybersecurity Framework (CSF)
- Compliance frameworks: PCI DSS, GDPR, SOC
- Critical thinking and written communication
