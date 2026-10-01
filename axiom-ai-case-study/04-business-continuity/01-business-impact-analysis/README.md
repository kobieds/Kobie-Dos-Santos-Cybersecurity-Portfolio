# Business Impact Analysis (BIA)

## Overview

This folder contains the Business Impact Analysis (BIA) developed for **Axiom AI Technologies**, a fictional B2B cloud AI/ML SaaS organization.

The BIA establishes the business requirements that form the foundation for the organization's Business Continuity and Disaster Recovery (BCP/DR) program.

It identifies critical business activities, the potential impact of disruption, recovery priorities, dependencies, and recovery objectives.

> **Portfolio Disclaimer:** Axiom AI Technologies is a fictional organization created for cybersecurity/GRC portfolio purposes. The information contained within this BIA is modeled for demonstration and does not represent an assessment of a real organization.

---

## Purpose

The purpose of the BIA is to determine:

* Which business activities are most critical.
* The potential impact of prolonged disruption.
* Maximum Tolerable Periods of Disruption (MTPD).
* Recovery Time Objectives (RTO).
* Recovery Point Objectives (RPO).
* Recovery priorities.
* Internal and external dependencies.
* Minimum resources required for continuity.
* Potential manual workarounds.
* Key recovery considerations.

The results are used to establish the strategic direction for subsequent BCP/DR planning.

---

## Methodology

The BIA evaluates business activities based on their operational importance and the consequences of disruption.

Each activity is assessed against factors including:

1. Business criticality.
2. Impact of unavailability.
3. Maximum Tolerable Period of Disruption.
4. Recovery Time Objective.
5. Recovery Point Objective.
6. Internal dependencies.
7. External dependencies.
8. Technology and information dependencies.
9. Minimum resources.
10. Manual workarounds and recovery considerations.

The resulting recovery priorities are used to sequence continuity and recovery activities.

---

## Recovery Priority Model

| Priority          | Description                                                                                            |
| ----------------- | ------------------------------------------------------------------------------------------------------ |
| **P1 — Critical** | Activities requiring the shortest recovery timeframe and receiving priority during a major disruption. |
| **P2 — High**     | Important activities restored after P1 capabilities have been stabilized.                              |
| **P3 — Moderate** | Supporting activities that can be restored after higher-priority services.                             |

These priority levels are modeled for portfolio purposes and would require validation by business owners in a real organization.

---

## Key Recovery Concepts

### Maximum Tolerable Period of Disruption — MTPD

The maximum period a business activity can remain unavailable before the resulting impact becomes unacceptable.

### Recovery Time Objective — RTO

The target time within which a business activity or service should be restored following a disruption.

### Recovery Point Objective — RPO

The target maximum amount of data loss measured in time.

---

## BIA Results

The modeled BIA evaluates **10 business and technology-supported activities** across the Axiom AI environment.

The activities include:

* Customer Support & Service Operations
* SaaS Platform Operations
* Identity & Access Administration
* Security Monitoring & Incident Response
* Software Development & Release Management
* Vulnerability Management & Security Remediation
* Third-Party & Supplier Security Management
* ISMS Governance & Compliance
* Customer & Business Communications
* Backup, Recovery & Data Restoration

The BIA identifies the most time-sensitive activities as those supporting core SaaS operations, security monitoring and incident response, backup/recovery, customer operations, identity and access, and business communications.

---

## Workbook Structure

The Excel workbook contains four primary worksheets.

### BIA

Contains the detailed business impact analysis for each activity, including:

* Process owner
* Business criticality
* Impact of disruption
* MTPD
* RTO
* RPO
* Recovery priority
* Dependencies
* Minimum resources
* Manual workarounds
* Recovery considerations
* Review requirements

### Summary

Provides an overview of the modeled BIA results, including activity counts and recovery-priority information.

### Recovery Requirements

Defines the P1, P2, and P3 recovery-priority model used within the assessment.

### Assumptions

Documents the assumptions and limitations associated with the modeled BIA values.

---

## Relationship to the BCP/DR Strategy

The BIA is the foundation for the next stage of Project 4.

The relationship is:

**Business Impact Analysis**

↓

**Recovery Requirements**

↓

**BCP/DR Strategy**

↓

**Business Continuity Plan**

↓

**Disaster Recovery Plan**

↓

**Testing & Exercises**

↓

**Lessons Learned & Continual Improvement**

The BIA determines **what needs to be recovered and how quickly**.

The BCP/DR Strategy determines **the strategic approach for maintaining and recovering those capabilities**.

---

## Framework Alignment

The BIA demonstrates concepts relevant to:

* ISO/IEC 27001:2022
* ISO 22301 — Business Continuity Management
* NIST Cybersecurity Framework
* NIST SP 800-34 — Contingency Planning Guide
* General business continuity and disaster recovery practices

The artifact is a portfolio demonstration and does not claim formal compliance or certification.

---

## Artifact

**Primary Artifact:**

`Axiom-AI-Business-Impact-Analysis.xlsx`

**Format:** Microsoft Excel Workbook

**Classification:** Internal Use

---

## Related Artifacts

### Previous Projects

* Project 1 — Risk Management
* Project 2 — Controls Assessment
* Project 3 — ISMS Implementation

### Project 4

* BCP/DR Strategy
* Business Continuity Plan
* Disaster Recovery Plan
* Tabletop Exercise
* Testing & Lessons Learned

---

## Portfolio Disclaimer

This Business Impact Analysis is a fictional cybersecurity/GRC portfolio artifact created to demonstrate practical application of business continuity, disaster recovery, risk management, and ISMS concepts.

The recovery objectives, priorities, dependencies, and assumptions are modeled examples and would require validation by appropriate business and technical stakeholders in a real organization.
