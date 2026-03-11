# Healthcare Security Strategy — Zeta Alpha Medical

**Enterprise Cybersecurity Policy Suite + Government-Funded Medical Data Center Framework**

---

## Overview

This repository contains a two-phase cybersecurity strategy developed for **Zeta Alpha Medical**, a fictitious medical diagnostic and treatment system (MDTS) technology company operating across the United States, Canada, and Singapore.

**Phase 1** delivers a complete enterprise security policy suite aligned to the NIST Cybersecurity Framework, covering governance, risk management, access control, acceptable use, mobile/IoT, and incident response across a multi-jurisdictional healthcare technology company subject to HIPAA, GDPR, and FDA regulation.

**Phase 2** extends the strategy to a government-funded medical data center housing protected health information (PHI). This phase escalates the compliance baseline from NIST CSF to **NIST SP 800-53 Rev. 5 HIGH**, implements the **NIST SP 800-37 Risk Management Framework (RMF)**, and introduces physical/environmental security policies for a facility categorized as **FIPS 199 HIGH** across confidentiality and integrity.

---

## Repository Contents

| Document | Description |
|----------|-------------|
| **[ZetaAlphCapstone_JohnWilliams.pdf](./ZetaAlphCapstone_JohnWilliams.pdf)** | Original capstone — 7-policy enterprise security strategy (NIST CSF aligned) |
| **[ZetaAlpha_PolicyHandbook_Revised.pdf](./ZetaAlpha_PolicyHandbook_Revised.pdf)** | Revised and professionalized edition of the enterprise policy suite |
| **[ZetaAlpha_PolicyHandbook_Revised.docx](./ZetaAlpha_PolicyHandbook_Revised.docx)** | Editable Word format of the revised handbook |
| **[ZA_DataCenter_PolicyFramework_Sections1-4_1.pdf](./ZA_DataCenter_PolicyFramework_Sections1-4_1.pdf)** | Data center policy framework — Sections 1–4 (executive context, information security program, risk management, physical/environmental security) |

### Coursework — Individual Policy Assignments

The `coursework/` directory contains the individual module assignments that were developed iteratively throughout the course and ultimately assembled into the capstone handbook. These show the policy development process from first draft through final integration.

| File | Module | Policy Area |
|------|--------|-------------|
| **[Module1Assignment_JohnWilliams.docx](./coursework/Module1Assignment_JohnWilliams.docx)** | Module 1 | Information Security Program & Privacy |
| **[RiskManagementPolicy_JohnWilliams.docx](./coursework/RiskManagementPolicy_JohnWilliams.docx)** | Module 2 | Risk Management & Incident Response |
| **[ZAModule3_JohnWilliams.docx](./coursework/ZAModule3_JohnWilliams.docx)** | Module 3 | Acceptable Use, Non-Compliance, Email/Messaging |
| **[MDMPolicy_JohnWilliams.docx](./coursework/MDMPolicy_JohnWilliams.docx)** | Module 4 | Mobile Device & IoT Security |
| **[ACPPolicy_JohnWilliams.docx](./coursework/ACPPolicy_JohnWilliams.docx)** | Module 5 | Access Control, Identification & Authentication |
| **[SecurityTraining_JohnWilliams.pptx](./coursework/SecurityTraining_JohnWilliams.pptx)** | Module 6 | Security Awareness & Training Program |
| **[ISEC 5430_Simmons.pdf](./coursework/ISEC%205430_Simmons.pdf)** | — | Course syllabus (ISEC 5430: Enterprise Cybersecurity, Baylor University) |

---

## Phase 1 — Enterprise Security Policy Suite

Seven policies covering the full operational footprint of a healthcare MDTS company:

| Policy | Scope |
|--------|-------|
| **Information Security Program** | Enterprise governance, risk management, incident response, NIST CSF alignment |
| **Risk Management & Contingency/Incident Response** | Risk identification, business impact analysis, disaster recovery |
| **Acceptable Use** | IT resource usage rules, BYOD provisions, disciplinary framework |
| **Non-Compliance** | Tiered violation classification, investigation and enforcement |
| **Email and Messaging** | PHI encryption requirements, monitoring, data retention |
| **Mobile Device and IoT Use** | Three-tier device model, NIST SP 800-124 threat management, IoT integration |
| **Access Control** | On/off-boarding, MFA, IAM integration, role-based access, compliance auditing |

**Regulatory scope:** HIPAA Security Rule, GDPR, FDA medical device cybersecurity guidance

---

## Phase 2 — Government-Funded Medical Data Center Framework

Extends Phase 1 into a dedicated data center housing PHI under federal funding obligations. This framework supersedes the enterprise policies within the data center boundary and introduces requirements that did not exist in the original suite.

### FIPS 199 Security Categorization

| Security Objective | Impact Level | Rationale |
|--------------------|-------------|-----------|
| **Confidentiality** | HIGH | PHI disclosure causes severe individual harm; HIPAA penalties up to $1.5M/year per violation category |
| **Integrity** | HIGH | Altered medical records or device telemetry can endanger patient lives |
| **Availability** | MODERATE | Repository (not real-time clinical system); extended downtime disrupts care continuity but does not halt clinical operations |
| **Overall** | **HIGH** | Highest watermark drives NIST SP 800-53 HIGH baseline selection |

### Sections Covered (v1.0)

| Section | Content |
|---------|---------|
| **1 — Executive Summary & Organizational Context** | Mission statement, government funding acknowledgment, regulatory compliance matrix (HIPAA, FISMA, NIST 800-53, FedRAMP, FIPS 199/200, 21 CFR Part 11, CMMC), applicability matrix, relationship to parent organization, FIPS 199 categorization |
| **2 — Information Security Program Policy** | Governance structure (CISO/CTO/ISSO/Privacy Officer), FISMA compliance, NIST SP 800-53 HIGH baseline implementation, FedRAMP considerations, control tailoring, continuous monitoring (ConMon) strategy, POA&M management |
| **3 — Risk Management Policy** | NIST SP 800-37 RMF six-step implementation (Categorize → Select → Implement → Assess → Authorize → Monitor), SSP requirements, FIPS 199/200 ongoing categorization, supply chain risk management (NIST SP 800-161), risk assessment methodology (NIST SP 800-30) |
| **4 — Physical & Environmental Security Policy** | Five-zone concentric access model (public → vault), mantrap requirements, visitor management, perimeter security, HVAC/temperature (ASHRAE TC 9.9), fire detection (VESDA) and clean agent suppression, water detection, 2N power distribution, rack-level security (TIA-942), media sanitization (NIST SP 800-88), loading dock procedures |

---

## Compliance Frameworks Referenced

| Framework | Application |
|-----------|-------------|
| NIST Cybersecurity Framework (CSF) | Phase 1 enterprise policy alignment |
| NIST SP 800-53 Rev. 5 (HIGH baseline) | Phase 2 data center control set — 20 families, 400+ controls |
| NIST SP 800-37 (RMF) | Phase 2 risk management methodology |
| NIST SP 800-30 Rev. 1 | Risk assessment methodology |
| NIST SP 800-88 Rev. 1 | Media sanitization |
| NIST SP 800-124 | Mobile device security (Phase 1) |
| NIST SP 800-161 Rev. 1 | Supply chain risk management |
| FIPS 199 / FIPS 200 | System categorization and minimum security requirements |
| HIPAA / HITECH | PHI protection and breach notification |
| FISMA | Federal information system security requirements |
| FedRAMP | Cloud/shared-service federal authorization (if applicable) |
| 21 CFR Part 11 | FDA electronic records and signatures |
| NIST SP 800-171 / CMMC | Controlled Unclassified Information (CUI) handling |
| GDPR | EU data protection (Phase 1 — Singapore/international operations) |
| ASHRAE TC 9.9 | Data center thermal guidelines |
| TIA-942 | Data center cabling standards |

---

## Skills Demonstrated

- **Federal Security Compliance** — FISMA, FedRAMP, NIST SP 800-53 HIGH baseline implementation, ATO process, continuous monitoring
- **Risk Management Framework (RMF)** — Full six-step NIST SP 800-37 implementation with SSP, SAR, and POA&M documentation requirements
- **Healthcare Regulatory Navigation** — HIPAA Security Rule, HITECH breach notification, 21 CFR Part 11 for medical device data, multi-jurisdictional compliance
- **Physical Security Architecture** — Concentric zone access model, mantrap design, VESDA fire detection, 2N power distribution, TIA-942 cabling
- **Supply Chain Risk Management** — NIST SP 800-161 aligned SCRM program with vendor registry, flow-down clauses, and tamper-evident procurement
- **Data Classification & Categorization** — FIPS 199 impact analysis driving control baseline selection and ongoing recategorization governance
- **Policy Development at Scale** — 11+ policies across enterprise and facility scopes with clear governance hierarchies, review triggers, and enforcement mechanisms

---

## Document History

| Version | Date | Scope | Description |
|---------|------|-------|-------------|
| 1.0 | Feb 2024 | Enterprise | Initial capstone policy handbook |
| 1.1 | Feb 2026 | Enterprise | Revised edition — standardized naming, reconciled governance roles, added PHI encryption requirements, professionalized structure |
| 1.0 | Feb 2026 | Data Center | New framework — Sections 1–4: executive context, information security program, risk management, physical/environmental security |

---

## Usage

This repository demonstrates end-to-end cybersecurity strategy development from enterprise governance through federal data center compliance. To adapt this framework:

1. **Review** the Phase 1 enterprise policies for organizational applicability, then assess whether your environment requires the Phase 2 federal/data center extensions.
2. **Customize** role references, technology stack details, jurisdictional requirements, and FIPS 199 categorization to match your specific operational profile.
3. **Implement** with appropriate training programs, acknowledgment procedures, SSP documentation, and ATO processes.
4. **Maintain** compliance through the annual review cycles, trigger-event processes, and continuous monitoring strategy defined throughout both phases.

---

## Confidentiality Note

This work was developed for a fictitious organization and does not contain real company information, personnel data, or proprietary systems. It serves as a demonstration of cybersecurity policy development principles for professional portfolio purposes.

---

## License

This work is available as a reference and learning resource. Please provide attribution if adapted for use in other projects.
